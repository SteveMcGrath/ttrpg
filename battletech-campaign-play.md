# Battletech Campaign Play Logistics

## Starting Stats

* **BPV**: 5200
* **Pilot Exp**: 4

## Mech Repair & Re-Arm Costs

| Damaged Component                       | BV Cost |
|:----------------------------------------|:-------:|
| Armor                                   | 3       |
| Internal Structure                      | 6       |
| Internal Structure (location destroyed) | 10      |
| Engines, Gyros, Sensors, Life Support   | 15      |

## Lance Up-Keep

In order to simplify covering the various costs in maintaining a Mech lance (pilot expenses, ammo, general maintinence, etc.)
up-keep is simply the x10 the lance's battle rating.  If up-keep isn't paid before the scenario begins, then every time a
battle roll is performed during the scenario, and that roll involves a weapon that consumes ammunition, then roll a d6 to
determine if the weapon has run out of ammunition.  On a 5+, the weapon has run dry and can no longer fire.  Further all
Pilot Skill Rolls will be at -1 for the duration of scenario.

## Scenario Payment Schedule

* **Base Pay**: 65x Battle Rating
* **Winnings**: Determined per scenario
* **Per Mech Killed**: 2x Tonnage

## Pilot Experience

Note that unless specified, all of the counters are cumulative and are not reset between scenarios.

| Event                                                      | Exp. Awarded | 
|:-----------------------------------------------------------|:------------:|
| Scenario participation                                     | 1            |
| Each internal location of enemy mech destroyed             | 1            |
| Each Fire Phase you cause internal damage to an enemy Mech | 1            |
| Each enemy mech destroyed                                  | 2            |
| Every 10th **successful** Pilot Skill Roll                 | 1            |
| Every **successful** Shutdown Roll                         | 1            |
| No **internal** damage at end of scenario                  | 1            |
| Every 2nd **successful** Close Combat attack               | 1            |
| Every 4th **successful** Indirect Fire attack (attacker)   | 1            |
| Every 4th **successful** Indirect Fire attack (spotter)    | 1            |

### Underdogs

Before the scenario begins, the opponents compare Battle Ratings, and the opponent with the lower rating is the underdog.
Each underdog player receives 1 experience immediately that can be assigned to the pilot of their choice.  Underdog players
may receive additional benefits based on the difference between the opposing forces.  To determine this difference, take
the Battle Ratings of the opposing forces and follow the table and formula below:

```
 Opposition Battle Rating / Underdog Battle Rating
```

| Difference      | Additional Awards                                            |
|:---------------:|:-------------------------------------------------------------|
| Less than 1.20  | No additional awards                                         |
| Less than 1.65  | 1 Exp. per surviving pilot and an additional 100 BV warchest |
| 1.65 or Greater | 2 Exp. per surviving pilot and an additional 200 BV warchest |

## Post Battle Checks

### Wounded Pilot

In order to determine the fate of any pilot that has been wounded during the course of the scenario, roll 2d6 and refer
to the table below for the outcome:

| Roll | Result         |
|:----:|:---------------|
| 2    | New Skill      |
| 3-4  | Negative Quirk |
| 5-11 | No effect      |
| 12   | 1 Exp.         |

If a **New Skill** is assigned, then roll a d6 to determine the award:

| Roll | Result            |
|:----:|:------------------|
| 1-2  | -1 Gunnery Skill  |
| 3-5  | -1 Pilot Skill    |
| 6    | 1 Exp.            |

### Pilot Skill Adjustment and Quirks

When adjusting a Pilot's abilities, only one action can be performed for each pilot.  This means if a Quirk is assigned
to the pilot are part of a **Wounded Pilot** check or other assignment, then this pilot is precluded from any of the
actions available here.

| Action            | 1st | 2nd | 3rd | 4th |
|:------------------|:---:|:---:|:---:|:---:|
| -1 Gunnery Skill  |  8  | 10  | 12  | 14  |
| -1 Piloting Skill |  4  |  6  |  8  | 10  |
| New Special Skill | Cost as indicated for skill

