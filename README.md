# studio_hw1

Reflection:

For this project, I've found new ways to piece together collages, and utilize the design space to bring my vision to life. I first made the sketch, and the original plan was to have the third collage be different facial features of diffferent characters from various manhwas, but because I realized the size difference of the photos I opted for a more reliable route. I intended for my project to serve as a personal collection of readings / webtoons / manhuas that the user could revisit, or share with others as a link. Because it includes images, others would be able to omit the step of searching up the name to see the art style. It is organized into 3 categories for now, the first one has mouse hover to see the art, and unhover to see the name. Second one rearranges the order whenever the page refreshes. And the third one has a interesting combination for the collage. An interesting element is the refresh and reorganize for the horror page to keep the images and re-shuffle them by exchanging positions and changing their dimensions according to the slots. I realized that some of the images (because all of them are img urls from google) are horizontal landscape mode compared to portrait mode, there wasn't possible to make them look good, whether that is zooming all the way out and leaving blank space or leaving it as is if its switched to a portrait slot and having the image zoom all the way in, so I decided to still have some element of movement by switching the two horizontal slots, and keeping the most detailed/portrait slot as is, and switching the similar dimensioned ones instead per reload. I also was really happy with the transparency overlay effect on hover I did for action page, as I like blue and red combinations, and it really shows the intensity of the manhuas I like. 

I've used the google font, utilized the w3schools massive collection of different css and html elements, and referenced youtube videos and forums to achieve the refreshing some slots while excluding others.

The most trouble I ran into is just troubleshooting css formatting fighting the html images, and forgetting the proper syntax and confusion with the extra/missing closing tags especially when I have so many div elements, accidentally putting a div outside when it should be inside, etc. I overlooked my div-class calling it navigation and Prettier ran into so many errors because of it, though I found it funny that the website never showed any indicators that it was supposed to be nav class. 

References and Links:

css hover transparency overlay: https://stackoverflow.com/questions/21423422/color-transparency-overlay-on-hover

- used it for my action hover transparent overlay part, it explains the :after pseudo element and gives an example using div:hover:after.

references for website 2: https://stackoverflow.com/questions/29969239/how-to-make-a-picture-change-randomly-in-a-website

-showed me how to random select item from array with Math.floor(Math.random() \* my 7 slots), reference explains math.random generates 0 to 1 and then gets a random number and rounds it to the nearest whole number with Math.floor. But this website only makes so user click and picture change to random.

https://www.youtube.com/watch?v=z3iKpCNlWU8&t=116s

- This youtube video further dives more into function randomNumber() using return Math.floor() at minute 2:52 demonstrating an example, and instead of replacing the image it creates random image feeds through using const container = "document.querySelector(."content"), const baseURL and const rows. I didn't need the randomSize but the randomNumber () function. And every time the user reloads the page, new images appear in the same grid format css created.

https://www.w3schools.com/css/css3_fonts.asp
-needed a refresher on importing fonts, explains @font-face rule and the differences between the font-style, font-weight.

https://fonts.google.com/specimen/Asimovian?preview.text=True%20Education&specimen.preview.text=True+Education&categoryFilters=Feeling:%2FExpressive%2FFuturistic&preview.script=Latn
-font I used for h3s.
