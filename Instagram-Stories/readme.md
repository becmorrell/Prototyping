# Instagram Stories

I've had great fun learning the video and camera in Origami to build something I use regularly!

## Table of contents

- [The challenge](#The-challenge)
- [Origami File](#Origami-File)
- [Demo](#Demo)
- [My process](#my-process)
- [Challenges](#challenges)


### The challenge

- Learn to use camera patch 
- Display the photo or video taken 

## Origami File 

https://github.com/becmorrell/Origami/blob/main/Instagram-Stories/Instagram-story.origami

## Demo


## My process

I started out with drawing the screens I wanted to display (photo and video), then building the layers for each screen directly in Origami.

I have added the following:

✅ `Camera patch`<br>
✅ `Long press` interaction to record a video <br>
✅ `Tap` interaction to capture a photo  <br>
✅ Link these into image and photo layers to display <br>

<img src="https://user-images.githubusercontent.com/77584099/142230885-3ff30c6d-0e3a-427e-bde4-1431d82e9ec2.png" width="700px">


✅ `Loop Builder` used for creating loop of color components <br>
✅ `Loop select` to select different colors of background and text on photo screen <br>

<img src="https://user-images.githubusercontent.com/77584099/142230579-7c325f9d-e27a-4141-b183-8ddb6697ebd3.png" width="700px">


✅ Added `text field` and logic to allow user to tap screen, enter text and end editing by tapping on screen or exiting the photo screen <br>

<img src="https://user-images.githubusercontent.com/77584099/142229637-e1a727d4-5ae4-4b15-bdb3-2bb7d7411242.png" width="700px">



## Challenges 🧠

This started out as a simple prototype to take a photo and video and display them on the screen. However, I got carried away with trying to replicate Instagram Stories! I've learnt alot during this process and loved playing around with the video and camera! 

‣ I started out creating to different screens, one for the photo and one for the video layer. When the long press was held for the record it would display the video screen and a tap interaction would display the photo scren. However, the logic for adding text on the screen was becoming messy and complex, so eventually I narrowed it down to one screen with both layers in to make this much cleaner. 

‣ Initially I used the capture button to both take a photo and present the screen, however the prototype was briefly displaying the old image prior to the new one. This created a flicker/jumping effect as the screen was displayed. I found `pulse on change` helpful in this situation. When the value in the camera patch changes (i.e a new photo or video is processed inside) a pulse is sent and then the screen can be displayed.







