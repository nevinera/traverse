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

- The attackers rolls some dice
- Any bonuses he may have are distributed to the dice as needed.
- Each die showing a 4 or better is a 'hit', natural sixes are 'critical strikes ('crits')
- The defender rolls some dice
- Any bonuses he has get added to dice as they are needed
- Each die showing a 5 or better is a 'block'
- Damage dealt is equal to 'hits + 2 x crits - blocks'

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

