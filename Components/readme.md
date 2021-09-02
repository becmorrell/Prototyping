# Decimal Place Patch 

Whilst building the temperature conversion example in Origami, I wanted the output of my conversion to round to one decimal place, however I found no way of doing this using exisiting patches. 
After searching the support group, a member had suggested using `multiplication`, `round` and `division` to return the decimal place required. 
I played around with this on the canvas and was amazed at how simple this was, so I wanted to create this into a patch to reuse and share. 

## Process

- I used the suggestion of multiplying the input number by either 10 for one decimal place, 100 for 2 decimal places and so on. Then using the `round` patch, followed by the divide by 10, 100 etc for the number of decimal places required.
- However, when the number was rounded to a whole number eg 25.9 rounded to 26, you would lose the one decimal place (26.0) and would appear as 26 instead.
- Therefore, I used `mod` to work out the remainder, if this was equal to 0 (i.e rounded to a whole number) then using an `option picker` to add the .0 as a text to ensure its not lost. 

<img src="https://user-images.githubusercontent.com/77584099/131850435-3ffc33b2-50db-4d5f-b790-40116f505a2c.png" width="600px">

### Origami File 

https://github.com/becmorrell/Origami/blob/main/






