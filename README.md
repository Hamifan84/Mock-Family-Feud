# Chick-fil-A Family Feud

An interactive, browser-based Family Feud game for Chick-fil-A team events, parties, and training activities. The game is implemented as a self-contained HTML file, so no build tools, server, or package installation are required.

## Features

- Family Feud-style answer boards with point values
- Multiple rounds with interactive answer reveals
- Two-team score tracking and face-off team selection
- Strike and buzzer sound effects using the Web Audio API
- Configurable game setup with custom team names and rounds
- Saved games using browser local storage
- Optional Fast Money finale with a configurable timer
- Responsive game controls and a final winner screen

## Run the game

1. Clone or download this repository.
2. Open [`Mock_Family_Feud.html`](./Mock_Family_Feud.html) in a modern web browser.
3. Select **Set Up Game** to configure team names, rounds, and optional Fast Money.
4. Use the on-screen controls to navigate between rounds, reveal answers, award points, and record strikes.

The game can also be opened directly from the repository after cloning:

```text
file:///path/to/cfa-familyfeud/Mock_Family_Feud.html
```

## How to play

1. Choose team names and either use the built-in rounds or create custom rounds.
2. Start the game and use the left and right navigation buttons to move between screens.
3. Reveal an answer by selecting its numbered card.
4. When prompted, select the team that won the face-off.
5. Use **Ding** for correct answers and **Buzz & Strike** for incorrect answers.
6. Continue through the rounds and use the Fast Money screen when enabled.
7. The final screen displays the winning team or a tie.

## Customization

Questions, answers, team names, scoring, and themes can be adjusted in the HTML and JavaScript. The setup screen supports custom rounds without editing the source.

## Files

| File | Description |
| --- | --- |
| [`Mock_Family_Feud.html`](./Mock_Family_Feud.html) | Standalone configurable game experience |
| [`cfa_game.html`](./cfa_game.html) | Alternate entry point for the same game experience |

## Browser support

Use a current version of Chrome, Edge, Firefox, or Safari. The game loads Google Fonts, Font Awesome, and one background image from external URLs, so an internet connection is recommended for the complete visual presentation. Sound effects require the browser to allow audio after a user interaction.

## License

This project is for personal and internal team use. Feel free to adapt it for other team events.
