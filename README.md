# Super-Pineapple
Project for Madhacks Fall 2017

Super Pineapple Thing is a HTML5 game written in Javascript for Phaser.io.  
All graphics (with the exception of the background tiles) are custom pixel art by Connor Stamper.

The enemies are first instantiated with random policies implemented in 3-layer neural networks 
(implemented as matrix operations in NumJS).  When an enemy is destroyed (either by another enemy or the player) 
the most successful enemy's policy is copied and slightly mutated to "give birth" to a new enemy.  
This method was inspired by "Evolution Strategies as a Scalable Alternative to Reinforcement Learning" (Salimans et al 2017), 
found here (https://arxiv.org/pdf/1703.03864.pdf).  

More information on this technique can be found here (http://superpineapples.azurewebsites.net/Moss699FinalReport.pdf).

The rest was us having a great time playing with Phaser!
