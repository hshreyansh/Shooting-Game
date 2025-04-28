# SHOOTING GAME #
This is a 2D pixel-art style shooting game developed in C++ using the graphics.h library. The player controls a spaceship, moves left and right across the screen, and shoots down aliens. The objective is to #destroy incoming enemies, avoid getting hit, and achieve the highest score possible before losing all lives.

🚀Features
Smooth spaceship movement with arrow keys.

Shooting mechanic triggered by 'X' or spacebar.

Aliens move horizontally, descend after screen edge hits, and shoot back at random intervals.

Explosion animations when an alien or the player gets hit.

Dynamic scoring system rewarding successful hits.

Lives system with heart icons displaying remaining lives.

Animated starry background for immersive gameplay.

Interactive Menu with Play, High Scores (placeholders), and Exit options.

Game Over and Restart functionality.

🛠 Technologies Used
C++

graphics.h (WinBGIm library)

Standard C++ libraries (cstdlib, ctime, conio.h, etc.)

🖥 System Requirements
Operating System: Windows

Graphics Library: graphics.h with BGI support

Resolution: 800×600 pixels

Compiler: Turbo C++, Dev-C++, or any modern IDE with graphics.h support

🎮 How to Play
Move Left/Right: Use Arrow Keys.

Shoot: Press X or Spacebar.

Goal: Destroy aliens while avoiding enemy bullets.

End Condition: The game ends when all 3 lives are lost.

⚙ Setup Instructions
Ensure graphics.h, libbgi.a, and required BGI files are installed and correctly linked in your C++ compiler.

Clone or Download the repository.

Open the .cpp file in your IDE.

Compile and Run the program.

Enjoy the gameplay!

📜 Additional Notes
Alien movement speed increases as your score increases, enhancing the game's difficulty curve.

Randomized alien bullets make the game challenging and unpredictable.

Swap buffers and delay functions are used for smooth frame transitions and visual effects.

Menu screen, star background, and basic high score placeholders included to simulate a complete arcade-style experience.
