```mermaid
graph LR;
CS(Cyclops Steel);
CB(Celestial Bronze);
Bronze(Bronze);

MC{{Magical-Creatures}};
Animals{{Animals}};
Undead{{Undead}};
Spirits{{Spirits}};
Bronze-->Humans;
Bronze-->Animals;
CB-->Humans;
CB-->Animals;
CB-->MC;
SI(Stygian-Iron)-->Animals;
SI-->MC;
SI-->Undead;
SI-->Spirits;
CS--> All
````
