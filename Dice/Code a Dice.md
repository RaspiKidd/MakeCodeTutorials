# Code a Dice

Have you lost a dice to your favourite game?
Why not code yourself a new one!

## What you will need
1 x micro:bit
1 x micro USB cable
1 x Battery pack (optional)

## Opening The Editor
1. Click on Google Chrome
2. Type [makecode.microbit.org](makecode.microbit.org)

## Code
### Setting up the coding area
1. Click and drag the **forever block to the left hand side and drop it in the bin.

### On start
1. Click on **Input**. CLick and drag a **show string** block to the coding area and attach it within **on start**.
2. Click where it says **hello** within the **show string** block and type **Shake Me**.

### Setting up Roll
1. Click on **Input**. Click and drag an **on shake** block to the coding area and drop it.
3. Click on **Variables**. Click on **Make a Variable...**. Type **Roll** and press enter.
4. Click and drag a **set Roll to 0** block to the coding area and attach it within the **on shake** block.
5. Click on **Math**. Click and drag a **pick random 0 to 10** block to the coding area and attach it within the **0** of the **set Roll to 0** block.
6. Click where it says **10** within the **pick random 0 to 10** block and type 6.

### Code for Rolling a 1
1. Click on **Logic**. Click and drag an **if true then else** block to the coding area and attach it under the **set Roll** block.
8. Click on **Logic**. Click and drag a **0 = 0** block to the coding area and attach it within the **true** of the **if then block**.
9. Click on **Variables** Click and drag a **Roll** block to the coding area and attach it within the first **0** of the **if then** block.
10. Click on **Basic**. Click and drag a **show leds** block to the coding area and attach it within the **if then** block.
11. Click the dot right in the middle of the **show leds** block to create the number 1 as it would appear on a dice.
12. Click on the small **+** sign next to **if true then** to create an **else if then** block.
13. Your code should now look like this.

### Code for Rolling a 2
1. Now repeat steps **1 to 3** from **Code for Rolling a 1**
15. Click on the **0** in the **if else then block** and type 1.
16. Click on the second dot in on the second row and the fourth dot in on the fourth row of the **show leds** block to make a number 2 as it would apprear on a dice.
17. Your code should now look like this.
18. Repeat Step 6 from **Code for Rolling a 1**

### Code for Rolling a 3
The code is now repeating it's self until the end just changing a few blocks. 

Let's see if you can get your code to look like this:

### Code for Rolling a 4
Your code should look like this

### Code for Rolling a 5
Your code should look like this

### Code for Rolling a 6 (completed code)
Your code should look like this: