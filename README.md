# bt-alt-rules
Draft for alternative (simpler/quicker) rules for Battletech.

# Goals of these rules
Drastically simplify the existing rules to speed up gameplay while keeping the fun parts.
## Simplification approach
 - Reduce the number of dice rolls drastically.
 - Use precomputed target numbers (required dice roll) where possible.
 - Even out probabilities by using d20.
 - Avoid large number of complex situational modifiers to dice rolls.
## Stuff to keep
 - Basically everything on the mech sheet.
 - Having your mech slowly blown to pieces.
 - Ability to use existing mech designs without making them all feel the same.
 - Keep all the decisions about target selection and heat management.
## Extra stuff
 - Allow further RPG elements.
 - Make Mechwarriors feel unique.

# Things to solve
- how many weapons hit??? 1xppc+1xlrm20 vs 12xmedlaser???
- hit zones???

# Order of turns
## Alternative 1
 - every mech rolls initiative: d20 + initiative skill + commander bonus
 - highest initiative goes first
### Unresolved
 - going last could be desirable?
 - bonus based on mech type (light +2, medium +1, heavy 0, assault -1)?
 - commander bonus?
	
## Alternative 2
 - each team rolls initiative: d20 + commander initiative skill
 - highest initiative chooses to go first or last
 - mechs alternate turns
### Unresolved
 - how to alternate with unequal mechs on teams? (rules should already exist)

# Taking turns
every mech gets one move action and one fire action
 - can be taken in any order
 - each action must be completed separately (no partial moves)
 - can make a second move action instead of firing
 - move can be zero hexes (mech still counts as moving inside hex)
 - moving creates no penalty
 - only one move action can be a jump
 - effects of firing a resolved before another mech takes a turn

### Unresolved
 - double move a good idea?
 - does move generate heat?
 - ability to return fire?

# Movement
## Movement speed
Movement speed is identical to the old walking speed value (example: locust 8, atlas 3).
## Move action
When performing a move action (normal move action), the mech can move a number of hexes up to 
it's movement speed. The mech can end it's movement facing any direction desired. Each hex moved
through (including the destination hex, excluding the starting hex) which contains difficult terrain 
(e.g. woods, swamps, water of a certain depth) counts as two hexes moved.
## Jumping
Instead of moving normally a mech with jump jets can move a number of hexes up to it's jumping
speed (jumping range), as with a normal move action the mech can face any direction after the jump.
A mech can only jump once per round, so when using a second move action only one of them can be 
a jump. When jumping all terrain is ignored and the mech can always move as many hexes as it's
current jumping speed is when jumping.
## Sprinting (2nd move action)
A mech can use it's fire action to perform a second move action using all the rules for the 
normal move action. If the first move action was a jump, the second move action can't be a jump
and vice versa.

### Unresolved
 - heat created by moving (especially jumping)
 - minimal movement
 - movement modifiers (e.g. damage)

# Evasion value
each mech has an evasion value (like AC in D&D):
 - base 10
 - \+ (walking speed - 4)
 - light +2, medium +1, heavy 0, assault -1
 - modified by pilot skill (-1? to +4?)
this is the base to hit the mech on d20
 - example: locust(light) 10+(8-4)+2 = 16
 - example: wolverine(medium) 10+(5-4)+1 = 12
 - example: atlas (assault) 10+(3-4)-1 = 8
if the mech looses walking speed due to damage, evasion value 
is adjusted immediately

### Unresolved
 - modifications to hit chance (woods, weapon range, cover)?
 - roll every weapon?
 - weapon ranges?
 - should rolling higher than required give a benefit?
 - using modifiers or D&D style advantage/disadvantage
  
