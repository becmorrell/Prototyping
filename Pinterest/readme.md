# Pinterest: 

Project 3: Practicing implementing loops and selecting one to present a screen

I've been doing alot of learning about loops - practicing with shapes, colors and screen transitions. I've now decided to put that into practice by replicating the Pinterest app using interactive loops.


## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [Summary](#summary)


## Overview

### The challenge

- To prototype the Pinterest feed using loops. 
- Transition a selected item to full screen 


### Origami File 

https://github.com/becmorrell/Origami/blob/main/Pinterest/Pinterest.origami

## Demo 

https://user-images.githubusercontent.com/77584099/125662618-bb0227f0-efab-4004-af19-abe59cda1a29.mp4



## My process

- I started with designing the layout on paper to understand the containers, bounds and buttons that I would need to add
- Then built the UI directly in Origami 

I have used this design to practice adding the following:

- Created components for 'suggested search' and 'pin image'
- Built the 'suggested search' bar using a `loop builder` of text inputs and colors
- Created a horizontal scroll for the 'suggested search' container
- Created a loop of 'pin images' using `loop builders` for images and text input
- Added `Tap interaction`, ` loop option switch` and `loop select` to display the last selected/tapped image in the loop
- Created a 'ghost' 'full screen' layer instead of resizing the selected image to prevent breaking the grid layout. The 'ghost' layer is second image layer that sits on top of the original grid of images and transitions from the selected image to full screen.
- Implemented `convert posiiton` patch to convert the position of the selected pin image from being relative to its parent, to the parent of the 'ghost' image. 

<img src="https://user-images.githubusercontent.com/77584099/125690039-37baf8fc-4a65-483b-9318-601fdba8b65e.png" width="600px" >


- Added a `switch` and `animation` patch to turn the 'full screen' opacity to 1 when an image is selected. 
- To return to the feed, I wanted to be able to pull the full screen image down to resize it back to the original feed. To do this, I used  a `scroll` patch along with `greater than` to detect when the image had been pulled down. I connected this to a pulse patch to turn off the switch. 

<img src="https://user-images.githubusercontent.com/77584099/125690058-30e5ecef-3dfb-4b80-8e29-8b13430d9a74.png" width="600px" >



### Summary

I've really enjoyed this project, I feel my knowledge of loops has really developed after spending time on basic projects using shapes and colors it was nice to start to use images, text and positions with the loops. I found the most difficult part of this project was calculating the start position of the full screen image transition.


If I had more time: 

- Learning how to drag the image down to dismiss it 

