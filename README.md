# Chess-Game

In this project I design a Chess Game in Java using the principles of Object Oriented Programming
I have divided this project into 6 classes
1. Spot: A spot represents one block of the 8×8 grid and an optional piece.
2. Piece: The basic building block of the system, every piece will be placed on a spot. Piece class is an abstract class. The extended classes (Pawn, King, Queen, Rook, Knight, Bishop) implements the abstracted operations.
3. Board: Board is an 8×8 set of boxes containing all active chess pieces.
4. Player: Player class represents one of the participants playing the game.
5. Move: Represents a game move, containing the starting and ending spot. The Move class will also keep track of the player who made the move.
6. Game: This class controls the flow of a game. It keeps track of all the game moves, which player has the current turn, and the final result of the game.
