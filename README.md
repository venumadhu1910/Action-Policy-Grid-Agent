In this project, I developed a grid-based environment to explore the application of reinforcement learning in pathfinding. The environment consists of a 100x100 grid filled with randomly placed obstacles, where an agent must navigate from a designated starting point to a goal point while avoiding these obstacles.

Key Components:
Grid Generation: A grid was created with a specific ratio of obstacles to represent challenges the agent must navigate around.

Agent Implementation: I implemented a Q-learning agent that learns to make optimal decisions through trial and error. The agent updates its Q-values based on rewards received from moving toward the goal and penalties for hitting obstacles.

Benchmarking: To evaluate the agent's performance, I also applied a value iteration method, allowing for comparison between the two approaches.

Visualization: The results were visualized, showcasing the grid, obstacles, and the agent's learned Q-values, providing insight into the agent's decision-making process.

Conclusion:
The project demonstrates the effectiveness of reinforcement learning in dynamic environments. By training the agent to navigate a grid with obstacles, I gained a deeper understanding of both Q-learning and value iteration techniques, highlighting their potential applications in real-world navigation problems.
