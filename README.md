### Snake Game Using Object-Oriented Programming (OOP) in C++

This project is a classic Snake game implemented in C++, demonstrating key Object-Oriented Programming (OOP) principles. Players can control a snake that moves across the console screen, eats food, and grows in length. The project highlights fundamental OOP concepts such as Encapsulation, Inheritance, Polymorphism, and Abstraction.

#### Game Features
- **Normal Snake Mode**: Navigate the snake to eat food, causing it to grow longer.
- **Fast Snake Mode**: Select a faster-moving snake for an added challenge.
- **Score Tracking**: Displays the player's score based on the number of food items eaten.
- **Real-time Controls**: Use W, A, S, and D keys to control the snake's movement in up, left, down, and right directions.
- **Game Over Mechanism**: The game ends if the snake collides with itself.

#### OOP Concepts Demonstrated

- **Encapsulation**: Encapsulation is achieved by grouping related attributes and methods into appropriate classes. For instance, the `Snake` class manages the snake’s length, body, and direction, while the `Board` class is responsible for rendering and game updates.

- **Inheritance**: The `FastSnake` class extends the `Snake` class, inheriting its properties and behavior, but with added functionality for faster movement.

- **Polymorphism**: Polymorphism is applied by using a base class pointer (`Snake*`) to refer to both `Snake` and `FastSnake` objects. The `move` method in `FastSnake` overrides the base class method, allowing the behavior to differ based on the object type.

- **Abstraction**: Abstraction is utilized by providing simple methods to interact with the game, such as `move` and `changeDirection` in the `Snake` class. The internal logic of the game, like rendering and input management, is handled by the `Board` class, abstracting complexity from the user.

#### Getting Started

##### Prerequisites
- A C++ compiler (e.g., `g++`).
- A Windows environment (the game relies on `<windows.h>` for console handling).

##### Compilation & Execution
To compile and run the game, open a terminal and navigate to the project directory. Use the following commands:



##### Controls
- **W**: Move up
- **A**: Move left
- **S**: Move down
- **D**: Move right

#### How to Play
1. Run the game executable.
2. Select between Normal Snake or Fast Snake mode.
3. Control the snake using the WASD keys to move.
4. The game ends when the snake collides with itself.

---

Created by **Adarsh Jha**. For questions or suggestions, feel free to reach out via [GitHub: AdarshCodes1221](https://github.com/AdarshCodes1221).
