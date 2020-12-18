# 1 Player Dice-Game

 ### A Two player nice game created with JQuery, CSS and HTML 

 **[PLAY HERE](https://arditti93.github.io/DIce-Game/)**

 ### Approach 

The `getElementById` method is used to access elements in the HTML.
Math.random() creates a number between 0 - 0.9, The "*6" multiplies random number by 6 - This creates a number between 0 - 5. Math.floor() takes a decimal number and converts it into an integer 2.4 = 2. The +1 is then added to create a number between 1 - 6. If the random number is “0” - it adds 1 to make it 1. if the random number is 5 - it adds 1 to make it 6.

Various logic using `if/else` statements is used to simulate the different aspects of the game for example;

```              
                if (dice !== 1) {
                    score += dice;
                    $("#score").html(playerScore);
                }
                else {
                    $(".player").html("<h2>Game over! you've rolled a one</h2>")
                    $(".roll").hide()
                    $("#gamePlay").hide()
                }
```
if the dice roll is not equal to 1, update and display the score by acessing elements with the id of score in the HTML. 

### Instructions

1. Click the button to to roll the dice.

2. The game end if a one is rolled or the score hits 20

3. when the score passes 20 the game is won

![dice](dice.gif)



