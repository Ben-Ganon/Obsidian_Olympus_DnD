```mermaid
graph LR;
CS(Cyclops Steel);
CB(Celestial Bronze);
Bronze(Bronze);

MC{{Magical-Creatures}};
Animals{{Animals}};
Undead{{Undead}};
Spirits{{Spirits}};
Bronze-->Humanoids;
Bronze-->Animals;
CB-->Humanoids;
CB-->Animals;
CB-->MC;
CB-->Undead
SI(Stygian-Iron)-->Animals;
SI-->MC;
SI-.->Undead;
SI-->Spirits;
CS-.-> All
````
