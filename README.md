# All Chess Moves

## Contains
- A formatted list of all possible chess moves
- The Python script used to generate the list

## Format
All moves are represented as strings of characters. All alphabet characters are lower case.

### Regular Moves
Regular moves consist of 4 characters in this order:
- The file of the starting square
- The rank of the starting square
- The file of the ending square
- The rank of the ending square

Example: "f5e4" means that a piece moved from f5 to e4.

### Exceptions

#### Castling
- "O-O" represents king's side castling
- "O-O-O" represents queen's side castling

#### Promoting
All promotion moves are fomatted like regular moves, but with an additional character appended to represent the piece to promote to.
- 'q' = queen
- 'r' = rook
- 'b' = bishop
- 'n' = night

Example: "e7e8q" means that a white pawn moved from e7 to e8 and promoted to a queen.

## Notes
- The moves in this list do not represent which color is moving, which piece is moving, capturing a piece, giving check, giving checkmate, or en passant.
- Some moves listed will not be legal moves in some chess positions. This is simply a list of all possible moves that could potentially be played given the right position.
