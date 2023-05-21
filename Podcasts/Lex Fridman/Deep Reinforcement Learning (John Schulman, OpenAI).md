# Summary of Deep Reinforcement Learning (John Schulman, OpenAI)

This video discusses deep reinforcement learning, which is a technique that can be used to solve a variety of problems. John Schulman explains how reinforcement learning differs from supervised learning and how it can be used for certain problems. He discusses some recent successes with deep reinforcement learning, including policy gradient methods.
John Schulman from OpenAI discusses deep reinforcement learning algorithms and how they are used to approximate the desired Q function. He notes that while these algorithms are useful, they are still not perfect and further refinement is necessary.

Detail Summary: 
00:00:00
Deep reinforcement learning is a technique that can be used to solve a variety of problems, including robotics and decision making.

00:05:00
Reinforcement learning is a subset of machine learning that deals with problems where the environment provides feedback to the agent on how well it is performing. It is similar to supervised learning in that the environment provides a question and an answer, but there is a delay between the environment providing the question and the agent receiving feedback. Additionally, stateful environments make the problem harder to solve as the agent does not have access to the function that predicts the cost when taking an action.

00:10:00
John Schulman explains the different types of machine learning and how they work. He explains how reinforcement learning differs from supervised learning and how it can be used for certain problems. He discusses some recent successes with deep reinforcement learning.

00:15:00
Deep learning algorithms have been able to solve complex problems such as playing video games and manipulating objects, but previously they had not been successful using general methods to solve them. Recently, there have been some success using policy gradient methods in 3D games.

00:20:00
Policy gradient methods are a broad and general class of reinforcement learning methods that are quite effective. The basic idea is to try to make the good trajectories more probable, without trying to figure out which were the good actions in which were the bad actions. More elaborate methods try to figure out which actions were good.

00:25:00
The score function grading estimator is a fundamental concept in reinforcement learning, and underlies methods such as policy grading. It can be computed using a sampling estimator and is valid even if the function f of X is unknown or discontinuous.

00:30:00
Deep reinforcement learning techniques can be used to optimize a system with differentiable pieces, such as a function, probability density, and policy gradient.

00:35:00
Deep reinforcement learning algorithms can be improved by using a temporal structure of the problem, deriving an estimator for the grading policy gradient, and using a discount factor.

00:40:00
The author discusses the intuition behind deep reinforcement learning, which is that an action should not affect rewards far in the future. He then provides a gradient estimator and an algorithm to implement it, which is straightforward. However, there are several issues that can be improved. One is with step sizes, which can be fixed by an annealing process. Another is with the policy grading estimator, which can be improved by increasing the step size or by changing the policy itself.

00:45:00
Deep reinforcement learning methods help to improve an agent's performance by adjusting its behavior based on the feedback it receives. In this video, John Schulman from OpenAI discusses a project where he and his colleagues used policy gradient methods to learn locomotion controllers for a humanoid robot in a realistic physics simulator.

00:50:00
John Schulman demonstrates how deep reinforcement learning can be used to solve problems that are difficult for conventional algorithms, such as a robot standing up after being dropped. The policy gradient method is robust to noise, allowing for long-term planning.

00:55:00
In reinforcement learning, different algorithms try to optimize a policy function, which uses an agent's actions to produce a reward. One such algorithm is the policy gradient method, which is distinguished by the explicit representation of the policy, and the optimization of the policy with respect to the parameters of the policy. Another algorithm is the cue function learning algorithm, which measures how good a state action pair is and uses this information to update the policy. The preferred method for solving the discrete-time optimal control problem with a finite number of states and actions is the conjugate gradient method, but this method can also be applied with continuous States and actions using an expressive function approximator. Finally, I'll introduce a different type of reinforcement learning algorithm, the state value function learning algorithm, which stores and updates the Q function using bellman equations.

01:00:00
The Bellman equation states that the optimal policy should satisfy a Q function that takes the Arg max of the optimal q function. This equation can be rewritten using the concept of a backup operator, which takes the Bellman equation and applies an arbitrary Q function to the right-hand side. This operator, Q star, is a fixed point of the bellman operator and is the optimal policy under a given policy.

01:05:00
This video introduces the bellman equation and binocs fixed point theorem, which can be used to prove that an optimal Q function exists for a Markov decision process. Two classic algorithms for solving MDPs, value iteration and policy iteration, are explained. These algorithms can be implemented without knowledge of the probability distribution of the state and action. However, if the system is accessed through sampling, then approximate versions of the bellman backup and bellmen schedule can be used to converge to the optimal Q function.

01:10:00
In this video, John Schulman from OpenAI discusses deep reinforcement learning algorithms, including neural fitted Q iteration, Boltzmann exploration, and DQn. These algorithms are useful for learning policies that approximate the desired Q function, which can then be used to optimize an objective function. While there is still debate over the relative merits of these algorithms, they are worth considering when designing deep reinforcement learning algorithms.

01:15:00
The video discusses the various methods for reinforcement learning, with Q function methods being more sample efficient but less reliable than policy gradient methods. It concludes that there is still room for improvement in the field, with further refinements to the methods being necessary to produce more reliable and robust results.

01:20:00
John Schulman discusses the challenges of deep reinforcement learning, and how those challenges relate to the design of neural networks. He notes that, while the optimization problem in reinforcement learning is difficult, it is not related to the architecture of the neural network.

01:25:00
Deep reinforcement learning algorithms are harder to learn when rewards are farther away, and the time step used when discretizing time is important.

