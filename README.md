# Tree-of-thought

For complex tasks that require exploration or strategic lookahead, traditional or simple prompting techniques fall short. Yao et el. (2023) and Long (2023) recently proposed Tree of Thoughts (ToT), a framework that generalizes over chain-of-thought prompting and encourages exploration over thoughts that serve as intermediate steps for general problem solving with language models.

ToT maintains a tree of thoughts, where thoughts represent coherent language sequences that serve as intermediate steps toward solving a problem. This approach enables an LM to self-evaluate the progress through intermediate thoughts made towards solving a problem through a deliberate reasoning process. The LM's ability to generate and evaluate thoughts is then combined with search algorithms (e.g., breadth-first search and depth-first search) to enable systematic exploration of thoughts with lookahead and backtracking.

![image](https://github.com/Jeevan672/Tree-of-thought/assets/88030873/b594f275-aa36-4db2-a33e-732f1f7ea868)


When using ToT, different tasks requires defining the number of candidates and the number of thoughts/steps.




In Tree-of-Thought (ToT) prompting, we generate multiple problem-solving steps or approaches 
for a given prompt and then use the AI model to critique them. The critique will be based on the 
model’s judgment of the solution’s suitability to the problem.
