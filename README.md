# Snake Game
The software development process Snake Game for IT214 .

<img width="500" alt="snake" src="https://user-images.githubusercontent.com/74800962/141614564-58b5d9e0-f4da-4fa2-a0a6-867ce130bcab.png">

## Idea of the game 

The snake try to eat the food (the orange square 🟧 ) , each time snake eats the score increase by 10  that done with help of growSnake function in [GameBoard.java](https://github.com/wesamhamad/Snake_Game/blob/main/src/GameBoard.java)
```java
private void growSnake() {
        snake.grow();
        score += 10;
    }
```
``
Note: you can change increasing of the score by change score vlaue in same file (ines 185-188)
``
## Controls

The keybindings are completely customizable on the in-game menus.
The default ones are:


| Keys              | Actions                    |
| ----------------- | -------------------------- |
| Arrow Keys        | Moves the snake            |
| q                 | Quits the game at any time |
| p                 | Pauses/Unpauses the game   |
| h                 | Show help during game      |


When the player loses the program exits and the final score is printed to the terminal.


# Output Smples
* Output1 : 

https://user-images.githubusercontent.com/74800962/141614866-96c99520-f4ee-48cc-9661-6e1b057c9706.mov

* Output2 :
 
![Snake_2](https://user-images.githubusercontent.com/74800962/141614868-74580ef1-061d-40ef-ae00-10e9a66a9c3c.gif)

# Learning Reference 
The code for this repo was inspired by [LazoCoder](https://github.com/LazoCoder/Snake)
