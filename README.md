# SNHU-CS370-pirate-intelligent-agent
SNHU CS370 pirate intelligent agent

Project Reflection

In this project, I worked on developing a pirate intelligent agent using deep Q learning to solve a maze-based pathfinding problem. The starter code provided included the environment setup through the TreasureMaze class, which defined the maze layout and rules, as well as the GameExperience class, which handled experience replay. Additionally, the notebook included helper functions for building the neural network model, training steps, and running the simulation.

The main portion of the work that I completed was implementing the qtrain() function, which handled the deep Q-learning algorithm. This included setting up the training loop, managing exploration versus exploitation using the epsilon value, storing experiences, and training the neural network using batches of past experiences. I also ensured the model was able to successfully learn an optimal path to the treasure and verified its performance using the provided completion check and simulation functions.

Connection to Computer Science

Computer scientists design, develop, and improve systems that solve complex problems through computation. Their work matters because it drives innovation in areas such as artificial intelligence, cybersecurity, data analysis, and software development. In this project, the use of reinforcement learning demonstrates how computer science can be applied to create systems that learn from experience rather than relying on hardcoded solutions.

When approaching a problem as a computer scientist, I focus on breaking the problem down into smaller components, understanding the inputs and outputs, and identifying the most appropriate algorithm or method to apply. In this case, the problem was not just finding a path in a maze, but designing a system that could learn that path over time. This required understanding both the environment and the learning algorithm, then integrating them into a working solution.

Ethical Responsibilities

As a computer scientist, I have a responsibility to consider how the systems I build impact both users and organizations. This includes ensuring that systems are reliable, secure, and do not produce unintended harmful outcomes. In the context of artificial intelligence, there is also a responsibility to recognize that these systems are influenced by the data and design decisions behind them.

While this project is relatively simple, it still reflects a larger reality in AI development. Systems do not truly understand problems, but instead learn patterns based on input and feedback. This means developers must be cautious about how systems are trained and used, especially in real-world applications where decisions can affect people directly. Ethical responsibility includes transparency, accountability, and making sure that the system behaves in a way that aligns with its intended purpose.
