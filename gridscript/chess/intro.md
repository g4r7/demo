# Chess

## Goal

The object of the game is to checkmate the opponent's king (see [`4k3/2R5/1R Rb8`](#/chess/scope?st=4k3/2R5/1R&xt=Rb8)), whereby the king is under immediate attack [`@b8`](#/chess/scope?st=4k3/2R5/1R&xt=Rb8,@b8)
 (in 'check') and there is no way to remove it [`@e8`](#/chess/scope?st=4k3/2R5/1R&xt=Rb8,@e8) from attack on the next move. There are also several ways a game can end in a draw.

## Rules

### Movement

Moving is compulsory; it is illegal to skip a turn, even when having to move is detrimental.
A player may not make any move that would put or leave the player's own king in check (see [`3r1k///3R///3K @Rd5`](#/chess/scope?st=3r1k///3R///3K&xt=@Rd5)).
If the player to move has no legal move, the game is over; the result is either checkmate (a loss for the player with no legal move) if the king is in check, or stalemate (a draw) if the king is not (see
[`K/2k/1q Ka8`](#/chess/scope?st=K/2k/1q&xt=@Ka8)).
