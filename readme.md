# Rock-Paper-Scissors with Jetson Nano


## Overview
![poster.png](img/poster.png)
You can try the Rock-Paper-Scissors game. 

## File

### `collection.ipynb`
Data collection for the rock-paper-scissor hand gestures.

### `train_model.ipynb`
Train the model with the data collected.

### `test_game.ipynb`
Code for actual gameplay process. This code is a simplification of game.ipynb. When you cloned this repository, you sholud try first.

### `game.ipynb`
Code for actual gameplay process, including GPIO lights and buttons. 

During the gameplay, the resulted model is used to recognize the hand gesture of the player.

### Table for meanings of folder names
>| Category | Meaning |
>|--|--|
>| one | Rock |
>| two | Paper |
>| three | Scissor |

## Demo

### `Prepare the train model` 
Open the "train_model.ipynb". 

Run all the cells in order.

If you run all the cells, you would get best_model.pth.

※You don't need to do this process every time.

### `Play the Rock-Paper-Scissors game ` 
Open the "test_game.ipynb". 

Run all the cells in order.

You can play the Rock-Paper-Scissors game. 

![game.png](img/game.png)

If you want to get good results, take the following pose.

![rock.png](img/rock.png)

![paper.png](img/paper.png)

![scissors.png](img/scissors.png)