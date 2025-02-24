Flappy Bird Voice-Controlled Game

Description

This is a simple Flappy Bird-style game where the player controls the bird using their voice instead of traditional input methods. The game runs on an HTML <canvas> and uses microphone input to detect sound levels. A loud noise (like clapping or speaking) makes the bird jump.

Features

Voice-Controlled Gameplay: The bird moves up when detecting sound from the microphone.

Gravity Effect: The bird naturally falls unless lifted by sound input.

Randomly Generated Pipes: Pipes appear at varying heights and move left across the screen.

Scoring System: The player earns points by passing through pipes.

Collision Detection: The game ends when the bird hits a pipe or the ground.

Restart Button: A button appears to restart the game upon failure.


How to Play

1. Allow Microphone Access: When prompted, enable mic access for the game to work.


2. Make Noise: Clap, speak, or make any loud sound to lift the bird.


3. Avoid Pipes: Navigate through the gaps in the pipes to keep the bird alive.


4. Score Points: Pass through pipes to increase your score.


5. Restart: If you crash, click the "Restart" button to play again.



Installation & Usage

1. Download or clone this repository.


2. Open index.html in a browser.


3. Grant microphone access when prompted.


4. Start playing!



Technologies Used

HTML5 Canvas for rendering graphics

JavaScript for game logic

Web Audio API for voice control


File Structure

|-- index.html
|-- script.js  (contains game logic)
|-- style.css  (optional for styling)
|-- assets/
    |-- flappybird.png
    |-- toppipe.png
    |-- bottompipe.png
    |-- qw.png (game over image)

Future Improvements

Add background music and sound effects.

Implement different difficulty levels.

Optimize microphone sensitivity for better control.


License

This project is open-source and free to use. Modify and improve as needed!

Enjoy playing Flappy Bird with your voice!

