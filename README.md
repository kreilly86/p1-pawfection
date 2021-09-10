# PAWFECTION
<hr>

Pawfection is a dog sitting service based in Galway, Ireland. The company was started after the founders realised there was a growing need for  an alternative to dog kennels for owners needing a place for their dog to stay while they go on holiday. 


Pawfection is aimed at dog owners in the Galway area, who may feel unsure and stressed about what to do with their dog when they go on holiday, or if they have an unforseen event that pops up and they need to find someone to sit their dog last minute. The services are highlighted clearly, with two options: our staff sitting the dog at the owners' home, or our staff sitting the dog in their home.

<hr>
<img src="assets/images/am-i-responsive-sshot.png" alt="screenshot of site homepage on ami.responsivedesign.is">
<hr>

## Features
<hr>

### Existing Features
<br>

#### LOGO
<hr>
<br>
I made the logo using Canva with this:

[Logo Template](https://www.canva.com/templates/EAEmw6OtL8Q-pet-shelter-logo/).

<br>
<img src="assets/images/logo.png">

 The colors are warm and inviting, and are also used throughout the site. The logo is intuitive as it is also a clickable link to bring the user back to the homepage.
<br>
<br>

#### NAVIGATION BAR
<hr>
<br>
The navigation bar is displayed clearly at the top and center of each page. It is the same throughout the site and takes the user between the Home page, the About Us page, Dog sitting page, Testimonials page, and Contact page.
<br>

The navigation bar has a bottom border style applied to show the user which page they are currently on, and a hover psuedo class which impliments a background color and border bottom style when the user hovers over each page link.
<br>

<img src="assets/images/nav-sshot.png">

<br>
<br>

#### BACKGROUND IMAGE
<hr>
<br>
<img src="assets/images/background-sshot.png">
<br>
The  Home Page background shows a dog sleeping on it's owners bed with a transparent text overlay giving a brief but precise overview of the business. The colors aren't too distracting, and the image is cosy and inviting.

<br>
<br>

#### FOOTER
<hr>
<br>
The footer is displayed at the bottom of each page, and uses a simple vertical line to divide up the contact information and opening hours to the left.
<br>
On the right social media links are displayed and the links will open in a new tab for ease of navigation.
<br>
<br>
<img src="assets/images/footer-sshot.png">

<br>
<br>


#### FLEX DISPLAY IMAGES WITH TEXT BOXES
<hr>
<br>
The About Us, Dog Sitting, and Testimonials pages have a simple design layout with warm colors, and images that compliment the text to give the user a positive sense of the business and its' ethos.
<br>
<br>
 Class attributes are used so that the style is consistent throughout the site. There are 4 different class selectors:
<br>
<br>
- One for a blue colored text box.
<br>
- One for the accompanying image.
<br>
- One for a gold colored text box.
<br>
- One for the accompanying image.
<br>
<br>
For ease of use the display: flex layout is used so that each of these pages can be efficiently targeted for responsiveness.
<br>
<br>
<img src="assets/images/flex-sshot.png">
<br>
<br>

#### THE ABOUT US PAGE
<hr>
<br>
The About us page gives a short description of how the business was formed, i.e that it met a need in the market for alternatives to dog kennels. For potential customers this information is vital so they are aware of the type of service provided.
<br>
<br>
There is also a section on the business ethos which further highlights the uniqueness of the business.
<br>
<br>

#### DOG SITTING PAGE
<hr>
<br>
The Dog Sitting page utilizes the simple image and text box display to seperate the two types of dog sitting service the business provides:
<br>
<br>
- Dog sitting in the owners' own home.
<br>
- Dog sitting in one of the Pawfections staffs' homes.
<br>
<br>
At the bottom of the Dog Sitting page there is a gold colored horizontal rule to divide the main content from an additional feature. This feature is an internal link button that takes the user to the contact page. This makes it quick for the user to submit a dog sitting request once they have just read about the services provided
<br>
<br>
<img src="assets/images/interested-button-sshot.png">
<br>
<br>

 #### TESTIMONIALS PAGE
 <hr>
<br>
The Testimonials page offers two reviews from satisfied customers, and covers both options of dog sitting, in the owners' home and in a staff members' home.
<br>
<br>


#### CONTACT US PAGE
<hr>
<br>
There is a contact form included on the site for potential customers to submit a message requesting more information, or to send details of dates when they need a dog sitter.
<br>
<br>
<img src="assets/images/contact-sshot.png">
<br>
<br>
The form only allows the user to hit send once all fields are completed, and the name and email fields will only accept text or email format as requested.
<br>
<br>
The send button is styled with a hover psuedo class, so the experience is more interactive for the user.
<br>
<br>
<img src="assets/images/send-sshot.png">
<br>
<br>
<img src="assets/images/hover-send-sshot.png">
<br>
<hr>

### FEATURES LEFT TO IMPLEMENT
<hr>
I would like to change the navigation bar when the site is used on a smaller device. Rather than have the menu shrink in size and move underneath the logo, I want to implement a hamburger mobile menu so that the user can easily hover over and see all of the navigation links. This would make the mobile design more sleek and polished. (example below from WSSchools)
<br>
<br>

<img src="assets/images/mobile-nav-sshot.png">
<br>

#### IMAGE AND TEXT HOVER
<hr>
<br>
I would like to develop my mobile size design for the site. I would use a feature of having the images display the text information when the user hovers over them. This would be a more sophisticated way of displaying the information, rather than the current scrolling from image to text box, to image etc.

<br>
<hr>


### TESTING
<hr>
<br>

- <strong>Navigation bar</strong>
<br>
<br>
-The navigation bar is fully functional. The links have all been tested on both desktop and mobile devices, and from all pages.
<br>
<br>
-The logo also works as a link to bring the user back to the home page.
<br>
<br>
-The navigation bar does alter position and falls under the logo on smaller devices, but is in keeping with the style of the site, and contains the same class styling.
<br>
<br>
- <strong>Footer</strong>
<br>
<br>
-The footer has absolute positioning and remains in place the bottom of all pages, and all all screen sizes. This has been tested on mobile and desktop.
<br>
<br>
-When I first started working on the home page I had various issues with positioning, and tried a fixed position for the footer. I also tried relative and absolute switching back and forth between the rest of the content, but found the footer floated half way up the page. Finally I was able to use absolute positioning and a defined height and margin-bottom to ensure the footer remained in position and cleared the rest of the page content without any gaps.
<br>
All social media links in the footer have been tested, and open in a seperate tab.
<br>
<br>

- <strong>Links and form button</strong>
<br>
<br>
-All internal links have been tested and work. There is a button at the bottom of the dog sitting page which takes the user directly to the contact page, it is working correctly.
<br>
<br>
-At first the send button on the contact form was sending the user to the Code Institute form dump page and taking them out of the site, but I changed this in the code to open a new tab.
<br>
<br>

#### LAYOUT TESTING

<hr>
<br>
The various parts of the site were tested for responsiveness using Devtools in Google Chrome. I had to make some significant layout changes to accomodate this. The site was designed in a deskptop first manner, so it was a struggle to make it work on smaller devices.
<br>
<br>
-<strong>Home Page</strong>
<br>
The home page had to be restructured for small devices, and the background cover image was brought to the center. I tested using a width property of 100vw on the image at mobile level but this left huge gaps of background showing, and wasn't consistent with the site. I moved the overlay text from the left position to the right to accomodate a better view and perception of the background image.
<br>
<br>
<img src="assets/images/mobile-homepage-sshot.png">
<br>
<br>
-<strong>Footer</strong>
<br>
<br>
The footer was tested for responsiveness, and at the smaller device level the social media icons feel below the footer creating grey background space. I resized the social media icons, and reduced the font size of the footer text. The layout works on mobile devices slightly differently with the social media icon links falling below the contact and hours information.
<br>
<br>
<img src="assets/images/footer-mobile-sshot.png">
<br>
<br>
<hr>

#### BUGS AND ISSUES
<hr>
<br>
<br>

One major layout issue I have encountered is working with flex display. For my About Us, Dog Sitting and Testmonials pages I created class attributes so I could apply the style to all 3 pages rather than code seperate layouts for each page. It has been challenging to make the layout work as one page includes landscape images, and the other two use portrait. 
<br>
<br>
I created two containers, one that holds one image and a gold coloured text box beside it, and the other that holds one image and a blue coloured text box beside it. To make the layout more interesting I decided to inverse the order of image and text betweem the two containers, this meant using the property 'flex-flow: row reverse' on the second container. Overall I prefer this layout but it has cause some issues with differences in margin and space. It mostly effects the about us page as seen here, there is a big space between the bottom image and text:
<br>
<br>
<img src="assets/images/about-issue-sshot.png">
<br>

At present I have tried to decrease the space but this causes issues on other pages. I have decided to keep the layout as I prefer how it looks on the other pages, rather than having a uniform two text boxes and two images aligned vertically. If there was more time I would like to refine this layout and learn more about using flex, and flexboxes.
<br>
<br>
-<strong>Favicon Error</strong>
<br>
<br>
When I tested my site on Dev tools I recieved an error that the favicon could not load. I used
[favicon.cc](https://www.favicon.cc/?) 
to make a favicon, and added it to my index.html head.
<br>
<br>





#### VALIDATOR TESTING
<hr>
<br>
HTML
<br>

-No issues were returned when passing through the [Offical WSC validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkreilly86.github.io%2Fp1-pawfection)
<br>

CSS

-No issues were returned when passing through the official [(Jigsaw)validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkreilly86.github.io%2Fp1-pawfection%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
<br>
<br>
<hr>

### DEPLOYMENT
<hr>
<br>
The site was deployed to GitHub pages. The steps to deploy are the following:
<br>
<br>
In the GitHub repository, navigate to the Settings tab
and click on'Pages'. Select the Main Branch. Once the main branch has been selected, the page will automatically be refreshed with a detailed ribbon display to indicate the successful deployment.
<br>
<br>
The live link can be found here: 

[Pawfection](https://kreilly86.github.io/p1-pawfection)

<hr>

### CREDITS
<hr>
Throughout the project I made use of tutorials and advice from the following websites:
<br>
<br>

*   [Code Institute](https://codeinstitute.net)

*   [W3Schools](https://www.w3schools.com/)

*   [Codecademy](https://www.codecademy.com/)
<br>
<br>

I also used Youtube tutorials to impliment aspects of the site:

<br>

* [Responsive Layout](https://www.youtube.com/watch?v=S0a7PEOi0do)

* [Flexbox in 20 minutes ](https://www.youtube.com/watch?v=JJSoEo8JSnc)

* [How to draw a line Hl or Vl](https://www.youtube.com/watch?v=48rZ_gNKxz0)



<br>

#### CONTENT
<br>

- The social media icons used in the footer, and the icons on the Dog Sitting Page were taken from 
[Font Awesome](http.s//fontawesome.com)
<br>
<br>
- The fonts I used in my site were Roboto Condensed, and Poppins which I took from Google Fonts.
<br>
<br>
- I tested the site color scheme using contrast grid from 
[Eight Shapes](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%230396a6%0D%0A%23f0efec%0D%0A%23590817%0D%0A%23f19820%0D%0A%23434248%0D%0A%2303515D%0D%0A%23154D5C%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A%0D%0A&es-color-form__tile-size=regular&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp)
<br>
<br>

#### MEDIA
<br>
-All images are taken from the free image site 

[Unsplash](https://unsplash.com/)




