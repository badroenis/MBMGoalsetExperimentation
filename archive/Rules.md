# Tournament Rules

In this document, you can find all of the rules and details about the tournament. Please reach out to the hosts in Discord if you have any questions.

## Table of Contents
* [Player Eligibility](#player-eligibility)
* [Tournament Structure](#tournament-structure)
* [Timeline](#timeline)
* [Match Rules](#match-rules)
  * [Variant Selection](#variant-selection)
* [Bingo Variants](#bingo-variants)
  * [Standard Bingo](#standard-bingo)
  * [Triple Bingo](#triple-bingo)
  * [Lockout Bingo](#lockout-bingo)
  * [Double Anti Bingo](#double-anti-bingo)
  * [Ascend Bingo](#ascend-bingo)
* [Goalset](#goalset)

## Player Eligibility
* All entrants must have at least one run submitted to the [Super Mario 64 leaderboards on speedrun.com](https://www.speedrun.com/sm64).
* All entrants must play on a platform and version that is accepted on the leaderboards. The restrictions on each platform are expressed in their respective Category Rules on speedrun.com.
  * [N64](https://www.speedrun.com/sm64?h=120_Star-n64&rules=category&x=wkpoo02r-e8m7em86.9qj7z0oq)
  * [VC](https://www.speedrun.com/sm64?h=120_Star-vc&rules=category&x=wkpoo02r-e8m7em86.jq6540ol)
  * [EMU](https://www.speedrun.com/sm64?h=120_Star-emu&rules=category&x=wkpoo02r-e8m7em86.5lmoxk01)
* Players must be available to play at least once a week starting August 1st, 2026. In the Losers Bracket, players are expected to play up to two matches a week.
* Players must be able to have their gameplay, bingo board, and the board's timer on their layout.

## Tournament Structure

* Entry will be capped at 32 participants. Still sign up in case of drop outs!
* Seeding will be based on 16/70/120 PBs. The PBs will be weighted by category length and distance to the current world records.
* Structure will be updated based on sign-ups
* Double elimination bracket
  * Single-game matches (Best of 1) until Top 8
  * Top 8 (Winners Semifinals + Losers Round 5 and onwards) matches will be Best of 3 (First to 2).

## Timeline

* Announcement - July 31st: Registration and Seeding
* August 1st: Bracket released, Scheduling begins
* August 3rd - Aug 14th: Round 1
* Aug 14th - Aug 22nd: Round 2 + Losers Round 1
* Aug 22nd - Aug 26th: Losers Round 2
* Aug 26th - Sep 2nd: Round 3 + Losers Round 3
* Sep 2nd - Sep 6th: Losers Round 4
* Sep 5th - Sep 10th: Winners Semifinals + Losers Round 5 (Top 8)
* Sep 8th - Sep 13th: Losers Round 6
* Sep 12th - Sep 17th: Winners Finals + Losers Semifinals (Top 4)
* Sep 17th - Sep 20th: Losers Finals + Grand Finals

This timeline provides a tentative estimate of the tournament progression. It will be updated as the total number of players becomes more clear. Players should expect to be available to play a match in all of these intervals (especially if they expect to make it further in the tournament). Any significant delays from scheduling will result in a forfeit.

## Match Rules

* Players are expected to arrive 15 minutes before the scheduled match.
* Each player's POV must be streamed to Twitch.
* Players must have their gameplay, bingo board, and the board timer on their layout at all times.
* The board is revealed when timing starts.
* Players are not allowed to watch the main stream, their opponent's gameplay, or have any stream chat open during their races. Violating this may result in immediate disqualification.
* All matches before the Top 8 (Winners Semifinals + Losers Round 5 for a full bracket) will be a single game (Best of 1). Once we reach Top 8, all matches will be Best of 3 (First to 2).

### Variant selection
For each match, variants will be selected through a pick/ban system. 

#### Game 1
We will use a coinflip to establish who decides whether they ban first or second. The first variant is then decided by the following process:
1. First player bans one variant.
2. Second player bans two variants.
3. First player chooses among the remaining two variants.

#### Games 2 and 3

In Best of 3 matches, for games after the first, variants already played in the match cannot be repeated. The winner of the previous game bans one variant from the remaining pool, and the loser picks from the variants that are left.

#### Bracket Reset

In Grand Finals, in the case of a Bracket Reset, the loser of the first set decides whether they ban first or second.

## Bingo Variants

Here are the detailed descriptions for each variant to be used in the tournament. For all variants except Double Anti, players reset when time starts. For Double Anti, players reset exactly one minute after time starts.

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

## Goalset

We are using a custom goalset that will be available on [Lockout.Live](https://lockout.live/)! This is also the website we will be using for matches. You can find the `.json` for the goalset [here](Super%20Mario%2064-Tournament%20Standard%20Set.json). A list of all of the goals and explanations for them can be found [here](Bingo%20Goals%20Specifications.md).