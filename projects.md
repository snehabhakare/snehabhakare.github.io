---
layout: default
title: Projects
---

### Coherent Rendering for Augmented Reality
Undergraduate Thesis, IIT Bombay

Coherent Rendering for Augmented Reality is concerned with seamlessly blending the virtual world and real world in real time. We are interested in applying real-world light to virtual objects. This implies the measurement of the real-world lighting, also known as photometric registration. In this project we implement a method to estimate high quality illumination using convolutional neural networks (CNNs). Our represention of light model of real world is based on spherical harmonics representation. The aim of this project is to make augmentations photorealistic while removing any constraints in the environment.

### Graphics - Modelling, Rendering and Animation
Course Project for CS475: Computer Graphics

[Code](https://github.com/Computer-Graphics-IITB/a3-animate-174050012_150050040)

<iframe width="560" height="315" src="https://www.youtube.com/embed/p9IwyA2sZ44" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In this project, a short film with the music box lying closed in a room is created. The animation shows the music box to open, and two figures that dance to a tune pop out and move to the music. Finally, the box closes again. The modelling involves creating all the models, creating the scene with other elements.Also, lighting and texture is added. Then, we script the animation, add music and then generate the movie. Finally we add camera animation and character animation. 

### Progressive Nets for Multitask Learning
Course Project for CS747: Foundations of Intelligent & Learning Agents

[Report](/docs/fila.pdf) / [Code](https://github.com/sumanvid97/FILA_Project)

![](/docs/prog_nets.png)

Deep neural networks provide rich representations that can enable reinforcement learning algorithms to perform effectively. Learning to solve complex sequences of tasks−while both leveraging transfer and avoiding catastrophic forgetting−remains a key obstacle to achieving human-level intelligence. Through this project, we have explored the area of multitask learning using the novel approach of progressive neural networks. This form of network architecture represents a step forward in the above stated direction: they are immune to forgetting and can leverage prior knowledge via lateral connections to previously learned features. We have evaluated this architecture on the baselines of the asynchronous advantage actor critic algorithm for two Atari games, Pong and Breakout.

### Content Based Image Retrieval Using Salient Orientation Histograms
Course Project for CS663 - Fundamentals of Image Processing

[Report](/docs/DIP.pdf) / [Code](https://github.com/Krunal2017/CS663-Project)

Content-aware image retrieval is a very important topic nowadays, when the amount of digital image data is highly increasing. Existing sketch based image retrieval (SBIR) systems perform at a reduced level on real life images, where background data may distort image descriptors and retrieval results. To avoid this, a preprocessing step is introduced in this [paper] to distinguish between foreground and background, using integrated saliency detection. To build the descriptor only on the most relevant pixels, orientation feature is extracted at salient Modified Harris for Edges and Corners (MHEC) keypoints using an improved edge map, resulting in a Salient Orientation Histogram (SOH). The proposed SBIR system is also augmented with a segmentation step for object detection. The method is tested on the THUR15000 and COREL10000 database, containing random internet images.

### Flappy Bird AI
Course Project for EE769: Introduction to Machine Learning

[Blog](https://medium.com/@videshsuman/using-reinforcement-learning-techniques-to-build-an-ai-bot-for-the-game-flappy-bird-30e0fd22f990) / [Code](https://github.com/sumanvid97/FlappyBird-AI)

![](/docs/flappy.gif)

The goal for this project was to explore the simple Q-learning technique and [Deep Q-Network] (DQN) to train an environment agnostic agent for the game, that can play on it’s own, achieving super-human scores. Also, faster convergence was ensured by implementing 𝜀-greedy & experience replay strategies.

[Deep Q-Network]: https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf

