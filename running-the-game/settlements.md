---
layout: default
title: Settlements
description: Stuff about settlements
parent: Running the Game
nav_order: 2
---

# Settlements

There are few things nicer than arriving in town after a long journey through the countryside, a hot bath tub and a nice feathery bed waiting for you. Though these nice luxuries, of course, did not fall from the sky.

To achieve this, towns, cities, villages, and castles can be abstracted with the asset system.

# Supply Ratings

As a general rule of thumb, the richer a town and the better its infrastructure, nicer it is to stay there. This rule of thumb is abstracted into a number that is called the supply rating of a settlement.

The supply rating of a settlement is analog to the masterpiece rating of an ordinary asset. When a character rests in a town, they may add its supply rating as dice to their roll and their minimum effort on their test is equal to the town's supply rating.

{: .note-title }
> Eyeballing It
>
> If you simply need a quick number without much of the details: most towns in villages have a simple supply rating of **1.** Harbor towns and cities have a supply rating of **2,** and magnificently rich and capitols a supply rating of **3.**

Extremely lush forests or oases may also be given a supply rating when [Making Camp](../playing-the-game/resting#making-camp).

Though, rpg thingy has a system for building towns and their surroundings from the ground up to determine their supply rating using [Assets](../playing-the-game/assets) to abstract structures.

{: .note-title }
> Why bother?
>
> Why would I want to put effort into calculating the supply rating of a town when I can simply assign a number and be done with it?
> 
> In longer running campaigns, towns and cities will sometimes take on the role of characters. Mostly commonly that role will be Home.
>
> Home can be improved but Home can also be destroyed. Surely the mill being burned down by bandits will have some consequences for the town and its wealth. As GMs, we often flesh out these consequences in the narrative but this system aims to also offer a tool to easily flesh them out even more with reasonable mechanical weight by making use of the asset system.


# Support Ratings

Masterpieces to not degrade for simple tests with only obstacle **1.** As assets can also be structures, this has helpful implications for building a coherent and interconnected world. When talking about structures, an asset's masterpiece rating is called its support rating instead.

{: .important }
> A river parts the forest in two. Crossing it is an uncertain task. The difficulty to cross it is **1.** A character could build a simple bridge across to cross. A bridge asset with rating **1** will help one person cross the river before collapsing (the river can still be crossed by succeeding on the difficulty **1** test without the help of the bridge). A bridge asset with rating **2** will help two people cross the river but a masterpiece bridge asset with rating **3** or higher does not degrade when used, as the difficulty against which it is used is only **1.**
>
> The bridge has a quality rating of **3** and a support rating of **1** (it will still degrade when used on tests with difficulty higher than its support rating, for example an ox and cart crossing the river, which would be a difficulty **2** test).


# Calculating Supply Rating

Settlements are, almost by definition, where multiple structures with a support rating of at least **1** accumulate.

{: .important }
> Next to the bridge with a support rating of **1,** a little town has formed around a magnificent mill asset with quality rating **5,** so its support rating is **2.**

A settlement's supply rating based on the surrounding assets and their support ratings. It is calculated just like a masterpiece/support rating.

| Surrounding Support Ratings | Supply Rating |
|:---------------------------:|:-------------:|
|            **1**            |       -       |
|            **2**            |       -       |
|            **3**            |       1       |
|            **4**            |       1       |
|            **5**            |       2       |
|            **6**            |       2       |
|            **7**            |       3       |
|           **...**           |      ...      |

{: .important }
> The bridge and mill around the town have a combined support rating of **3,** so the supply rating of the town is **1.** When characters rest in the town, they add an extra die to their rest roll and their minimum effort for that test is also **1.**
>
> Should the existing assets be improved and/or new supporting structures be built around the town, its supply rating would improve. Should the existing assets degrade or be destroyed, its supply rating would decrease.



# Structures

Calculating supply rating already is a very handy tool to give characters to the towns and cities characters will visit. In some cases, though, they demand even more detail. For these cases, you can use individual structures with their own support ratings.


## Leisure Structures

The most common example of structures to flesh out are leisure structures, which are relevant when characters are recovering while resting and which are always strongly associated with either a specific [Attribute](../characters#attributes) or condition type.  
They contribute their support rating to the settlement as normal, but their support rating may also be used to add dice to recovery tests made either with the corresponding attribute or for the corresponding condition type, just like you would add dice from a masterpiece asset. As such, when you use a support rating to add dice to your roll, your minimum effort for that test is equal to the structure's support rating.

Leisure structures might also allow for skills to be used for recovery tests other than normal.

Per recovery test, only **1** leisure structure may contribute additional dice.

Some examples for leisure structures are:

- A coliseum, which would be associated with Vigor and allow recovery tests to be made with Fight or Maneuver by participating in the coliseum for a thrilling display of martial prowess, simply enjoying the show, or training on the sparring grounds.
- A palace garden, which would be associated with Intuition and allow recovery tests with Means or Wilderness by going for a serene stroll through the water gardens, washing the dirt off bruised flesh, or watching a reenactment.
- An academy, which would be associated with Reason and allow recovery tests with Influence or Means by getting aid from a trained surgeon or banker, or spending some quiet time in the library.
- A hospital, which would be associated with physical conditions and allow recovery tests with Influence or Means by acquiring medical care.
- A theater, which would be associated with mental conditions and allow recovery tests with Maneuver or Craft by processing your troubles in drama.
- A courthouse, which would be associated with social conditions and allow recovery tests with Influence or Fight by proving (or "proving") your innocence.

{: .important }
> After a tumultuous journey, Maro arrives in the city of Artir, famed for its magnificent bathhouses. He could have made for a different town, but he wanted to return to exactly here. After dealing with cutthroats and turncloaks at every corner, taking stress left and right, he is exhausted beyond words. When he finally steps into the steamy halls, bliss finally returns to him.
>
> Because of the city's respectable supply rating of **4,** Maro achieved enough successes to possibly rid himself of all his conditions. Thankfully, he can use the bathhouse's impressive support rating **3** to add **3** additional dice to his Intuition recovery tests and emerges condition-free, even with a `Well Rested` boon to boot.
> 
> Should fate befall him again like this, he is sure to return. And should something threaten the splendid city of Artir, Maro will rush to aid without hesitation, to protect the city and her wonderful bathhouse.


## Other Structures





# Increasing the Scale

Just like the supply rating is one level above support and masterpiece ratings, so can this system be extended to easily simulate even grander scales.

For example can a barony be given a wealth rating based on the supply ratings of the towns and castles within, just like a duchy can be given an influence rating based on the baronies it contains, while the duchy is again part of a kingdom.  
Almost like a fractal, a kingdom asset is made of smaller assets, which are again made of even smaller assets.

The asset system can also be used as a guidance of straining effects on settlements. Just like degradation of structures can negatively influence a town's supply rating, so can a large host occupying it as it strains the settlement by using more than its supply rating, degrading the settlement asset in the process.
