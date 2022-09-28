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
        content: Conditions & Resting
        url: /conditions-and-resting
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

To position for a conflict, test a skill that is not the relevant skill and notes the effort they achieved.


## Benefits

Then, each participant in the conflict chooses a benefit depending on their noted effort. There is one general benefit to choose from and three that are each available depending on what attribute you tested with.  
These benefits only last for the duration of the conflict.

### Any Attribute

- Create a trait on the scene with rating equal to your effort

### Vigor

- Create a Boon on yourself or an ally (or a Bane on an opponent) with rating equal to your effort
- Add your effort to your team's morale

### Intuition

- Discard **1** asset with rating equal to or less than your effort for the duration of the conflict
- Regain **1** asset with rating equal to or less than your effort which was discarded during this conflict

### Reason

- Learn of the highest rated hidden trait with rating equal to or less than your successes



# The Conflict

A conflict is essentially a sequence of [Contests](/skill-tests#contests).

Turn order is determined by whoever initiated the conflict. Should it ever be uncertain, the captain with the highest effort and their team go first. During a team's turn they may act in whatever order they choose until each member has acted once.  
When all members of a team have acted, its captain tests to keep morale if its morale has been broken. Then continue with the next team in turn order.


## Acting during a Conflict

During their turn, a character may choose to surrender and remove themselves from the conflict. They can no longer influence the outcome, but they are out of harm's way.  
When a team member surrenders or otherwise laves the conflict, they inflict **1** damage to their team's morale.  
When a team's captain surrenders or otherwise laves the conflict, they damage their team's morale by the number of remaining members on their team.

To act, a character has two choices, either attack an opponent to inflict stress upon and damage their morale, or try to gain an advantage just like you would during positioning.

### Attacking

To attack, test the relevant skill with any attribute against an opponent of your choice.

If your opponent achieved more effort, they inflict the difference as damage to your team's morale.

If you achieved more effort, you inflict the difference as stress to your opponent. You also inflict that difference as damage to your opponent's morale.  
If the defender struggles to defend because of your disposition, they can only reduce either the stress you inflict on them _or_ the damage to their team's morale but not both.

### Positioning during Conflicts

Instead of testing the relevant skill to inflict stress on an opponent and their team's morale, you may test a skill, as if positioning. You still choose an opponent who will try to stop or at least hinder your efforts.

Instead of inflicting stress and reducing your opponent's morale, you gain an effect as you would during positioning, though your effort is reduced by your opponent's effort.  
Your opponent cannot defend against your efforts with the attribute you are disposed against.

Your opponent still damages your Morale as normal, if they achieve more effort than you.


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



# Disposition

The three attributes do not only form the foundation of your character but of all other characters and creatures you will encounter on your adventures, sometimes even the environment itself.

The scoundrel, who ambushes you in the gloomy ally; the moonlit lord, who anticipates your every move; even passive obstacles such as a river's roaring current, they all have attributes just like you.  
When you create your character, you choose one of two possible dispositions you have against these foes, and edge you have during conflicts. Your disposition represents a certain knack you have against the other approaches, a weakness you might exploit. But beware, for your enemies also have dispositions.

Your disposition may impose a penalty on your target when they defend against you with a certain attribute. Each of your attributes is disposed against one of the other two attributes. During a conflict, when an opponent defend against you with an attribute you are disposed against, they can only prevent stress you deal them _or_ damage you deal to their team's morale, not both.


## Disposition I

**Reason struggles to defend against your Vigor:** You are a force too overwhelming, your attacks are too mighty, your speeches are too gripping, they cannot be faced with a cool demeanour for you leave no demeanour cool.

**Vigor struggles to defend against your Intuition:** You change course too deftly, your attacks are a stunning barrage, your lies are too tricky a web to navigate, they cannot be faced head-on with brute force for you bend like grass in the wind.

**Intuition struggles to defend against your Reason:** Your plans are too well-thought-out, your attacks are too precise, your rhetorical traps are too sophisticated, they cannot be weaseled out of for you have thought of everything.

## Disposition II

**Intuition struggles to defend against your Vigor:** You are a force too overwhelming, your attacks are too mighty, your speeches are too gripping, they cannot be faced with the cowardice of a weasel for you leave no place left to hide.

**Reason struggles to defend against your Intuition:** You change course too deftly, your attacks are a stunning barrage, your lies are too tricky a web to navigate, they cannot be faced with a cool demeanour for they still think about your last move while you are crossing the finish line.

**Vigor struggles to defend against your Reason:** Your plans are too well thought out, your attacks are too precise, your rhetorical traps are too sophisticated, they cannot be faced head-on with brute force for every careless step spells disaster.



# Static conflict






# Boons & Banes

Sometimes during a scene or [conflict](conflicts) you want to help yourself or an ally, or hinder an opponent. In that case, you may create a Boon to aid or a Bane to hinder. In conflicts, you may to so during [Positioning](/rules/conflicts.md#positioning) and hence, also during the conflict like any other Positioning.

When you test a skill to create a Boon or Bane, the number of successes (or excess successes if someone defends against your attempt) determines the Boon's/Bane's rating.

You may also turn excess successes after you have succeeded on a test into a Boon on yourself or, if you succeeded in a contest, into a Bane on your opponent by spending up to **1** Favour for each excess success to create a Boon/Bane with rating equal to the amount of Favour spent this way.

When a Boon or a Bane is created, its creator associates it either with the [Approach,](Approaches) or the [Skill](Skills) they used to create it. If the Bane or Boon is created during a conflict, its creator may choose attacking or defending instead of an Approach or a Skill.

- If an Approach was chosen, the Boon or Bane may only be used with the associated Approach but any skill.
- If a skill was chosen, the Boon or Bane may only be used with the associated skill but any Approach.
- If attacking was chosen, the Boon or Bane may be used to attack during the conflict with any Approach and any skill but not to defend.
- If defending was chosen, the Boon or Bane may be used to defend during the conflict with any Approach and any skill but not to attack.
- If a Boon or Bane is used with a different action, Approach or skill than intended, its rating is halfed (rounded down).

Boons & Banes only last for the context they were created in. In most cases that means for the duration of the conflict or for the duration of the scene.


## Boons

A Boon may be used on any roll where it would make sense that it would help you. When you use a Boon, add dice equal to the Boon's rating to your roll. Though, after you do, the Boon is used up and vanishes.

If you have multiple Boons which might fit, you have to choose only one of them.

Boons with extraordinary high ratings may let you add a number of dice (as shown below) to your roll without using up the Boon and without it vanishing.

|                      **Boon Rating**                      |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  |
|:---------------------------------------------------------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Dice that can be added<br/>without the Boon vanishing** |  -  |  -  |  1  |  1  |  2  |  2  |  3  |  3  |  4  |  4  |

> Cyrene wants to hide and sneak behind enemy lines. The camp is well guarded; someone is expecting her. The GM sets the obstacle to sneak into the camp at **2.** Cyrene tests Maneuver with the Approach of Intuition as she steps from shadow to shadow and rolls a phenomenal **5** successes. Easily enough to succeed. She spends **1** Favour and turns the **3** excess successes into a Boon named `Hidden from Sight` with rating **3** on herself. She chooses to associate it with Intuition instead of Maneuver.
>
> In the enemy camp, she finds her target of her assassination mission: the loathsome merchant king Samson. Cyrene and the GM agree that they are more interested in the fallout of this event than the assassination itself, so murdering the merchant discretely and making it out unseen will be a resolved with a  single test with obstacle **3.**
>
> Cyrene's initial roll shows only **2** successes, but she may now invoke her Boon `Hidden from Sight` to gain **3** extra dice for her assassination attempt. The **3** extra dice turn her attempt into a success. The Boon has been used and vanishes and so does Cyrene into the night.


## Banes

Banes are temporary detrimental [traits](traits), though Banes, are one-use only. After a Bane increased the obstacle of a test or was used by an opponent to get extra dice, it vanishes.

If an opponent has multiple Banes which you might use to aid you, you have to choose only one of them.

A Bane is not itself one of your opponent's traits, so you may invoke both a Boon and a detrimental trait for additional dice.

If you are affected by a Bane, your opponent's may use it to add dice to their rolls during contests and conflicts. If you instead test against a static obstacle, it is always assumed that the GM compels your highest rated Bane.

Banes with extraordinary high ratings may let you add a number of dice (as shown below) to your roll without using up the Bane and without it vanishing.

|                      **Bane Rating**                      |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  |
|:---------------------------------------------------------:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Dice that can be added<br/>without the Bane vanishing** |  -  |  -  |  1  |  1  |  2  |  2  |  3  |  3  |  4  |  4  |

> The caravan Maro is escorting is being ambushed. One of the bandits is covered in mean battle scars, so Maro decides to leverage his superior mobility before engaging him directly. He tries to create a Bane with Maneuver and Intuition on the bandit by throwing sand into his eyes, who fails to defend against the attempt. Maro rolls **2** excess successes and creates a Bane named `Sand in my Eyes!` with rating **2** on the bandit. He chooses to associate it with defending.
>
> Anyone attacking the bandit or defending against one of his attacks may now add **2** to their roll once, as either way, the Bane vanishes after it has been used.


## Enduring Boons & Banes

Sometimes either extremely powerful effects like magic or the GM for narrative reasons might create Boons or Banes that endure for longer but a moment.

An enduring Boon degrades by **1** rating when it is used to add half or more (rounded up) of its rating as dice to a roll (instead of vanishing like normal Boon would).

An enduring Bane degrades by **1** rating after its rating was added to an obstacle.

When an enduring Boon/Bane reaches a rating of **0,** it vanishes.

An enduring Boon/Bane only degrades whenever a normal Bane/Boon would degrade (so extremely high rated enduring Boons and Banes may last even longer).

Enduring Banes/Boons may exist beyond a single conflict/scene, if it makes narrative sense.

> Cyrene and Maro have sneaked into a sleeping dragon's hoard to recover a long-lost artifact. The GM makes it quite clear that any test they fail while searching for the artifact will draw the attention of the dragon, though, thankfully, the dragon is asleep and has an enduring Bane on it called `Caught in a Deep Slumber` with a rating of **3** and associated with Intuition.
>
> Maro starts climbing the hoard of gold with a Maneuver test but the dice forsake him, and he rolls no successes. He invokes the `Caught in a Deep Slumber` Bane for free and adds **3** extra dice to his roll, turning it into a success, though the `Caught in a Deep Slumber` Bane degrades to a rating of **2** as a result. The dragon turns in his sleep, one eye almost opens but Maro remains unnoticed. The two of them have some breathing room before the dragon wakes. For now.
