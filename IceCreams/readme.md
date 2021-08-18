# Tinder Ice Cream Selection 

Project 4: Use of swipe interaction, loops and tabs 

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

https://github.com/becmorrell/Origami/blob/main/Pinterest/Pinterest.origami

## Demo 

https://user-images.githubusercontent.com/77584099/125662618-bb0227f0-efab-4004-af19-abe59cda1a29.mp4



## My process

- I built the UI directly into Origami 
- Firstly, I started with a loop of Ice cream images to create the content cards 
- Added 'horizontal swipe' to these images using a `pop switch` and transtion patches
- Animated the card scale to grow as it becomes the active card displayed on the screen 





- When adding a tap interaction to the `like` or `dislike` buttons, initially one tap interaction would swipe all of the images. This is due to the tap interaction being a single tap, rather than a loop of taps. 
- I wanted to send a pulse for the image that is currently displayed on the screen to move it either right or left. 
- In order to do this, I used `loop sum` to get the total of both right and left swipes, then compare this against the index of images in the loop using `equals exactly`.  




- The second screen displays favourite images selected by the user. To create this, I used a `loop filter` to select the images that had been 'liked' or swiped to the right to display on this screen.
- 


<img src="https://user-images.githubusercontent.com/77584099/125690039-37baf8fc-4a65-483b-9318-601fdba8b65e.png" width="600px" >



<img src="https://user-images.githubusercontent.com/77584099/125690058-30e5ecef-3dfb-4b80-8e29-8b13430d9a74.png" width="600px" >



### Summary

This was a quick project to practice the use of swipe interaction from Origami patterns. I have enjoyed practicing the combination of loops and logic within this prototype. In particular, the challenge of creating a loop of taps using the `equals exactly` alongside the `and` patch to link the 'like' and 'dislike' buttons with the `pop switch`. 

