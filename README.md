# Wordy (Wordle Clone with JavaFX)

Wordy is a recreation of the online game [Wordle](https://www.nytimes.com/games/wordle/index.html) using JavaFX. This was my final project for CSCE 314: Programming Languages at Texas A&M University. Since this was a school project, I can't share my source code with you, but you are welcome to download the game and try it out yourself!

<p align="center">
  <img src="/images/blankGUI.png" alt="Wordy GUI" width=500 />
</p>

## Features

<p align="center">
  <img src="/images/loadSaveFeature.png" alt="Load/Save Feature" width=250 />
  <img src="/images/gameInProgress.png" alt="Game In Progress" width=250 />
  <img src="/images/statScreen.png" alt="Post-Game Stats" width=250 />
</p>

- **Load & Save**: Pick up where you left off after quitting a game in progress.
- **Responsive Virtual Keyboard**: Letters you've guessed will be color coded, and if they are not present in the correct word, the button will be disabled.
- **Statistics Tracking**: Various personal stats, such as your guess distribution and streak, are tracked across all of your playthroughs.

## Requirements

This project requires **JDK 17** or later, which you can find here:

[Download JDK](https://www.oracle.com/java/technologies/downloads/)

Select the version that matches your OS and architecture. I recommend downloading the latest version of JDK. After downloading, follow the instructions
to install it.

## Download

Windows: [wordy-windows.zip](https://github.com/rstacks/wordy/raw/main/wordy-windows.zip)

Linux: [wordy-linux.tar.gz](https://github.com/rstacks/wordy/raw/main/wordy-linux.tar.gz)

## Instructions for Running the Game

- Extract the contents of the zip file or tarball to a known location. For Linux users, run this command from the directory that contains your download:

```
$ tar -xzf wordy-linux.tar.gz
```

- **Make sure that the** <code>wordy-1.0.jar</code> **file is in the same directory as all four text files.**
- On Windows, simply double-click on the jar file to start the game. Linux users should run the following command from the directory of the extracted files (this should also work for Windows users):

```
$ java -jar wordy-1.0.jar
```

## How to Play

- Check out [Wordle](https://www.nytimes.com/games/wordle/index.html) to find out how to play the game.
- Guess the correct word by clicking on the keyboard buttons on screen.
- Letters you've guessed that are not in the correct word will be disabled, similar to Wordle's "Hard Mode."
- Start a new game with a new word at any time by clicking the **Reset** button.
