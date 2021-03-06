# DreamWorks Animation Challenge - October 2016

## Problem Statement:

You will need to use your coding ability to create ‘sparks’. You are provided with some models/assets, a reference scene and a rough sketch for visual direction. You can start with the reference scene and its coding language or create your own from scratch in your language/platform of choice (You are free to make your own desktop program with OpenGL). You are not allowed to use any physics/collision engines such as Bullet, unity, unreal etc. You essentially have to write code for the mathematics (external vector/math library allowed) and physics (external library not allowed as mentioned above) of the motion of the sparks.


## Various Levels of Complexities:

L0: Basic natural motion of sparks (projectile motion, air and ground friction)  
L1: Collision with ground plane  
L2: Sparks should split randomly post collision to give variation  
L3: Collision with a minimum of one of the given primitive shapes  
L4: Collision with the ‘Stanford Bunny’  

You are free to use graphical enhancements (sprites/glow/complex-lighting etc.) on your output to make it visually appealing and look natural/realistic.

![alt tag](https://github.com/ganeshbelgur/dreamWorks_Oct2016/blob/master/persp.jpg)
![alt tag](https://github.com/ganeshbelgur/dreamWorks_Oct2016/blob/master/ortho.jpg)

# My Submission:

The objective of my hack was to simulate the motion of sparks from a saw blade. I managed to achieve the all important projectile motion of the particles, basic collision detection and the splintering effect of spark particles on collision. I wanted to implement a bounding volume hierarchy if time permitted me to do so. The collisions would have become more accurate and efficient to compute.

## Preview: YouTube

<a href="http://www.youtube.com/watch?feature=player_embedded&v=dLn6G82HxNI" target="_blank"><img src="https://github.com/ganeshbelgur/dreamWorks_Oct2016/blob/master/thumbnail.jpg" alt="DreamWorks Animation Challenge | Ganesh B R" width="900" height="500" border="10" /></a>

## Instructions to run the Code:

1: Start a simple HTTP server at the root directory

```shell
sudo python -m SimpleHTTPServer 4000
```

2: Go to any browser and type in the following URL

```shell
localhost:4000
```

## Test Environment:

Ubuntu 16.04 <br/>
Google Chrome Browser <br/>