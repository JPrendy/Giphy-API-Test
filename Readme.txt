James Prendergast
GIPHY'S API TEST
UI ENGINEER TEST

Instructions
-----------------
. If you have any problem with the images, I would recommend cleaning your computers cache.

. I included an image folder which keeps hold of an image that is used
as a favicon and as an icon when used on your mobile.

. I included "manifest.json", this file contains information to change how the web
the app appears on a mobile providing a better experience.

. "style.css" contains all the CSS I used to make the application. It contains all the notes
on how the header, navbar, buttons and footer appear in the application.

. All the material that connect to Giphy API JSON is in the file "function.js". This file
contains functions that are called when the buttons are pressed. It retrieves the url value associated
with the button. with this url, it goes through the JSON available at this url until it gets the gifs files.
It returns 25 gifs files associated with the button. The gif files are put into div in order to separate them and allow for easier editing.
Along with every gif, a hyperlink is created which you can click to bring you to the giphy url.

. Whenever you hover over a gif its height and width are increased this is done by CSS hover affects.

. To allow pagination to occur, I decided how many page I wanted you to visit. I decided 4, you can change the number to any and it should
work as long as it does not run into the giphy limit in the giphy api url. So, it creates 4 buttons that have a page value in the url. when you
press the display button it retrieves the url to find which image set to return. So, it could be the first 25, the next 25 and so on. This makes
adding additional pages very easy and dynamic.

. Finally, I was unsure how detailed and dynamic you wanted the css to be since normally I use frameworks like Bootstrap, which make
it a lot quicker to make more detailed designs. So, if you want a better example of my UI and UX experience. I would recommend to look
at my Portfolio Website http://jamesmauriceprendergast.com/ or ask to look at my final year project.
