# Java Chess 

This project was made apllying my skills in Java and OOP. 

Based in this UML diagram:

![UML_jc](https://user-images.githubusercontent.com/77849954/120394166-6fa2e300-c309-11eb-9e2a-8e31c17ad069.jpeg)

## How to play

At first, the white player needs to choose the piece he wants to move, informing to the console the correspondend letter and number. 
So the terminal will show the possible moves for the chosen piece.
The player must inform the place (a valid place!) where he wants to move the chosen piece. 
After the white move, the turn will change for the black pieces.

![2](https://user-images.githubusercontent.com/77849954/120394733-3cad1f00-c30a-11eb-9e2f-e8b696fa9e0b.PNG)
![3](https://user-images.githubusercontent.com/77849954/120394729-3c148880-c30a-11eb-8a3b-be48ebfb125c.PNG)

### Pieces Capture and Invalid Positions

If the player chooses a position where he does not have a piece, or the position of an opponent's piece, the terminal will alert about it and ask for a new position: 

![4](https://user-images.githubusercontent.com/77849954/120394910-8269e780-c30a-11eb-8203-6b3484f12a40.PNG)

If there is a opponent piece in the chosen position, it will be captured.

![5](https://user-images.githubusercontent.com/77849954/120394912-83027e00-c30a-11eb-8226-f59b9facdbc3.PNG)

### Pawn promotion

The pawn piece that reaches the eighth row can be replaced by a bishop, knight, rook, or queen of the same color.
The console will ask the player which piece he wants to transform into:

![6](https://user-images.githubusercontent.com/77849954/120532527-1f358f00-c3b6-11eb-97df-6f0d69f959a7.PNG)
