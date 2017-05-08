# Arithmetic Functions

1. Max - a simple function to find the maximum value.

In column AI, type Maximum value

In column AJ, type =MAX(N:N)

In english:

= denotes the start of a function

MAX is the name of the function that finds the maximum value in a column or row

(N:N) The parenthesis hold the cells you want to include in your calculations. "N:N" means the entire N colum that has numbers in it.

## Hit enter

![][1]

[1]: images/4-arithmetic-functions/hit-enter.png

## Add forumlas

In this data set, we want to find the total number of cases per year for the illnesses combined.

![][2]

[2]: images/4-arithmetic-functions/add-forumlas.png

## Step 1. 

In cell D1, "Total".

We could add the following formula in cell d2 =300+12 to get a total of 312. We'd have to repeat with the numbers in each cell.

That is laborious and doesn't take advantage of Excel's functionality.

Instead, we will write a formula that taps cell locations where the numbers are.

So we will write in cell d2, =B2+C2 to see the total. 

![][3]

[3]: images/4-arithmetic-functions/step-1-.png

## Propagate the formula

For the totals for the other years, you do NOT want to type =B3+C3 and then =B4+C4, etc.

Instead look at bottom right corner of the D2, and you'll see a little box. 

Hover over that box and your white cross turns into a black cross. Double-click when you have the black cross and the formula propagates through out the relevant columns.

![][4]

[4]: images/4-arithmetic-functions/propagate-the-formula.png