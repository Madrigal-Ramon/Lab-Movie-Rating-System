# Movie Rating System
This is a Java program that allows users to rate movies and provides feedback based on their ratings. 
The program also recommends films based on the user's favorite genre.

## Approach
User Input Handling:
    The program prompts the user to enter their name and greets them.

Movie Ratings:
    The user is asked to input the names of 5 movies and rate each one on a scale of 1 to 10.
    Input validation ensures that ratings are within the valid range.

Average Rating Calculation:
    The program calculates and displays the average rating of all movies.

Rating Classification:
    Based on the average rating, the program classifies the user's movie taste using if-else statements.

Favorite Movie Check:
    The program checks if the user rated any movie as a 10 (masterpiece) or below 4 (low rating) and provides feedback.

Consistent Ratings Check:
    Using logical operators (&& and ||), the program checks if all ratings are high or if any rating is very low.

Genre Preferences:
    The user is asked to input their favorite genre, and the program uses a switch statement to respond.

Movie Recommendation:
    Based on the user's favorite genre, the program recommends a movie using the conditional (? :) operator.

## Reflection Question

The difference between a nested if from an if-else is that a nested if is an if statement within another if statement, Which is used whenever you need to check multiple conditions hierarchically. Meanwhile, an if-else is used to execute one block of code if a condition is true and another block if the condition is false. Also, it is mainly used for binary decisions (one or the other). The advantages of a switch over multiple if statements are readability, efficiency, and simplicity. For instance, it would be easier on the eye to read a single variable being compared to multiple constants. As having to read an abundance of if-else statements. Conditional operators simplify decision-making since it is a simpler, easier, and shortened version of an if-else statement. Short-circuit evaluation is a behavior in which the second argument is evaluated only if the first argument does not meet the result. For instance, in a && (AND) if the first argument evaluates to false then the second argument would not become evaluated and also become false. The same goes for the || (OR) if the first argument evaluates to true then the second argument would not evaluate and become true as well.
