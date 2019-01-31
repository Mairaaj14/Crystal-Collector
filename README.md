# 💎 Crystal Collector Game 💎
# Welcome

## Overview
In this project we will be creating a crystal collector game using HTML, JavaScript and CSS!

This is a fun and interactive game for web browsers.
The game consists of a player guessing the given number by adding the values of each gem.
The player is given four gem options, one blue, one green, one red and one yellow. They will be displayed at bottom of page.
The player will be given a RANDOM NUMBER between 15-120.
When player clicks on any gem it will add a specific number of points to the total score located at bottom of page. Each gem has a hidden value of between 1 and 12.
The player wins the game by matching the random number given at beginning of the game and they lose if the score goes above the random number.
Game will never reveal the number of each gem, instead the total score will be updated after each gem is clicked.
The total amount of wins and losses will be displayed and updated everytime the player wins or losses.
Everytime the game restarts the player is given a new random number and the gems have different hidden values.

![alt text](crystalcollector.gif)

### Getting Started
You will need to create your HTML files, and in a separate folder create an `assets` folder where you will have two folders
`css and images` in your css folder that's where you want your CSS stylesheet `style.css`.
Your css file will be in charge of the front-end, you control and decide the styling of every part of your portfolio.
To make our portfolio responsive, the @media screen tags must be added in your CSS file.

Here is a code snippet of how my media screen tags and my styling looks like:

``` 
 @media screen and (max-width: 980px) {
    .container {
      width: 100%;
      max-width: 960px;
      margin: 0 auto;
      clear: both;
    }
    #masthead {
      position: fixed;
      z-index: 99;
      width: 100%;
      max-width: 960px;
      margin: 0 0 30px;
      overflow: auto;
      color: #ffffff;
      background: #ffffff;
      border-bottom: 2px solid #cccccc;
    }
  }

  @media screen and (max-width: 768px) {
    .container {
      width: 100%;
      max-width: 768px;
      margin: 0 auto;
      clear: both;
    }
    #masthead {
      position: fixed;
      z-index: 99;
      width: 100%;
      max-width: 768px;
      margin: 0 0 30px;
      overflow: auto;
      color: #ffffff;
      background: #ffffff;
      border-bottom: 2px solid #cccccc;
    }
  }

  @media screen and (max-width: 640px) {
    .container {
      width: 100%;
      max-width: 640px;
      margin: 0 auto;
      clear: both;
    }
    #masthead {
      position: static;
      z-index: 99;
      width: 100%;
      max-width: 640px;
      margin: 0 0 30px;
      overflow: auto;
      color: #ffffff;
      background: #ffffff;
      border-bottom: 2px solid #cccccc;
    }
  }

```

### Built With
* HTML
* CSS
* [VSC](https) - Visual Studio Code, Editor
* [Github Pages](https) - Deployment

## Authors

* **Maira Jimenez** - *Initial work* - [Mairaaj14](https://github.com/Mairaaj14)


## Acknowledgments

* Jerome Chenette
* Sasha Patsel
* Jimmy Tu
