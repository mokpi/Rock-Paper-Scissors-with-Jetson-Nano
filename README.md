
# Rock-Paper-Scissors with Jetson Nano

![poster.png](img/poster.png)
You can try to play the **Rock-Paper-Scissors game with a Jetson Nano**! 

## Files

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

### Folders inside `dataset`
>| Category (Folder Name) | Meaning |
>|--|--|
>| one | Rock |
>| two | Paper |
>| three | Scissor |

## Demo

### 1. Prepare the trained model
Open `train_model.ipynb` and run all the cells in order.

If you run all the cells, you should get `best_model.pth` file, this file will be used as the model to recognize hand gesture.

※ You don't need to do this process every time.

### 2. Play the Rock-Paper-Scissors game 
Open `test_game.ipynb` and run all the cells in order.

You can play the Rock-Paper-Scissors game after you run the last cell. 

![game.png](img/game.png)

## Enhancing Recognition Results
### (For now)
If you want to get good hand gesture recognition results, the following poses are recommended.

#### Rock
<img src="img/rock.png" width="600">
#### Paper
<img src="img/paper.png" width="600">
#### Scissors
<img src="img/scissors.png" width="600">

### Further development

1. Collecting more data to train the network would certainly improve
    the accuracy of the network. 
    - different environments and lighting
    - different colors
    - use a better camera
2. We use Alexnet for the recognition. Choosing a more suited network may help.
