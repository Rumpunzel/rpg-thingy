---
layout: default
title: Assets
description: Stuff about assets
parent: Playing the Game
nav_order: 4
has_children: true
---

# Assets

Assets are an abstraction of tools in the fictional world. Tools, in this context, is anything from artisan's tools, weapons, armor, riding horses, mills to grind flour, and castle fortifications to defend against a siege.

Assets have a specific use case. A weapon can be used to attack with [Fight](../../characters/skills#fight), a horse can be used to travel distances with [Maneuver](../../characters/skills#maneuver) or [Wilderness](../../characters/skills#wilderness), an aristocrat's written favor may be used with [Influence](../../characters/skills#influence) at court, etc.

Assets may have additional properties such as weapons being able to be used as assets for other skills than Fight or granting other benefits (see [Gear](#gear)). To use such a property, you must use the asset for minimum effort on a test.

You may buy new assets (see [Buying](../resting#buying)) and create new assets or improve assets you already own (see [Forging](../resting#forging-assets)).


## Inventory

You may carry up to **6** assets with you at a time. If you want to gain an asset while your inventory is full, you need to discard an asset you own to gain it


## Quality Rating

Each asset has a quality rating. Usually, this rating is between **1** and **3.** Though, some special asset such as castles and other structures, as well as masterfully crafted gear might exceed even that.

You may use an asset after rolling with a fitting skill to gain minimum effort for that test equal to the asset's quality rating. This can (and often will) result in you succeeding on a test you would have otherwise failed or at least reduce your margin of failure. After you use an asset, its quality rating degrades by **1.**

If an asset's quality rating drops to **0,** it can no longer be used.

{: .important }
> Maro finds himself in a skirmish with a vicious assassin who ambushed him in a darkened street corner.
> 
> Maro attacks him with his axe, though luck isn't on his side, and he rolls **0** hits. His opponent achieved **1** effort. He is quicker than Maro and threatens to deflect the blow. Maro may now use his `Axe` asset with a quality rating of **2** to get a minimum effort of **2** on his test.
> 
> He does and drives his `Axe` into his opponent's armored shoulder. As he used his `Axe`, it degrades and loses **1** quality rating. It now has a quality rating of **1** but the assassin suffered a minor injury despite his efforts and will be easier to fight from now on.

### Masterpieces

Some assets are so well crafted for their purpose that they are considered masterpieces. These assets have a masterpiece rating in addition to their quality rating, which grants them additional benefits.

If an asset's quality rating is **3** or greater, it is considered a masterpiece, and it has a masterpiece rating as described in the table below.  
You may use a masterpiece asset to gain minimum effort equal to its quality rating, just like you would a normal asset. Alternatively, you may use a masterpiece asset to gain minimum effort equal to its masterpiece rating instead and if you succeed on the test, the asset does not degrade.

| Quality Rating | Masterpiece Rating |
|:--------------:|:------------------:|
|     **1**      |         -          |
|     **2**      |         -          |
|     **3**      |         1          |
|     **4**      |         1          |
|     **5**      |         2          |
|     **6**      |         2          |
|     **7**      |         3          |
|    **...**     |        ...         |

### Off-Label Usage

When using an asset for with a skill or [Attribute](../../characters#attributes) other than its intended purpose, it grants only **1** minimum effort for that test.  
If the asset is a masterpiece, instead it can only be used to gain minimum effort equal to its masterpiece rating.

If an asset was not originally intended to be used for a purpose, but it makes sense that it would help you and the table agrees, the asset grants its full minimum effort for that test. Though, afterward it degrades to quality rating **0.**

{: .important }
> Maro chases a young dragon on his trusty steed Athena across the plains. Unfortunately, the dragon arrives at the nearest town first. Now a battle is unavoidable.
> 
> Fighting a dragon, even as young as this one, is not anything Maro would take lightly, though even with precautions taken, and riding circles around the scaled beast, the fight goes poorly.
> 
> When it finally takes a deep, flaming breath and rears its head towards the town, Maro sees no other way but to ride


## Gear

Gear assets are more specific versions of general assets. They work just like normal assets but have additional properties. These properties are only for their corresponding skill [Gauntlets](../gauntlets), only when the asset is used on a skill test to gain minimum effort. An asset's properties can only be used as long as it has a quality rating of at least **1.**

Some assets may be only specifically be used to attack or defend. If they are used for minimum effort to attack or defend but weren't meant to do so, it is treated as an [Off-Label Use](#off-label-usage).
Whether an asset is used to attack is signified by a 🗡 and by a 🛡 if it is meant to defend. Sometimes a different skill is listed, such as a **Longbow** is used to for Maneuver during Fight gauntlets. If there is no additional information given, the gear asset is neither meant to attack nor defend, though it may, of course, still be used for that as an off-label use.
Outside of gauntlets, gear assets may be used on skill tests regardless if they were meant for attacking or defending as long as it makes sense in the narrative.

Gear assets will become significantly more powerful when they are masterpieces, as you may use their abilities more often without degrading the asset.

Gear assets list a specific paraphernalia required to both create and improve them. When spending paraphernalia to craft while resting, at least one of them needs to be the listed paraphernalia for you to attempt the test.  
Some gear asset list an additional paraphernalia. You need one of each paraphernalia to create or improve the asset. In addition, if an additional paraphernalia is listed, it increases the number of paraphernalia required for any Craft tests by **1.** This does not increase the crafting test's difficulty, though this does increase the difficulty of tests to buy and sell the gear asset.

Rarely, gear assets require another masterpiece quality gear asset to be created.  
The difficulty for the test to create the new asset is the required asset's masterpiece rating, which is lost in the process (on either success or failure). If the test was successful, the desired gear asset is created and rating for the newly created asset is the required asset's masterpiece rating.  
After being created, the asset can be improved like any other asset.  
When buying and selling such an asset, its quality rating is considered to be doubled.

A gear asset may have a trait called `Exquisite`. This trait is relevant for Influence, Craft, and Resource tests, concerning the asset itself. Meaning an asset's `Exquisite` trait will increase the difficulty to create, improve, and buy it. Though it may also be invoked in social situations. Additionally, increase your effort by **1** when selling an `Exquisite` asset.

A gear asset may also have a property called **Fortified.** A **Fortified** asset's masterpiece rating is equal to its full quality rating.

At the top of each category of gear, there is also generic variant without properties. They do not require specific paraphernalia to be crafted as they are simply normal assets. Of course, they are still associated with an attribute, just like any other asset.  
Use these for, for example, improvised weapons or instead of its lengthy list of gear entirely.

{: .note-title }
> Why use Gear?
>
> You can play {{ site.title }} without gear entirely, as assets are an already useful abstractions. If you use gear, you should use them for the purpose for which I designed them:
> - To add meaningful choices to gauntlets
> - Because I think they're neat
>
> So if, for example, your game does not have a lot of Fight gauntlets, gear adds little meaningful choice and may be neglected. Or simply use them cause you think they're neat.
