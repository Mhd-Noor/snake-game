# 🐍 Snake Game

Welcome to my Snake Game! 🎮 This project is a fun implementation of the classic Snake game using Python and Pygame. The goal is simple: eat the fruit and grow your snake while avoiding collisions with the walls and yourself! I know the repository has been made recently while I have coded this last year(2023). If only my younger self had known how to use version control😁

## 💡 Inspiration

As a first-year student with no prior coding experience, I utilized my term break to explore my passion for programming. Initially unsure of which game to create, After extensive research and decided on a Snake game. I viewed it as a perfect challenge and an entry-level project. I started with a basic game using blocks on a Tetris-like grid and gradually transformed it into a visually appealing game. Below is the documentation of my journey.
## 🛠️ Key Features

Dynamic Gameplay: The snake moves continuously, and you control its direction with arrow keys. 🕹️
Fruit Mechanics: Eating fruit causes the snake to grow, adding an exciting challenge as the game progresses. 🍏
Collision Detection: The game ends if the snake collides with the walls or itself, keeping the gameplay intense! 🚧
Custom Graphics: I designed unique graphics for the snake and the fruit, enhancing the overall visual experience. 🎨
## 🔑 Key Functions

Movement Control: The snake's movement is managed using pygame.KEYDOWN events, allowing smooth directional changes.
Collision Checking: The game continually checks for collisions with walls and the snake's body to determine if the game is over.
Sound Effects: Although disabled in the GitHub version due to audio setup issues, I initially included sound effects for when the snake eats fruit. 🔊
## ⚙️ How It Works

### SNAKE Class
This class defines the properties and behaviors of the snake, including:

- **Initialization**: The snake's body is represented as a list of `Vector2` objects, each holding its coordinates.
- **Movement Logic**: The **`move_snake()`** function updates the position of the snake based on its current direction, utilizing a copy of the body to handle growth.
- **Graphics Management**: Methods such as **`update_head_graphics()`** and **`update_tail_graphics()`** handle the dynamic rendering of the snake's head and tail based on its movement.

### FRUIT Class
This class manages fruit generation:

- **Random Positioning**: The fruit appears at random coordinates on the grid, implemented using **`random.randint()`** to ensure variety in gameplay.
- **Rendering**: The **`draw_fruit()`** function uses Pygame to render the fruit on the screen.

### MAIN Class
This class orchestrates the game loop:

- **Game Update Logic**: The **`update()`** function calls methods to move the snake, check for collisions, and detect game-over conditions.

## ⚠️ Note on GitHub

Due to audio configuration issues, the sound functionality may not work when running the code directly on GitHub or similar environments. However, the game runs flawlessly in my local setup where I have the appropriate audio dependencies installed. But you can feel free and download the code and run it in your system

Feel free to clone the repository and run the game locally to experience the fun! 🚀

## 🤝 Contributing

I welcome contributions! If you have suggestions or improvements, please feel free to submit a pull request.
