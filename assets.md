---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Assets
description: Stuff about assets

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Conditions & Resting
        url: /conditions-and-resting
    next:
        content: Conflicts
        url: /conflict
---

# The Basics

Assets have a specific use case. A weapon can be used to attack with [Fight](/skill-list#fight), a horse can be used to travel distances with [Maneuver](/skill-list#maneuver) or [Wilderness](/skill-list#wilderness), an aristocrat's written favor may be used with [Influence](/skill-list#influence) at court, etc.

Each asset has a quality rating. Usually, this rating is between **1** and **3.** Some special asset such as castles might exceed a quality rating of **3.**

An asset may be used in one of two ways. You may only use a single asset on a roll, and you may only use an asset in only one of these two ways this way.

- After rolling with a fitting skill and if the number of the successes rolled is lower than the asset's rating, treat the roll as if you had rolled successes equal to the asset's rating. After you use an asset, its quality rating degrades by **1.**

- Add half of its rating (rounded down) as dice to your roll. When you do, the asset also degrades.

If an asset's quality rating drops to 0, it can no longer be used.

When you use an asset to increase your successes, but you still fail at the test, the asset does not increase the [Favor](/character#favor) you gain. You only get Favor for successes you have actually rolled.

**Off-label Usage:** When using an asset for with skill other than its intended purpose, its rating is considered to be halved (rounded down) for that test. When using an asset with an [Attribute](/character#attributes) other than its intended purpose, its rating is considered to be halved (rounded down) for that test. After rounding down, an asset's rating is always at least **1.** If an asset is not intended for a use case but just makes perfect sense in the narrative at that moment, the GM may allow you to use an asset without halving its rating.

**Masterwork:** A asset does not degrade if its rating is more than double the number of successes required to succeed on the test it is used.

Assets may have additional properties such as weapons being able to be used as assets for other skills than Fight or granting other boons or have traits of their own (see [Gear](/gear)).

You may buy new assets and create new assets or improve assets you already own (see [Resting](/conditions-and-resting#crafting)).

> Maro finds himself in a skirmish with a vicious assassin who ambushed him. Maro attacks with his axe, though luck isn't in his favor, and he rolls **0** successes. His opponent rolled **1** success. He is quick and threatens to deflect the blow. Maro may now use his `Axe` asset with a quality rating of **2** to treat the roll as if he had rolled **2** successes. If he does, the asset degrades as he drives the axe into his opponent's armor and the axe loses **1** quality rating. It now has a quality rating of **1** but the assassin suffered a mean wound to the chest.



# Crafting Assets

To create an asset with quality raring **1** is a test difficulty **1** test.

After being created, assets can only be improved by **1** rating at a time. To improve an asset from a quality rating of **2** to a quality rating of **3,** is a difficulty **3** test.

Improving an asset with rating **0** (an asset which broke after being used) grants **1** extra die to the test.



# Supply Rating

There are few things nicer than arriving in town after a long journey through the countryside, a hot bath tub and a nice feathery bed waiting for you. Though these nice luxuries, of course, did not fall from the sky.

As a general rule of thumb, the richer a town and the better its infrastructure, nicer it is to stay there. This rule of thumb is abstracted into a number that is called the supply rating of a settlement. When a character rests in a town, they may add its supply rating as dice to their roll.

**Eyeballing It:** If you simply need a quick number without much of the details: most towns in villages have a simple supply rating of **1.** Harbor towns and cities have a supply rating of **2,** and magnificently rich and capitols a supply rating of **3.**

Extremely lush forests or oases may also be given a supply rating when resting with [Wilderness](/skill-list#wilderness).

Though, rpg thingy has a system for building towns and their surroundings from the ground up to determine their supply rating using [assets](/assets) to abstract structures.

<div class="callout">
    <p>
        <strong>Why would I want to put effort into calculating the supply rating of a town when I can simply assign a number and be done with it?</strong>
    </p>
    <p>
        In longer running campaigns, towns and cities will sometimes take on the role of characters. Mostly commonly that role will be Home.
    </p>
    <p>
        Home can be improved but Home can also be destroyed. Surely the mill being burned down by bandits will have some consequences for the town and its wealth. As GMs, we often flesh out these consequences in the narrative but this system aims to also offer a tool to easily flesh them out even more with reasonable mechanical weight by making use of the asset system.
    </p>
</div>


## Support Ratings

According to the Masterwork rule, assets with rating **3** or higher to not degrade for simple tests with only obstacle **1.** As assets can also be structures, this has helpful implications for building a coherent and interconnected world. This **1** a structure asset can support is called its support rating.

The support rating of a structure assets is the highest obstacle of test it can be used for without degrading.

> A river parts the forest in two. Crossing it is no trivial task. The obstacle to cross it is **1.** A character could build a simple bridge across to cross. A bridge asset with rating **1** will help one character cross the river before collapsing (the river can still be crossed by succeeding on the obstacle **1** test without the help of the bridge). A bridge asset with rating **2** will help two characters cross the river but a bridge asset with rating **3** or higher does not degrade when used, as the obstacle against which it is used is only **1.**
>
> The bridge has a quality rating of **3** and a support rating of **1.**
>
> (Note that the bridge will still degrade by obstacles higher than its support rating, for example an ox and cart crossing the river, which would be an obstacle **2** test)


## Calculating Supply Rating

Settlements are, almost by definition, where multiple structures with a support rating of at least **1** accumulate.

> Next to the bridge with a support rating of **1,** a little town has formed around a magnificent mill asset with quality rating **5,** so its support rating is **2.**

A settlement's supply rating based on the surrounding assets and their support ratings is half of the sum of all relevant support ratings (rounded down).

> The bridge and mill around the town have a combined support rating of **3,** so the supply rating of the town is **1.** When characters rest in the town, they add an extra die to their rest roll.
>
> Should the existing assets be improved and/or new supporting structures be built around the town, its supply rating would improve. Should the existing assets degrade or be destroyed, its supply rating would decrease.


## Leisure Structures

Calculating supply rating already is a very handy tool to give characters to the towns and cities characters will visit. In some cases, though, they demand even more detail. For these cases, you can deploy leisure structures, who are always strongly associated with either a specific [Attribute](/character#attributes) or Condition type. They contribute their support rating to the settlement as normal, but also add dice equal tot heir support rating to recovery rolls made either with the corresponding Attribute or for the corresponding Condition type.

Leisure structures might also allow for skills to be used for the recovery roll than normal.

Per recovery roll, only **1** leisure structure may contribute additional dice.

Some examples for leisure structures are:

- A coliseum, which would be associated with Vigor and allow recovery rolls with Fight or Maneuver. Participating in the coliseum for a thrilling display of martial prowess, simply enjoying the show, or training on the sparring grounds will add dice equal to the coliseum's support rating to all recovery tests made with Vigor.
- A palace garden, which would be associated with Intuition and allow recovery rolls with Resources or Wilderness. Going for a serene stroll through the water gardens, washing the dirt off bruised flesh, or watching a reenactment will add dice equal to the palace garden's support rating to all recovery tests made with Intuition.
- An academy, which would be associated with Reason and allow recovery rolls with Influence or Resources. Getting aid from a trained surgeon or banker, or spending some quiet time in the library will add dice equal to its the academy's support rating to all recovery tests made with Reason.
- A hospital, which would be associated with physical conditions with Influence or Resources by acquiring medical care.
- A theater, which would be associated with mental conditions and allow recovery rolls with Maneuver or Craft by processing your troubles in drama.
- A courthouse, which would be associated with social conditions and allow recovery rolls with Influence or Fight by proving (or "proving") your innocence.

> After a tumultuous journey, Maro arrives in the city of Artir, famed for its magnificent bathhouse. He could have made for a different town, but he wanted to return to exactly here. After dealing with cutthroats and turncloaks at every corner, taking conditions left and right, he is exhausted beyond words. When he finally steps into the steamy halls, bliss finally returns to him.
>
> Because of the city's respectable supply rating of **4,** Maro achieved enough successes to possibly rid himself of all his conditions, if he manages to success on all recovery tests. Thankfully, he can add the bathhouse's impressive support rating of **3** (its total quality rating is **7**) to his Intuition recovery rolls and emerges Condition-free, even with a `Well Rested` Boon to boot. Should fate befall him again like this, he is sure to return. And should something threaten the splendid city of Artir, Maro will rush to aid without hesitation, to protect the city and her wonderful bathhouse.


## Fractals

