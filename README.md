# Classic Arcade Game Clone

## Description

In the **Classic Arcade Game Clone** game you have a Player and Enemies (Bugs). The goal of the player is to reach the water, without colliding into any one of the enemies. The player can move left, right, up and down. The enemies move in varying speeds on the paved block portion of the scene.

## How to start the game

* Open the folder "Project(Amir Hossain)-Classic Arcade Game Clone".
* Click on `index.html`

## Rules

Once a the player collides with an enemy, the game is reset and the player moves back to the start square. Once the player reaches the water the game is won.


## How it works

**The Enemy function, which initiates the Enemy by**
*Loading the image by setting this.sprite to the appropriate image
*Setting the Enemy initial location.
*Setting the Enemy speed

**The update method for the Enemy**
*Updates the Enemy location
*Handles collision with the Player

**The Player function, which initiates the Player by**
*Loading the image by setting this.sprite to the appropriate image
*Setting the Player initial location
*The update method for the Player
*The render method for the Player

## Things to be observed

*Left key should move the player to the left, right key to the right, up should move the player up and down should move the player down.
*Recall that the player cannot move off screen
*If the player reaches the water the game should be reset by moving the player back to the initial location
*You can add your own Player methods as needed.


## License

The contents of this repository are covered under the [MIT License](https://choosealicense.com/licenses/mit/#). The license file has been attached as `LICENSE.txt`.


