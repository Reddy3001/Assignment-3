#  DQN Pong Agent (PyTorch)

This project trains a Deep Q-Network (DQN) to play **Pong** using a Convolutional Neural Network (CNN) and experience replay.  
The agent learns by watching the game frames, taking actions, collecting rewards, and improving step-by-step over many episodes.

---

##  Features

- Convolutional Neural Network (CNN) for processing game frames  
- Experience Replay Memory for stable learning  
- Target Network to reduce training instability  
- Epsilon-Greedy strategy for exploration vs. exploitation  
- Frame preprocessing (crop, grayscale, downsample)  
- Training script for **200 episodes**  
- Live score visualization after every 10 episodes  
- Automatic model checkpoints every 100 episodes  

---