The maximum number of special skills for each skill type are determined based on the skill level for the Pilot.  For each
skill type, check the table below to understand how many special skills may be assigned to the Pilot.  Further when
selecting a special skill for a Pilot, each **Lance** may have only **2** of the same skill, with special exception to
_[Floats Like a Butterfly](#butterfly)_, in which only **1** is allowed for each lance.

| Skill Type Level | Maximum Number of Special Skills |
|:----------------:|:---------------------------------|
|      4+          |   1                              |
|      3           |   2                              |
|      2           |   3                              |
|      1           |   4                              |
|      0           |   5                              |

### Hiring Replacement Pilots

Not everyone can survive every scenario,

2d6

| Roll | Skill Level | Hiring Cost | Gunnery Skill | Piloting Skill |
|:----:|:------------|:-----------:|:-------------:|:--------------:|
|  3+  | Rookie      | 200         | 5             | 6              |
|  7+  | Regular     | 300         | 4             | 5              |
|  10+ | Veteran     | 600         | 3             | 4              |
|  12  | Elite       | 900         | 2             | 3              |

### BV Skill Table

* **G**: Gunnery Skill
* **P**: Piloting/Driving/Anti-Mech Skill

|    |  P0  |  P1  |  P2  |  P3  |  P4  |  P5  |  P6  |  P7  |  P8  |
|:--:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| G0 | 2.42 | 2.31 | 2.21 | 2.10 | 1.93 | 1.75 | 1.68 | 1.59 | 1.50 |
| G1 | 2.21 | 2.11 | 2.02 | 1.92 | 1.76 | 1.60 | 1.54 | 1.46 | 1.38 |
| G2 | 1.93 | 1.85 | 1.76 | 1.68 | 1.54 | 1.40 | 1.35 | 1.28 | 1.21 |
| G3 | 1.66 | 1.58 | 1.51 | 1.44 | 1.32 | 1.20 | 1.16 | 1.10 | 1.04 |
| G4 | 1.38 | 1.32 | 1.26 | 1.20 | 1.10 | **1**| 0.95 | 0.90 | 0.85 |
| G5 | 1.31 | 1.19 | 1.13 | 1.08 | 0.99 | 0.90 | 0.86 | 0.81 | 0.77 |
| G6 | 1.24 | 1.12 | 1.07 | 1.02 | 0.94 | 0.85 | 0.81 | 0.77 | 0.72 |
| G7 | 1.17 | 1.06 | 1.01 | 0.96 | 0.88 | 0.80 | 0.76 | 0.72 | 0.68 |
| G8 | 1.10 | 0.99 | 0.95 | 0.90 | 0.83 | 0.75 | 0.71 | 0.68 | 0.64 |

## Selling Mechs, Weapons, Armor, or Internals

In order to sell any Mechs, the Mech must be in an undamaged condition (fully repaired).  Also when selling any equipment
to the merchants, all sales are final.  To determine the sale price of any equipment, roll 2d6 and refer to the table
below to determine the sale price of the equipment.  Clan players (only when selling clan-only equipment) will get the
best of 3 rolls when determining price.

| Roll | Result                              |
|:----:|:------------------------------------|
| 2    | 50% BV (get rid of it at any price) |
| 3-5  | 75% BV (at least it's something)    |
| 6-10 | 100% BV (seems reasonable)          |
| 11   | 125% BV (drive a hard bargain)      |
| 12   | 150% BV (found a sucker)            |

## Purchasing Mecs, Weapons, or Internals

Merchants throughout the Inner Sphere might have the equipment you happen to be looking for, depending on the parts.
In order to determine if the merchant has the part you desire, roll a d6 to determine if the merchant carries the
item your looking for (yes, that means the player rolls for each item).  A Player can increase the chance of aquiring
an item they especially desire by greasing a few palms and paying an additional 25% above market value to decrease the
rarity by one step.

Weapons and components may be swapped within an existing Mech as long as the item is of the same type and fits within
the existing space on the Mech.  For example, Pulse Lasers may be replaced with other Direct Energy (DE) weapons, or
Auto-Cannons could be replaced with another Direct Ballistic (DB) weapon of similar size.

All purchases must be declared before rolling.  The Player must have the necessary funds to purchase the item before
attempting to purchase, and a Player may only attempt to roll once for each item per scenario session.

| Result | Availability |
|:------:|:-------------|
|   1+   | Very Common  |
|   2+   | Common       |
|   3+   | Uncommon     |
|   4+   | Rare         |
|   5+   | Very Rare    |
|   6+   | Unique       |

## Merchant Weapons & Equipment Tables

### Energy Weapons

| Item                        | Inner Sphere | Availability | Item BV | Ammo BV | Clan | Availability | Item BV | Ammo BV |
|:----------------------------|:------------:|:-------------|:-------:|:-------:|:----:|:-------------|:-------:|:-------:|
| ER Laser (Large)            | x            | Rare         | 163     | -       | x    | Rare         | 248     | -       |
| ER Laser (Medium)           | x            | Rare         | 62      | -       | x    | Rare         | 108     | -       |
| ER Laser (Small)            | x            | Rare         | 17      | -       | x    | Rare         | 31      | -       |
| ER Laser (Micro)            | -            | -            | -       | -       | x    | Rare         | 7       | -       |
| Flamer                      | x            | Common       | 6       | -       | x    | Common       | 6       | -       |
| Heavy Laser (Large)         | -            | -            | -       | -       | x    | Rare         | 244     | -       |
| Heavy Laser (Medium)        | -            | -            | -       | -       | x    | Rare         | 76      | -       |
| Heavy Laser (Small)         | -            | -            | -       | -       | x    | Rare         | 15      | -       |
| Laser (Large)               | x            | Uncommon     | 123     | -       | -    | -            | -       | -       |
| Laser (Medium)              | x            | Common       | 46      | -       | -    | -            | -       | -       |
| Laser (Small)               | x            | Common       | 9       | -       | -    | -            | -       | -       |
| PPC (Heavy)                 | x            | Common       | 317     | -       | -    | -            | -       | -       |
| PPC                         | x            | Rare         | 176     | -       | -    | -            | -       | -       |
| PPC (Light)                 | x            | Very Rare    | 88      | -       | -    | -            | -       | -       |
| PPC (SNub-Nose)             | x            | Very Rare    | 165     | -       | -    | -            | -       | -       |
| PPC (Support)               | x            | Very Rare    | 14      | -       | -    | -            | -       | -       |
| ER PPC                      | x            | Very Rare    | 228     | -       | x    | Very Rare    | 412     | -       |
| Plasma Cannon               | -            | -            | -       | -       | x    | Unique       | 170     | 21      |
| Plasma Rifle                | x            | Very Rare    | 210     | 26      | -    | -            | -       | -       |
| Plasma Rifle (Man Portable) | x            | -            | 12      | 2       | -    | -            | -       | -       |
| Pulse Laser (Large)         | x            | Very Rare    | 119     | -       | x    | 265          | -       | -       |
| Pulse Laser (Medium)        | x            | Very Rare    | 48      | -       | x    | 111          | -       | -       |
| Pulse Laser (Small)         | x            | Very Rare    | 12      | -       | x    | 24           | -       | -       |
| Pulse Laser (Micro)         | -            | -            | -       | -       | x    | 12           | -       | -       |

### Ballistic Weapons

| Item                        | Inner Sphere | Availability | Item BV | Ammo BV | Clan | Availability | Item BV | Ammo BV |
|:----------------------------|:------------:|:-------------|:-------:|:-------:|:----:|:-------------|:-------:|:-------:|
| AC/2                        | x            | Uncommon     | 37      | 5       | -    | -            | -       | -       | 
| AC/5                        | x            | Uncommon     | 70      | 9       | -    | -            | -       | -       |
| AC/10                       | x            | Uncommon     | 123     | 15      | -    | -            | -       | -       |
| AC/20                       | x            | Rare         | 178     | 22      | -    | -            | -       | -       |
| "Bearhunter" Super-Heavy AC | -            | -            | -       | -       | x    | -            | 4       | 0       |
| "Firedrake" Support Needler | x            | -            | 2       | 0       | -    | -            | -       | -       |
| Flamer (Vehicle)            | x            | -            | 5       | 1       | x    | -            | 5       | 1       |
| Gauss AP                    | -            | -            | -       | -       | x    | Very Rare    | 21      | 35      |
| Gauss Rifle (Heavy)         | x            | Very Rare    | 346     | 43 n/e  | -    | -            | -       | -       |
| Gauss Rifle                 | x            | Rare         | 320     | 40 n/e  | x    | Very Rare    | 320     | 40 n/e  |
| Gauss Rifle (Light)         | x            | Very Rare    | 159     | 20 n/e  | -    | -            | -       | -       |
| Gauss Rifle (David)         | x            | -            | 7       | 1       | -    | -            | -       | -       |
| Gauss Rifle ("King David")  | x            | -            | 7       | 1       | -    | -            | -       | -       |
| Gauss (Grand Mauler)        | x            | -            | 6       | -       | -    | -            | -       | -       |
| Grenade Launcher (Auto)     | x            | -            | 1       | -       | -    | -            | -       | -       |
| Grenade Launcher (Heavy)    | x            | -            | 2       | -       | x    | -            | 2       | -       |
| HAG 20                      | -            | -            | -       | -       | x    | Unique       | 267     | 33 n/e  | 
| HAG 30                      | -            | -            | -       | -       | x    | Unique       | 401     | 50 n/e  | 
| HAG 40                      | -            | -            | -       | -       | x    | Unique       | 535     | 67 n/e  |
| LB 2-X AC                   | x            | Rare         | 42      | 5       | x    | Rare         | 47      | 6       | 
| LB 5-X AC                   | x            | Rare         | 83      | 10      | x    | Rare         | 93      | 12      |
| LB 10-X AC                  | x            | Rare         | 148     | 19      | x    | Rare         | 148     | 19      |
| LB 20-X AC                  | x            | Very Rare    | 237     | 30      | x    | Very Rare    | 237     | 30      |
| Light AC/2                  | x            | Rare         | 30      | 4       | -    | -            | -       | -       |
| Light AC/5                  | x            | Rare         | 62      | 8       | -    | -            | -       | -       |
| Machine Gun (Heavy)         | x            | Common       | 6       | 1       | x    | Common       | 6       | 1       |
| Machine Gun                 | x            | Very Common  | 5       | 1       | x    | Very Common  | 6       | 1       |
| Machine Gun (Light)         | x            |              | 5       | 1       | x    | -            | 5       | 1       |
| Mortar (Heavy)              | x            |              | 17      |         | -    | -            | -       | -       |
| Mortar (Light)              | x            |              | 9       |         | -    | -            | -       | -       |
| Nail/Rivet Gun              | x            |              | 1       | 0       | x    | -            | 1       | 0       |
| Recoilless Rifle (Heavy)    | x            |              | 22      |         | x    | -            | 12      | -       |
| Recoilless Rifle (Medium)   | x            |              | 19      |         | x    | -            | 19      | -       |
| Recoilless Rifle (Light)    | x            |              | 12      |         | x    | -            | 22      | -       |
| Tsunami                     | x            |              | 6       |         | -    | -            | -       | -       |
| Rotary AC/2                 | x            | Unique       | 118     | 15      | -    | -            | -       | -       |
| Rotary AC/5                 | x            | Unique       | 247     | 31      | -    | -            | -       | -       |
| Ultra AC/2                  | x            | Very Rare    | 56      | 7       | x    | Very Rare    | 62      | 8       |
| Ultra AC/5                  | x            | Very Rare    | 112     | 14      | x    | Very Rare    | 122     | 15      |
| Ultra AC/10                 | x            | Very Rare    | 210     | 26      | x    | Very Rare    | 210     | 26      |
| Ultra AC/20                 | x            | Very Rare    | 281     | 35      | x    | Very Rare    | 335     | 42      |

### Missle Weapons

| Item                        | Inner Sphere | Availability | Item BV | Ammo BV | Clan | Availability | Item BV | Ammo BV |
|:----------------------------|:-------------|:------------:|:-------:|:-------:|:----:|:-------------|:-------:|:-------:|
| Advanced SRM-1              | -            | -            | -       | -       | x    | Rare         | 15/3    | 2       |
| Advanced SRM-2              | -            | -            | -       | -       | x    | Rare         | 30/6    | 4       |
| Advanced SRM-3              | -            | -            | -       | -       | x    | Rare         | 45/9    | 6       |
| Advanced SRM-4              | -            | -            | -       | -       | x    | Rare         | 60/8    | 8       |
| Advanced SRM-5              | -            | -            | -       | -       | x    | Rare         | 75/15   | 10      |
| Advanced SRM-6              | -            | -            | -       | -       | x    | Rare         | 90/18   | 12      |
| ATM-3                       | -            | -            | -       | -       | x    | Rare         | 53/-    | 14      |
| ATM-6                       | -            | -            | -       | -       | x    | Rare         | 105/-   | 26      |
| ATM-9                       | -            | -            | -       | -       | x    | Rare         | 147/-   | 36      |
| ATM-12                      | -            | -            | -       | -       | x    | Rare         | 212/-   | 52      |
| LRM-1                       | x            | Common       | 14/3    | 2       | x    | Common       | 17/3    | 2       |
| LRM-2                       | x            | Common       | 20/4    | 3       | x    | Common       | 25/5    | 3       |
| LRM-3                       | x            | Common       | 29/6    | 4       | x    | Common       | 35/7    | 5       |
| LRM-4                       | x            | Common       | 38/8    | 5       | x    | Common       | 46/9    | 6       |
| LRM-5                       | x            | Common       | 45/9    | 6       | x    | Common       | 55/11   | 7       |
| LRM-6                       | -            | -            | -       | -       | x    | Common       | 69/14   | 9       |
| LRM-7                       | -            | -            | -       | -       | x    | Common       | 77/15   | 10      |
| LRM-8                       | -            | -            | -       | -       | x    | Common       | 88/18   | 11      |
| LRM-9                       | -            | -            | -       | -       | x    | Common       | 95/19   | 12      |
| LRM-10                      | x            | Common       | 90/18   | 11      | x    | Common       | 109/22  | 14      |
| LRM-11                      | -            | -            | -       | -       | x    | Common       | 139/28  | 18      |
| LRM-12                      | -            | -            | -       | -       | x    | Common       | 141/29  | 18      |
| LRM-13                      | -            | -            | -       | -       | x    | Common       | 161/32  | 20      |
| LRM-14                      | -            | -            | -       | -       | x    | Common       | 163/33  | 21      |
| LRM-15                      | x            | Common       | 136/27  | 17      | x    | Common       | 164/33  | 21      |
| LRM-16                      | -            | -            | -       | -       | x    | Common       | 214/43  | 27      |
| LRM-17                      | -            | -            | -       | -       | x    | Common       | 215/43  | 27      |
| LRM-18                      | -            | -            | -       | -       | x    | Common       | 217/43  | 27      |
| LRM-19                      | -            | -            | -       | -       | x    | Common       | 218/44  | 27      |
| LRM-20                      | x            | Common       | 181/36  | 23      | x    | Common       | 220/44  | 27      |
| MML-3                       | x            | Common       | 29/6    | 4       | -    | -            | -       | -       |
| MML-5                       | x            | Common       | 45/9    | 6       | -    | -            | -       | -       |
| MML-7                       | x            | Common       | 67/13   | 8       | -    | -            | -       | -       |
| MML-9                       | x            | Common       | 85/17   | 11      | -    | -            | -       | -       |
| MRM-1                       | x            | Common       | 9/2     | 1       | -    | -            | -       | -       |
| MRM-2                       | x            | Common       | 13/3    | 2       | -    | -            | -       | -       |
| MRM-3                       | x            | Common       | 18/4    | 2       | -    | -            | -       | -       |
| MRM-4                       | x            | Common       | 23/5    | 3       | -    | -            | -       | -       |
| MRM-5                       | x            | Common       | 28/6    | 4       | -    | -            | -       | -       |
| MRM-10                      | x            | Common       | 56/11   | 7       | -    | -            | -       | -       |
| MRM-20                      | x            | Common       | 112/22  | 14      | -    | -            | -       | -       |
| MRM-30                      | x            | Common       | 168/34  | 21      | -    | -            | -       | -       |
| MRM-40                      | x            | Common       | 224/49  | 28      | -    | -            | -       | -       |
| Rocket Launcher 1           | x            | Common       | 2       |         | -    | -            | -       | -       |
| Rocket Launcher 2           | x            | Common       | 3       |         | -    | -            | -       | -       |
| Rocket Launcher 3           | x            | Common       | 4       |         | -    | -            | -       | -       |
| Rocket Launcher 4           | x            | Common       | 5       |         | -    | -            | -       | -       |
| Rocket Launcher 5           | x            | Common       | 6       |         | -    | -            | -       | -       |
| Rocket Launcher 10          | x            | Common       | 18      |         | -    | -            | -       | -       |
| Rocket Launcher 15          | x            | Common       | 23      |         | -    | -            | -       | -       |
| Rocket Launcher 20          | x            | Common       | 24      |         | -    | -            | -       | -       |
| SRM-1                       | x            | Common       | 15/3    | 2       | x    | Common       | 15/3    | 2       |
| SRM-2                       | x            | Common       | 21/4    | 3       | x    | Common       | 21/4    | 3       |
| SRM-3                       | x            | Common       | 30/6    | 4       | x    | Common       | 30/6    | 4       |
| SRM-4                       | x            | Common       | 39/8    | 5       | x    | Common       | 39/8    | 5       |
| SRM-5                       | x            | Common       | 47/9    | 6       | x    | Common       | 58/12   | 8       |
| SRM-6                       | x            | Common       | 59/12   | 7       | x    | Common       | 59/12   | 7       |
| Streak SRM-1                | -            | -            | -       | -       | x    | Very Rare    | 20/4    | 3       |
| Streak SRM-2                | x            | Very Rare    | 30/6    | 4       | x    | Very Rare    | 40/8    | 5       |
| Streak SRM-3                | -            | -            | -       | -       | x    | Very Rare    | 59/12   | 7       |
| Streak SRM-4                | x            | Very Rare    | 59/12   | 7       | x    | Very Rare    | 79/16   | 10      |
| Streak SRM-5                | -            | -            | -       | -       | x    | Very Rare    | 99/20   | 13      |
| Streak SRM-6                | x            | Very Rare    | 89/18   | 11      | x    | Very Rare    | 118/24  | 15      |

### Other Equipment

| Item                         | Inner Sphere | Availability | Item BV | Ammo BV | Clan | Availability | Item BV | Ammo BV |
|:-----------------------------|:-------------|:------------:|:-------:|:-------:|:----:|:-------------|:-------:|:-------:|
| Active Probe                 | -            | -            | -       | -       | x    | -            | 12 (def)| -       |
| Active Probe (Light)         | -            | -            | -       | -       | x    | -            | 7 (def) | -       |
| Anti-Missle System           | x            | -            | 32 (def)| 11 (def)| x    | -            | 32 (def)| -       |
| Anti-Personnel Pod (A-pod)   | x            | -            | 1 (def) | -       |
| Anti-Battle Armor Pod (B-pod)| x            | -            | 2 (def) | -       |
| Artemis IV FCS               | x            | -            | -       | -       |
| Backhoe                      | x            | -            | 8       | -       |
| Bridge-Layer (Heavy)         | x            | -            | 20 (def)| -       |
| Bridge-Layer (Medium)        | x            | -            | 10 (def)| -       |
| Bridge-Layer (Light)         | x            | -            | 5 (def) | -       |
| Beagle Active Probe          | x            | -            | 10 (def)| -       |
| Bulldozer                    | x            | -            | 10 (def)| -       |
| CASE                         | x            | -            | -       | -       |
| C3 Computer Master           | x            | -            | -       | -       |
| C3 Computer Slave            | x            | -            | -       | -       |
| Chainsaw                     | x            | -            | 7       | -       |
| Combine                      | x            | -            | 5       | -       |
| Dual Saw                     | x            | -            | 9       | -       |
| Guardian ECM Suite           | x            | -            | 61 (def)| -       |
| Hatchet                      | x            | -            | DMGx1.5 | -       |
| Heavy-Duty Pile Driver       | x            | -            | 5       | -       |
| Improved C3 Computer         | x            | -            | -       | -       |
| Improves Narc Launcher       | x            | -            | -       | -       |
| Machine Gun Array            | x            | -            | -       | -       |
| MASC                         | x            | -            | -       | -       |
| Mining Drill                 | x            | -            | 6       | -       |
| Narc Missle Beacon           | x            | -            | 30/6    | 0       |
| Narc (Compact)               | x            | -            | 16/4    | 0       |
| Nail/Rivet Gun               | x            | -            | 1       | 0       |
| Popup Mine                   | x            | -            | 6       | -       |
| Retractable Blade            | x            | -            | DMGx1.75| -       |
| Rock Cutter                  | x            | -            | 6       | -       |
| Spot Welder                  | x            | -            | 5       | -       |
| Sword                        | x            | -            | DMGx1.75| -       |
| TAG                          | x            | -            | -       | -       |
| Targeting Computer           | x            | Unique       | -       | -       |
| Triple-Strength Myomer       | x            | -            | -       | -       |
| Industrial Triple-Str Myomer | x            | -            | -       | -       |
| Wrecking Ball                | x            | -            | 8       | -       |

## Skills

| Cost | Skill Type | Skill      |
|:----:|:-----------|:-----------|
|   1  |            | [Forward Observer](#fwdobserv)
|   1  |            | [Lucky 1](#lucky1)
|   1  |            | [Melee Specialist](#meleespec)
|   1  |            | [Slugger](#slugger)
|   1  |            | [Stand-Aside](#stand_aside)
|   2  |            | [Blood Stalker](#bloodstalker)
|   2  |            | [Cluster Hitter](#cluster_hitter)
|   2  |            | [Eagle's Eyes](#eagle_eyes)
|   2  |            | [Fist Fire](#fistfire)
|   2  |            | [Iron Will](#ironwill)
|   2  |            | [Jumping Jack](#jumpingjack)
|   2  |            | [Lucky 2](#lucky)
|   2  |            | [Manuevering Ace](#man_ace)
|   2  |            | [Marksman](#marksman)
|   2  |            | [Melee Master](#meleemaster)
|   2  |            | [Sandblaster (LB 20-X)](#sandblaster)
|   2  |            | [Speed Demon](#speeddemon)
|   2  |            | [Streetfighter](#streetfighter)
|   3  |            | [Antagonizer](#antagonizer)
|   3  |            | [Combat Intuition](#combatint)
|   3  |            | [Float Like a Butterfly](#butterfly)
|   3  |            | [Lucky 3](#lucky3)
|   3  |            | [Multi-Tasker](#multitasker)
|   3  |            | [Natural Grace](#natgrace)
|   3  |            | [Ranger Master (Long)](#rm_long)
|   3  |            | [Scrounger](#scrounger)
|   3  |            | [Sniper](#sniper)
|   3  |            | [Tactical Genius](#tacgenius)
|   3  |            | [Terrain Master (Forest Ranger)](#tm_fr)
|   3  |            | [Terrain Master (Mountaineer)](#tm_mntn)
|   3  |            | [Weapons Specialist (Any Weapon Type)](#weaponspec_lrm)
|   4  |            | [Starpshooter](#sharpshooter)


### Antagonizer _Cost 3)_ <a name="antagonizer"></a>

Instead of a weapon attack, select one target in LOS and within 10 hexes.  Pilot's unit
makes a **Piloting Skill Roll** with a **+4 modifier**.

* _**Success**_: Target must move towards the Pilot using the unit's fastest Movement Type
                 and the most direct route, and may only attack the Pilot.  This effect
                 ends after a number of turns equal to the Pilot's MoS, if Pilot moves
                 greater than 10 hexes away, or if another unit damages target.

* _**Failed**_: no effect.

### Blood Stalker _(Cost 2)_ <a name="bloodstalker"></a>

**-1 To-Hit Modifier** against single enemy (+2 against all others) until enemy retreats
or is disabled/destroyed.

### Cluster Hitter _(Cost 2)_ <a name="cluster_hitter"></a>

Each **Weapon Attack Phase**, choose one:

* Add a **+1** modifier on the **Cluster Hits Table** for all the Cluster weapons.
* Make an **Aimed Shot** with one Cluster weapon with **+3 To-Hit Modifier**; if
  successful, all clustered rounds hit the target location (may not target head).
  The attacking unit may not have moved or fired other weapons and cannot make
  physical attacks if using this ability.

### Combat Intuition _(Cost 3)_ <a name="combatint"></a>

Declare use during the **End Phase**; this pilot chooses to suffer 1 point of pilot
damage (no Consciousness Roll).  Select an opposing unit.  After **Initiative** on
the following turn, choose one:

* This unit may perform all movement, weapon, and physical attacks in the order
  against it's target at any point before the target moves.  The target has no
  movement modifiers but is not Immobile.  Damage takes effect **immediately**.
  This unit may not make further attacks this turn.  All normal modifiers to
  attacks against the unit apply.
* This unit moves after all other units and declares its fire last.

### Eagle's Eyes _(Cost 2)_ <a name="eagle_eyes"></a>

Function as a Beagle Active Probe with a range of 1 hix (or adds 1 hex to the range
of any Active Probe, if present).  Add +2 target modifier for attacks from
minefields, and boobytraps, and a -2 modifier for clearing minefields or traps if
the Pilot's unit has the ability to do so.

### Fist Fire _(Cost 2)_ <a name="fistfire"></a>

Requires a functional arm, including hand actuator.  After a successful punch or
physical weapon attack, the attacker fires one DFB or DFE weapon located in the
same arm with **-1 To-Hit Modifier**.  If successful, the weapon damage is applied
to the same location as the physical attack.

### Float Like a Butterfly _(Cost 3)_ <a name="butterfly"></a>

The Pilot fan force their opponent to re-roll either a combat or critical roll.
Can be used 3 times per scenario.

### Forward Observer _(Cost 1)_ <a name="fwdobserv"></a>

When spotting for an artillery unit, grands a **-1 To-Hit Modifier** to that unit's
attack.  When adjusting fire, apply an additional -2 modifier until unit shots land
on-target.  May also make attacks during the **Weapon Attack Phase** while spotting
without imposing a To-Hit Modifier on the artillery attack.

### Iron Will _(Cost 2)_ <a name="ironwill"></a>

Opponents using the _Animal Mimicry_, _Antagonizer_, or _Demoralizer_ SPAs against
the Pilot receive a +2 target modifier for activate the ability.

### Jumping Jack _(Cost 2)_ <a name="jumpingjack"></a>

Reduce **Attacker Movement Modifier** from +3 to +1 after jumping.

### Lucky 1 _(Cost 2)_ <a name="lucky1"></a>

May re-roll a failed attack roll or **Piloting Skill Roll** 1 times per scenario.
The second roll **must** be accepted.

### Lucky 2 _(Cost 2)_ <a name="lucky2"></a>

May re-roll a failed attack roll or **Piloting Skill Roll** 2 times per scenario.
The second roll **must** be accepted.

### Lucky 3 _(Cost 2)_ <a name="lucky3"></a>

May re-roll a failed attack roll or **Piloting Skill Roll** 3 times per scenario.
The second roll **must** be accepted.

### Manuevering Ace _(Cost 2)_ <a name="man_ace"></a>

May make **Lateral Shifts**.  Apply a -1 modifier to **Piloting Skill Rolls**
to avoid skidding.

### Marksman _(Cost 2)_ <a name="marksman"></a>

May make a special **Aimed Shot** attack as if using a targeting computer; may
only fire one weapon.  Or, apply an additional **-2 To-Hit Modifier** if making
an **Aimed Shot** with a targeting computer.

### Melee Master _(Cost 2)_ <a name="meleemaster"></a>

May attempt one extra punch, kick, or club attack per **Physical Attack** phase.

### Melee Specialist _(Cost 1)_ <a name="meleespec"></a>

Apply a **-1 To-Hit Modifier** for physical attack rolls; add 1 point of damage
to successful attacks.

### Multi-Tasker _(Cost 3)_ <a name="multitasker"></a>

May make an attack against a secondary target in the front arc at a
**+0 To-Hit Modifier**, and in the side or rear arcs at a **+1 To-Hit Modifier**.

### Natural Grace _(Cost 3)_ <a name="natgrace"></a>

Reduce the cost of entering buildings or ultra-heavy terrain by 1 MP, apply a -1
target modifier to **Piloting Skill Rolls** to avoid falling, damage from buildings
or falls, or setting off mines; may torso twist 2 hexes instead of one; map "flip"
a single arm regardless of which actuators are present.

### Range Master (Long) _(Cost 3)_ <a name="rm_long"></a>

Attacks at **Long Range** receive a **+0 To-Hit Modifier**, while attacks at
**Short Range** receive a **+4 To-Hit Modifier**.

### Sandblaster (LB 20-X) _(Cost 2)_ <a name="sandblaster"></a>

When rolling on the **Cluster Hots Table** for a successful LB 20-X attack, add
one of the following modifiers to the roll:

* **Short Range**: +4
* **Medium Range**: +3
* **Long Range**: +2
* **Extreme Range**: +2

### Scrounger _(Cost 3)_ <a name="scrounger"></a>

When buying, selling, or repairing equipment or Mechs, apply the following:

* When buying or repairing equipment or Mechs, reduce the cost by 10%.
* When selling equipment or Mechs, the selling price is increased by 10%.

### Sharpshooter _(Cost 4)_ <a name="sharpshooter"></a>

If remaining stationary and not making physical attacks, may fire one weapon only
as an **Aimed Shot**.  Successful attack grants extra potential critical hit, even
if armor remains in the location.

### Slugger _(Cost 2)_ <a name="slugger"></a>

May improvise and use a club single-handed, allowing use of weapons in the torso
and other arm as normal.

### Sniper _(Cost 3)_ <a name="sniper"></a>

Reduce range **To-Hit Modifiers** by half: **+1 for Medium**, **+2 for Long**,
**+3 for Extreme**.

### Speed Demon _(Cost 2)_ <a name="speeddemon"></a>

Add 1 MP to Running and +2 MP to Sprinting movement, but may not make weapon or
physical attacks that turn.

### Stand-Aside _(Cost 1)_ <a name="stand_aside"></a>

May spend +1 MP to pass through a hex occupied by an enemy unit by making a
**Piloting Skill Roll** with a +2 modifier.  Apply a +1 modifier for each weight
class by which the enemy unit is heavier; -2 for each weight class by which the
enemy unit is lighter.

### Street Fighter _(Cost 2)_ <a name="streetfighter"></a>

May conduct physical attacks during the **Weapon Attack Phase** instead of the
**Physical Attack Phase**.

### Tactical Genius _(Cost 3)_ <a name="tacgenius"></a>

Prior to play, select a commander for your force.  If the Pilot is your force
commander, you may re-roll your initiative roll once each turn.  The second roll
**must** be accepted, even if worse than the first.

### Terrain Master (Forest Ranger) _(Cost 3)_ <a name="tm_fr"></a>

Pilot's unit receives -1 MP to all movement costs in woods or jungle hexes, and
applies a -1 modifier to the **Piloting Skill Roll** for moving through jungle
hexes.  If Pilot expended walking MP and is within woods or jungle hex, attacks
against the Pilot receive a **+1 To-Hit** terrain modifier.

### Terrain Master (Mountaineer) _(Cost 3)_ <a name="tm_mntn"></a>

Subtract 1 MP from all movement costs when moving through gravel, rough/ultra-rough,
or rubble/ultra-rubble hexes, and for any level charges (including sheer cliffs).
Apply -1 to all **Piloting Skill Rolls** in such terrain.

### Weapons Specialist (Single Weapon) _(Cost 3)_ <a name="weaponspec_lrm"></a>

Apply a **-2 To-Hit Modifier** when attacking with any installed single weapon of the
Pilot's choice.  The weapon specialization must be decided when initially taking this
skill.

