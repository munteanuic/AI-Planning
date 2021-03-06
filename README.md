# AI Planning

## Authors
Ioana Munteanu & Julie Malyshev

## Demo
[Click here!](https://www.youtube.com/watch?v=TT40YGtXIXI)

## Installation
1. Download [Processing](https://processing.org/download/).
2. Clone the repository.
3. Open it in Processing and press 'Run'.

## Description
 - A 3D simulation of two agents moving	through a static environment, created using Processing. 
 - The agents are represented by some spiders and their goal is to reach the flies (the red spider's target is the red fly and the yellow spider's goal is the yellow fly). They also need to avoid the raindrops in the grass, represented by blue spheres.
 -  We used the A Star technique for AI planning, which will find the ideal path between the spider and the fly. The nodes are not represented in the simulation for aesthetic reasons, but the edges between them are represented with white lines depicting the spider's web.
 
## User interaction
 - arrows: move the obstacle (dark blue raindrop)
 - space: pause/resume simulation
 - r: moves spiders to initial position
 - WASD: move the red spider
 - Scroll wheel: move in/out
 - Mouse drag: rotate/pan camera

## Programming language
- Processing 

## Difficulties
- I tried to use some existing PNG images for the fish but the number of FPS was extremely low.
- I could not create the obstacle avoidance  (I managed to make a flock avoid an object but not to come back as a flock right after).
- I had a hard time figuring out the right coefficients for separation, cohesion, and avoidance. 



