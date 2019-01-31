# 💎 Crystal Collector Game 💎
# Welcome

## Overview
In this project we will be creating a crystal collector game using HTML, JavaScript and CSS!

This is a fun and interactive game for web browsers.
The game consists of a player guessing the given number by adding the values of each gem💎.
The player is given four gem options, one blue, one green, one red and one yellow. They will be displayed at bottom of page.
The player will be given a RANDOM NUMBER between 15-120.
When player clicks on any gem it will add a specific number of points to the total score located at bottom of page. Each gem has a hidden value of between 1 and 12.
The player wins the game by matching the random number given at beginning of the game and they lose if the score goes above the random number.
Game will never reveal the number of each gem, instead the total score will be updated after each gem is clicked.
The total amount of wins and losses will be displayed and updated everytime the player wins or losses.
Everytime the game restarts the player is given a new random number and the gems have different hidden values.

![alt text]()

### Getting Started
You will need to create an HTML and CSS file and for the game functionality you will be using JavaScript's library jQuery.
In your game.js file you will need to have click event functions for each gem in order to know when a gem has been clicked by the user. You will also need to create functions for when user wins or losses a game. In order to generate a random number you need to use the `Math.random` function.

Here is a code snippet of how I used Math.random and Math.floor to generate a random number and assign it to the user:

``` 
var randomNumber = Math.floor(Math.random() * 105 + 15)
    
    //Selects a random number to be shown to the user at the beginning of the game.
    //Number should be between 15-120.
    
    $('#randomNumber').text(randomNumber);
    
    //Setting up random numbers for each gem
    //Random number has to be between 1 and 12.
     var num1= Math.floor(Math.random() * 11 + 1)
    var num2= Math.floor(Math.random() * 11 + 1)
    var num3= Math.floor(Math.random() * 11 + 1)
    var num4= Math.floor(Math.random() * 11 + 1)
    //Declaring variables for tallies
    var playerTotal= 0;
    var wins= 0;
    var losses= 0;
    
    $("#numberWins").text(wins);
    $("#numberLosses").text(losses);
    //Resets the game
    function reset() {
        randomNumber= Math.floor(Math.random()*105+15);
        console.log(randomNumber)
        $("#randomNumber").text(randomNumber);
        num1= Math.floor(Math.random() * 11 + 1);
        num2= Math.floor(Math.random() * 11 + 1);
        num3= Math.floor(Math.random() * 11 + 1);
        num4= Math.floor(Math.random() * 11 + 1);
        playerTotal= 0;
        $("finalTotal").text(playerTotal);
    }

```

### Built With
* HTML
* CSS
* jQuery JavaScript
* [VSC](https) - Visual Studio Code, Editor
* [Github Pages](https) - Deployment

## Authors

* **Maira Jimenez** - *Initial work* - [Mairaaj14](https://github.com/Mairaaj14)


## Acknowledgments

* Jerome Chenette
* Sasha Patsel
* Jimmy Tu
