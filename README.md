# Nibbles
Built by Chris Heriot
linkedin.com/in/christopherheriot

It's easy to loose track of what's underneath the libraries we rely on so this will be a fun back-to-basics exercise.

Dom interaction has been isolated to the GameBoard object. Input and timers are isolated to the Controls object. This way adding additional game logic like walls, speed increases, or disappearing food could be unit tested independent of complications.

Browser tested in Chrome 57.0.2950.4 dev and Firefox Developer Edition 52.0a2.

### Usage
Press an arrow key to begin. Ctrl+R to start over.

### Run
Open the html file.

### Build
rm cheriot-snake.zip; mkdir cheriot-snake; cp snake.html README.md cheriot-snake/; zip -r cheriot-snake.zip cheriot-snake/; rm -rf cheriot-snake
