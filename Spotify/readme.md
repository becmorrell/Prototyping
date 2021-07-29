# Spotify: 

Project 4: 

After spending some time working through the origami scrolling patterns, I wanted to recreate the Spotify playlist screen which has several animations linked to the scroll

## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [Summary](#summary)


## Overview

### The challenge

- To prototype a Spotify playlist screen
- Create a collapsible header and introduce navigation bar as you scroll 


### Origami File 

https://github.com/becmorrell/Origami/

## Demo 




## My process

- I built the UI directly in Origami
- Firstly, I created a component for the 'song' cells. Then, I linked the component to a `loop builder` of images and text input to create a list of songs.

- As you scroll a Spotify playlist, the album artwork transitions from full size to just under half size, before it then fades as the playlist scrolls behind a navigation bar.
- I initially designed the playlist artwork container outside of the 'scroll bounds and contents', however this meant as you start to scroll, the songs were disappearing behind the artwork before the artwork had transitioned and faded off the page.
- I was having difficulty replicating this without using the scroll interaction patch, however I wanted to delay when the songs appeared to scroll until the header transition was complete.
- In order to start the scroll further up the screen, I had to cancel out the y scroll using a `min` patch to calculate the point of when the scroll would start.



- As you scroll the artwork off the page, the navigation bar transitions onto the screen from the top, displaying the playlist name. 
- The Navigation bar is there all the time to allow for the back button to be displayed, however the text and opacity of the bar changes as you scroll. 
- To position the navigation bar on top of the scroll bounds, I used a negative top margin on the scroll bounds. Following this, I added a `progress` patch to introduce the margin along with increasing opacity of the navigation bar.



- I also added `jump to y position` on tapping the status bar to replicate this iOS pattern.
- Created overscroll animation to enlarge album artwork as you drag down from the top of the screen. 


### Summary

This was a quicker project concentrating on just scroll patterns from the Origami tutorials. I enjoyed the challenge of working out how to delay the transition of the artwork and navigation bar as you scroll.



If I had more time: 

- Transition text to appear from the bottom of the navigation bar rather than the top (as iOS)


