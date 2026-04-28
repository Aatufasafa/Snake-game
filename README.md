🐍 Snake Game (Tkinter)

A classic Snake game built using Python’s tkinter library, featuring smooth controls, simple animations, and a visually appealing grid-based design.

🎮 Features
Responsive keyboard controls with buffered input for smoother movement
Animated snake head and body with alternating colors
Dynamic apple with subtle floating animation
Score tracking displayed in real-time
Collision detection (walls and self)
Game over screen with restart option (R key)
Centered window and custom-designed grid background
🛠️ Technologies Used
Python
Tkinter (GUI)
Collections (deque) for input handling
Math module for animation effects
⚙️ How It Works
The game runs on a fixed grid where each tile represents a movement unit
The snake moves continuously based on velocity (vx, vy)
Direction inputs are queued to prevent illegal instant reversals
The body follows the head by updating segment positions in reverse order
When the snake eats food:
The body grows
Score increases
Food respawns at a random grid location
🎯 Controls
Arrow Keys → Move snake
R → Restart game after Game Over
