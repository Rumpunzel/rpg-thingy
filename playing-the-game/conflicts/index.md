---
layout: default
title: Conflicts
description: Stuff about conflicts
parent: Playing the Game
nav_order: 3
---

# Conflicts

When the stakes are high, and you want to circle in on each individual decision to see who comes out on top, then that calls for a conflict. A lot of the time fights with important enemies will be handled through conflicts, as will crucial chases, heated debates, and even something like a deciding competition between craftsmen or trade guilds.

A conflict is divided between at least two sides, each with their own captain, though there can be more than two teams with different goals and essentially a sequence of [Contests](../skill-tests#contests). Each side has a captain and needs at least one character to fulfill that role but may include many more characters.


## Starting a Conflict

To start a conflict, establish a goal for each side and name a captain for each side. Most of the time this will be the character who initiated the conflict and their target.  
All remaining characters who want to participate in the conflict either join an existing team or, if their goal differs from the established goals, form a new team with them as captain.  
A character may abstain from a conflict, though that means they can only witness and not influence its outcome.

Then determine the relevant [Skill](../../characters/skills) for the conflict. ([Fight](../../characters/skills#fight) for skirmishes; [Influence](../../characters/skills#influence) for debates; [Maneuver](../../characters/skills#maneuver) for chases; etc.)

Turn order is determined by whoever initiated the conflict.

During a team's turn each of its members may act in whatever order they choose until each member has acted once.  
When all members of a team have acted, its captain tests to keep morale if its morale has been broken. Then continue with the next team in turn order.


## Ending a Conflict

When all members of a team have surrendered or are otherwise no longer able to act, they lose the conflict and do not achieve their goal.

A team, whose morale has been broken, loses the conflict and does not achieve its goal if either of the following conditions is true:

- None of its members have entered their [Last Stand](#last-stand).
- All its members, who have entered their Last Stand have perished.
- All their opponents have been defeated (meaning all teams lose the conflict).

When only one team whose morale has not been broken remains, they win the conflict and achieve their goal.

Should all teams lose the conflict, it spells catastrophic disaster. Depending on the narrative, all teams might achieve their goals or none at all. A battle might leave the countryside in ruins with neither party having achieved their objective; the plotting of two rival underground factions might drive them both to ruin as they assure their mutual destruction; a heated debate between the king and his advisor about succession rights might end in them finding understanding for each other, leaving their disputes behind, and deciding on a third solution. When in doubt, settle for a compromise without any winners.



# Morale

During a conflict, each team's capability to fight on is represented by their morale, or more specifically, the damage to their morale. A team captain's main responsibility is to ensure their team's morale does not break lest they will most likely lost the conflict.

## Building Morale

Whenever a member of a team in a conflict succeeds on a test, their captain adds **1** to their team's morale.

## Losing Morale

Whenever a member of a team in a conflict fails to succeed on a test, their captain subtracts **1** from their team's morale.

When a team's morale drops below **0,** the team gains a `BROKEN MORALE` trait with rating equal to the amount of morale they are below **0.**  
This trait counts as a character trait for each team member and may be used against them like any other character trait.

When a team's morale reaches **0** or more, they lose their `BROKEN MORALE` trait.

## Keeping Morale

At the end of each turn, if a team has a `BROKEN MORALE` trait, its captain must test a skill that is not the relevant skill to keep their team's morale from breaking. The test's base difficulty is equal to the `BROKEN MORALE` trait's rating.

If the captain does not succeed on the test, their team's morale breaks.  
Otherwise if the captain succeeds, or if the team does not have a `BROKEN MORALE` trait, the team keeps their morale.

A captain's teammates may help their captain keep morale by testing with them as a group (increase the test's difficulty by **1** for each teammate who tests beyond the captain).



# Acting during a Conflict

To act, a character has three choices, either attack an opponent to inflict stress upon and damage their morale, try to gain an advantage just like you would during positioning, or surrender.


## Attacking

To attack, test the relevant skill with any attribute against an opponent of your choice.

If your opponent achieved more effort, they inflict **1** damage to your team's morale (see [Losing Morale](#losing-morale)).

If you achieved more effort, you inflict the difference as stress to your opponent.

Anyone may help their teammates defend as a group when one of their allies is attacked, but they can only do so, if they are not themselves attacked. To keep an opponent from protecting one of their allies, have one of your teammates attack and occupy them.


## Gaining an Advantage

Instead of testing the relevant skill to inflict stress to an opponent, you may test a different skill to gain an advantage.  

You still choose an opponent who will try to stop or at least hinder your efforts and, just as with attacking, your opponent cannot defend against your efforts with the attribute you are disposed against.

Instead of inflicting stress, and depending on the margin of effort you achieved, you gain an advantage. These advantages only last for the duration of the conflict.  
Your opponent still damages your morale if they achieve more effort than you.

There is a general benefit and three that are each available from which to choose depending on with which attribute you tested.  

|   Attribute   |                                                                                          Advantage                                                                                           |
|:-------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|    **Any**    |                                          [Create a Boon or Bane](../boons-&-banes#creating-boons--banes) with rating equal to your margin of effort                                          |
|   **Vigor**   |                                                                       Add your margin of effort to your team’s morale                                                                        |
| **Intuition** | Discard **1** of your opponent's asset with rating equal to or less than your margin of effort / Gain **1** asset with rating equal to or less than your margin of effort discarded this way |
|  **Reason**   |                                                         Learn of your opponent's lowest rated secret trait, which is unknown to you                                                          |

{: .important }
> The caravan Maro is escorting is being ambushed by bandits. One of the bandits is covered in mean battle scars, so Maro decides to leverage his superior mobility before engaging him directly. He tries to create a bane with Maneuver and Intuition on the bandit by running circles around him and throwing sand into his eyes. The bandit fails to defend against the attempt. Maro rolls **2** excess hits and creates a bane named `SAND IN MY EYES!` with rating **2** on the bandit.
>
> Anyone attacking the bandit or defending against one of his attacks may now add **2** to their roll once after which the bane vanishes.


## Surrendering

During their turn, a character may choose to surrender and remove themselves from the conflict. They can no longer influence the outcome, but they are out of harm's way.  
When a team member surrenders or otherwise laves the conflict, they inflict **1** damage to their team's morale.  
When a team's captain surrenders or otherwise laves the conflict, they damage their team's morale by the number of remaining members on their team.



# Last Stand

Should you not have an empty stress box to absorb stress you suffered during a conflict, and you spend Favor to gain a new trait (as detailed in [Stress](../../characters/wounds#stress)) and you must choose between the following two options:

- Immediately surrender from the conflict.
- Enter your Last Stand.

Additionally, when a team's morale breaks, any of its members, which have not yet entered their Last Stand, may enter their Last Stand to potentially prevent them from losing.

Your Last Stand represents one last chance to still achieve your team's goal, to rage, potentially for the last time, even against the most desperate of odds.

During your Last Stand you can still act normally in the conflict, despite your grievous setbacks until your leave your Last Stand. Resolve your actions as you normally would with the following exceptions:

- When all opposing teams have lost the conflict, you leave your Last Stand and you live to see another day. You gain an [Epiphany](../advancement#epiphany).
- If, at any point during your Last Stand, you cannot fully absorb the stress you suffered, or your team's morale breaks again, you perish. (Depending on the type of conflict, you either die in battle, are exiled forever, completely lose you mind, etc.)



# Preludes

In general, in Gauntlet Forge, not ever does a conflict erupt spontaneously out of the blue. There is always at least a brief moment, a calm before the storm, in which sides anticipate imminent confrontation. If characters are surprised at the start of a conflict, then it should be only ever about _how_ their opponent engaged them, maybe even _who exactly_ engaged them but not ever that they were engaged at all.

Sometimes there is more than but a brief moment. For example, an army forming formation before a battle; hunters tracking a beast before the confrontation; a chase before interrogating a subject. For these occasions, introduce a prelude before the actual conflict.

During a prelude, all teams test to [Gain an Advantage](#gaining-an-advantage). If it would not make sense to gain that advantage through a contest, set the difficulty based on an environmental trait and resolve it as a simple test.



# Uncontested Conflicts

Though most conflicts are contested, sometimes the narrative calls for a conflict without any active opposition, such as surviving a long and arduous journey, creating an unfathomable piece of art, or undertaking a ludicrous economic endeavour.

An uncontested conflict works very similarly to a normal conflict,
