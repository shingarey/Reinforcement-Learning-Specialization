# Reinforcement-Learning-Specialization
Master the Concepts of Reinforcement Learning. Implement a complete RL solution and understand how to apply AI tools to solve real-world problems.

The Reinforcement Learning Specialization consists of 4 courses exploring the power of adaptive learning systems and artificial intelligence (AI).

**[Course 1. Fundamentals of Reinforcement Learning](course1/README.md)**

- Formalize problems as Markov Decision Processes 
- Understand basic exploration methods and the exploration / exploitation tradeoff
- Understand value functions, as a general-purpose tool for optimal decision-making
- Know how to implement dynamic programming as an efficient solution approach to an industrial control problem

**Course 2. Sample-based Learning Methods**
In this course, you will learn about several algorithms that can learn near optimal policies based on trial and error interaction with the environment - 
learning from the agent’s own experience. Learning from actual experience is striking because it requires no prior knowledge of the environment’s dynamics, yet can still attain optimal behavior. 
We will cover intuitively simple but powerful Monte Carlo methods, and temporal difference learning methods including Q-learning. 
We will wrap up this course investigating how we can get the best of both worlds: algorithms that can combine model-based planning (similar to dynamic programming) and temporal difference updates to radically accelerate learning.

By the end of this course you will be able to:
 
- Understand Temporal-Difference learning and Monte Carlo as two strategies for estimating value functions from sampled experience
- Understand the importance of exploration, when using sampled experience rather than dynamic programming sweeps within a model
- Understand the connections between Monte Carlo and Dynamic Programming and TD. 
- Implement and apply the TD algorithm, for estimating value functions
- Implement and apply Expected Sarsa and Q-learning (two TD methods for control) 
- Understand the difference between on-policy and off-policy control
- Understand planning with simulated experience (as opposed to classic planning strategies)
- Implement a model-based approach to RL, called Dyna, which uses simulated experience 
- Conduct an empirical study to see the improvements in sample efficiency when using Dyna

**Course 3. Prediction and Control with Function Approximation**

n this course, you will learn how to solve problems with large, high-dimensional, and potentially infinite state spaces. 
You will see that estimating value functions can be cast as a supervised learning problem - function approximation - allowing you to build agents that carefully balance generalization and discrimination in order to maximize reward. 
We will begin this journey by investigating how our policy evaluation or prediction methods like Monte Carlo and TD can be extended to the function approximation setting. 
You will learn about feature construction techniques for RL, and representation learning via neural networks and backprop. 
We conclude this course with a deep-dive into policy gradient methods; a way to learn policies directly without learning a value function. 
In this course you will solve two continuous-state control tasks and investigate the benefits of policy gradient methods in a continuous-action environment. 

Prerequisites: This course strongly builds on the fundamentals of Courses 1 and 2, and learners should have completed these before starting this course.  Learners should also be comfortable with probabilities & expectations, basic linear algebra, basic calculus, Python 3.0 (at least 1 year), and  implementing algorithms from pseudocode.

By the end of this course, you will be able to: 

-Understand how to use supervised learning approaches to approximate value functions
-Understand objectives for prediction (value estimation) under function approximation
-Implement TD with function approximation (state aggregation), on an environment with an infinite state space (continuous state space)
-Understand fixed basis and neural network approaches to feature construction 
-Implement TD with neural network function approximation in a continuous state environment
-Understand new difficulties in exploration when moving to function approximation
-Contrast discounted problem formulations for control versus an average reward problem formulation
-Implement expected Sarsa and Q-learning with function approximation on a continuous state control task
-Understand objectives for directly estimating policies (policy gradient objectives)
-Implement a policy gradient method (called Actor-Critic) on a discrete state environment

**Course 4. A Complete Reinforcement Learning System (Capstone)**

In this final course, you will put together your knowledge from Courses 1, 2 and 3 to implement a complete RL solution to a problem. 
This capstone will let you see how each component---problem formulation, algorithm selection, parameter selection and representation design - fits together into a complete solution, and how to make appropriate choices when deploying RL in the real world. 
This project will require you to implement both the environment to stimulate your problem, and a control agent with Neural Network function approximation. 
In addition, you will conduct a scientific study of your learning system to develop your ability to assess the robustness of RL agents. 
To use RL in the real world, it is critical to (a) appropriately formalize the problem as an MDP, (b) select appropriate algorithms, (c ) identify what choices in your implementation will have large impacts on performance and (d) validate the expected behaviour of your algorithms. 
This capstone is valuable for anyone who is planning on using RL to solve real problems.

To be successful in this course, you will need to have completed Courses 1, 2, and 3 of this Specialization or the equivalent.

By the end of this course, you will be able to: 

Complete an RL solution to a problem, starting from problem formulation, appropriate algorithm selection and implementation and empirical study into the effectiveness of the solution.
