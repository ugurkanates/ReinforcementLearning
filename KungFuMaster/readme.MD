This is Kung Fu master is a classic Atari 2600 game released in 1980's.
There are 5 levels in this game and goal is side scrolling enemies and beating each level boss level while getting good scores.


I created an agent to play Kung Fu Master using reinforcement learning.
I implemented DeepMind 2013 and 2015 algorithms regarding to Atari enviroments and techniques regarding deep neural networks and RL.


My implementation done with Python 3.7  using numpy,PyTorch and OpenAI GYM Atari environment.

So far it can take clear enemies until all bosses.
Bosses are very challenging for RL agent in this game because they dont get immediate reward like most of actual real life applications
or current video games and boss health gets back incredibly fast so even for actual player its pretty tough game.
So it stucks with local optima for most bosses in the game.
I am currently exploring (Proximal Policy Optimization (PPO) ,APE-X  and some different exploration algorihms deep exploration, go explore), reward shaping)

Training of actual level takes 650'ish episode to beat level . 
I train my models either with Google Collab or renting a great GPU system from Vast.ai

This is an ongoing project .

Currently implemented algorithms are

# DQN- Deep Neural Network using Q learning with error clip
# DDQN - Deep Neural Network using Double Q learning  with error clip/on off toggle.

Here's some pics from rewards and game.

Reward
![Image](https://pasteboard.co/IuMgtY7.png)

Beating the level
![Image](https://pasteboard.co/IuMhmil.gif)


https://cdn-b-east.streamable.com/video/mp4 - Actual video of clearing boss level.

