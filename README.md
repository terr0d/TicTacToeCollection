# Tic-Tac-Toe Collection

This project is a collection of Tic-Tac-Toe variants implemented using Pygame. I'm planning on rewriting it to OOP.

## Key Features

1.  **Multiple Game Modes:**
    *   **Classic:**  The traditional 3x3 Tic-Tac-Toe game.
    *   **3-Tac:**  A strategic variant where players can only have 3 active markers on the board at a time.
    *   **Tetris-like:** Markers fall from the top of the grid like Tetris pieces, filling empty spaces from the bottom up.
    *   **Ultimate Tic-Tac-Toe:** A complex meta-game played on a 3x3 grid of 3x3 Tic-Tac-Toe boards.  The position of the move in a smaller grid determines which of the larger grids your opponent must play in next.

2.  **Configurable Settings:**
    *   **Game Volume:** Adjust the volume of sound effects.
    *   **Music Volume:** Control the volume of the background music.
    *   **Themes:**  Choose from a selection of visual themes, each providing a distinct look.
    *   **Save Settings:** Changes to volume and theme are saved to `src/settings.json` and automatically loaded the next time the game starts.

3.  **User Interface:**
    *   **Main Menu:**  Provides options to Play, access Settings, or Quit the game.
    *   **Game Mode Selection:**  Allows players to choose their desired game mode and view a short description of each.
    *   **Settings Menu:**  Offers sliders for volume control and buttons for theme selection.
    *   **In-Game UI:**  Displays the current game board, player scores, and provides visual feedback for winning lines.
    *  **Bot/Human Player**: Player can choice to play against computer (Bot) or another player locally.

4.  **Sound and Music:**
    *   [**Background Music:**](https://www.youtube.com/watch?v=CyJKo-XQGHg)  an amazing dungeon synth track by Vindkaldr

5.  **Bot Opponent:**
    * Bot opponent is available for all game modes.
