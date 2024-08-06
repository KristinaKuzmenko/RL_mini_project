## Policy Iteration for Frozen Lake Environment

# Overview:
In this project, I implemented the policy iteration approach to determine the optimal policy for managing an agent in the Frozen Lake environment. This method is distinct from value iteration, which iteratively updates the value function based on the maximum action value. The policy iteration method involves two main steps: policy evaluation and policy improvement.

# Details:

# Policy Evaluation:
- Start with a random policy.
- Evaluate the value function for the given policy.
# Policy Improvement:
- Improve the policy based on the updated value function.
- Iterate until the policy converges to the optimal policy.
# Results:

The optimal policy obtained using policy iteration matched the results from value iteration, confirming the validity of the implementation.
The agent's behavior under the optimal policy was visualized. Given the stochastic nature of the environment (is_slippery=True), the agent does not always reach the goal.
The success rate of the agent reaching the goal was calculated.
An animation was created to depict the agent's behavior. With each new run, the animation changes, illustrating the variability in the agent's attempts. The maximum number of steps for the agent was set to 100; if the goal is not reached within these steps, the attempt is considered unsuccessful.