# Cause and Effect Game

## Getting Started

Welcome! In this tutorial we will walk you through the basics of the Makecode Arcade platform and create a simple cause and effect game.

Click the next button to get started. 
Click the immersive reader button to listen to the instructions.
Click the lightbulb button to see the sample code.

## Step 1- Make a Background
Let's create a solid color background! From the Scenes menu drag the ``||scene:set.BackgroundColor||`` into the 'on start' block.

Click in the grey oval and select your favorite color.
```blocks
scene.setBackgroundColor(0)
```

## Step 2- Load a Sprite
Sprites are the characters in your game. You can draw your own or use one of the pre made ones.

From the Sprites menu, drag the ``||variables:set mySprite to||`` block and drag it into the on start block.

```blocks
scene.setBackgroundColor(4)
//@highlight
let mySprite = sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player)
```
