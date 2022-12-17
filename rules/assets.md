---
# Page settings
layout: default
keywords:
comments: false
permalink: /assets

# Hero section
title: Assets
description: Stuff about assets

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Resting
        url: /resting
    next:
        content: Conflicts
        url: /conflicts
---

# Assets

Assets are an abstraction of tools in the fictional world. Tools, in this context, is anything from artisan's tools, weapons, armor, riding horses, mills to grind flour, and castle fortifications to defend against a siege.

Assets have a specific use case. A weapon can be used to attack with [Fight](/skill-list#fight), a horse can be used to travel distances with [Maneuver](/skill-list#maneuver) or [Wilderness](/skill-list#wilderness), an aristocrat's written favor may be used with [Influence](/skill-list#influence) at court, etc.

Assets may have additional properties such as weapons being able to be used as assets for other skills than Fight or granting other benefits or have traits of their own (see [Gear](/gear)).

You may buy new assets (see [Resting](resting#crafting)) and create new assets or improve assets you already own (see [Crafting](/#crafting)).


# Quality Rating

Each asset has a quality rating. Usually, this rating is between **1** and **3.** Though, some special asset such as castles and other structures, as well as masterfully crafted gear might exceed even that.

You may use an asset after rolling with a fitting skill to gain minimum effort for that test equal to the asset's quality rating. This can (and often will) result in you succeeding on a test you would have otherwise failed or at least reduce your margin of failure. After you use an asset, its quality rating degrades by **1.**

If an asset's quality rating drops to **0,** it can no longer be used.

When you use an asset for minimum effort, but you still fail at the test, the asset does not increase the [Favor](character#favor) you gain. You only get Favor for the hits you have actually rolled.

> Maro finds himself in a skirmish with a vicious assassin who ambushed him in a darkened street corner.
> 
> Maro attacks him with his axe, though luck isn't on his side, and he rolls **0** hits. His opponent achieved **1** effort. He is quicker than Maro and threatens to deflect the blow. Maro may now use his `Axe` asset with a quality rating of **2** to get a minimum effort of **2** on his test.
> 
> He does and drives his `Axe` into his opponent's armored shoulder. As he used his `Axe`, it degrades and loses **1** quality rating. It now has a quality rating of **1** but the assassin suffered a wound despite his efforts and will be easier to fight from now on.


## Masterpieces

Some assets are so well crafted for their purpose that they are considered masterpieces. These assets have a masterpiece rating in addition to their quality rating, which grants them additional benefits.

If an asset's quality rating is **3** or greater, it is considered a masterpiece, and it has a masterpiece rating as described in the table below.

You may use a masterpiece asset to gain minimum effort equal to its quality rating, just like you would a normal asset. In addition, you may use a masterpiece asset to gain minimum effort equal to its masterpiece rating instead without degrading the asset's quality rating.

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

### Masterpiece Traits

Additionally, all masterpieces have a masterpiece [Trait](character#traits) describing its exceptional quality with rating equal to is masterpiece rating.  
Increasing a masterpiece's quality rating might increase the masterpiece trait's rating while degrading a masterpiece's quality rating might result in it losing its masterpiece rating and with it its masterpiece trait.

When you test a skill, you may invoke **1** of your assets' masterpiece traits either on a test fitting of that asset's purpose or by describing how you would leverage that trait to your advantage. When you do, add its masterpiece trait's rating as dice to your roll. This does not degrade the asset.

You may only invoke a single of your assets' masterpiece traits per test. If there are multiple fitting traits, you may only choose **1** of them.


## Off-Label Usage

When using an asset for with skill other than its intended purpose, its rating is considered to be **1** for that test  
If the asset is a masterpiece, instead its rating is considered to be the asset's masterpiece rating for. This may result in the asset not being considered a masterpiece for this test.

When using an asset with an [Attribute](character#attributes) other than its intended purpose, it always degrades, even if it is a masterpiece. If the asset already degraded, it degrades an additional time.

If an asset was not originally intended to be used for a purpose, but it makes perfect sense that it would help you and the table agrees, you may use an asset without any penalties for that test.



# Inventory

TODO



# Crafting Assets

You can create new assets and improve existing assets while [Resting](resting#crafting). Most of the time this creates a Craft test but sometimes a different skill might be created such as Influence to create, for example, an `Agreement with the Red Council` asset.

To create an asset with quality raring **1** is a test difficulty **1** test.

After being created, assets can only be improved by **1** rating at a time. To improve an asset from a quality rating of **2** to a quality rating of **3,** is a difficulty **3** test.

Restoring an asset with rating **0** (an asset which broke after being used) to rating **1** grants **1** extra die to the test.

To attempt a test to create or improve and asset, you need a number of resources equal to the test's difficulty, which are consumed with the test, success or failure.

## Resources

You get resources when resting, either in the wilderness by making camp or in settlements when preparing for downtime. Sometimes you might also find assets that function as materials while adventuring.

A material can be anything from branches, steel, an animal carcass, a rare herb, to even something immaterial such as shelter from the forces of nature or comfortable bed. A material is something you either need to directly craft an asset or something which grants you the peace and quiet to work without disturbances. 

Resources come in three varieties.

### Sturdy

`Sturdy` resources are needed to create simple weapons and build structures. This category encompasses lumber, stone, shelter, and access to high-society.

### Supple

`Supple` resources are needed to create food, art, clothing and nurture animals. This category encompasses raw food, plants, and comfort (like a warm campfire).

### Precious

`Precious` resources are needed to create refined weapons and armor, fine instruments, and draft contracts. This category encompasses metal, paper, ink, gemstones, rare flowers, and indispensable information.
