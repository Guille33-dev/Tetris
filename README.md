# Tetris in Java 🎮

This project implements the classic **Tetris** game in **Java**, using **Swing** for the graphical interface and **JUnit 5** for unit testing.

## 📋 Requirements

To run this project, you need to have installed:

- **Java JDK 11 or later**
- **JUnit 5** (to run tests)
- **Git** (to clone the repository)

## 🚀 Installation and Execution

1. Clone this repository to your computer:
   ```sh
   git clone https://github.com/your-username/tetris.git
   ```
2. Navigate to the project folder:
   ```sh
   cd tetris
   ```
3. Compile the code:
   ```sh
   javac -d bin src/tetris/*.java
   ```
4. Run the game:
   ```sh
   java -cp bin tetris.TetrisGUI
   ```

## 🎮 Game Controls

- **Left Arrow**: Move the piece left.
- **Right Arrow**: Move the piece right.
- **Down Arrow**: Speed up the falling piece.
- **Spacebar**: Instantly drop the piece.

## 🧪 Unit Testing

To run unit tests with JUnit 5:

1. Ensure JUnit 5 is properly configured in your environment.
2. Compile and run the tests:
   ```sh
   javac -cp ".:lib/junit-5.7.1.jar" -d bin src/test/tetris/*.java
   java -cp ".:bin:lib/junit-5.7.1.jar" org.junit.platform.console.ConsoleLauncher --scan-class-path
   ```

## 📜 License

This project is licensed under the **MIT License**. You are free to use and modify it. Enjoy coding! 🚀

