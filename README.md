# README

## Table of Contents
* [Overview](#overview)
* [Goalset](#goalset)
* [Bingo Variants](#bingo-variants)
* [Acknowledgements](#acknowledgements)

## Overview
This is a fork of YogoC's repo for the Multi-Bingo Mayhem 2026 tournament for experimenting with the SM64 bingo goal set. Feel free to make your own changes, preferably on a different branch.

The [Super Mario 64 Bingo Guide](https://docs.google.com/document/d/13cVrO2_c435ysJOeOyZMzo0AFFWDLGleZ5UTPoCDOxM/edit?tab=t.0#heading=h.3znysh7) has a lot of information about the general rules of the game, some goals that may not be super clear at first, and some routes that come up only in bingo. I highly recommend looking through it! 

I am also creating a [YouTube playlist](https://www.youtube.com/playlist?list=PLFDvSQTjFNZ4) of bingo videos including things not on the guide! (Special thank you to Benedict and everyone else for contributions.) They may be added to the guide later, but some are probably too situational for more casual players.

## Goalset

We can import a custom goal set to [Lockout.Live](https://lockout.live/) with the `.json` file!
- A list of all of the goals and explanations for them can be found [here](Bingo%20Goals%20Specifications-%20Badro%20Set.md). 
- You can find the `.json` for the goal set [here](Super%20Mario%2064%20Goals-%20Badro%20Set.json).
- Yogo's original `.json` for the goal set is [here](Super%20Mario%2064%20Goals-%20Tournament%20Standard%20Set.json).

### All bingo variants have ***16 Star No LBLJ*** Rules applied. This means:

* ***NO LBLJ, NO SBLJ, NO CRACKSLIDE***
* ***NO SKIPPING THE 8 STAR DOOR***
* ***ONLY MIPS CLIP TO SKIP 30 STAR DOOR***

## Bingo Variants

Here are the detailed descriptions for each variant used in the tournament. For all variants except Double Anti, players reset when time starts. For Double Anti, players reset exactly one minute after time starts.

### Standard Bingo
* Complete one line on the 5x5 bingo board and collect the grand star in BitS.
* A goal may only be marked once it has been completed.
* In order for the bingo to be valid, all goals on the line must be satisfied when collecting the grand star in BitS.

### Triple Bingo
* Complete three lines on the 5x5 bingo board and collect the grand star in BitS.
* A goal may only be marked once it has been completed.
* In order for the bingo to be valid, all goals on the line must be satisfied when collecting the grand star in BitS.

### Lockout Bingo
* Complete as many goals as possible on the 5x5 bingo board before your opponent.
* A goal may only be marked once it has been completed.
* Each goal can only be marked by one player: once one player marks it, the other player is locked out of that goal.
* Once a goal is marked (correctly), it will not be unmarked.
* The match ends when a player reaches 13 goals (*there is no need to collect the grand star*).

### Double Anti Bingo
* Complete two lines on the bingo board and collect the grand star in BitS.
* The first minute of the match has no gameplay, but the players study the board and must submit a line for their opponent to complete to the hosts by the one minute mark.
* One of the two lines completed must be the line assigned by your opponent.
* The hosts will notify each of the players in Discord what line they have been assigned by their opponent.

### Ascend Bingo
* Complete a goal on the top row of the bingo board and two "shiny" goals highlighted on the bingo board.
* The board has "fog of war" over it. Only the bottom row is revealed at the start.
* Each completed goal reveals all of the goals adjacent to it (not diagonal).
* Timing ends when the last goal needed to win is marked (*there is no need to collect the grand star*). This can either be a goal on the top row (if two shiny goals have already been collected) or the second shiny goal (if a goal on the top row has already been collected).
* Goals are not unmarked. However, to finish the game, there must be a connected path from the bottom to the shiny and the top goals that are all satisfied.
  * For example, if "Lose Mario's Hat" is a goal on the board, you can lose the hat, mark the goal, then get the hat back. However, if your path from bottom row to top row or shiny goals is dependent on "Lose Mario's Hat", you must lose Mario's hat in order to finish the game.

### Acknowledgements

Thank you [YogoC](https://www.twitch.tv/yogoc) for hosting the tournament and creating this goal set and repo! 

Thanks to [Benedict](https://twitch.tv/benedictfleur123) for help with making the goalset, playtesting, proofreading, and general organizational help. Thanks also to SecretAdept for making the icons and helping get the goalset on [Lockout.Live](https://lockout.live/)!
Thank you all who helped playtest the goals and give feedback over the past few months!