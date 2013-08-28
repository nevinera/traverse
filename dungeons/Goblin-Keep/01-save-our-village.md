# Dungeon A01: Save Our Village!

The village of Sormic is beset by goblins, and has had enough of their thieving.
Food is running low and pets and small children have recently gone missing.
They have hired you to decrease the numbers of the beastly little creatures.

## Map

```text
                                                _______________
                                                |  10x10      |
                                                | shaman      |                        _________
                                                |             |                       |  5x5    | - contians 1 false tile
                                                |             |                       |treasure | no enemies
                                                _______________                       |_________|
                                                      |   |                             =   =
                                                      |   |                             =   =   = barred door between
              __________________          _______________________________             ___________
              |  10x10          |         |    16x16                    |             | 10x10   |
              |                 |         |                             |             |         |
              | knockback/trip  | _ _ _ _ |                             | _ _ _ _ _ _ |         |
              |     enemy       | _ _ _ _ |                             | _ _ _ _ _ _ |         |
              |  dung pit       |         |              fire           |             |         |
              ___________________         |                             |             ___________
                                          |                             |
                                          |                             |
                                          _______________________________
                                                      |     |
                                                      |     |
                                                _________________
                                                |    10x10      |
                                                |               |
                                                |               |
                                                |               |
                                                |_______________|
                                                      |     |
                                                      entrance
```

## Working Notes

Bonus of some variety for full sweep of dungeon (healing potion or minor equipment)

#### Introduction round
- predominantly small melee
- miniboss = shaman - ranged magic
- couple ranged physical

#### Overall
- include a few minor traps (tripwire, false floor, dart hole)
- include 1 or 2 hazards (bonfire in center room, dung pit)
- include 1 obstacle (barred door = attack door to get through.  If trying to flee, may present problem for heroes)
- potentially include 1 empty room (they do exist, make 'em nervous)
- treasure (goblin treasure = largely junk) room?
- introduce few minor conditions
  - sleeping goblins / dazed
  - poison from wounds - 1 or 2 enemies, dung pit fall

### Monsters

#### Goblin Raider

3 MP, 3 AP, 4 HP

- Stab: 3AP, 2pp. If target has at least one othe goblin adjacent to them, +1 bonus to the attack.
- Scurry: 3Ap, gain 5MP
