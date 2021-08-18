# Tinder Ice Cream Selection 

Project 5: Use of swipe interaction, loops and tabs 

## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [Summary](#summary)


## Overview

### The challenge

- To build Tinder for Ice Creams using loops, swipe and tap interactions 
- Present a screen with selected Ice creams using a tab bar


### Origami File 

https://github.com/becmorrell/Origami/blob/main/IceCreams/IceCream.origami


## Demo 

https://user-images.githubusercontent.com/77584099/129890974-62ce7fb9-899c-4b40-a1f5-e9ff12ae6b3e.mp4


## My process

- I built the UI directly into Origami 
- Firstly, I started with a loop of Ice cream images to create the content cards 
- Added 'horizontal swipe' to these images using a `pop switch` and transtion patches
- Animated the card scale to grow as it becomes the active card displayed on the screen 


<img src="https://user-images.githubusercontent.com/77584099/129891034-b8132136-c04f-4531-9a07-9cb28e6ba353.png" width="700px">


- When adding a tap interaction to the `like` or `dislike` buttons, initially one tap interaction would swipe all of the images. This is due to the tap interaction being a single tap, rather than a loop of taps. 
- I wanted to send a pulse for the image that is currently displayed on the screen to move it either right or left. 
- In order to do this, I used `loop sum` to get the total of both right and left swipes, then compare this against the index of images in the loop using `equals exactly`.  

<img src="https://user-images.githubusercontent.com/77584099/129891055-424016a2-eb8c-49fa-9553-b83853372189.png" width="700px">

- The second screen displays favourite images selected by the user. To create this, I used a `loop filter` to select the images that had been 'liked' or swiped to the right to display on this screen.

<img src="https://user-images.githubusercontent.com/77584099/129891049-4e6376c5-892a-4f81-9276-e44387e726fc.png" width="700px">


### Summary

This was a quick project to practice the use of swipe interaction from Origami patterns. I have enjoyed practicing the combination of loops and logic within this prototype. In particular, the challenge of creating a loop of taps using the `equals exactly` alongside the `and` patch to link the 'like' and 'dislike' buttons with the `pop switch`. 


