# Spotify Year in Review: 

This is a project to have fun with loads of animations!

## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

- Recreate Spotify Wrapped 2021
- Create a Progress bar 
- Animate text and images to make it look fun! 

### Origami File 

[https://github.com/becmorrell/Origami/blob/main/Airbnb/Airbnb.origami](https://github.com/becmorrell/Origami/blob/main/Airbnb/Airbnb.origami)

## Demo 

https://user-images.githubusercontent.com/77584099/119469922-b871ff00-bd3f-11eb-8af5-278dc63c4431.mov

## My process

- I have used this design to practice adding the following:

    - Creating a reusable 'progress bar' component 
    - Looping the 'progress bar' based on number of groups to display
    - Used the `stopwatch` patch and logic to determine the progress of the active group

<img src="https://user-images.githubusercontent.com/77584099/146184116-af281b80-2103-4e1b-90a1-54cf7571d201.png" width="700px">

 
    - Used a counter to monitor how many items out of the loop have been completed 
    - Used an `option picker` to alternate between 0%, 100% and the live % progress
    
<img src="https://user-images.githubusercontent.com/77584099/146184285-24d509df-664e-46aa-8a0e-b097d7325955.png" width="700px">


    - Used groups instead of screens to display each flow 
    - Used one option picker to present each group and one to start the animations on that particular group 
    - Added alot of `delay` and `transition` patches to start animating! 

<img src="https://user-images.githubusercontent.com/77584099/146184384-9ae5ae75-68eb-47d6-a885-90737a4c2a0e.png" width="800px">


### What I learned 🧠

- Using a `progress` patch after a `progress` patch to speed up animations at a specific time point
- Using stroke to animate a mask of an image (giving the effect its being filled in - see group 6)
- Using the `option picker` to alternate between 0% progress (i.e the progress hasnt started yet), 100% (i.e that progress baris completed) and the live progress

This has been such a fun project to replicate! I couldnt find a simpler way to complete this with loops due to the groups being so different, therefore there is quite alot of repitition withn the prototype
