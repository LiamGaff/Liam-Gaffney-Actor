# Actor Webpage
![](assets/images/readme.md_hero_img.png)
I am designing this webpage as part of my MS1 project for Code Institute's Diploma in Software Development. This will also be my own personal Actor's Webpage that has been designed to showcase my work and keep
people up to date with my career so far. I hope to use this webpage to market and advance my career. An example of the deployed webpage can be found [here](https://liamgaff.github.io/Liam-Gaffney-Actor/).

# UX

## User Stories
As a user I would like:

* To instantly have visual confirmation of what the actor looks like.
* To be able to view the actor's work.
* To be able to easily navigate through the actor's webpage.
* To find information about the actors training and work history.
* To have access to the actors contact information for possible collaboration.
* To be able to contact the actor directly through the webpage if I have a question.
* To be able to view the webpage on any device.
* To be able to view the webpage on a number of browsers.

## Strategy
This project was designed to provide a user-friendly and informative webpage that allows the users to get to know the client/actor. The main objective of the webpage is the promotion of the client/actor and their career. The target audiance of the webpage are casting agents and other people within the film/theatre industry.

## Scope
The aim was to keep the webpage simplistic so I avoided overpopulating it with unnecessary content. All the content falls inline with user needs and provides users with all neecessary information in regards to the client/actor. The site conatains five sections (Header, Showreel Section, About Section, Gallery and Contact Section).

## Structure
Every second a user spends on the actors webpage matters, so easy navigation and flow of content is of utmost importance. There is an interactive navigation menu at the top of the site that allows users to easily access any section at the click of a button. Also each section heading is linked to that individual section so when clicked on it will bring you staright down to the next piece of content(this is an alternative to using the scroll bar). As the users will vary in age the easy navigation system in place will allow all types of users an intuitive way to move through the site.

## Skeleton
The webpage was designed to keep users engaged and so I chose to go with a very retro and dramatic feel that suited the type of audiance/users  I wish to target. This effect was achieved through the choice of text and colours which are discussed further in the following sections.

## Design
  **Wire Frames**
  
  The webpage was designed using 
  Balsamiq to crate some basic 
  wireframes(Link below)
  
  [Wireframes](wireframes.md)


**Colours**

* I used a turquoise (#56c1c1) colour for all my headings as I felt it matched nicely with the hero image.

* For the rest of the text I either used a simple shade of white or blue to blend nicely with the rest of the content and dark background. This blend of colours provided the retro look and feel that I was aiming for.(I asked a number of people of all different ages if they could easily read the text with the chosen colours.)

**Typography**

* I used the "Goldman" font for all my heading as I felt it really made the the text stand out and it seemed to fall inline with the dramatic look I wanted to achieve. 
* I then used "Roboto-Condensed" for the rest of my text as it seemed to pair nicely with the Goldman and it came reccomended by [Google Fonts](https://fonts.google.com/).

**Backgrounds**

* The background for the header is a photo of the actor(me) and was chosen to instantly show off the actor in his working environment.
* The rest of the page was given a navy blue colour (#243c56). This made the rest of the content stand out to the user.

# Features
## Exsisting Features
* **Nav** - The webpage will have a responsive nav in the top right corner that will be linked to all the sections of the page. On small viewports the nav will change to burger icon containing the nav elements.

<img src="assets/images/features_nav_2.png" width="250" height="250"/>

Drop down navigation menu for small screen sizes.

<img src="assets/images/features_nav_1.png" width="200" height="250"/>

* **Showreel** - An iFrame element was used to embed a video from [YouTube](https://www.youtube.com/embed/6bVErQjUwtA) which showcases the actors work(this showreel is to be updated soon).

* **Gallery** - An interactive photo gallery in the form of a carousel was added to the webpage to conveniently display some shots of the actor at work.

<img src="assets/images/features_gallery.png" width="250" height="300"/>

* **Links** - Buttons and links that lead users to the actors other profiles, webpages and social media are dispersed through out the page.

* **Form** - A contact form to contact the actor directly through the webpage was added to the contact section. This form currently doesn't work but is to be updated in the future.

## Features Still to Be Implemented
* An external page is to be added that will contain a blog to keep users up to date on the actors career.
* A section for the actor to upload new monologues and scenes for users to view and comment on.

# Technologies Used
## Languages
* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks and Programs
* [Bootstrap 4.5](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
> Used to get the overall layout of the Webpage.

* [Balsamiq](https://balsamiq.com/wireframes/?gclid=Cj0KCQiA48j9BRC-ARIsAMQu3WSc14tIkeDZUlWDIVOa-Acbyn1s5XvsJJ6CnWplwD7_WPcgk-C4cTgaAsaNEALw_wcB)
> I used Balsamiq to make my wireframes.

* [GitHub](https://github.com/)
> GitHub was used to push content to the repository.

*  [TinyPNG](https://tinypng.com/)
> TinyPNG was used to compress my images and files.

*  [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator)
> CSS code was checked using CSS W3C CSS Validator.

* [Online Beautifier](https://beautifier.io/)
> Online Beautifier was used to beautify my HTML code.
# Testing
As the webpage was being built Chrome developer tools were used to ensure that the code was working smoothly. Each section was then tested again every time a new feature was added.

Pre-deployment I checked that the webpage met all the user needs previously stated.

The webpage was tested on multiple viewports each time a section was added or updated to make sure everything was working correctly.
Post-deployment the webpage was tested across a number of devices to ensure it remained responsive. Some of the devices that were tested: Iphone 5, Iphone 11, Samsung A5, Samsung S8, Ipad pro and a Toshiba laptop.

Post-deployment the webpage was opened and tested on three different search engines Google Chrome, Firefox and Safari.

**Bugs**

Most bugs I encountered were solved through the use of Bootstrap or were simple mistakes that were easily fixed in my CSS code.

* Carousel 
> I originally encountered an issue with the carousel that I got from Bootstrap, this was mainly to do with it's positioning . This problem was fixed using the flex utility from Bootstrap.
  Also the photos that were added to the gallery had to be adjusted to fit within the carousel.
* Gallery Section 
>After I corrected the carousel position it seemed that a new problem had arose. When viewing the site on a view port bigger than 720px the sections would collapse in on top of each other. This problem was fixed by simply adjusting the height of all the sections in my CSS.

*  Nav 
> I had to return to my nav as it seemed that it would move out of place when i viewed the webpage on a mobile device. Once again this was fixed using the flex utility from Bootstrap.
(The nav toggler icon currently moves up and down when clicked on. I left this as it seems to work as a feature of the application.)

* [W3C Markup Validator](https://validator.w3.org/nu/#textarea)
>W3C Markup Validator was used to check the HTML code. Any bugs that came up were due to outdated styles in the iframe element. These were simply removed and then resolved by updating the CSS for the iframe element.

* Viewport Testing
> The webpage was opened on a number of different screen sizes to ensure it worked on all viewports. The webpage did run into trouble when opened on viewports with a width smaller than 400px as all the content was pushed slightly to the left. This was resolved by removing the padding from from the iframe video in the showreel section.

## Functionality Test
Nm | Test | Action | Test result |
-- | ---- | ------ | ----------- |
#1 | Navigtion links | Click on each nav link to access sections | Passed |
#2 | Section heading links | Click on section headings to move through sections | Passed |
#3 | Showreel | Click on showreel to play | Passed |
#4 | Text links | Click on links in about me section | Passed |
#5 | Carousel | Click on arrows to move through gallery | Passed |
#6 | Button links | Click on IMBD and Spotlight buttons to be transferred to each site | Passed |
#7 | Form | Enter details to form, click submit for page response | passed |
#8 | Social media links | Click on links to be transferred | Passed |

## Browser Compatibility Test
Nm | Action | Test result |
-- | ------ | ----------- |
#1 | Chrome | Passed |
#2 | Firefox| Passed |
#3 | Safari | Passed |

# Deployment
The site was developed using [Gitpod IDE](https://gitpod.io/), the code was then added and comitted to git and pushed to my Github repository.

The site was deployed to GitHub pages. See below for instructions.

* Log on to GitHub repository.
* Click on settings.
* Scroll to GitHub pages.
* Change your source to Branch - Master.
* Hit save.
* Scroll up to find and retrieve the link to your deployed website.

## How to clone this project
## With Gitpod
* Create a Gitpod account and install Gitpod Browser extension for chrome.
* Log into your gitpod account.
* Go to [Github repository](https://github.com/LiamGaff/Liam-Gaffney-Actor) and click on the green "Gitpod" button.
* This will open a new Gitpod workspace created from the code in the github repoitory where you can work.

## Local IDE
* Go to my Github repository [here](https://github.com/LiamGaff/Liam-Gaffney-Actor).
* Under the repository name click on "clone or download"
* In the clone with HTTPs section copy the clone URL for the repository.
* In your local IDE open the terminal and change you directory to where you want the clone to be made.
* In the terminal type _git clone_ and then paste the repoitory URL.
* Press enter and a clone will be created.

# Credits

## Code
* The interactive structure and layout of the code  https://getbootstrap.com/docs/4.5/layout/overview/
* Embeded youtube video copied from youtube
* Photo gallery carousel https://getbootstrap.com/docs/4.5/components/carousel/
* Resources such as W3schools and Stackoverflow were used to come up with solutions to various problems I encountered
* Some ideas for the code (such as the social media links) were taken from mini projects done through out the course. 

## Acknowledgements
* I would also like to credit and thank my mentors Brian Macharia and Oluwasuen Owonikoko for all their help in guiding me through my first milestone project.