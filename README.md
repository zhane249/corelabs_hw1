# studio_hw1
Reflection:

For this project, I've found new ways to piece together collages, and utilize the design space to bring my vision to life. I first made the sketch, and the original plan was to have the third collage be different facial features of diffferent characters from various manhwas, but because I realized the size difference of the photos I opted for a more reliable route. I intended for my project to serve as a personal collection of readings / webtoons / manhuas that the user could revisit, or share with others as a link. Because it includes images, others would be able to omit the step of searching up the name to see the art style. It is organized into 3 categories for now, the first one has mouse hover to see the art, and unhover to see the name. Second one rearranges the order whenever the page refreshes. And the third one has a interesting combination for the collage. 

I've used the google font, utilized the w3schools massive collection of different css and html elements, and referenced youtube videos and forums to achieve the refreshing some slots while excluding others.


References and Links:

css hover transparency overlay: https://stackoverflow.com/questions/21423422/color-transparency-overlay-on-hover 
- used it for my action hover transparent overlay part, it explains the :after pseudo element and gives an example using div:hover:after.

references for website 2: https://stackoverflow.com/questions/29969239/how-to-make-a-picture-change-randomly-in-a-website

-showed me how to random select item from array with Math.floor(Math.random() * my 7 slots), reference explains math.random generates 0 to 1 and then gets a random number and rounds it to the nearest whole number with Math.floor. But this website only makes so user click and picture change to random.

https://www.youtube.com/watch?v=z3iKpCNlWU8&t=116s 
- This youtube video further dives more into function randomNumber() using return Math.floor() at minute 2:52 demonstrating an example, and instead of replacing the image it creates random image feeds through using const container = "document.querySelector(."content"), const baseURL and const rows. I didn't need the randomSize but the randomNumber () function. And every time the user reloads the page, new images appear in the same grid format css created.

https://www.w3schools.com/css/css3_fonts.asp
-needed a refresher on importing fonts, explains @font-face rule and the differences between the font-style, font-weight.

https://fonts.google.com/specimen/Asimovian?preview.text=True%20Education&specimen.preview.text=True+Education&categoryFilters=Feeling:%2FExpressive%2FFuturistic&preview.script=Latn
-font I used for h3s.