---
bulwark: "- **Bulwark:** When defending, increase your effort by **1** for each **6** you roll."

deadly: "- **Deadly:** When attacking, decrease your opponent's minimum effort by **1** + this asset's masterpiece rating. This does not reduce minimum effort gained from one of your conditions."

durable: "- **Durable:** This asset only degrades below quality rating **1,** if you roll a **1.**"

ferocious: "- **Ferocious:** When attacking, increase your effort by **1** for each **6** you roll."

ranged: "- **Ranged:** Reduce morale damage you take by this asset's quality rating."

reach: "- **Reach:** When you create a [Boon](/character#boons) with Maneuver, it becomes [Enduring](/character#enduring-boons--banes)."

reliable: "- **Reliable:** Increase the minimum effort you gain from another asset by **1** + this asset's masterpiece rating."

tactical: "- **Tactical:** This asset may be used for Maneuver tests without penalty. When testing Maneuver, add **1** + its masterpiece rating as dice to your roll."

versatile: "- **Versatile:** This asset may be used with any attribute without penalty."

wicked: "- **Wicked:** When adding dice from a boon or bane created with Intuition, also add **1** + this asset's masterpiece rating as dice to your roll."


# Page settings
layout: default
keywords:
comments: false
permalink: /gear

# Hero section
title: Gear
description: Stuff about gear

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: BACK TO HOMEPAGE
        url: /
    next:
        content: Read Rules
        url: /character
---

# Gear

Gear [Assets](/assets) are more specific versions of general assets. They work just like normal assets but have additional properties. These properties are only for their corresponding skill [Conflicts](/conflicts), only when the asset is used on a skill test to gain minimum effort. An asset's properties can only be used as long as it has a quality rating of at least **1.**

Some assets may be only specifically be used to attack or defend. If they are used for minimum effort to attack or defend but weren't meant to do so, it is treated as an [Off-Label Use](/assets#off-label-usage).
Whether an asset is used to attack is signified by a 🗡 and by a 🛡 if it is meant to defend. Sometimes a different skill is listed, such as a **Longbow** is used to for Maneuver during Fight conflicts. If there is no additional information given, the gear asset is neither meant to attack nor defend, though it may, of course, still be used for that as an off-label use.
Outside of conflicts, gear assets may be used on skill tests regardless if they were meant for attacking or defending as long as it makes sense in the narrative.

Gear assets will become significantly more powerful when they are masterpieces, as you may use their abilities more often without degrading the asset.

Gear assets list a specific resource required to both create and improve them. When spending resources to craft while resting, at least one of them needs to be the listed resource for you to attempt the test.  
Some gear asset list an additional resource. You need one of each resource to create or improve the asset. In addition, if an additional resource is listed, it increases the number of resources required for any Craft tests by **1.** This does not increase the crafting test's difficulty, though this does increase the difficulty of tests to buy and sell the gear asset.

Rarely, gear assets require another masterpiece quality gear asset to be created.  
The difficulty for the test to create the new asset is the required asset's masterpiece rating, which is lost in the process (on either success or failure). If the test was successful, the desired gear asset is created and rating for the newly created asset is the required asset's masterpiece rating.  
After being created, the asset can be improved like any other asset.  
When buying and selling such an asset, its quality rating is considered to be doubled.

A gear asset may have a trait called `Exquisite`. This trait is relevant for Influence, Craft, and Resource tests, concerning the asset itself. Meaning an asset's `Exquisite` trait will increase the difficulty to create, improve, and buy it. Though it may also be invoked in social situations. Additionally, increase your effort by **1** when selling and `Exquisite` asset.

A gear asset may also have a property called **Fortified.** A **Fortified** asset's masterpiece rating is equal to its full quality rating, even outside of conflicts.

At the top of each category of gear, there is also generic variant without properties. They do not require specific resources to be crafted as they are simply normal assets. Of course, they are still associated with an attribute, just like any other asset.  
Use these for, for example, improvised weapons or instead of its lengthy list of gear entirely.

<div class="callout">
    <p>
        <strong>Why use Gear?</strong>
    </p>
    <p>
        You can play rpg-thingy without gear entirely, as assets are an already useful abstractions. If you use gear, you should use them for the purpose for which I designed them:
    </p>
    <ul>
      <li>To add meaningful choices to conflicts</li>
      <li>Because I think they're neat</li>
    </ul>
    <p>
        So if, for example, your game does not have a lot of Fight conflicts, gear adds little meaningful choice and may be neglected. Or simply use them cause you think they're neat.
    </p>
</div>



# Influence Gear

|    Gear    |   Use    | Properties | Resources  |
|:----------:|:--------:|:----------:|:----------:|
| **Finery** | 🛡 Vigor |     -      | `Precious` |
|            |          |            |            |
| **Finery** | 🛡 Vigor |     -      | `Precious` |



