# Lottery Simulator

A browser-based lottery simulator that lets you configure prize quantities and draw winners with weighted probability.

## Features

- Define prizes and their quantities — each draw is weighted by remaining count
- Update prize quantities at any time before drawing
- Probabilities recalculate automatically after each draw
- Runs entirely in the browser — no backend required

## Usage

Open `index.html` directly in any modern browser, or use the hosted version:

https://shenxingy.github.io/Lottery_simulator/

1. Select a prize from the dropdown and set a new quantity, then click **Update**
2. Click **Simulate** to draw a winner — the prize pool shrinks by one each draw
3. Remaining quantities and live probabilities are shown on screen

## Customization

Edit the `prizes` object at the top of the `<script>` block in `index.html` to change the prize names and default quantities.

![Preview](https://github.com/shenxingy/Lottery_simulator/blob/main/Preview.png)
