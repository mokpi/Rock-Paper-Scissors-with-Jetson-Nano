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
Code for testing gameplay process. This code is a simplified version of `game.ipynb`, the GPIO part indicating the device's choice of Rock/Paper/Scissor is removed. 

Try running this file before `game.ipynb` when you clone this project.

### `game.ipynb`
Code for actual gameplay process, including GPIO lights and buttons. 

During the gameplay, the trained model is used to recognize the hand gesture of the player.

### Table for meanings of folder names
>| Category | Meaning |
>|--|--|
>| one | Rock |
>| two | Paper |
>| three | Scissor |

## Demo

### Prepare the train model
Open the "train_model.ipynb". 

Run all the cells in order.

If you run all the cells, you would get best_model.pth.

※You don't need to do this process every time.

### Play the Rock-Paper-Scissors game 
Open the "test_game.ipynb". 

Run all the cells in order.

You can play the Rock-Paper-Scissors game. 

![game.png](img/game.png)

If you want to get good results, take the following pose.

Rock
![rock.png](img/rock.png)
Paper
![paper.png](img/paper.png)
Scissors
![scissors.png](img/scissors.png)
