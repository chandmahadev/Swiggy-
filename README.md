# Magical Arena Game

Welcome to the Magical Arena Game! In this game, players engage in magical battles using their unique strengths and abilities.

## How to Run

To run the game, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone the project repository.
3. Open a command prompt or terminal and navigate to the project directory.
4. Compile the Java code using the following command: javac Main.java
5. Run the game using the following command: java Main
## Game Rules

- Each player has a health value, strength level, and attack power.
- Players take turns attacking each other, using a combination of their attack power and a random die roll.
- The defending player's strength level and another die roll are used to determine the defense value.
- The difference between the attack value and defense value is subtracted from the defending player's health.
- The game continues until one player's health reaches zero.

## Running Tests

The project includes JUnit tests to ensure the correctness of the game logic. To run the tests:

1. Ensure you have JUnit 5 or later version in your project dependencies.
2. Open a command prompt or terminal and navigate to the project directory.
3. Compile the test classes using the following command:javac -cp .:path/to/junit.jar MagicalArenaTest.java
4. Run the tests using the following command:java -cp .:path/to/junit.jar:path/to/hamcrest.jar org.junit.runner.JUnitCore MagicalArenaTest
## Acknowledgments

Special thanks to the developers who contributed to this project.

## References

- [JUnit Documentation](https://junit.org/junit5/docs/current/user-guide/)
- [Java SE Documentation](https://docs.oracle.com/en/java/javase/index.html)
