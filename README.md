# Go AI Agent – Foundations of AI Final Project (CSCI 1411, Brown University)

This project was completed as the final assignment for Brown University’s *Foundations of AI* (CSCI 1411) course. The objective was to build an autonomous agent to play 5x5 Go against a variety of opponents, including TA-designed bots and agents submitted by peers, in a class-wide tournament.

I implemented my agent in Python, using PyTorch to develop a deep value network using the statistics from hundreds of games and integrate it with search-based strategies. My goal was to build a hybrid agent that could adaptively choose moves using a learned evaluation function and dynamic time management strategies.

---

## Project Highlights

- **Tech Stack**: Python, PyTorch
- **AI Techniques**:
  - Deep learning value network
  - Minimax-based search with a learned evaluation function
  - Monte Carlo Tree Search 
  - Flexible time allocation per move based on game phase
  - State caching for move-to-move continuity

---

## Challenges & Insights

- Balancing exploration depth with time limits proved difficult; aggressive lookahead often ran over time.
- Reinforcement learning was considered, but time constraints and training complexity led to a supervised learning focus.
- Debugging state transitions in Go (due to transpositions and board symmetry) required custom visualizations and manual testing.

---

To maintain academic integrity, the code for this project is private. I'm happy to share implementation details or provide access to the source code upon request by recruiters or hiring managers.

