---
# Page settings
layout: default
keywords:
comments: false
permalink: /conflicts

# Hero section
title: Conflicts
description: Stuff about conflicts

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Assets
        url: /assets
    next:
        content: Next page
        url: '#'
---

# Conflicts

When the stakes are high, and you want to circle in on each individual decision to see who comes out on top, then that calls for a conflict. A lot of the time fights with important enemies will be handled through conflicts, as will crucial chases, heated debates, and even something like a deciding competition between craftsmen or trade guilds.

A conflict is divided between at least two sides, each with their own captain, though there can be more than two teams with different goals. Each side has a captain and needs at least one character to fulfill that role but may include many more characters.

To start a conflict, establish a Goal for each side and name a captain for each side. Most of the time this will be the character who initiated the conflict and their target.  
All remaining characters who want to participate in the conflict either join an existing team or, if their goal differs from the established goals, form a new team with them as captain.  
A character may abstain from a conflict, though that means they can only witness and not influence its outcome.

Then determine the relevant [Skill](/skill-list) for the conflict. ([Fight](/skill-list#fight) for skirmishes; [Influence](/skill-list#influence) for debates; [Maneuver](/skill-list#maneuver) for chases; etc.)



# Morale

During a conflict, each team's capability to fight on is represented by their morale, or more specifically, the damage to their morale. A team captain's main responsibility is to ensure their team's morale does not break lest they will most likely lost the conflict.

### Building Morale

Whenever a member of a team in a conflict succeeds on a test, their captain notes the margin of effort and adds it to their team's morale.

### Damaging Morale

Whenever a member of a team in a conflict fails to succeed on a test, their captain notes the margin of effort and subtracts it from their team's morale.

When a team's morale drops below **0,** the team as a whole gain a `Broken Morale`. Increase that trait's rating by **1** for each point of morale below **0.**  
This trait counts as a character trait to be used against the teams members during contests.

### Keeping Morale

At the end of each turn, if a team has a `Broken Morale` trait, its captain must test a skill that is not the relevant skill to keep their team's morale from breaking. The test's base difficulty is equal to the `Broken Morale` trait's rating.

If the captain does not succeed on the test, their team's morale breaks.  
Otherwise, or if the team does not have a `Broken Morale` trait, the team keeps their morale.

A captain's teammates may help their captain keep morale by testing with them as a group (increase the test's difficulty by **1** for each teammate who tests beyond the captain).



# Positioning

In rpg-thingy, not ever does a conflict erupt spontaneously out of the blue. There is always at least a brief moment, sometimes even a lengthy period of time, a calm before the storm, in which sides anticipate imminent confrontation and position themselves.  
If characters are surprised at the start of a conflict, then only ever about _how_ their opponent engaged them, maybe even _who exactly_ engaged them but not ever that they were engaged at all.

Before a conflict, a team positions, either literally by forming a formation or leveraging their environment; but also figuratively, by motivating their comrades, ensuring supply lines, researching the enemy and sneaking up on them.

To position for a conflict, test a skill that is not the relevant skill and note the effort you achieved.


## Benefits

Each participant in the conflict chooses a benefit depending on their noted effort. There are two general benefit to choose from and three that are each available depending on what attribute you tested with.  
These benefits only last for the duration of the conflict.

### Any Attribute

- Create a trait on the scene with rating equal to your effort
- Create a Boon on yourself or an ally (or a Bane on an opponent) with rating equal to your effort

### Vigor

- Add your effort to your team's morale

### Intuition

- Discard **1** asset with rating equal to or less than your effort for the duration of the conflict; or regain **1** asset with rating equal to or less than your effort which was discarded during this conflict

### Reason

- Learn of the highest rated hidden trait with rating equal to or less than your successes



# The Conflict

A conflict is essentially a sequence of [Contests](/skill-tests#contests).

Turn order is determined by whoever initiated the conflict. Should it ever be uncertain, the teams with the highest morale goes first. During a team's turn each of its members may act in whatever order they choose until each member has acted once.  
When all members of a team have acted, its captain tests to keep morale if its morale has been broken. Then continue with the next team in turn order.


## Acting during a Conflict

To act, a character has three choices, either attack an opponent to inflict stress upon and damage their morale, try to gain an advantage just like you would during positioning, or surrender.

### Attacking

To attack, test the relevant skill with any attribute against an opponent of your choice.

If your opponent achieved more effort, they inflict the difference as damage to your team's morale.

If you achieved more effort, you inflict the difference as stress to your opponent. You also inflict that difference as damage to your opponent's morale.  
If the defender struggles to defend because of your disposition, they can only reduce either the stress you inflict on them _or_ the damage to their team's morale but not both.

Anyone may help their teammates defend as a group when one of their allies is attacked, but they can only do so, if they are not themselves attacked. To keep an opponent from protecting one of their allies, have one of your teammates attack and occupy them.

### Positioning during Conflicts

Instead of testing the relevant skill to inflict stress on an opponent and their team's morale, you may test a skill, as if positioning. You still choose an opponent who will try to stop or at least hinder your efforts.

Instead of inflicting stress and reducing your opponent's morale, you gain an effect as you would during positioning, though your effort is reduced by your opponent's effort.  
Your opponent cannot defend against your efforts with the attribute you are disposed against.

Your opponent still damages your Morale as normal, if they achieve more effort than you.

### Surrendering

During their turn, a character may choose to surrender and remove themselves from the conflict. They can no longer influence the outcome, but they are out of harm's way.  
When a team member surrenders or otherwise laves the conflict, they inflict **1** damage to their team's morale.  
When a team's captain surrenders or otherwise laves the conflict, they damage their team's morale by the number of remaining members on their team.

## Ending a Conflict

When all members of a team have surrendered or are otherwise no longer able to act, they lose the conflict and do not achieve their goal.

When a team's morale breaks, any of its members may enter their [Last Stand](#last-stand) to potentially prevent them from losing.

A team, whose morale has been broken, loses the conflict and does not achieve its goal if either of the following conditions is true:

- None of its members have entered their Last Stand.
- All its members, who have entered their Last Stand have perished.
- All their opponents have been defeated (meaning all teams lose the conflict).

When only one team whose morale has not been broken remains, they win the conflict and achieve their goal.

Should all teams lose the conflict, it spells catastrophic disaster. Depending on the narrative, all teams might achieve their goals or none at all. A battle might leave the countryside in ruins with neither party having achieved their objective; the plotting of two rival underground factions might drive them both to ruin as they assure their mutual destruction; a heated debate between the king and his advisor about succession rights might end in them finding understanding for each other, leaving their disputes behind, and deciding on a third solution. When in doubt, settle for a compromise without any winners.



# Last Stand

Should you not have an empty box to absorb stress you suffered during a conflict, and you spend Favor to gain a new trait (as detailed in [Stress](/conditions-and-resting#stress)), you must choose between the following two options:

- Immediately surrender from the conflict.
- Enter your Last Stand.

Your Last Stand represents one last chance to still achieve your team's goal, to rage, potentially for the last time, even against the most desperate of odds.

During your Last Stand you can still act normally in the conflict, despite your grievous setbacks until your leave your Last Stand. Resolve your actions as you normally would with the following exceptions:

- During your Last Stand, if any of your actions cause the morale of an opposing team to break, you gain an [Epiphany](/epiphany)
- When all opposing teams have lost the conflict, your leave your Last Stand and you live to see another day.
- If, at any point during your Last Stand, you suffer any stress, you perish. (Depending on the type of conflict, you either die in battle, are exiled forever, completely lose you mind, etc.)



# Uncontested Conflicts

Though most conflicts are contested, sometimes the narrative calls for a conflict without any active opposition, such as surviving a long and arduous journey, creating an unfathomable piece of art, or undertaking a ludicrous economic endeavour.

An uncontested conflict works very similarly to a normal conflict,
