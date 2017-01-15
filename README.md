# CSY1018_assignment1

## Cover 

Name: Kitsantas Fotios    
Student ID: 17421808    
GitHub Repository: https://github.com/fkitsantas/CSY1018_assignment1    
Website Link (on GitHub): https://fkitsantas.github.io/CSY1018_assignment1/    

<img src="images/cover.png" alt="Cover" />

## Abstract

On this assignment our goal is to design and develop a Personal Webpage that consists of a 'starter' personal portfolio to support our future employability with the strictly use of HTML5 and CSS, while working our website on a simple text editor.

## Analysis

The way I implemented my website was done on steps.        

Started by creating my index.html and myStyle.css file. The Index document as a base for my project that will have (and share) the structure that I would like to use on all of my pages, same as the CSS file that will have all the CSS rules that i need in order to achieve the style I would like my webpage to have.

Linking my HTML page with the CSS style (myStyle.css) i created on /css/ folder.

Declaring the "Header" section of my page. The static content i need it to have on top of every page.
I include there the code for the music as it's not an element that will appear on page and I consider it as part of the header page.
However, this could be placed anywhere on the HTML file.


The Audio file (mp3) that I used is an Unlicensed mp3 (bensound-rumble.mp3) that i downloaded from
http://http://www.bensound.com/ . I put this on my page as a background music with the use of the default
HTML5 player and the attributes of autoplay in order to start on the background automatically during the time
that it takes for my page to load fully, plus loop in order to play nonstop (for those who enjoy the specific song).
I did use the ID of "bg_music" on the <audio> tag because I am planning to put some extra effort if <br>
there is time and give the use the ability to pause/stop the music with some buttons somewhere on site.
For now, since there are no buttons either, I have the "hidden" in order to just make it invisible on
page.

