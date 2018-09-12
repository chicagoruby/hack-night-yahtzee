# Yatzee

Yahtzee is a classic multi-player dice game. From Wikipedia:

_The objective of the game is to score points by rolling five dice to make certain combinations. The dice can be rolled up to three times in a turn to try to make various scoring combinations._

## Gameplay

A game consists of thirteen rounds. After each round the player chooses which scoring category is to be used for that round. Once a category has been used in the game, it cannot be used again. 

The categories are as follows:

*TOP SECTION*:
- **Category**: Ones | **Scores**: The sum of dice with the number 1
- **Category**: Twos | **Scores**: The sum of dice with the number 2
- **Category**: Threes | **Scores**: The sum of dice with the number 3
- **Category**: Fours | **Scores**: The sum of dice with the number 4
- **Category**: Fives | **Scores**: The sum of dice with the number 5
- **Category**: Sixes | **Scores**: The sum of dice with the number 6

*BOTTOM SECTION*
- **Category**: Three of a Kind | **Description**: At least 3 dice with the same value | **Scores**: The sum of all dice
- **Category**: Four of a Kind | **Description**: At least 4 dice with the same value | **Scores**: The sum of all dice
- **Category**: Full House | **Description**: 3 of one number, 2 of another | **Scores**: 25 points
- **Category**: Small Straight | **Description**: 4 sequential dice | **Scores**: 30 points
- **Category**: Large Straight | **Description**: 5 sequential dice | **Scores**: 40 points
- **Category**: Yahtzee | **Description**: 5 Dice with the same value | **Scores**: 50 points
- **Category**: Chance | **Description**: Any values | **Scores**: The sum of all dice

During each round, the player can roll up to three times. After each roll, the player chooses which dice values the player wants to keep and which dice values to re-roll. At the end of the third roll, or before if the player chooses, the player records a mark in one of the 13 score categories.

If the dice do not match the requirements of any category, the player must choose a category and score a 0 for that category. Some combinations offer the player a choice as to which category to score them under; e.g., a full house could be scored as the face values in the top section, or in the Full House, the Three-Of-A-Kind, or the Chance categories. The Chance category is often used for a turn that will not score well in any other category.

If the player throws a Yahtzee and has already filled the Yahtzee box with a score of 50, they score a Yahtzee bonus and get an extra 100 points. However, if they throw a Yahtzee and have filled the Yahtzee category with a score of 0, they do not get a Yahtzee bonus.

If a player scores a total of 63 or more points in the six boxes in the top section, a bonus of 35 is added to the upper section score.

## The Application

You are building an application that will allow you to play multiple turns, either in single player or multiplayer mode. You will need to simulate dice rolls, choosing which dice to set aside, and decide how you want to record the score. Make sure you are displaying the game card when it is needed so that the player can pick which category they want to play. You should be able to maintian a running score for each player.

## Stretch 

### Scoring analysis

Many combinations will allow you to score in more than one category. Analyze each throw against your scorecard to show the scoring options for each roll. Which categories would this combination fit into and how many points would you yield for each category?

### Stored games

Keep track of your scores. Export your game cards so you can keep track of your best scores!
