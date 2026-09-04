# Boom or Bust? Innovation Prediction Exercise

**Version 2.0 — September 2026**

A browser-based educational game that challenges players to predict which expert-endorsed innovations became commercial successes and which became market failures.

## Overview

Every innovation in this exercise won a *Popular Science* "Best of What's New" award between 2010–2019. Despite expert endorsement, some became transformative successes while others failed. Players have 30 seconds per case to predict the outcome.

**Play now:** https://ammonsalter-del.github.io/Boom-or-Bust/ or open `index.html` in any modern browser. No installation required.

## What is new in version 2.0

- Every one of the 34 cases fact-checked against public sources, with dates, figures and outcomes corrected
- Two cases changed: Kymriah moves from success to failure, Google Now removed from the pool
- Company, brand and inventor names removed from everything a player sees before answering, so the card no longer gives away its own answer
- No *Popular Science* headline or sentence is reproduced anywhere in the game
- Keyboard answers: B or left arrow for Boom, N or right arrow for Bust, 1 to 3 for confidence, Enter for the next case
- Accessibility: labelled buttons, a spoken announcement of each case and each result for screen readers, and a visible focus outline
- Artwork on the opening screen and a logo in the header
- Links to the other games in the Innovation and Entrepreneurship Playbook
- A link preview picture and tags, so a shared link shows something

## Features

- 34 verified innovations (17 successes, 17 failures)
- 10 randomly selected cases per session, never two from the same company
- 30-second decision timer with speed bonuses
- Confidence betting system (1×, 2×, 3× multipliers)
- Detailed outcome explanations with lessons
- Achievement badges and streak tracking
- Single HTML file with no dependencies

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

See `TEACHING-GUIDE.md` for a fuller session plan.

## Technical Details

- **Single file:** everything in one HTML file, about 260KB including the artwork
- **No dependencies:** HTML, CSS and plain JavaScript. The one outside request is the Google Fonts stylesheet
- **Browser support:** any modern browser (Chrome, Firefox, Safari, Edge)
- **Mobile friendly:** responsive on phones, tablets and desktops
- **Link preview:** `social-preview.jpg` must sit beside `index.html` for shared links to show a picture
- **Analytics:** Google Analytics counts visitors, and only if the visitor accepts. The game collects no personal information

## Customisation

The game is self-contained and can be modified:

- **Add or edit cases:** the `innovations` array in the `<script>` section
- **Adjust timing:** the `TIMER_DURATION` constant (default 30 seconds)
- **Change game length:** the `GAME_LENGTH` constant (default 10 cases)
- **Styling:** all CSS is in the `<style>` section

## Source Attribution

All innovations are verified winners of *Popular Science* magazine's "Best of What's New" awards. Descriptions are original summaries; outcome data compiled from public sources.

## How this game was made

I designed and directed this game and I maintain it. The code was written by Claude Fable and Claude Opus 4.7, working to my design and instructions. The artwork is from Gemini. I chose the cases, checked the outcomes against public sources, and approved everything in the game.

## Author

**Ammon Salter**
Warwick Business School

## License

This work is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share** — copy and redistribute in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit to Ammon Salter
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix or transform, you must distribute under the same license
