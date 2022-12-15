---
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

Gear [Assets](/assets) are more specific versions of general assets. They work just like normal assets but have additional properties. These properties are only for their corresponding skill [conflicts](conflicts), only when the asset is used on a skill test. An asset's properties can only be used as long as it has a quality rating of at least **1.**

Some assets may be only specifically be used to attack or defend. If they are used for minimum effort to attack or defend but weren't meant to do so, it is treated as an off-label use and its rating is considered to be **1** (or its masterpiece rating, if the asset is a masterpiece) for that test.  

Gear assets also list the specific resource required to both craft and improve them.  
Some gear asset list an additional resource as required when crafting it. Either of the listed resources may be used to create or improve the asset. In addition, if an additional resource is listed, it increases the number of resources required for any Craft tests by **1,** though this does not increase the crafting test's difficulty. This also increases the difficulty of tests to buy and sell the gear asset.

Very few gear assets require another gear asset of at least masterpiece quality to be created. The masterpiece assets consumed by the process; the corresponding rating for the new asset is the rating of the consumed asset's masterpiece trait. After being created, the asset can be repaired like any other asset.


# Influence Gear




# Fight Gear

Assets for Fight conflicts come in two variations: weapons to attack and armor to defend. Though some weapons (such as the bow) have a different use they will aid you in Fight conflicts nonetheless.


## Weapons

|          Weapon           |  Attack   |            Properties             |             Resources              |
|:-------------------------:|:---------:|:---------------------------------:|:----------------------------------:|
|          **Axe**          |   Vigor   |             _Deadly_              |              `Sturdy`              |
|         **Mace**          |   Vigor   |            _Piercing_             |              `Sturdy`              |
|         **Sword**         | Intuition |     _Defensive<br>Versatile_      |             `Precious`             |
|        **Knives**         | Intuition |             _Wicked_              |             `Precious`             |
|         **Spear**         |  Reason   |              _Reach_              |              `Sturdy`              |
|                           |           |                                   |                                    |
|       **Warhammer**       |   Vigor   |       _Deadly<br>Piercing_        |       `Sturdy` + `Precious`        |
|         **Estoc**         | Intuition |      _Defensive<br>Piercing_      |       `Precious` + `Supple`        |
|         **Bill**          |  Reason   |         _Reach<br>Wicked_         |       `Sturdy` + `Precious`        |
|         **Pike**          |  Reason   |             _Ranged_              |       `Sturdy` + `Precious`        |
|                           |           |                                   |                                    |
|        **Poleaxe**        |   Vigor   |   _Deadly<br>Piercing<br>Reach_   | `Sturdy` + `Precious`<br>Intricate |
|       **Longsword**       | Intuition | _Defensive<br>Reach<br>Versatile_ | `Precious` + `Supple`<br>Intricate |
|                           |           |                                   |                                    |
| **Longbow /<br>Crossbow** |     -     |      _Ammunition<br>Ranged_       |        `Supple` + `Sturdy`         |
|        **Arrows**         |  Reason   |        _Deadly<br>Missile_        |              `Supple`              |
|         **Bolts**         |  Reason   |       _Piercing<br>Missile_       |              `Sturdy`              |

##### Ammunition

- A **Longbow** requires **Arrows** with quality rating of at least **1** to be used
- A **Crossbow** requires **Bolts** with quality rating of at least **1** to be used

> This weapon requires ammunition to be used.

##### Deadly

When attacking, increase your effort by **1** for each **6** you roll more than your opponent.

> This weapon hits harder or finds its target more precisely.

##### Defensive

When defending with this weapon's attack Attribute, may add its masterpiece rating + **1** as dice to the roll in addition to gaining minimum effort from this or another asset.

> This weapon offers respectable defensive qualities for anyone with fast reflexes.

##### Piercing

When attacking, decrease your opponent's minimum effort by **1** for each **1** they roll.

> This weapon is especially good at piercing or ignoring an opponent's armor.

##### Ranged

This weapon also has the _Reach_ property (the attack attribute is considered to be Reason).

In addition, if you use this weapon to create a boon with Maneuver, it becomes [enduring](/character#enduring-boons--banes).

> This weapon excels at keeping foes at a distance.

##### Reach

- This weapon is also an asset for [Positioning](/conflicts#positioning) with Maneuver and its attack attribute
- While defending, if you have a [Boon](/character#boons) created with Maneuver:
  - you may force the attackers to attack with Maneuver instead of Fight,
  - you may defend with Maneuver instead of Fight,
  - and this weapon gains the _Defensive_ property

> This weapon's main purpose is keeping an opponent at a distance and exploiting that advantage.

##### Versatile

May be used to attack with any attribute without penalties.

> This weapon can be used to attack in multiple different ways without compromise.

##### Wicked

When attacking, double all dice from boons and banes which were created with Intuition.

> This weapon exploits an opponent's weakness and surprises better than any other.

> This weapon exploits an opponent's weakness and surprises better than any other.

##### Intricate

For Influence, Craft, and Resource tests, this weapon's quality rating is increased by **1.**  
This also increases the difficulty to of tests to create, improve, buy, and sell this weapon.

> This weapon is an impressive feat of craftsmanship.

##### Missile

When attacking with Reason, if your opponent successfully defends, ignore all stress and morale damage you would suffer.

- **Arrows** require a **Longbow** with quality rating of at least **1** to be used
- **Bolts** require a **Crossbow** with quality rating of at least **1** to be used

> Missing a foe from a safe distance is a lot healthier for body and soul than missing up close.



## Armor

|    Name    |  Defend   |       Properties        |               Resources                |
|:----------:|:---------:|:-----------------------:|:--------------------------------------:|
| **Padded** | Intuition |       _Reliable_        |                `Supple`                |
| **Shield** |  Reason   |       _Defensive_       |                `Sturdy`                |
|            |           |                         |                                        |
|  **Mail**  |   Vigor   | _Fortified<br>Reliable_ | `Precious`<br>_Masterpiece **Padded**_ |

##### Defensive

When defending, may add this armor's masterpiece rating + **1** as dice to the roll in addition to gaining minimum effort from this or another asset.

> This armor not only protects you but also increases your protection on top of other armor.

##### Fortified

When defending with Vigor, the masterpiece rating of this armor is equal to its full armor rating.

> There is no better protection than fortified armor.

##### Reliable

When defending, this armor degrades below armor rating **1** only if you roll a **1.**

> As long as it does not suffer any direct hits, this armor will protect you.



# Maneuver Gear

|         Name         | Properties |     Resource     |
|:--------------------:|:----------:|:----------------:|
|  **Climbing Gear**   |            |                  |
| **Draft Horse/Mule** |            |                  |
|   **Riding Horse**   |            |                  |
|     **Warhorse**     |            |                  |

- **Warhorse:** When attacking with a weapon with the _Reach_ property, it also gains the _Versatile_ property for that attack


# Wilderness Gear

|       Name        | Properties |     Resource     |
|:-----------------:|:----------:|:----------------:|
|     **Cloak**     |            |                  |
|  **Rowing Boat**  |            |                  |



# Craft Gear




# Means Gear


