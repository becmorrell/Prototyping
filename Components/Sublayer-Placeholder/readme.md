# Sublayer Placeholder

I have been practicing working with the sublayer placeholder using some simple examples to really get to grips with it. 

See file below for scrollable component with option to flick between horizontal and vertical scroll. 

A quick summary: 
- Creating the component, adding the sublayer to it
- Creating a loop of shapes
- Absolutle positioning the sublayer to be able to manipulate the x / y position
- Using an enum input to choose horizontal / vertical scroll 

## Challenges: 
- If you horizontal scroll (altering the -X position on the scroll patch) then change to the Y scroll, occasionally the componenet would appear to be off the screen due to the final -X position. 
- To avoid this, I have had to use `pulse on change` and `delay` patch with `scroll settings` in order to reset X and Y position to 0 when changing the direction.  

<img src="https://user-images.githubusercontent.com/77584099/144883055-aec1e940-ef17-4abd-99f1-09534c0970d9.png" width="700px">


### Origami File 

https://github.com/becmorrell/Origami/blob/main/Components/Sublayer-Placeholder/sublayer-with-scroll-direction.origami
