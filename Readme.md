# 2D Platformer Game Features

## Movement Control:
The player can move left and right using horizontal input.
The movement speed can be adjusted via the `moveSpeed` variable.

## Jump Mechanics:
The player can jump when grounded, utilizing the `jumpForce` variable to determine jump height.
A double jump feature is implemented, allowing the player to jump again while in the air if they haven't already used their double jump.

## Ground Detection:
The script uses a ground check mechanism with a `groundCheckPoint` and a `LayerMask` to determine if the player is on the ground.
This ensures that jumps can only be executed when the player is grounded.

## Animation Control:
The player's movement speed and grounded state are communicated to the animator to trigger appropriate animations.
The sprite's orientation is flipped based on the direction of movement, providing a visual cue for the player's direction.