# Twitter: 

Project 2: Implementing loops and screen transitions

The idea of this project was to continue consolidating the use of components and scrolling, however challenge myself to use loops instead of duplicating lots of components!


## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

To make the Twitter homepage built using loops. Adding a screen transition that will select a loop to display the corresponding tweet on the screen.

### Origami File 

[https://github.com/becmorrell/Origami/blob/main/Twitter/Twitter%20screen%20transition%20and%20loops.origami

## Demo 


https://user-images.githubusercontent.com/77584099/121022539-5337f800-c79a-11eb-9b84-1e6925347cf1.mov


## My process

- I started with designing the layout on paper to understand the containers, bounds and buttons that I would need to add

- I have used this design to practice adding the following:
    - Created profile components for 'stories' and 'tweets'
    - Built the 'stories' using `loop builder` for profile image and name    
    - Nested horizontal scrolling for stories 
    - Created a 'tweet container' component 
    - Built the homepage feed using multiple `loop builders` (for each layer in the tweet, including whether the tweet displays an image, or text only
    - Published port outside the component to be able to display or hide the 'blue tick' on the profile of the tweet
    - Used `loop option switch` and `loop selector` for the tap interation display the layers of the tweet tapped on
    - Animated the 'social media' icons with scale and used a mask for color on the icon
    - Used `option picker` to animate the tap interaction to display the total number of likes, comments or retweets once tapped
    - Implemented `and` and `not` patches for the screen transition, so that when you tap anywhere other than the social icons on the container it transitions to screen 2.



### What I learned

Firstly, loops are incredible! Very easy to build with saving alot of time inputting data. However, you then end up with a lot of `loop builders` and the great task of linking them up to `loop selectors` for each piece of information/text/image. I guess this leads me onto a next project on how to handle data!

- I learnt how to use `option picker` and add `sum` to this to animate the tap on the social icons

If I had more time: 

- I would have liked to link the number of retweets from the feed to screen 2, however thats learning for a future project 
-  I realise that after completing the project - things were starting to look messy - so fo future practice, labelling loops, pacthes and ordering things as much as possible to stay organised

