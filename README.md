# SuperMarioBot: Using Deep Q-Learning to Play Super Mario Bros.

Final project for Columbia MA Stats course GR5242 Advanced Machine Learning, in which we teach AI how to play Super Mario Bros (NES). 

+ Project members: 
  + **Sam Kolins**
  + **Atishay Sehgal**
  + **Arpita Shah**
  
# Introduction

In 2013, researchers at Google DeepMind published the paper Playing Atari with Deep Reinforcement Learning, in which for the first time, a neural network algorithm learned how to play a video game in a fairly organic sort of way by playing against itself and training on the images produced from those play sessions. Since then, in just five short years, a whole host of enthusiastic data scientists have trained neural networks on a wide variety of different games. Most of these games have been Atari games, but for our project we wanted to be a bit more ambitious and try ***Super Mario Bros.*** for the Nintendo Entertainment System (NES), using Deep Q-Learning. In particular, this means we want to get Mario to the end of the level before time runs out and without dying.

# Objective and Level Design

The goal of the game, as mentioned previously, is to get to the end of the ***first level*** represented by a flag that Mario needs to touch to beat the level. This is tricky because Mario faces obstacles (pipes, floating walls), enemies and bottomless pits along the way. Mario also only starts with three lives. Contact with enemies and pits result in a loss of a life. The loss of all three lives results in a **Game Over**. Mario also runs agains the clock and can time-out if he doesn't move.

In particular, Super Mario Bros. is a side-scrolling platformer, meaning Mario will need to continue moving right in order to access the end of the level. 
