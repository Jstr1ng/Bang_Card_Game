# Bang! — Game & CPU Simulation

A C-based, command-line implementation of the popular card game **Bang!**, built with custom data structures and object-oriented design principles in C. Developed as a final course project.

## Overview

In this turn-based card game, two or more players battle each other using cards to deal damage, heal, or alter the flow of the match. Every game is unique thanks to a randomized card distribution system.

## Features

- **Randomized card distribution** — no two matches play out the same way
- **Save-state system** — freeze all stats and hands, then resume later
- **Local multiplayer** — player-vs-player on a single device
- **Automated CPU player** — simulates full games against itself using a probabilistic model trained on statistical data logged from previous human matches

## Tech

- **Language:** C
- **Interface:** CLI (turn-based)
- **Architecture:** custom data structures, object-oriented methodologies in C

## Build & Run

```bash
git clone https://github.com/Jstr1ng/Bang_Card_Game.git
cd bang-cli
make
./bang
```

## Status

Solo project — final course project.

## License & Rights

Copyright © 2026 [Jacopo Strina]. All Rights Reserved.

This repository is published for **portfolio and demonstration purposes only**. No permission is granted to copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this software, in whole or in part, without explicit prior written permission from the author.

Viewing and cloning for personal, non-commercial evaluation (e.g. by recruiters or reviewers) is permitted; any other use requires the author's consent.

See [`LICENSE`](./LICENSE) for full terms.
