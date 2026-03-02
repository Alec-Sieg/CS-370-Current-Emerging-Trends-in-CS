# CS-370-Current-Emerging-Trends-in-CS-

Pirate Intelligent Agent — Portfolio Reflection
About the Project

In this project, I developed a deep Q-learning algorithm to train a pirate NPC to navigate a maze and find treasure before a human player. I was provided with starter code including the TreasureMaze.py environment, the GameExperience.py experience replay class, and the overall notebook structure. What I created myself was the core qtrain function, which included the exploration and exploitation logic, the experience replay training loop, the target network update mechanism, and the win rate tracking that determined when the agent had successfully learned to solve the maze from any starting position.

Connecting to Computer Science
What do computer scientists do and why does it matter?
Computer scientists solve complex, real-world problems by designing systems that can process information, learn from data, and make decisions. This project is a direct example of that: rather than hardcoding a solution, I built an agent that learned through trial and error how to navigate an environment it had never seen before. This kind of work matters because it powers technologies that affect everyday life, from navigation systems and medical diagnostics to fraud detection and accessibility tools.

How do I approach a problem as a computer scientist?
This course taught me to break large problems into smaller, testable components. When my qtrain function threw errors, I did not try to fix everything at once. I isolated each issue, traced it back to its source, and tested incrementally. I also learned to read existing code carefully before writing my own, since understanding the GameExperience and TreasureMaze classes was essential to writing code that worked with them correctly. This methodical, curious approach is something I will carry into every future project.

What are my ethical responsibilities to the end user and the organization?
Building intelligent agents comes with real ethical responsibilities. An agent that behaves unpredictably or unfairly can cause harm, even in a game context. More broadly, the AI systems built by computer scientists are increasingly making decisions that affect people's lives, which means transparency, fairness, and privacy must be built in from the start rather than added as an afterthought. My responsibility is to test thoroughly, document clearly, and always consider how my work could affect the people who interact with it.
