# Deep Deterministic Policy Gradients (DDPG) resource

Deep Deterministic Policy Gradients (DDPG) is a reinforcement learning algorithm that combines two techniques: Deep Q-Networks (DQN) and Deterministic Policy Gradient (DPG). It was introduced in 2015 by Timothy P. Lillicrap et al.

DDPG is designed to work well on continuous control problems where the action space is continuous, such as robotic control or game control, where the output of the agent is not just a single action, but a continuous set of actions.

The algorithm is based on actor-critic architecture, where the actor learns to select actions based on the current state, and the critic learns to evaluate the actions selected by the actor. The actor and critic are both implemented as neural networks, which are trained using gradient descent techniques.

# useful links
- [Deep Deterministic Policy Gradient | DDPG Actor-Critic in Python](https://www.youtube.com/watch?v=jr213tdSMqw)
- [Everything You Need to Know About Deep Deterministic Policy Gradients (DDPG) | Tensorflow 2 Tutorial
](https://www.youtube.com/watch?v=4jh32CvwKYw)
- [Deep Deterministic Policy Gradients github](https://github.com/cookbenjamin/DDPG)
- [Deep Deterministic Policy Gradients blog](https://towardsdatascience.com/deep-deterministic-policy-gradients-explained-2d94655a9b7b)
- [Deep Deterministic Policy Gradients PDF](https://www.researchgate.net/publication/351029346_Deep_Deterministic_Policy_Gradient_Based_on_Double_Network_Prioritized_Experience_Replay)