I use the IMG html tag, with the characteristics of the class "logo" in order to set an image on the
top of my page as the logo of my website, and in order to make it look more like a "website logo" i created
an IMG class named as "logo" on my CSS and added few cool characteristics as the "border-radius: 50%;" so that
it adds that circle cut effect (that could alternativly do on an Image Editor and save the "around the circle"
area as a transparent background. I also added the position relative attribute in order to be able to use a 2nd
CSS rule and put a text (as a Welcome text in the beggining, then changed my mind and replaced it with just a
"website title"). I did this because i wanted to achieve to put the text ON TOP of the image in order to make it 
look like a real website logo.

Text added on a \<p> class logo, styled with some characteristics to make it look more like a logo, and placed above the image
that I use as my webpage's logo. I also used a font from "Google Fonts" in order to make it look a bit better.

I created my website's Navigation Bar as a list of elements (that work as links), then I make it act as a
Navigation Bar for my website by the use of CSS styles to make them arrange on the same raw with a specific appereance.
i set the ID of this to nav, so everything on this unordered list is going to get characteristics from the specific
styleset that I created for "nav" on my CSS file.

I am Listing my Links one by one on as linked elements in order to create my Navigation bar. Styling was taken from W3Schools. Link: http://www.w3schools.com/w3css/w3css_navigation.asp
After my list was complete, i added the style on my css in order to make that ordered list appear in 1 line as a navigation bar. After that I'm closing the ul tag and the section of it with < /ul > < /div >

Adding 2 <br /> in order to fix the position of my title 2 pixels lower than the navbar.
After trying to validate my HTML5 code, i got a warning about the html tag and language, so i changed < html > to < html lang="en" > in order to fix it.

Then I am dding some "welcome" text with 2 different sizes. 1 big for the actual "Welcome" and a smaller one for the descriptive text under my welcoming message.

I use < br /> to get down the line just in order to push my footer on a specific height according to my taste. Then I am Declaring the "Footer" section of my page. The static content i need it to have on every page on the bottom.

Added Horizontal Rule just for the style, to distinguish my main content from the footer.
And created the class footer on my CSS to add some extra attributes in order to place the HR always on the bottom of the page according
to the browser's window.

Adding the 2 images that link to the W3Schools Validator and adjust their position with the div id="validations" tag, and Using target="_blank" in order to open the 2 links on my footer on a new window of my browser and not exit my page. 

Then I copy the code of the index.html and create 3 new documents with the same code, one for each section I need to have on my assignment. Bio, Cv, Contact.
By having done that I already have the base to work on (the html code that creates my navigation bar and my whole page style) and I can change the actual information that appear on the middle of it (eg. Welcoming text of my index changes to CV data or Bio, or the Contact form).

Then I move to the Bio page.

Same code as Index.html in order to generate the page style, then I am Adding a text description of the specific section of my page and after that I am Adding a picture of myself as "Gill Bate's picture". Text was styled from CSS with the use of \<p> and \<p class="big"> to distinguish the normal text and the Heading.

Then I move to the CV page.

Same code as Index.html in order to generate the page style, then I am adding the content of it.

I use a styled < div > and 2 stlyes of \<p> ( \<p> and <p class="big" ) in order to add my CV data placed the way I want them as a Heading and text under it, then I leave some data to be used with a FlexBox.

Adding a CSS Flexbox because it is required by the assignment. Code was taken from the example of W3Schools: http://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox_flexline<br>
My Flexbox consists of flex containers and flex items in order to create a 3 collumn sorting like if i had my data on a table.

Then I move to the Contact page.

Same code as Index.html in order to generate the page style, then I am adding the content of it.

Contact Form was taken from https://codepen.io/ssbalakumar/pen/uzDIA example, and modified it in order to adjust it to my webpage's needs.<br>
Original example had more input boxes, and the method it used was different. I changed the code and use method="get" and action="mailto:email" in order for the form to actually open an Email Client locally on your computer and try to send the email.
Since i took advantage of that ready code, i put it's CSS info on a different css file (contact.css) and link it, in order to show that you can use more than 1 .css files on an html page, instead of copying the code of it inside my main CSS style.

Now Regarding my CSS Style file called myStyle.css.

At the beggining of the file I am Importing Fonts from "Google Fonts" in order to use them on my page's style. First will be used for my logo, second will be used on my navigation bar's style.

Then i set my page's basic style. I use a background i edited myself for the website, and put it on the center of the page, fixed. At the same time i also set the background-color for just in case the page lags and delays to download/show the background.. as an alternative.

Then the style for the TEXT i placed under the Logo of my page. I also add opacity in order to make it "fainted" infront of my picture. People tend to put the logo's text into the Logo Image and have them binded. I did the same thing with the use of CSS.

Then i am Styling my default \<p> , in order to make a standard text style to use on my page.

Then I Created a class that can be used with \<p> and what I want to do is to actually replicate what we could do with \<h1>, \<h2> etc.

I then create a p.titles class of \<p> . Same thing as with p.big, i just align it to the left in order to use it on my CV.

Created a class that can be used with < div > in order to be able to use specific styling on my Unordered list.

Created a class that can be used with < ul > in order to be able to use specific styling on my Unordered list. 

I set the styling of an unvisited link.
I set the styling of a visited link.
I set the styling of a mouse over link.
I set the styling of a selected link.

Created a class that can be used with <img> in order to put some specific characteristics on my Logo image.

Created a class that can be used with < img > in order to put some specific characteristics on my Footer images.

Then i make a class in order to use it for fxing the align of my Footer images to center.

Creating my NavBar styling. Styling was taken from W3Schools. Link: http://www.w3schools.com/w3css/w3css_navigation.asp

Adding a CSS Flexbox because it is required by the assignment. Code was taken from the example of W3Schools: http://www.w3schools.com/css/tryit.asp?filename=trycss3_flexbox_flexline <br>
My Flexbox consists of flex containers and flex items in order to create a 3 collumn sorting like if i had my data on a table.

I am setting the style of the Horizontal Rule that i will use on my page (Generally).
I am setting the style of the Horizontal Rule that i will use on my page (Specifically on the footer) 

Then I am setting the style of the Image and Text on my "Bio" page. Placing the text on the left and the image on the right side
