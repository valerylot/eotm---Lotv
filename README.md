//Valery Lot
//10/19/2026
//Mini Challenge #4 Employee of the Month
//What we did: Fixed bugs in a Javascript file

# Employee of the Month Machine

Isaiah's Taco Truck has a little program that works out who gets employee of the month.

Jacob, Jose and Jsaiah wrote it. It does not work.

## What to do

1. Put this folder somewhere you will find it again and open it in VS Code.
2. Go Live, then open the Console.
3. Fix it until the whole file runs top to bottom with no errors and the answers are right.

**There are six bugs.** Every single one of them is something we covered this morning. You are not missing a piece of JavaScript you have never seen.

## Rules

- **Change one thing at a time, then look at the Console again.** This is the whole skill. Changing four things and reloading tells you nothing about which one mattered.
- **Do not rewrite the file.** Find the broken line and fix that line. Deleting a function and writing your own version does not count.

## What it should do when it works

- Print the three names
- Print the total tacos dropped this month
- Print how many shifts each person worked
- Print the average number of shifts
- Print how many people are eligible for employee of the month

If a number looks strange to you, it probably is. Check it by hand.

## When you are done

In your `README.md`, write up all six. For each one: what you saw, and what caused it. Symptom first, then cause.

## If you finish early

Three more, and these are **not** things we have covered. Do not go changing the file for these. Just open the Console, type them in, and see if you can work out what is going on.

```javascript
[10, 9, 100].sort()
```

```javascript
0.1 + 0.2
```

```javascript
typeof null
```

The first one does not give you `[9, 10, 100]`. The second one is not `0.3`. The third one claims `null` is an object.

All three are real and all three are famous.

## BUG LOG
1. Line 7, had "" in warnings, removed the "" and changed to 0 because everyone starts at 0 warnings anyway
2. Line 7,  had "7", removed the " " around the number 7 tacosDropped 
3. Line 14, changed Name to name
4. Line 19, changed const to let, so that the variable can change
5. Line 28, removed the = from <= so for loop is not out of bounds
6. Line 39, there was not a return statement for the avg variable, added a return statement