# Fight Gear

Assets for Fight conflicts come in two variations: weapons to attack and armor to defend. Though some, such as the **Helmet,** are not used to attack or defend, but they will aid you in Fight conflicts nonetheless.


## Vigor Gear

|      Weapon      |                  Properties                  |                      Resources                      |
|:----------------:|:--------------------------------------------:|:---------------------------------------------------:|
|    🗡 **Axe**    |                 _Ferocious_                  |                      `Sturdy`                       |
|   🗡 **Mace**    |                   _Deadly_                   |                      `Sturdy`                       |
| 🗡 **Warhammer** |             _Deadly, Ferocious_              |                `Sturdy` + `Precious`                |
|  🗡 **Poleaxe**  | _Deadly, Ferocious, Tactical_<br>`Exquisite` |                `Sturdy` + `Precious`                |
|  🛡 **Shield**   |             _Bulwark, Tactical_              |                `Sturdy` + `Precious`                |
|   🛡 **Mail**    |         **Fortified**<br>`Exquisite`         | `Supple` + `Precious`<br>_Masterpiece **Gambeson**_ |

{{ page.bulwark }}
{{ page.deadly }}
{{ page.ferocious }}
{{ page.tactical }}


## Intuition Gear

|        Weapon         |                   Properties                    |       Resources       |
|:---------------------:|:-----------------------------------------------:|:---------------------:|
|     🗡 **Knife**      |                    _Wicked_                     |      `Precious`       |
|     🗡 **Dagger**     |                _Deadly, Wicked_                 | `Supple` + `Precious` |
|   🗡 + 🛡 **Sword**   |                   _Versatile_                   |      `Precious`       |
|   🗡 + 🛡 **Estoc**   |             _Deadly_<br>`Exquisite`             |      `Precious`       |
| 🗡 + 🛡 **Longsword** | _Ferocious, Tactical, Versatile_<br>`Exquisite` | `Supple` + `Precious` |
|    🛡 **Gambeson**    |                    _Durable_                    |       `Supple`        |

{{ page.deadly }}
{{ page.durable }}
{{ page.ferocious }}
{{ page.tactical }}
{{ page.versatile }}
{{ page.wicked }}


## Reason Gear

|     Weapon      |                Properties                 |       Resources       |
|:---------------:|:-----------------------------------------:|:---------------------:|
|  🗡 **Spear**   |                _Tactical_                 |       `Sturdy`        |
|   🗡 **Bill**   |            _Tactical, Wicked_             | `Sturdy` + `Precious` |
| 🗡 **Crossbow** |            _Ranged, Tactical_             |  `Sturdy` + `Supple`  |
|   🗡 **Pike**   |             _Reach, Tactical_             | `Sturdy` + `Precious` |
| 🗡 **Arbalest** | _Deadly, Ranged, Tactical_<br>`Exquisite` | `Sturdy` + `Precious` |
| 🗡 **Longbow**  | _Ranged, Reach, Tactical_<br>`Exquisite`  |  `Sturdy` + `Supple`  |
| 🛡 **Buckler**  |                _Tactical_                 |       `Sturdy`        |

{{ page.deadly }}
{{ page.reach }}
{{ page.ranged }}
{{ page.tactical }}
{{ page.wicked }}


## Special Gear

|      Weapon       |         Properties         |       Resources       |
|:-----------------:|:--------------------------:|:---------------------:|
| 🗡 **Ammunition** |         _Reliable_         |       `Supple`        |
|   🗡 **Barbed**   |   _Ferocious, Reliable_    | `Supple` + `Precious` |
|   🗡 **Bodkin**   |     _Deadly, Reliable_     | `Supple` + `Precious` |
|   🛡 **Helmet**   |         _Reliable_         |      `Precious`       |

{{ page.deadly }}
{{ page.ferocious }}
{{ page.reliable }}



# Maneuver Gear

|         Name         |     Use      | Properties | Resources |
|:--------------------:|:------------:|:----------:|:---------:|
|  **Climbing Gear**   | 🗡 Intuition |            |           |
| **Draft Horse/Mule** |   🗡 Vigor   |            |           |
|   **Riding Horse**   | 🛡 Intuition |            |           |
|     **Warhorse**     | 🗡 🛡 Vigor  |            |           |

- **Warhorse:** When attacking with a weapon with the _Reach_ property, it also gains the _Versatile_ property for that attack



# Wilderness Gear

|       Name        |   Use    | Properties | Resources |
|:-----------------:|:--------:|:----------:|:---------:|
|     **Cloak**     | 🛡 Vigor |            |           |
|  **Rowing Boat**  | 🗡 Vigor |            |           |



# Craft Gear




# Means Gear


