# Paolo's Plumbing
## Milestone Project 1 
### by Nat Thomson
---

![alt text](/README-files/multi-markup.png)

Live site: https://natthomson.github.io/mp1-plumbing/

Repository: https://github.com/NatThomson/mp1-plumbing

Please also see: [notes on Resubmission](#notes-on-resubmission)

## Table of Contents
1. [UX](#ux)
* Purpose of Project
* User Stories
* Design Choices
  - color scheme
  - typography
  - imagery
* Wireframes

2. [Technologies Used](#technologies-used)
* Languages used
* Frameworks, Libraries & Programs Used 

3. [Testing](#testing)

4. [Addressing User Stories](#addressing-user-stories)

5. [Bugs](#bugs)

6. [Deployment](#deployment)

7. [Credits](#credits) 
* Code
* Content
* Media 
* Research
* Acknowledgements


___
## UX

### Purpose of Project
The purpose of the project is to create a website advertising a ficticious plumber and their services. Paolo does a lot of on call work (emergency work such as leaks, burst pipes etc.) and therefore needs visitors to his website to be able to get in touch with him urgently. He also needs a way in which customers can get in touch with him to enquire about less urgent jobs. Paolo's target audience is essentially anyone within a reasonable distance that might need plumbing work so the website needs to feature a clear, accesible UI that anyone from 18 to 80 can make use of. 
___
### User Stories
The user will:
1. be able to easily view the website on a variety of different devices
2. be able to get in contact in a variety of ways including in case of emergency
3. be able to interact with all website elements
4. be able to navigate to all pages of the website
5. be able to tell if the website will provide services in their area
6. have a clear sense of the purpose of the website

___
### Design Choices

Below is the color pallete originally selected for the website. The thought behind it was that blues and greys have a calming effect, match the logo colors and anchor a sense of the sites purpose with plumbing conjuring thoughts of grey pipes, silver taps, blue water etc. Having tried these colors out I decided to add a soft shade of white #FCF5E5 to aid in webaim contrast criteria. I also find that personally black text on a bright white background to be unkind on the eyes so a softer more parchment shade of white seemed a better option. 

![alt text](/README-files/screenshots/color-pal.png)

I decided to stick with one modern looking font for the website: 'Mukta' as shown below.
I used a variety of differnt font weights to help show a differnece in text importance much in the same way as font-size. 

![alt text](/README-files/screenshots/font-mukta.png)

All images (withthe exception of the logo) were taken from pexels using various search criteria. 
I decided on two 'hero' images for the index page (or one of viewed on a device with a small screen width). The first image is of a set of taps in a rather attractive bathroom implying that it is the work of the business owner and reinforces it is in fact a plumbing website. The second image is of a professional yet friednly looking plumber hard at work further reassuring site visitors they are in the right place for their plumbing needs.  
![alt text](/assets/images/index-hero.avif)
![alt text](/assets/images/teste-hero.avif)
The final imagery to mention is that of the logo; created using DALL.E 2 - an image generating AI. The logo is the letter 'P' for Paolo with a dripping tap to reinforce the fact that he is a plumber. It was created by using the descriptive text of 'The letter P with a tap, digital art'. after putting it into a circle using CSS I think it looks very professional. 
![alt text](/assets/images/paolo-logo.png)

It is also worth noting the hover effects on the index and testemonial text elements which on hovering produce a soft grey border. This paired with the previously touched upon inage zoom effects help to create a more modern interactive feel for the website. 


### Wireframes
original index page wireframe 
![alt text](/README-files/home%20page.png)
original contact page wireframe
![alt text](/README-files/contact.png)
original testimonials page wireframe
![alt text](/README-files/testimonials.png)

## Deviations from Initiial Design

Firstly I initiially invisaged there beign a hero image on every page. Tjis proved to appear too claustraphobic and resulted in uneccessary scrolling to get to the important content. Instead I opted for two hero images on the index page appearing side by side with a subtle zoom in animation or one on top of the other on a medium screen size or just one on small screen sizes. The map too was removed form the index page and only appears at the bottom of the content page now. In its place is a brief description of the areas covered fitting in much nicer with the rest of the page.    

## Technologies Used

- Balsamiq - used for creating the wireframes seen at the top of this file. 
- HTML5 & CSS3 - languages used 
- gitpod.io - only IDE I used for coding
- DallE2 - this image generating AI was used to create the logo
- Font Awesome - used for decorative icons
- pexels - source of all images on website 
- google maps - used to create the custom map
- bootstrap 4 - used for the navbar, various layouts and footer
- google fonts - source of 'Mukta' font
- imagecolorpicker.com - used to take a color from the AI generated logo and then provide an appropriate color pallete
- mycolor.space - also consulted for color scheme
- iloveimg.com - used to resoze and crop images
- avif.io - used to convert images from jpeg to avif files
- Chrome Devtools - relied upon heavily for visualising style changes and troubleshooting minor issues with code. 


## Testing

_As the site is now complete it is worth noting that all interactive elements have been tested in Chrome, Firefox and Safari on Macbook, Chrome and Safari on an iPhone mini 13 and Chrome and Safari on an iPad. There has been no loss of functionality found on any of the browsers and devices tested._



The process of testing the website took place over several stages of the build. Testing was carried out from the very beginning in simple ways such as changing the background color of the index.html to red to make sure the style.css file linked up correctly or adding lorum ipsem text to get a feel for what the website would look with a full ammount of text before I was ready to put in the final text. 

During the build provess when a minor error occured or when I wanted to quickly see the result of changing margin/padding values I relied heavily on Chrome DevTools. 

Once the build was compelte or near complete I made use of the Lighthouse feature within DevTools. This gave me a detailed report on the load time of each page on both desktop and mobile. You can view the reports here:

[index desktop](/README-files/testing-files/lighthouse-desktop-index.pdf)
[contact desktop](/README-files/testing-files/lighthouse-desktop-contact.pdf)
[testemonial desktop](/README-files/testing-files/lighthouse-desktop-testemonial.pdf)
[index mobile](/README-files/testing-files/lighthouse-mobile-index.pdf)
[contact mobile](/README-files/testing-files/lighthouse-mobile-contact.pdf)
[testemonial mobile](/README-files/testing-files/lighthouse-mobile-testemonial.pdf)

All pages have passed through html and css valisdation using https://jigsaw.w3.org/

___
## Addressing User Stories

Here we shall explore the user needs as outlined in the [User Stories](#user-stories) section and demonstrate how each user need has been met. 

1. _be able to easily view the website on a variety of different devices_

This has been acheived in a variety of ways. Firstly I have made use of responsive structuring devices such as flexbox and bootstrap. I used flexbox on the index page to allow the text elements to appear side by side on a large screens and on top of one another on small screens so the user will not have to scroll horizontally or zoom in. The images on the index page too have been structured using flexbox and similarly appear side by side then on top of one another on small screens. The contact and testemonials page use bootstrap for their struturing to create similarly responsive effects with testemonials appearing in a grid on large screens and a list on small screens. The navigation bar at the top of screen too is styled responsively using bootstrap to allow for the menu to appear at thte top of the browser window on large screen sizes and condenses down into a hamburger menu on smaller screens. 

2. _be able to get in contact in a variety of ways including in case of emergency_

Upon opening the home page the user is faced with a large, clear button labelled 'Emergency? click here' below the hero image/images. When clicked on a mobile device they will immediately be prompted with a 'call _number_' pop up. Similarly on desktop devices the device will try to make the phoen call with whatever software it has i.e. facetime etc. On top of this there is a clearly labelled 'contact' page the user can get to by interacting with the menu. On this page the user is given the option of filling out a contact form, sending an email bu interacting with a clearly labelled email enquiry link. There is even a definitely genuine business address provided below for those who wish to write. 

3. _be able to interact with all website elements_

All links take the user to the approprite place including the social media links in the footer. 
The contact form is clearly labelled and is editable. text sizes in all interactive elements are large enough on all screen sizes aiding in the sites overall accesibility.  

4. _be able to navigate to all pages of the website_

Navigating to all pages of the website is easy via the navigation menu. THere is no need to use browser controls (back, forward) although they work as they should. 

5. _be able to tell if the website will provide services in their area_

A general list of areas is described in the 'Where we work' section on the index page with further detail being granted in the form of an interactive google map displaying a clear outline of the areas Paolo is prepared to travel for emergency call out work. 

6. _have a clear sense of the purpose of the website_

The purpose of the website is clear from the logo and heading, through the clear use of imagery and icons further reinforcing the purpose of the website. 

___
## Bugs 
### Fixed 
1. 
- Problem: The hamburger menu on the navbar was not collapsing/expanding.
- Solution: After some research it turned out that I had been missing the jquery script from the head section. Once that was put in it worked as intended. 
2. 
- Problem: Empty side-scrollable space on left and right side of index.html.  
- Solution: This was actually an easy fix as it had cropped up in a previous lesson on the use of bootstrap layouts. Bootstrap automatically adds negative margins called gutters. To remove them I had to add a .no-gutters class to each bootstrap row. 
3. 
- Problem: The intended background color for the navbar was appearing below the rest of the navbar.
- Solution: Removing the .bg-light class from the navbar fixed the issue. Assuption being that .bg-light has underlying styling that was contradictory to the styling I was applying to the navbar with CSS. 
4. 
- Problem: contact.html not showing updates in gitpod preview.
- Solution: Save work, commit, close it and open it again. Assuming the equivelant of clearing browser cache. 
5. 
- Problem: The navbar resizes at a differnt break-point on index.html compared to on the other two pages. 
- Solution: The pages had differnet classes. index.html was navbar-expand-md whereas the other two pages had navbar-expand-lg. The problem was righted once all three had the same attributes. This was probably caused by copying the navbar across before I had decided on the styling definate. 

### Post Deployment

6. 
- Problem: all images showing as broken img links on live website. 
- Solution: This took a little time and would have been helped by more patience on my part. At first I thought that it might be the case that the file ectensions had to be upper case for Github Pages. However this proved fruitless. My next step was to try altering the file paths from "/assets/images" to "../assets/images". This too had no effect. I then tried "./assets/images" which did not appear to work whereas in actual fact it had worked but I had been too omaptient and did not allow Pages time to load properly, assumed it had not worked and then tried the first three attempts again before finally realising ".assets/images" was correct. 

### Unresolved Bugs
It is worth noting that in Chrome on the iPhone mini 13 there is empty white space to the left and right of the screen on all of the web pages. NOW RESOLVED by implememting overflow-x: hidden;
___
## Deployment

In order to deploy this wwebsite you must go to the repository: https://github.com/NatThomson/mp1-plumbing > click on settings, located above green gitpod button > click on pages, located on left hand menu > under Build and deployment, source,  click to deploy from branch > select main branch. 
Now back in the repository, when you navigate to 'environments' on the right hand side it will say github-pages. click here and you will be taken to a page with all deployments of the website. the most recent one will be labelled active. Now click VIEW DEPLOYMENT to see the love website. 
For further information please visit: https://docs.github.com/en/pages/quickstart 

___
## Potential Future Development for the Website
In future iterations of the website I would add a 'services' page so customers get a more detailed view of what Paolo offers and a 'gallery' page to showcase previous work undertaken by Paolo. 



___
## Credits
### Content
- All code (unless where other-wise stated) was written by myself. The same too is to be said of the text on the webpage. 
- With the exception of the logo, all images are form pexels.com. 
 
### Personal 
Special thanks must be given to the tradespeople in my family who inspired me to design a website of this manner, my mentor Jack for his invaluble advice and contributions and my Wonderful Wife for supporting me as always. 

___
# Notes on Resubmission

After having recieved a fail for my initial MP1 Project Submission of the same name I imported the feedback into an Excel spreadsheet and filtered it by 'no' giving me a clear outline of every criterion causing the resulting failure. From this I drew up a plan to resolve the numerous issues. During this process I have corrected and ammended many peices of code within the various HTML, CSS & MD files. Where i felt it appropriate I have left certain elements the same and justified that choice, for example some elements no longer match the original wireframes but I have acknowledged this and given reasons as to why.  