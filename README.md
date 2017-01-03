# SnakesAreSpreading

1. Give your game a name via an HTML element
    ex: (<h1>My Awesome Game Name</h1>)

2. Add a game surface ("canvas") for your snake to spread
    ex:(<canvas id="the-game" width="400" height="320" />)

3. Give your snake some styling. Locate the spot in the index.html file where the "insert the style sheet" is and add in the following
  <link rel="stylesheet" href="style.css" type="text/css">

4. Below the div containing the canvas, draft the instructions on how to play your game

5. Insert the script which controls your snake. Locate the spot in the index.html file where the "insert the javascript" is and add in the following
<script type="text/javascript" src="game.js"></script>

6. Add a instructions for the user on how to start the game.
(Hint - Line 23)

7. Keys
Find the variable 'keys' on line 165, this is what helps control your snake. Utilizing the website http://keycode.info/ insert the key that will start your game in the start_game array.
(ex: start_game: [13, 32])

8. Repeat the same concept in step 7, but for the arrays left, right, up, down.
