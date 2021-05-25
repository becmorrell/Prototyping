
https://user-images.githubusercontent.com/77584099/119469922-b871ff00-bd3f-11eb-8af5-278dc63c4431.mov

# Learning Origami: 

This is the first project I set myself to duplicate the Airbnb app to learn how to layout the prototype, use animation and basic X and Y scrolling. 

## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

I set myself a challenge to duplicate the Airbnb app, making the landing page interactive with scroll and animated buttons.

### Origami File 

[https://github.com/becmorrell/Origami/blob/main/Airbnb/Airbnb.origami](https://github.com/becmorrell/Origami/blob/main/Airbnb/Airbnb.origami)

## Demo 



## My process

- I started with designing the layout on paper to understand the containers, bounds and buttons that I would need to add

- I have used this design to practice adding the following:
    - Layout on containers
    - Adding buttons, then animating them with scale when tapped
    - Created multiple horizontal scrolling containers within a vertical scroll 
    - Creating card components for the explore and live anywhere sections. 
    - Utilising the `layer info` and `size unpack` patches to create a grid layout in 'Explore Nearby' section. 
    - Placing the tab bar, inserting icons into this and then customised the tint color 
    - I learnt that you can add a tap interaction to the status bar, using the `scroll settings` patch `jump to y pulse` to animate the return to the top of the page. 
    - Finally I added paging scroll the 'live anywhere' cards using the `scroll settings` to set page width



### What I learned

This is the first project I have completed using origami, I'm happy with the outcome. I'd say it looks close to the design of their landing page. 
- I feel I have started to get my head around layout on the containers, thinking about it in the same way as flexbox helps. Ensuring the anchor points, layout direction and auto grow are all correct on the inspector panel. 
- This project helped to consolidate how to create a component and then reuse that within the design, allowing you to quickly change the text/image etc. 
- Finally it has helped to consolidate vertical and horizontal scrolling
