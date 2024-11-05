# Instructions  
In the last exercise, you used nested for-loops to have the turtle draw a square repeatedly to make a snowflake. Use this repl.it link to have yertle draw the following shapes using nested loops. We encourage you to work in pairs on this.
## Steps
1. Complete the code in the active code window below to draw a snowflake of triangles. Remember that triangles have 3 sides and you will need to turn 120 degrees (external angle) 3 times to draw the triangle. Use the `turnAmount` variable for the single turn after drawing a triangle. How many times did you need to run the outer loop to go all the way around? Try changing the turnAmount variable to 40 to see how many times you need to loop with a wider distance between the triangles.

2. In the exercise above, you figured out how many times to run the outer loop to finish the snowflake. You may have noticed that the number of times the loop needs to run is related to the angle you turn before drawing the next triangle. These turns have to add up to 360 degrees to go all the way around. Change the outer loop so that it runs the number of times needed by using a formula with the `turnAmount` variable and 360. Can you draw a snowflake using more or less triangles than before by just changing the turnAmount value?

3. Create another variable called `n` for the number of sides in the polygon the inner loop draws. Change the angle in the inner loop to also use a formula with 360 and this new variable. Can you change your snowflake to draw squares or pentagons instead?

4. Let’s add some more color! Add an if/else statement that changes the [Color](https://docs.oracle.com/javase/7/docs/api/java/awt/Color.html) of the pen before the inner loop depending on whether the outer loop variable is odd or even. Remember that even numbers have no remainder when divided by 2.

5. Be creative and design a unique snowflake! 


