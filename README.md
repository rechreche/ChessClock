# ChessClock
This Project provides you a chess clock that works in the following way:

Two Timers: A chess clock consists of two separate timers, one for each player. These timers run independently of each other.

Initial Setup: At the beginning of the game, both timers are set to the same initial time allotment for each player. The total time available for a game can vary, but it is often set at 60 minutes for each player (known as "G/60" in chess notation), with the option to add increments (additional time) after each move.

Timing Mechanism: When it's a player's turn to move, they press a button on their side of the clock to stop their timer and start the opponent's timer simultaneously. This action signals the end of their move.

Opponent's Turn: The opponent then has their own timer running while they consider their move. Once they make their move, they press their button to stop their timer and start the original player's timer again.

Running Out of Time: If a player's timer reaches zero before they make a move (they "flag" or "time out"), they lose the game, even if they have a winning position on the board. In some cases, a player may lose the game even if they have insufficient material to checkmate their opponent within the remaining time.

