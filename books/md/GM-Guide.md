# GM Guide <a name="gm_guide"></a>

For the sake of brevity, and in the name of this being the very first version of this guide, we're going to make a few assumptions.

Firstly, that you've GM'd a game before, in any system. This is a big one, and if you haven't, you might want to try cutting your teeth on a more fleshed out system such as [D&D 4e](http://dnd4.wikia.com/wiki/D%26D4_Wiki) or [Rissus](http://www222.pair.com/sjohn/risus.htm). Or just dive right into OMNE; we're not your real mom.

Secondly, that you have a prediliction toward creating fantasy worlds. This is pretty important because nearly all of the content enclosed in this guide is for the creation of the world in which your game will be set. In OMNE, unlike D&D, world-building often a critical part of being a GM.

Thirdly, that you can read. Otherwise, this is probably unhelpful.

Fourthly, and finally, that you've read at least the intro of the [Core Rulebook](../Core-Rulebook.md), which should give you some context into the OMNE system.

## Building Worlds <a name="building_worlds"></a>
- What are worlds?
- Creates, items, rituals

## Creating Creatures <a name="creating_creatures"></a>
- Tags and characteristics
- Innate skills
- Generating enemies
- Caveat: do whatever

## Instantiating Items <a name="instantiating_items"></a>
- Tags and characteristics
- Special abilities
- Assigning value
- Generating loot

## Defining Rituals <a name="defining_rituals"></a>
- Rituals as a concept
- Tags and characteristics
- Pairing to skills
- Energy systems

## Creating and using Tags <a name="creating_and_using_tags"></a>
- Creating tags
- Existing tags

### Sizes
| Tag     | Effect                            |
|:--------|:----------------------------------|
| Fine    | STRN, STAM, VSBL: `-4` AGIL: `+4` |
| Minute  | STRN, STAM, VSBL: `-3` AGIL: `+3` |
| Tiny    | STRN, STAM, VSBL: `-2` AGIL: `+2` |
| Small   | STRN, STAM, VSBL: `-1` AGIL: `+1` |
| Medium  | STATS: `+0`                       |
| Large   | STRN, STAM, VSBL: `+1` AGIL: `-1` |
| Huge    | STRN, STAM, VSBL: `+2` AGIL: `-2` |
| Massive | STRN, STAM, VSBL: `+3` AGIL: `-3` |
| Vast    | STRN, STAM, VSBL: `+4` AGIL: `-4` |


### Size Modifiers
| Tag               | With Tag | Effect                     |
|:------------------|:---------|:---------------------------|
| Naturally Armed   | Fine     | DMG: `+0`                  |
|                   | Minute   | DMG: `+0`                  |
|                   | Tiny     | DMG: `+1`                  |
|                   | Small    | DMG: `1d4 - 2`, min `1`    |
|                   | Medium   | DMG: `1d6 - 2`, min `1`    |
|                   | Large    | DMG: `1d6`                 |
|                   | Huge     | DMG: `1d8`                 |
|                   | Massive  | DMG: `2d8 + 4`             |
|                   | Vast     | DMG: `3d10 + 10`           |
| Naturally Armored | Fine     | DMG: `-0`                  |
|                   | Minute   | DMG: `-0`                  |
|                   | Tiny     | DMG: `-1`                  |
|                   | Small    | DMG: `-(1d4 - 2)`, min `1` |
|                   | Medium   | DMG: `-(1d6 - 2)`, min `1` |
|                   | Large    | DMG: `-1d6`                |
|                   | Huge     | DMG: `-1d8`                |
|                   | Massive  | DMG: `-(2d8 + 4)`          |
|                   | Vast     | DMG: `-(3d10 + 10)`        |


### Characteristics
| Tag            | Description                                 |
|:---------------|:--------------------------------------------|
| Consumable     | Can be consumed.                            |
| Damaging       | Can be used to deal damage.                 |
| Healing        | Can be used to restore health.              |
| Long Lasting   | Has a duration.                             |
| Non-physical   | Cannot be affected by physics.              |
| Physical       | Affected by physics.                        |
| Protecting     | Can reduce damage from `Physical` entities. |
| Ranged         | Has a physical range.                       |
| Sentient       | Is sentient.                                |
| Skill Boosting | Can boost an entity's skill.                |
| Skill Reducing | Can reduce an entity's skill.               |
| Stat Boosting  | Can boost an entity's stat.                 |
| Stat Reducing  | Can reduce an entity's stat.                |


