# Chess-AI-companion
Chess AI
This Python code is this repository aims to develop a Chess Artificial Algorithm capable if defeating a human opposition. It utilizes the NegaMax Algorithm with Alpha-beta prunning.
## Negamax Algorithm
Negamax is a variation of the minimax algorithm  deployed in two-player turn based games like chess. The Negamax aims for simplicity as it does not take into account the distinguishing effect between the minimizing and the maximizing player.
## Minmax Algorithm
The minimax algorithm is a decision-making algorithm usually associated with a two player game where each player take turns, making it perfect for a game of chess. Minimax works from the perspective of a winning and a losing player, the former aims to minimize the outcome while the latter aims to maximize the outcome. Starting from its current position, the minimax utilizes a tree to represent all possible moves in the
current game state as well as possible future moves to a certain depth before deciding on its next best move based off its evaluation of the tree leaves.
## Alpha Beta Pruning
Alpha-beta pruning serves as a optimization technique for the minimax algorithm as it reduces the number of nodes the minimax algorithm has to evaluate, this was introduced by McCarthy in 1956 as a solution to this problem, hence making the process faster. The key factor in the Alpha-beta pruning is that it makes the minimax algorithm efficient in its approach by shuffling out already examined leaves and keeping the evaluation of a leaf the algorithm recognizes as a best move so the process does not have to be repeated for every game state.

The ”alpha” and ”beta” in alpha-beta pruning represent the best values that the maximizing and minimizing player, respectively, can guarantee at a given point in the game while the ”pruning” of the trees allows the minimax algorithm to evaluate more moves in the same amount of time for a fixed number of moves hence leading to a more efficient and powerful AI
