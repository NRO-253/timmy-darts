# Timmy Darts

A tablet scorer for our lunch-break 301 against **Timmy**, the extra player who throws a fixed number every round, with all our house rules built in.

**Play it:** open the GitHub Pages link of this repository on the tablet and add it to the home screen.

## What it does

- 301 (or 501), double out, entered by tapping a dartboard (or a keypad)
- Timmy with his house rules: sitting out when you're not below him, free rounds, the Stellrunde, clean 26s, 26 by subtraction, banking, trading, giving and vaulting 26s, the Stellrunde random result, skipping a turn
- Freaky Friday Timmy and Super Madness Timmy, each with a hot or cold form per game
- Every rule can be switched on or off; "Vanilla 301" turns Timmy off
- Checkout and 26 tips, handicaps, achievements, monthly champion, rating
- Stats per player with a dartboard heatmap and CSV export
- Backup export and import as a JSON file

## Where the data lives

Players, games and settings are saved in the browser of the device that runs the page. Nothing is sent anywhere. Use **Rules → Backup** to save a copy or move your games to another device.

## How it is published

The whole app is one file, `index.html`. GitHub Pages serves it straight from the `main` branch, so every commit to `main` is live within a minute or two.
