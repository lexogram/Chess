# Chess Trainer

*NOTE: This project is currently at the planning stage. None of the features described below has been implemented yet.*

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
* Playing Blind

## Heat Map
An overlay that shows the "heat map" of a chess game. In other words, a display where the squares that are safe to move to are shown in a "safe" colour (green ), and the squares that are controlled by the opponent are shown in an aggressive colour (red). Evenly disputed squares appear yellow. Neutral squares are shown in with no tint.

The size of each piece depends on the usefulness of that piece in its current position. For example, a knight in a corner appears smaller than a knight in the centre, to indicate that its range of action is reduced. A piece that is pinned will be smaller than if it were not pinned. A piece that can be used in the current move to mate the opponent could appear larger.

The total number of moves currently available to each player can be shown.

## Checklist of threats and opportunities
The player can select a piece to see a detailed report of the threats and opportunities associated with it. This feature can be associated with a checklist, so that the player thinks in a systematic way about how the position could develop.

## Custom Starting Position
You can start a game from a given position (using FEN notation). This could have been saved from a previous game, as the position before one of the players made a bad move. A Waypoint button allows you to save the current position of the game, so that you can come back to that position later, and explore alternative possibilities. You can save personal notes with any waypoint.

## Handicap
You can use the FEN notation of the starting position to remove certain pieces from the better player, or you can allow the weaker player a pre-determined number of moves at the start of the game before the opponent can begin.

## Take Back a Move
Each player can take back a pre-determined number of moves. This number may be different for each player. A player with the role of coach can allow the other to take back any move, at their own discretion.

## Visualize Opponent's Moves
Many game engines allow you to select a currently playable piece and see which squares it can move to. Sometimes it would be useful to see what the opponent's possible reposts could be. Selecting one of the other player's pieces:
* Desaturates all the opponent's pieces, to indicate that no move for that side is actually possible
* Indicates the squares to which that piece could move with a 🚫 or ✋ icon (to indicate that the move cannot yet be played)

## Touch Rule
In connection with the Take Back a Move feature, this can be limited to repositioning the piece that was actually moved (just as if the move had been illegal in tournament play).

## Evaluation
Players can see a computer evaluation of their position during play.

## Chat
Players can chat while playing.

## Move Opponent's Pieces
Both players can move their own and each other's pieces around, to illustrate a sequence of hypothetical moves. A Reset button returns all the pieces to the current playing position.

## Playing Blind
When you are imagining what the board will look like after a series of moves, looking at the board with the pieces in their current position can hinder your thoughts. This feature will encourage you to practise visualizing a position on the board, without looking at it.
* Set position, plus notation describing a series of moves. 
* Questions about the new position, such as "Is the King in check?"
* Exercises in restoring a game position from memory
* Visualization. When you make a move, the new position fades back to the initial position. When you touch a square, the piece that is currently on the square (if there is one) will reappear.
* Names provide shortcuts to recognition (chunking). Tests in naming openings and typical arrangements of pieces, like castling, fianchetto and épaulette.
