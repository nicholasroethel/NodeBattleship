# NodeBattleship

NodeBattleship is a multiplayer Battleship game made with Node.js and socket.io.
At the start of the game, five ships of different sizes are placed randomly in a 10 x 10 grid.
The players then take turns firing shots at the opponent's grid until one player has sunk all of
the opponent's ships.

![Battleship screenshot](http://inf123.github.io/battleship-screenshot.png)

## Install

Step 1: Download/clone.
```
git clone https://github.com/nicholasroethel/NodeBattleship
```
Step 2: Install dependencies.
```
npm install
```
Step 3: Start server.
```
node server.js
```
Step 4: Open http://yourhost:8900/ in your browser to play.

## Docker

Step 1: Download/clone.
```
git clone https://github.com/nicholasroethel/NodeBattleship
```
Step 2: Install Docker.

Step 3: Build the Docker Container.
```
docker build -t battleship .
```

Step 4: Run the Docker Container.
```
docker run -p 8901:8900 battleship
```

Step 4: Open http://yourhost:8901/ in your browser to play.


## Play live on Heroku

Step 1: Visit the site

Go to: https://node-battleship.herokuapp.com/


## Notes
This game was orignally forked from https://github.com/inf123/NodeBattleship. However, it has been modified to work with Docker and to be hosted on Heroku
