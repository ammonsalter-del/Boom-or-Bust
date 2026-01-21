# Boom or Bust? Innovation Prediction Exercise

A browser-based educational game that challenges players to predict which expert-endorsed innovations became commercial successes and which became market failures.

## Overview

Every innovation in this exercise won a *Popular Science* "Best of What's New" award between 2010–2019. Despite expert endorsement, some became transformative successes while others failed. Players have 30 seconds per case to predict the outcome.

**Play now:** https://ammonsalter-del.github.io/Boom-or-Bust/ or Open `boom-or-bust-professional.html` in any modern browser. No installation required.

## Features

- 36 verified innovations (18 successes, 18 failures)
- 10 randomly selected cases per session
- 30-second decision timer with speed bonuses
- Confidence betting system (1×, 2×, 3× multipliers)
- Detailed outcome explanations with lessons
- Achievement badges and streak tracking
- Works offline — single HTML file, no dependencies

## Learning Objectives

- Recognise the inherent uncertainty in technology commercialisation
- Understand that expert endorsement doesn't guarantee market success
- Identify common patterns in innovation success and failure

## Educational Use

Works well as a session opener for courses on:
- Innovation management
- Technology strategy
- Entrepreneurship
- R&D management

Typical discussion questions:
- Why do expert judges struggle to predict commercial success?
- What patterns distinguish winners from losers?
- How should this change how we evaluate new technologies?

## Technical Details

- **Single file:** Everything contained in one HTML file (~100KB)
- **No dependencies:** Pure HTML, CSS, and vanilla JavaScript
- **Browser support:** Any modern browser (Chrome, Firefox, Safari, Edge)
- **Mobile friendly:** Fully responsive — works on phones, tablets, and desktops
- **Offline capable:** Works without internet connection

## Customisation

The game is fully self-contained and can be modified:

- **Add/edit innovations:** Find the `innovations` array in the `<script>` section
- **Adjust timing:** Modify `TIMER_DURATION` constant (default: 30 seconds)
- **Change game length:** Modify `GAME_LENGTH` constant (default: 10 cases)
- **Styling:** All CSS is in the `<style>` section

## Source Attribution

All innovations are verified winners of *Popular Science* magazine's "Best of What's New" awards. Descriptions are original summaries; outcome data compiled from public sources.

## Author

**Ammon Salter**  
Warwick Business School, University of Warwick

Built with assistance from Claude (Anthropic)

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share** — copy and redistribute in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit to Ammon Salter
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix or transform, you must distribute under the same license