### Modifiers
| Tag         | With Tag       | Effect                     |
|:------------|:---------------|:---------------------------|
| Petty       | Damaging       | DMG: `1`                   |
|             | Protecting     | DMG: `-1`                  |
|             | Healing        | HP: `+1`                   |
|             | Skill Boosting | Skill: `+1`                |
|             | Skill Reducing | Skill: `-1`                |
|             | Stat Boosting  | Skill: `+1`                |
|             | Stat Reducing  | Skill: `-1`                |
| Weak        | Damaging       | DMG: `1d4 - 2`, min `1`    |
|             | Protecting     | DMG: `-(1d4 - 2)`, min `1` |
|             | Healing        | HP: `+(1d4 - 2)`, min `1`  |
|             | Skill Boosting | Skill: `+2`                |
|             | Skill Reducing | Skill: `-2`                |
|             | Stat Boosting  | Skill: `+2`                |
|             | Stat Reducing  | Skill: `-2`                |
| Meager      | Damaging       | DMG: `1d6 - 2`, min `1`    |
|             | Protecting     | DMG: `-(1d6 - 2)`, min `1` |
|             | Healing        | HP: `+(1d6 - 2)`, min `1`  |
|             | Skill Boosting | Skill: `+3`                |
|             | Skill Reducing | Skill: `-3`                |
|             | Stat Boosting  | Skill: `+3`                |
|             | Stat Reducing  | Skill: `-3`                |
| Basic       | Damaging       | DMG: `1d6`                 |
|             | Protecting     | DMG: `-1d6`                |
|             | Healing        | HP: `+1d6`                 |
|             | Skill Boosting | Skill: `+4`                |
|             | Skill Reducing | Skill: `-4`                |
|             | Stat Boosting  | Skill: `+4`                |
|             | Stat Reducing  | Skill: `-4`                |
| Moderate    | Damaging       | DMG: `1d8`                 |
|             | Protecting     | DMG: `-1d8`                |
|             | Healing        | HP: `+1d8`                 |
|             | Skill Boosting | Skill: `+5`                |
|             | Skill Reducing | Skill: `-5`                |
|             | Stat Boosting  | Skill: `+5`                |
|             | Stat Reducing  | Skill: `-5`                |
| Substantial | Damaging       | DMG: `2d8 + 4`             |
|             | Protecting     | DMG: `-(2d8 + 4)`          |
|             | Healing        | HP: `+(2d8 + 4)`           |
|             | Skill Boosting | Skill: `+6`                |
|             | Skill Reducing | Skill: `-6`                |
|             | Stat Boosting  | Skill: `+6`                |
|             | Stat Reducing  | Skill: `-6`                |
| Grand       | Damaging       | DMG: `3d10 + 10`           |
|             | Protecting     | DMG: `-(3d10 + 10)`        |
|             | Healing        | HP: `+(3d10 + 10)`         |
|             | Skill Boosting | Skill: `+7`                |
|             | Skill Reducing | Skill: `-7`                |
|             | Stat Boosting  | Skill: `+7`                |
|             | Stat Reducing  | Skill: `-7`                |


### Stat Modifiers
| Tag           | Effect      |
|:--------------|:------------|
| Mighty        | STRN: `+3`  |
| Strong        | STRN: `+1`  |
| Weak          | STRN: `-1`  |
| Puny          | STRN: `-3`  |
| Strenghtless  | STRN: `N/A` |
|               |             |
| Exact         | DEXT: `+3`  |
| Accurate      | DEXT: `+1`  |
| Imprecise     | DEXT: `-1`  |
| Clumsy        | DEXT: `-3`  |
| Nonprehinsile | DEXT: `N/A` |
|               |             |
| Graceful      | AGIL: `+3`  |
| Nimble        | AGIL: `+1`  |
| Uncordinated  | AGIL: `-1`  |
| Bumbling      | AGIL: `-3`  |
| Static        | AGIL: `N/A` |
|               |             |
| Hearty        | STAM: `+3`  |
| Tough         | STAM: `+1`  |
| Feeble        | STAM: `-1`  |
| Frail         | STAM: `-3`  |
| Incorporeal   | STAM: `N/A` |
|               |             |
| Obvious       | VSBL: `+3`  |
| Conspicuous   | VSBL: `+1`  |
| Unremarkable  | VSBL: `-1`  |
| Imperceptible | VSBL: `-3`  |
| Invisible     | VSBL: `N/A` |
|               |             |
| Brilliant     | INTL: `+3`  |
| Clever        | INTL: `+1`  |
| Simple        | INTL: `-1`  |
| Idiotic       | INTL: `-3`  |
| Mindless      | INTL: `N/A` |
|               |             |
| Visionary     | CRTV: `+3`  |
| Inventive     | CRTV: `+1`  |
| Untalented    | CRTV: `-1`  |
| Insipid       | CRTV: `-3`  |
| Predetermined | CRTV: `N/A` |
|               |             |
| Suave         | CHAR: `+3`  |
| Charming      | CHAR: `+1`  |
| Crass         | CHAR: `-1`  |
| Detestable    | CHAR: `-3`  |
| Unrelatable   | CHAR: `N/A` |
|               |             |
| Obssesed      | ZEAL: `+3`  |
| Passionate    | ZEAL: `+1`  |
| Passive       | ZEAL: `-1`  |
| Apathetic     | ZEAL: `-3`  |
| Stoic         | ZEAL: `N/A` |
|               |             |
| Observant     | PRCP: `+3`  |
| Alert         | PRCP: `+1`  |
| Inattentive   | PRCP: `-1`  |
| Oblivious     | PRCP: `-3`  |
| Insensate     | PRCP: `N/A` |