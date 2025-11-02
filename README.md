# Notes

All these are things to keep in mind. These are things to adjust per-game and **NOT** something you have to do. Especially for Movement, Jumps, and "Juice" sections

Please check out [TL;DR](#tldr), and [Resources Used](#resources-used)

Note: Platforming isn't just movement; **level design matters** too

## Design Principles

"The movement in a platformer feels natural, but behind the scenes, it’s anything but."

- Make the platforming feel "natural"
- Make the player feel in control of the movement
  - (So much so that it's ok to "cheat for the player")
- And a tip for beginners: do **NOT** make it **unecessarily** hard. (Players want to have fun)

## The Unique Mechanic

Every platformer needs a unique mechanic

Examples:

- Gravity switch
- Teleportation

## Add Other Movement Options too

Jumping and moving may be good, but is often not enough, so here's some common other movement mechanics

- Climbing
- Wall Jumping
- Dashing
- Double Jump
- The "Pogo" from Hollow Knight

## Movement (Oh no, PHYSICS!?)

The speed curve (adjust this for different feel).

- Instant movement - fighting games and precise movement
  - ![Instant movement](images/movement/instantMovement.png)

- Slidey movement - ice level kind of stuff
  - ![Slidey movement](images/movement/slideyMovement.png)

- In between movement - "the goldilocks amount" b/c it is more natural than instant movement
  - ![In Between movement](images/movement/inBetweenMovement.png)

## Jumps (Oh no, MORE Physics!?)

The jump curve (adjust this for different kinds of jump feel)

- Real life physics jump (takes the same time to go up than go down)
  - ![real life physics jump graph](images/jumps/idealjump.png)

- fast fall (makes jumps feel less floaty)
  - ![fast falling](images/jumps/fastfall.png)

- You can also make the jump floaty by decreasing the gravity after reaching the peak of a jump
  - (Didn't feel like finding an image for this one)

- Varying heights - Allow the player to control the heights of jumps based on how long they hold the space bar

- Having a different air acceleration than when on the ground - could add to realism, but can also hurt...

## Camera

The player needs to be able to see where they are going.

Different methods of camera movement

- Automatic side scrolling
- Static (doesn't move until the next level)
- Fixed on the player (often the movement of the camera will be damped)

## Assists - "Cheating" for the player

- Coyote Time
  - Give the player an extra time window to jump even if they are no longer touching the ground.
  - ![alt text](images/assists/coyoteTime.gif)

- Jump Buffering - If you press and hold the jump button a short time before landing, you will jump on the exact frame that you land.

- Ceiling Corner Correction
  - If jumping into the corner of a ceiling, nudge the player so they will clear the ceiling.
  - ![alt text](images/assists/ceilingCornerCorrection.gif)

- Edge Corner Correction
  - Same idea as ceiling correction, but instead do it horizontally for platforms.
  - (This is a less common mechanic tho)
  - ![alt text](images/assists/edgeCornerCorrection.gif)

- Max X and/or Y velocity - makes it so the player will never go too fast

## "Juice" - The "impact" of movement

- Particles - when running, landing, or jumping
- Sounds - when running, landing, or jumping
- Animations - when running, landing or jumping
- Stretching the character in the direction they are moving
- Slightly tilting character towards the direction they run
- Having an afterimage of the character if they move *super* fast

Don't overdo it, but these things can really make the movement feel real.

## Platformers are more than just movement

Level design is also crucial, but won't be talked about here.

## TL;DR

To make a good platformer...

- Make the movement feel natural
- Be forgiving to the player

## Resources Used

- [Platformer's Toolkit](https://gmtk.itch.io/platformer-toolkit)
- [Why Does Celeste Feel So Good to Play?](https://www.youtube.com/watch?v=yorTG9at90g)
- [Math for Game Programmers: Building a Better Jump](https://www.youtube.com/watch?v=hG9SzQxaCm8)
- \+ Many More
