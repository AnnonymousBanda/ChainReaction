
# Chain Reaction - Java & Swing

## Introduction

**Chain Reaction** is a clone of the popular Chain Reaction game, built using Java and the Swing framework. In this two-player strategy game, players take turns placing orbs in a grid. The goal is to dominate the board by causing chain reactions that eliminate your opponent's orbs.

The game is played on an n x n grid. Each cell can hold a certain number of orbs before it "explodes," sending orbs to neighboring cells and potentially causing a chain reaction. The player who completely eliminates their opponent's orbs wins.

## Features
- Turn-based two-player game (Red vs Blue).
- Chain reaction mechanic based on grid cell capacity.
- Graphical user interface (GUI) built with Java Swing.
- Simple and intuitive gameplay.

## Prerequisites

To run this project, you will need:
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) version 8 or higher
- [Git](https://git-scm.com/) (to clone the repository)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AnnonymousBanda/ChainReaction
    ```

2. Navigate to the project directory:
    ```bash
    cd ChainReaction
    ```

3. Compile the project using the following command:
    ```bash
    javac Main.java
    ```

## Running the Game

1. Run the application by executing:
    ```bash
    java Main
    ```

2. The game window will appear with an 8x8 grid by default. Red player goes first.

3. Take turns clicking on the grid cells to place orbs. When a cell reaches its maximum capacity, it will explode, sending orbs to the adjacent cells and causing chain reactions.

4. The game ends when one player dominates the board and eliminates the other player's orbs.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
