# Uno Game Application
This project is a Java-based simulation of the popular card game Uno, inspired
particularly by the Uno Flip variation. The game is known for its simple rules
and exciting gameplay.

## Overview
This is an implementation of the popular card game, Uno created by group number 18.
Players try to match the color or number of the card on top of the pile in the middle.
Special cards like SKIP, REVERSE, WILD, and WILD_DRAW_TWO introduce additional 
strategic elements to the game.

In This Milestone (Milestone 2), we met our primary objective which was transitioning
the game from its old form (terminal-based) to a GUI-based iteration. This graphical
upgrade aims to provide a more immersive and user-friendly experience for players.

## Rules of Uno
1. Players try to match the card on the card pile by color or number.
2. Special cards introduce additional game dynamics.
3. The first player to discard all cards wins the round.

Enjoy the game!

For more detailed rules, please refer to the official Uno Rules.

## Installation
This is a simple Java project which doesn't require any additional installation apart
from Java runtime environment. You can clone this repository or download it to your
local machine.

### Prerequisites:
- Java SE Development
- Your preferred IDE (e.g., IntelliJ IDEA, Eclipse, VS Code, etc.)

### Steps:
1. Clone the repository to your local machine or download the zip file.
2. Open the project in your chosen IDE. 
3. Build and run the project from the IDE.

Alternatively, you can navigate to the project directory in the terminal and run
the Java files from there.

## Features
- Multiplayer gameplay.
- Interactive Graphical user interface.
- Supports special Uno Flip cards and actions.
- AI Players.
- Saving and loading.

## Usage
After running the main method in the StartScreen class, a JFrame will pop up where the game 
will begin. You will be prompted to enter the player's names and then you may begin playing.
The game is played in a turn-based system, and you can see who's turn it is, actions, and
any necessary input you need to provide.
Follow the on-screen instructions for playing the game.

## Code Structure
### Classes
1. AlertEvent: Represents an event that carries a message for alert dialogs within the game.

2. Card
    - Represents a card with a color, type, and value.

3. CardTest
    - Contains tests for the `Card` class functionality.

4. CardType
    - Enum defining the types of cards (e.g., NUMBER, SKIP, REVERSE).

5. Color
    - Enum defining the colors of cards.

6. Deck
    - Represents the deck of Uno cards with shuffle and draw capabilities.

7. DeckTest
    - Contains tests for the `Deck` class functionality.

8. Game
    - Manages the overall game logic, player turns, and game status.

9. GameController
    - Listens to and processes action events to control game flow.

10. GameScreen
    - The GUI for the main game, displaying the current state and accepting user input.

11. GameTest
    - Contains tests for the `Game` class functionality.

12. InputEvent
    - Represents an event that carries user input data.

13. Player
    - Represents a player with a name and a hand of cards.

14. PlayerScore
    - Manages the scoring system of the game.

15. PlayerScoreTest
    - Contains tests for the `PlayerScore` class functionality.

16. PlayerTest
    - Contains tests for the `Player` class functionality.

17. PromptEvent
    - Represents an event that carries a message and options for user prompts.

18. SpecialCard
    - Represents a special type of card in the game with additional rules.

19. SpecialCardTest
    - Contains tests for the `SpecialCard` class functionality.

20. StartScreen
    - The initial GUI for game setup, allowing addition of players and game start.

21. StartScreenEvent
    - Represents an event related to the start screen, such as adding a new player.

22. UnoEvent
    - Represents a game event, such as a change in the current top card or a player's turn.

23. UnoUtil
    - A utility class providing additional functionality to support the game logic.

## Future Roadmap
As we continue to evolve our Uno Game Application, the upcoming enhancements will enrich the user's experience
and introduce new challenges. In the upcoming Milestone 3, we are focusing on the following key developments:

- Uno Flip Integration: in our next milestone we will add the integration of Uno Flip cards, which will add
  a new twist to the classic Uno game. We aim to implement the unique rules and scoring mechanisms that come
  with Uno Flip, providing players with a dynamic and engaging game variant.

- AI Player Capability: To increase the challenge, we will be adding the ability to play against AI opponents.
  These AI players will be designed with flexibility in mind, allowing them to adopt various strategies.

Feedback from users and TAs will be invaluable as we continue to enhance and
refine the game's interface and mechanics.

## License and Contact
Yasmina Younes 101193167 - yasminayounes@cmail.carleton.ca

Jaden Sutton 101180717 - jadensutton@cmail.carleton.ca

Nick Yung 101173976 - nicholasyung@cmail.carleton.ca

Caleb Lui Yee 101187217 - caleb.lui-yee@cmail.carleton.ca

Project Link: https://github.com/yasmina-younes/UNO
