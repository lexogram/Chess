# Chess Trainer

This web app allows you to play chess with an online opponent, and provides you with feedback as to the strengths and weaknesses of the current position.

Features include:

* Heat Map
* Custom Starting Position
* Handicap
* Take Back a Move
* Touch Rule
* Evaluation
* Chat
* Move Opponent's Pieces

## Heat Map
An overlay that shows the "heat map" of a chess game. In other words, a display where the squares that are safe to move to are shown in a "safe" colour (green ), and the squares that are controlled by the opponent are shown in an aggressive colour (red). Neutral squares are shown in with no tint.

The size of each piece depends on the usefulness of that piece in its current position. For example, a knight in a corner appears smaller than a knight in the centre, to indicate that its range of action is reduced. A piece that is pinned will be smaller than if it were not pinned. A piece that can be used in the current move to mate the opponent could appear larger.

## Custom Starting Position
You can start a game from a given position (using FEN notation). This could have been saved from a previous game, as the position before one of the players made a bad move.

## Handicap
You can use the FEN notation of the starting position to remove certain pieces from the better player, or you can allow the weaker player a pre-determined number of moves at the start of the game before the opponent can begin.

## Take Back a Move
Each player can take back a pre-determined number of moves. This number may be different for each player. A player with the role of coach can allow the other to take back any move, at their own discretion.

## Touch Rule
In connection with the Take Back a Move feature, this can be limited to repositioning the piece that was actually moved (just as if the move had been illegal in tournament play).

## Evaluation
Players can see a computer evaluation of their position during play.

## Chat
Players can chat while playing.

## Move Opponent's Pieces
Both players can move their own and each other's pieces around, to illustrate a sequence of hypothetical moves. A Reset button returns all the pieces to the current playing position.