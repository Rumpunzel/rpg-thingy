---
layout: default
title: Skill Tests
description: Stuff about skill tests
parent: Playing the Game
nav_order: 1
has_children: true
---

# Skill Tests

When you consult the dice, the game calls it a **Skill Test.** Forge Gauntlet uses a **d6** dice pool system. So whenever the game calls for dice to be rolled, roll a handful of six-sided dice equal to the rating of the [Attribute](../../characters/attributes) with which you chose to test. Each die can either be a hit or a miss, depending on if its face shows at least the training of the skill with which you chose to test.  
All hits counted together are called **Effort.** Achieving more Effort is always better.

A test has a difficulty, a number that defines how much Effort it takes to succeed on the test, otherwise the test is a failure. There are no tests without consequences. No matter if you succeed on a test or fail it, you will either get what you want and/or suffer a setback. Either way, after a test both the narrative and your character make progress, either by achieving your goal or by growing with your failures.


## Challenges

Challenges are the most basic form of test. A test is simple when there is no other character or creature to directly or indirectly keep you from achieving your goal, or they are simply trying to keep you from achieving your goal without having any other goals of their own.

{: .note-title }
> Examples of Challenges
>
> - Jumping a ravine
> - Haggling with a merchant
> - Forging a weapon
> - Quietly murdering a guard keeping watch
> - Buying a horse


## Contests

When another character, creature, or even multiple not only want to keep you from achieving your goal but have a goal of their own; or when you want to keep them from achieving their goal, the action is resolved in a contest.

{: .note-title }
> Examples of Contests
>
> - A race to the finish line
> - A bidding war at an auction
> - Two rivals competing to see who can forge the better weapon
> - A tavern brawl to impress a patron
> - Taming a horse that wants to eat your underwear

## Gauntlets

In general, a contest can handle any interaction between two or more characters; disagreements, arm-wrestling, races, even fights with only one test for each side.  
And simple tests handle everything else without an opposing side; athletic challenges, public speeches, travelling, and even murder.

But a single roll does not always have enough weight to justify its effect on the narrative. For those occasions, when the stakes are high and the current scene requires a more dramatic resolution, Forge Gauntlet offers a more intricate resolution mechanic called a [Gauntlet](../gauntlets). In essence, it is a series of contests but with a lot more room for details and casualties. They are detailed in their own chapter.

{: .note-title }
> Examples of Gauntlets
>
> - Narratively poignant fights
> - Long-winded chases
> - Heartfelt debates
> - Grappling for influence over a city between underground factions
> - Continent-spanning journeys


## Improving with Failure

When you fail a skill test, you do not get what you want, but you mark **1** **XP** for the skill you used.

Apart from completing goals, this is the only way go gain **XP** for your skills.


## Resolving Tests in Revue

{: .note-title }
> Resolving Tests in Revue
>
> - Choose a goal to achieve.
> - Describe what action you would like to undertake in the fiction.
> - Choose a skill according to your goal and described action.
> - Pick an [Attribute](../../characters#attributes). If you have already described an action, try and go with the Attribute most fitting your description. Otherwise, let your choice of Attribute guide your roleplay.
> - Determine if the test will be simple, a contest, or a gauntlet.
> - **Roll the dice.**
> - The target number for your dice is determined by the skill you've chosen. Every face of a die that comes up as at least that number, is a hit, all others are misses.
> - Use traits either for dice modifiers, extra dice, or an increases difficulty, and spend Favor.
> - Determine the outcome of the test. If you succeeded, you get what you want, otherwise mark **1** **XP** and resolve the consequences of the test.

The following flowchart shows how to resolve a skill test step by step.

```mermaid
%%{init: {'theme': 'dark', "flowchart" : { "curve" : "basis" } } }%%
flowchart TD
    Goal[Choose a goal to achieve] -->|Describe your action| Test{Determine Test}

    Test -->|Passive Opposition| Challenge(Challenge)
    Test -->|Active Opposition| Contest(Contest)
    Test -->|It's Complicated| Gauntlet[Gauntlet<br><br>Procedure does not fit into this Flowchart<br>In essence a Sequence of Contests]
    Gauntlet --> Contest
    
    Challenge -->|Determine Opposition| Difficulty(Set Difficulty<br>equal to Trait Rating)
    Contest --> Dice(Determine<br>Skill & Attribute)

    Difficulty -->|Difficulty greater than 3| Gauntlet
    Difficulty --> Dice(Determine<br>Skill & Attribute)
    Dice --> Wound(Set Minimum Difficulty<br>According to Relevant Wound)
    Wound -->|Accept Difficulty| Roll(Roll Dice)
    Wound -->|Choose to create Boon| Increase(Increase Difficulty by Trait Rating)
    Increase --> Roll
    Roll -->|Choose to add Dice| Add{Choose Trait,<br>Boon, or Bane}

    Add -->|Accept Result| Outcome
    Add -->|Spend Favor| Modifier(Resolve Dice Modifier)
    Modifier --> Outcome{Judge<br>Outcome}

    Add -->|Environmental Trait| AddDice(Add Dice equal to Rating)
    Add -->|Opponent's Character Trait| AddDice
    Add -->|Boon| AddDice
    Add -->|Opponent's Bane| AddDice
    AddDice -->|Accept Result| Outcome
    AddDice -->|Spend Favor| Modifier

    Outcome -->|Accept Result| Resolve{Resolve}
    Outcome -->|Use Detrimental Trait| Trait(Increase Difficulty<br>by Trait's Rating)
    Outcome -->|Use Asset| Asset(Gain minimum Effort<br>equal to Asset's Rating)
    Asset --> Resolve
    Trait -->|Gain Favor| Resolve
    Resolve -->|Effort greater than Difficulty| Success[fa:fa-check You get what you want]
    Resolve -->|Effort equal to Difficulty<br>during a Challenge<br>or Defending during a Contest| Success
    Resolve -->|Effort equal to Difficulty<br>when attacking during a Contest| Failure[fa:fa-x You do not get what you want]
    Resolve -->|Effort less than Difficulty| Stress(Suffer Stress equal to Margin of Failure)

    Stress --> Failure
    Failure --> XP(fa:fa-plus Gain 1 XP)
```
