# Pintrest: 

Project 3: Practicing implementing loops and selecting one to present a screen

I've been doing alot of learning about loops - practicing with shapes, colors and screen transitions. I've now decided to put that into practice duplicating the Pintrest app using interactive loops.


## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [Summary](#summary)


## Overview

### The challenge

To make a duplicate of Pintrest using loops. Then challenging myself to be able to select one that will transition to a full size screen.

### Origami File 



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
    - Created a ghost 'full screen' layer and positioned loop of 'pin images' on this - this is the image that then converts to full screen size. Then added a `switch` and `animation` patch to turn the 'full screen' opacity to 1 when tapped. 
    - Used `loop select` for size and position to transition from its current size and position to the end state of full screen. 
    - Implemented `convert posiiton` patch to input the start posiiton to the loop select (due to the component position being relative to its parent, in this case the 'food pin' parent is Container, the convert patch makes it relative to the ghost 'full screen') 
    - Finally, utilised the 'pop switch' to drag the 'full screen' image down back to the starting position.



### Summary

I've really enjoyed this project, I feel my knowledge of loops has really developed after spending time on basic projects using shapes and colors it was nice to start to use images, text and positions with the loops. I found the most difficult part of this project was converting the position of the image from its start to end state. 


If I had more time: 

- Learning `text input` to add to the search bar 
- Adding drag down so that the image drags down to resize 

