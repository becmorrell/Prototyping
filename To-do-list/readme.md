# Todo List: 

Project 6: 

Building quick prototypes directly into Origami from Frontend Mentor javascript challenge page.
 

## Table of contents

- [Overview](#overview)
  - [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
  - [Summary](#summary)


## Overview

### The challenge

- To recreate the interactve Todo list 
- Use text input to allow the user to create their own items to add to the todo list
- Be able to select an item to mark as complete


### Origami File 

https://github.com/becmorrell/Origami/blob/main/

## Demo 


https://user-images.githubusercontent.com/77584099/127471337-295d4e17-923f-4fc8-b4b0-37fb6011c0fb.mp4




## My process

- Created a component for the 'Todo' list cell
- Linked the component to a `loop builder` of texts to create a 'demo list'
- Added a text field for the user to add new items to the list. This feeds into `loop insert at end` patch to update the list.
- Whilst editing the list, the content shifts up the screen to account for the keyboard displaying on top of the layers.

<img src="https://user-images.githubusercontent.com/77584099/135120464-723aaed3-4d84-4576-9214-383acb76a33e.png" width="600px"> 

- To create the completed list of items, I used the `loop filter` patch. This is the output of the the `loop insert at end` patch which filters the loop to those marked as compelte i.e a true boolean. 
- to hide the checkbox once it has been marked as completed, I used a port from `enable` inside the component. 

<img src="https://user-images.githubusercontent.com/77584099/135120447-f67c763c-6a7d-4310-af1f-e5878dfec83b.png" width="600px"> 


Finally I wanted to add some fun to the prototype! What better way than confetti once you have marked all items of the list as complete. 
- For this, I used the `particle system`, made a loop of colors, used a `counter` patch with a `repeating pulse` to move through the loop to dsiplay different colours as the confetti fires.
- once all the booleans are true in the option switch (i.e have been marked as completed) then the pulse will fire for confetti 

<img src="https://user-images.githubusercontent.com/77584099/135120420-ec954e82-f7f5-4f17-bfa4-457de459f06d.png" width="600px"> 


### Summary

- Great practice to use text field, components, loops and loop filter to be able to display and alter the list of created 'todo' items
- The UI design of this prototype isnt great, however this project was more about the quick building of the it rather than design.
- The most challenging part of this prototype was creating the confetti - creating the looping colors, using a repeating pulse for the counter and working out to display a burst of confetti rather than flowing particles. 



If I had more time: 

- I would try to add drag and drop to move the items in the list 


