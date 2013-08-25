## Types of Attacks

There are two main categories of attack, 'physical' and 'magical'.
Physical attacks can have subtypes 'slashing', 'piercing', and 'bashing', while
magical attacks can have subtypes 'fire', 'arcane', 'bio', 'holy', and 'dark'.

Attacks are also described as one of:

- Melee: adjacent squares only, diagonals included
- Reach: adjacent squares and squares at range(2) in the same row or column
- Range(X): any square reachable within X moves

All of those range types require "line of sight", which is measured from the centers
of the two squares - the line between the two centers must not cross any walls, or other
non-traversable obstacles, but *can* cross units, terrain, etc.

These other ranges do *not* require line-of-sight:

- Distance(X): must be within X squares of the target, but obstacles an walls are ignored
- Minion(X): a creature needs to be able to move to target with X MP

## Basic Mechanic

An attack proceeds as follows:

- The attacker rolls some dice
- Any bonuses he may have are distributed to the dice as needed.
- Each die showing a 4 or better is a 'hit', natural sixes are 'critical strikes ('crits')
- The defender rolls some dice
- Any bonuses he has get added to dice as they are needed
- Each die showing a 5 or better is a 'block'
- Damage dealt is equal to 'hits + 2 x crits - blocks'

## Persistent Effects

Many abilities say that something is true 'for X turns' or 'until their next turn'.
Those cards do not produce an effect and then get discarded, they *are* the effect -
until that effect ends, they will remain in front of whoever is being granted (or cursed
with) the effect.

Effects that last 'for X turns' or 'for X rounds' are placed in the appropriate location with
X different counters on them - each time the condition is fulfilled (end of that player's turn,
end of a round), remove one counter. When the last counter is removed, the card is discarded.

Unless otherwise stated, a bonus that is applied by a card lasts only through the completion of that one card's action.  For example, if a card that states "the target gets a +1 bonus to their defense" is played, the defense bonus would end once that card is resolved and would not extend into the next card played.

## Notation

Attacks are generally more succinctly described - they typically look like "3pb+1" or "1mh".
The first number is how many dice are to be rolled - this is the 'power' of the attack.
The two letters following are the type and subtype of the damage, and the last number
(if there is one) is the 'bonus'.

Defenses are much less frequently described, but bonuses are described like "+1 die against
magic" or "+2 against bashing attacks". The former adds a die to the defense roll, and the
latter adds to the defense bonus.

One fairly frequently used mechanic is to make multiple rolls and select the best of them -
this is written as "2x3ps+2".

Many abilities do not involve an attack, but instead have you roll some dice, add them up,
an consult a table of outcomes. These rolls are described as "2d6" or "4d6". Often you
only care about the highest or lowest value rolled out of a dice pool - that is written like
"max(3d6)", or "min(2d6)".

## Bonuses

Bonuses are added to dice to increase the number of successes. They are added to the highest
failing die until it is a success, and then to the next-highest; you cannot choose to apply
it in some other fashion, though you may sometimes wish to. A 'natural' roll refers to the
number actually visible on the die, but any other reference refers to the adjusted value.

In addition, some attacks have keyword bonuses:

- Knock-back: if any damage is dealt by this attack you may slide your target one square directly away from you.
- Crushing: Natural 5s are considered 'critical' as well.
- Poisoned: if any damage is dealt, causes the poisoned status (see below)
- Penetrating: target does not get to roll defense
- Focused: all hits are critical
- Flaming: if any damage is dealt, target is on fire.

## Statuses

There are some conditions that are used by many abilities - these are called 'statuses', and
have their own card. When an ability applies a status, the unit with the status takes the appropriate
status card and places it in front of them.

If a card says to 'afflict' a target, put the actual card in front of that target like a status - it
doesn't reach your discard pile until its effect ends.

- Poisoned: at the start of each turn, roll 1d6: on a 1 lose 2 AP, on 2-4 take 1 damage, on 6 discard this card.
- Stunned: at the start of your next turn, roll 2d6. If the total is above 10 nothing happens, if it's above seven
  you lose 2 AP and 2 MP, otherwise you lose all AP and MP this turn.
- Dazed: at the start of your next turn, lose all Of your MP.
- Defenseless: unit does not get to roll defense dice against any attack, lasts for one turn.
- On Fire: at the beginning of target's turns, he chooses either to lose 3AP and 2 MP and remove this status,
  or to take 1 damage.
