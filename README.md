# infiniteClash
 2D Top-down hack'n'slash survival game
### Game Outline
- Boxhead inspired
- Movement across 2d plane, camera top down
- Projectiles fire from the player towards the mouse on click
- Projectiles pierce certain numbers of enemies before disappearing
- Melee weapons swing around the player on variable speeds, radii and arcs
- Class selection that provides stat multipliers and class passives
- Can equip items in between waves through a menu
- Baseline 1 melee weapon, 1 ranged weapon, 1 ability, 1 class passive, 1 passive, 1 ultimate
- Attacking with a melee weapon and dodging costs stamina
- Atacking with a ranged weapon costs ammo
- Recover ammo by hitting enemies with a melee weapon or through pickups
- Abilities can be casted infinitely on a cooldown
- Ultimates have no cooldown but cost ultimate charge
- Recover ultimate charge by dealing damage and slowly over time
- Multiple enemy types, boss battles that start on certain waves
- Multiple enemy types, damage based on attack animations not collision
- Enemies scale based off a rising wave multiplier both in number and stat
- Enemies can also have special modifiers like more health, more speed, etc
- Possibly dodge hundreds of bullets on screen as score gets higher? .. Can the player shoot hundreds of bullets?
- Unsure about adding obstacles and environment collision
- Possible later feature to allow player to build barricades rooms and corridors as defensive structures?

## Classes and descriptions

| Class name | Strengths | Weaknesses | Class Passive |
|  :---:       |  :---:    |    :---:   |      :---:     |
| Wrecker <br> (Melee foci) | melee damage, health | mobility, dodge duration/distance, ammo recovery | Can use two melee weapons. something with taking damage? |
| Deadeye <br> (Range foci) | ammo recovery, dodge distance | ultimate charge | Can use two ranged weapons. can recover ammo in more ways? |
| Untouchable <br> (Dodge foci) | dodge distance, dodge duration, mobility | health, ultimate regen | can cancel own attacks with dodge freely? |
| Evoker <br> (Ability foci) | ultimate charge, skill damage, ultimate damage | None | Skill cooldown halved. equipped passive effects are doubled? |


## Melee Weapon type examples
| Name | Strengths | Weaknesses | Area | Notes |
|  :---:       |  :---:    |    :---:   |      :---:     |     :---:     |
| Sword | None | None | 120&deg; | Balanced weapon |
| Daggers | attack speed, damage | range, knockback | 360&deg; | Up close and personal, high damage, high risk |
| Spear | range, knockback | narrow hitbox | no sweep | Low risk and knocks enemies back to kite |
| Halberd | range | attack speed, knockback | 220&deg; | Cleaving weapon, good for taking on groups. Swats away projectiles. |
| Greatsword | damage, range, knockback, ranged defence | attack speed | 160&deg; | Slow but sends enemies flying if they survive. Swats away projectiles.|
| Staff | knockback, ranged defence  | damage | 160&deg; | Low damage but sends enemies flying. Swats away projectiles.|
|  |  |  |  |  |


## Ranged Weapon type examples
| Name | Strengths | Weaknesses | Notes |
|  :---:       |  :---:    |    :---:   |      :---:     |
| Rifle | ammo | None | Balanced weapon |
| Shotgun | area, damage | None | Wide area blast |
| Sniper | damage, piercing | fire rate   | Single target slayer, bad for groups |
| SMG | damage, fire rate | ammo | Spray and pray and then run out of ammo |
| Javelin | ammo, piercing | projectile speed | Thrown weapon but does not go over enemies |
| Grenade | area, damage | ammo, fire rate, projectile speed | Thrown weapon, able to throw over obstacles |

## Passive examples
| Name | Strengths | Weaknesses | Special |
|  :---:       |  :---:    |    :---:   |      :---:     |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

## Ability examples
| Name | Strengths | Weaknesses | Special |
|  :---:       |  :---:    |    :---:   |      :---:     |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

## Ultimate examples
| Name | Strengths | Weaknesses | Special |
|  :---:       |  :---:    |    :---:   |      :---:     |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |


## Enemy examples
| Name | Strengths | Weaknesses | Notes |
|  :---:       |  :---:    |    :---:   |      :---:     |
| Grunt | None | None | Balanced, common |
| Runner | speed, damage | health | Runs ahead of allies. Will occasionally move evasively |
| Heavy | health, damage | speed | Cannot be pierced by ranged weapons |
| Shieldbearer | health |  | Redirects all damage in fixed area away from allies and towards oneself |
| Swarmer | numbers | health, damage | Spawns in packs |
| Bomber | damage | health | Explodes within certain radius of player, can be detonated by player to kill surrounding enemies |
| Thrower | damage | health | Uses ranged attacks, grenades or javelins |
| Stalker | speed, damage | health | Redirects all damage in fixed area away from oneself and towards allies. If alone, will move evasively |


