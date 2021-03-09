### @explicitHints true

# Turtle Logo - Lesson #4 - Advanced

## Turtle Logo - Lesson #4, with variables and sprites @unplugged
**Making the Turtle's Pen Change Color.**

In this lesson you will change the color of the trails the **Turtle Objects** leave behind.
![](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson4-advanced/raw/main/assets/color_screenshot.png)

## Step 1
Code your solution below.

```ghost
let myTurtle = turtle.fromSprite(sprites.create(img`
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
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 25)
myTurtle.turnDirectionByDegrees(TurtleTurnDirection.Right, 90)
myTurtle.setPenColor(0)
myTurtle.say("Hello, World!")
```
