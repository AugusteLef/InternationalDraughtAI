# InternationalDraughtAI

In this assignment we were asked to build a computer player for the game of International Draughts. In short, International Draughts is a two player strategy game played on a 10x10 board of which only the dark fields are used to initially position 20 white pieces and 20 black pieces. The players in turn move a piece of their own color diagonally over the board. The white player starts the game. Pieces of the opponent may be captured by jumping over them to an empty field. Finally, the player without any remaining moves looses the game.

## 3 steps 
1) implement and extend the basic Alpha-Beta Algorithm
2) implement an evaluation function able to evaluate the state of the draughts game
3) integrate these two functions in framework for playing a draughts tournament

## Ressources

To achieve these objectives we based our work on different resources. Our two main resources were of course the lecture notes and the book Introduction to Artificial Intelligence [1]. The presentation made by Wieger Wesselink on Computer Draught Evaluation [4] also give us some insights on how we can improve our program by implementing custom extensions based on pro-player tactical. For example we learned that material advantage was very important (way more than in chess), that formation is also an important factor or that tempi need to be taken into account. Finally we also used an very well written article on Draughts AI [3]. We will discuss these features and their implementation later. For the moment, we will talk about the main algorithm of our Draught player : the alpha-beta algorithm
