# 100devs tic-tac-toe Group Project  


### Roadmap    

#### index.html    
```
[X] Will handle the structure of the gameboard
[X] Will have 4 sections based on the mockups by Ana:
    ->1st stage gameboard
      -triggered on page load 
      -intro gameboard 
      -displays the game title & player modes
    ->2nd stage gameboard
      -triggered when a player chooses an opponent
      -displays an input player name notification window
      -notification window has an input field for the player(s) name
       and a start button
    ->3rd stage gameboard
      -triggered when a player clicks start
      -displays an empty gameboard with player name(s) below X and O
      -random player starts at this point
    ->4th stage gameboard
      -triggered when a player wins or draws
      -gameboard is full of X and O at this point
      -displays notification window with the winner or draw
      -notification window also has a 'play again' & 'back to menu'
[X] Will have a night/day mode button   
```

#### main.js
```
[X] Will connect objects to the DOM (majority of the event listeners etc)
[X] Will initiate game instances depending on player opponent choice
[X] Will handle swithcing between different gameboard states
[X] Will control dark/light mode
[X] Will control mouse hover actions

```
#### gameBoard.js
```
[X] The gameboard is made up of 9 indidivual cells/squares
[X] No need to render the board since index.html handles the structure
    ->target each individual cell/square on the gameboard

```
#### boardCell.js
```
[X] 
```

#### File & Folder Structure   
```
|-README.md  
|-index.html  
  |-assets  
    |-fonts  
    |-mockups  
  |-js  
    |-board.js   
    |-game.js   
    |-main.js   
    |-player.js   
    |-space.js   
    |-token.js   
  |-stylesheet   
    |-mediaqueries.css   
    |-mediaqueries.scss   
    |-mixins.css   
    |-mixins.scss   
    |-normalize.css   
    |-stylesheet.css   
    |-stylesheet.scss   
```

   
