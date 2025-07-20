# Pong
  ## A simple Pong game built in Unity using C#

- [Pong](#pong)
- [Description](#description)
- [Features](#features)
- [Project Structure](#project-structure):
  - [Scenes](#scenes)
  - [Scripts](#scripts)
- [Gameplay](#gameplay)
- [Menu](#menu)
- [Pause 1 (before start game)](#pause-1-before-start-game)
- [Pause 2 (during match)](#pause-2-during-match)
- [Playground](#playground)
- [Future](#future)
- [License](#license)

## Description
  This repository contains a minimalist version of the classic Pong arcade game, created in Unity using C#. It features a clean menu system, pause and score UI, and responsive paddle and ball physics. This is part of a series of small Unity projects under the AJ4 Projects umbrella.

## Features
  - Built with Unity and C#
  - Local 2-player gameplay
  - Simple scoring system
  - Pause and resume functionality
  - Clean main menu for scene navigation
  
## Project Structure
  The project contains the following components:
 
### Scenes:
  Menu – Start screen.
  Game – Core Pong gameplay with two paddles and a ball.

### Scripts:
  GameManager.cs - manages game state and score tracking.
  Goal.cs - detects goals and triggers scoring.
  MenuManager.cs – handles scene changes and quitting the game.
  Pause.cs - handles pause logic, UI toggling, and restarting rounds.
  Paddle.cs - handles paddle input and movement for each player.
  Ball.cs - controls ball movement and resets.

## Gameplay
Two players control paddles on either side of the screen:
  - Player 1 uses Up and Down.
  - Player 2 uses W and S.

The goal is to hit the ball past the opponent’s paddle. Each goal updates the score and resets the game state to pause mode.
  
## Menu
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/9916d377-4a66-42d4-b225-c0edfb8fc3e4" />
  Main menu screen with a simple and clean layout.
  
## Pause 1 (before start game)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/064c8183-43b0-454b-a7bf-3c089b9acfe2" />
  Pause screen showing info, how to back to menu and how start game again.

## Pause 2 (during match)
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/9076cf3e-d096-41d8-a500-e763501587ce" />
  Pause screen showing info, how to back to menu and how start game again. But now with score.

## Playground
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/9b708179-a233-4ccd-967f-bd8424ced124" />
  Gameplay screen showing Pong board.
  
  
## Future
  I plan to add more small Unity projects to this repository. Some existing projects may be updated or improved over time.
For larger projects or collaboration ideas, feel free to connect with me on [Discord](https://discord.gg/gEXcTbWQ6V). 

## License
  This project is licensed under the [MIT License](https://opensource.org/license/mit/).
