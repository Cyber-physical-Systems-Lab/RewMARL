# RewMARL
This repo implements mutualistic reward shaping in multi-agent reinforcement learning (MARL) to enhance robot cooperation. Tested on CartPendulum, ShadowHand, and Mobile Manipulation, it improves stability, convergence, and coordination. Includes code, results, and documentation. Contributions welcome! 🚀

This repository contains code for Investigating Symbiosis in Robotic Ecosystems: A Case Study for Multi-Robot Reinforcement Learning Reward Shaping.

Code is being prepared and will be available soon...


## Example Environments

| CartPendulum | ShadowHand | MobileFranka |
|:---:|:---:|:---:|
| ![CartPendulum](docs/CartPendulum.gif) | ![ShadowHand](docs/ShadowHand.gif) | ![MobileFranka](docs/MobileFranka.gif) |
| **Cooperative Balancing:** Multiple agents control different aspects of the double cart-pendulum system, requiring coordinated actions to maintain balance. | **Shadow Hand Object Passing:** Multiple agents controlling different finger groups of the dexterous hand, collaborating through shared rewards to manipulate and pass objects with precision. | **Mobile Manipulation:** Combining base movement and arm control agents that benefit from shared reward signals to perform coordinated navigation and manipulation tasks. |

## Key Features
- **Bio-Inspired Reward Shaping**: Implements a formal symbiosis model to enhance cooperation in MARL.
- **Symbiotic Interaction Taxonomy**: Categorizes agent interactions as mutualism, commensalism, and parasitism.
- **Improved Learning in Complex Tasks**: Enhances stability, convergence, and variance reduction in high-dimensional environments.

![HelloCat](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)