# Tic-Tac-Toe-Reinforcement-Learning-with-Q-Learning-Algorithm

This project explores the application of evolutionary algorithms in machine learning through a practical implementation of the Q-Learning algorithm in the game of Tic-Tac-Toe. This project aims to demonstrate how a simple AI can evolve and improve its game strategy over time using model-free reinforcement learning techniques.
Evolutionary algorithms mimic the process of natural selection to solve optimization problems iteratively. Among these, the Q-Learning algorithm stands out for its ability to learn the value of actions in specific states without a model of the environment. This project applies Q-Learning to enable a self-learning AI agent to play Tic-Tac-Toe, adjusting its strategy based on the outcomes of thousands of games.

**Project Structure**

- `main.py`: The main script that initializes the game and starts the AI learning process.
- `q.py`: Contains the Q-Learning algorithm implementation, including the learning and decision-making logic.
- `tictactoe.py`: The Tic-Tac-Toe game logic and environment.
- `agent.py`: Defines the AI agent that learns and plays Tic-Tac-Toe using the Q-Learning algorithm.

**Methodology**

The Q-Learning algorithm's core is to update the Q-values based on the reward received for actions taken in specific states, using the Bellman equation. This process iterates over thousands of games, allowing the AI to refine its strategy incrementally.

**Results**

Our AI agent demonstrates significant improvement in gameplay, reaching a point where it becomes a formidable opponent that can at most tie or win against human players, showcasing the effectiveness of the Q-Learning algorithm in teaching AI to adapt and evolve strategies in a controlled environment.

## How to Run
- 1. Ensure you have Python installed on your machine.
- 2. Clone this repository to your local machine.
- 3. Run `python main.py` in your terminal to start the game.

## References
Several key resources were instrumental in the development of this project. These include academic articles on evolutionary algorithms, reinforcement learning, and practical guides on implementing Q-Learning in Python.
