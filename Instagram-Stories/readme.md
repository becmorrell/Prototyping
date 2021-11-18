# Instagram Stories

I've had great fun learning to use the camera patch in Origami to build something I use regularly! I got abit carried away and used the text field to make the prototype more interactive!

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

https://user-images.githubusercontent.com/77584099/142415889-f3d352af-47ff-460c-a994-87d1de981885.mp4


## My process

I started out with drawing the screens I wanted to display (camera, photo edit and video edit), then building the layers for each screen directly in Origami.

I have added the following:

✅ `Camera patch`<br>
✅ `Long press` interaction to record a video <br>
✅ `Tap` interaction to capture a photo  <br>
✅  Link these into image and video layers to display <br>

<img src="https://user-images.githubusercontent.com/77584099/142419574-4e42b9d0-b965-4ab5-b9f4-ab9a6e24dbdb.png" width="700px">


✅ `Loop Builder` used for creating a color picker by looping color components <br>
✅ `Loop select` to change the background and text colors on photo edit screen <br>

<img src="https://user-images.githubusercontent.com/77584099/142230579-7c325f9d-e27a-4141-b183-8ddb6697ebd3.png" width="700px">


✅ Added a `text field` and lots of logic to begin and end editing it! <br>

<img src="https://user-images.githubusercontent.com/77584099/142229637-e1a727d4-5ae4-4b15-bdb3-2bb7d7411242.png" width="700px">



## Challenges 🧠

This started out as a simple prototype to take a photo and video and display them on the screen. However, I got carried away with trying to replicate Instagram Stories! I've learnt alot during this process and loved playing around with the camera and video! 

‣ I started out creating two different editing screens, one for a photo and one for a video. Long pressing the capture button would present the video edit screen and a tap would present the photo edit screen. However, I was duplicating the logic for adding text, so I condensed them into one edit screen with both the video and photo layers. 

‣ Initially I used the capture button to both take a photo/video and present the edit screen, however the prototype was briefly displaying the old image/video prior to the new one, causing a flicker/jumping effect. I found `pulse on change` helpful in this situation. When the value in the camera patch changes (i.e a new photo or video is processed inside) a pulse is sent and then the screen can be displayed.

<img src="https://user-images.githubusercontent.com/77584099/142230885-3ff30c6d-0e3a-427e-bde4-1431d82e9ec2.png" width="700px">







