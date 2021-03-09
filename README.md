### @explicitHints true

# Turtle Logo - Lesson #4

## Turtle Logo - Lesson #4 @unplugged
**Making the Turtle's Pen Change Color.**

In this lesson you will change the color of the trail the **Turtle** leaves.
![color](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson4/raw/main/assets/color_screenshot.png)

## Step 1
** Follow Along**

Once again, all our programs begin with an ⇢``on start``⇠ block. Then you need to add the **Turtle** using the ⇢``show turtle``⇠ block.
```blocks
turtle.showTurtle()
```

## Step 2
** Follow Along**

The **Turtle** by default leaves a white trail behind it. This color can be changed by using the ⇢set turtle's pen color to ▢⇠ block.
```blocks
turtle.showTurtle()
turtle.setPenColor(1)
```

## Step 3
** Follow Along**

Inside the ⇢set turtle's pen color to ▢⇠ block, select the "▢" and select *red*. Now add a ⇢myTurtle move forward 25 steps⇠ block to see the new red trail.
```blocks
turtle.showTurtle()
turtle.setPenColor(2)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 4
** Follow Along**

You can even change the color more than once. After moving forwards, add another ⇢set turtle's pen color to ▢⇠ block and change the color to *blue* then add forwards again.
```blocks
turtle.showTurtle()
turtle.setPenColor(2)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
turtle.setPenColor(8)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 5
** Try it Out**

Now try moving the **Turtle** some different distances, different directions, turning and changing color.
```blocks
turtle.showTurtle()
turtle.setPenColor(8)
turtle.moveTurtleDirection(TurtleDirection.Backward, 25)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Right, 90)
turtle.setPenColor(2)
turtle.moveTurtleDirection(TurtleDirection.Forward, 50)
turtle.turnTurtleDirectionByDegrees(TurtleTurnDirection.Left, 90)
turtle.setPenColor(7)
turtle.moveTurtleDirection(TurtleDirection.Forward, 25)
```

## Step 6
**Success!**

You can now change the trail color the **Turtle** leaves.

## Step 7
**Your Turn**

Get your **Turtle** to:
- move
- change its trail color
- turn
- move again
- then say, "I can change colors!"

## Step 8
**Done**

You have successfully completed your forth lesson in Turtle Logo.

```ghost
turtle.say("Hello, World!")
```
