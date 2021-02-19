# Village Winery 

A family owned business producing quality wines and organising wine tasting tours. 
Due to remote location it occasionally might be difficult to discover this little hidden gem.
I decided to create a web site which will not only provide an online presence,
but will also help potential clients find the location easier. 
Ability to browse products and services offered which is aimed towards increase of the amount of visits
,bottles of vines sold and the owner's revenue. 
Previous customer’s experiences will be available 
and lastly contacting the owner for any queries using the form provided. 
## UX
***
### User Stories


* User 1 : As a wine lover I want to find a place where I can taste quality wine.
* User 2 : I want to find a remote, romantic location and enjoy a glass of wine.
* User 3 : As a wine collectioner I want to be able to order a botle of wine from different parts of the world.
* User 4 : As a user I want to navigate site easily to find products and services.
* User 5 : As a user I want to be able to contact the owner and book a tour.


This website is aimed towards those who are wine collectioners, connoisseurs, bars or restaurants owners looking for a quality wine suplier 
or just a people who want to enjoy a good glass of wine in a calming environment.

Website's design is responsive and mobile devices first friendly. Design is minimalistic and elegant with all features included to 
create a positive user experiences.

## Features
***

### Landing Page
* Navbar
   * Home
   * Our Wines
   * Gallery
   * Contact Us
* Hero image
* Map of the location
* Footer with links to social media
### Our Wines
* A photos with different selection of wines
* A text eplaining about the products
* Order online button
### Gallery
* Number of interior and exterior photos
### Contact Us
* Contact form for getting in touch


### Features Left to Implement
* Feature which will still need to be implemented is abilty to make an online payment. 
  This is planned to be implemented at later stage of the course completiton when I gain knowledge of how to achieve that.
* Linking contact form to corporate email address. This will be implemented in case this website is used for existing business 
  as currently it is only designed and developed for educational purpose.  

## Technologies Used 
***

* __HTML/HTML5__ used for a basic sturucture of the page and content.
* __CSS/CSS3__ used to add style to the page and its content.

### Wireframe,Frameworks,Libraries and other programms :
***

* [__Bootsrap 4.1.3__](https://getbootstrap.com) as a framework.
* [__Balsamiq__](https://balsamiq.com) used for creating a wireframe.
* [__Online Convert__](https://image.online-convert.com) used to convert photos to webp format.
* [__Google Fonts__](https://fonts.google.com) used for projects fonts.
* [__Gitpod__](https://gitpod.io) used as a development environment.
* [__Canva__](https://www.canva.com) used for logo creting.
* [__Fontawesome__](https://fontawesome.com) used for adding icons.
* [__Colormind__](http://colormind.io) used for color pallete selection.
* Mozila DevTools used for debbugging and testing.
* Google DevTools used for debugging na testing.
* [__Youtube__](https://www.youtube.com/) used as a general source of information.
* [__W3Scool__](https://www.w3schools.com/) used as a general source of information.
* [__Pexel__](https://www.pexels.com/) used to download majority of website's images.
* [__Stackoverflow__](https://stackoverflow.com/) used as a general source of information.

### Project Wireframe Link :
***
To see Project Wireframes please click the link: <a href="https://github.com/kuzGo/village-winery/tree/master/assets/wireframe">Wireframes</a> 


## Testing &  debbugging:
***

Pre-deployment testing:

 At the early stage of my project for testing the website I used Mozilla and Google Chrome DevTools to test responsiveness,accessibility and any potential bugs on different
device models and screen sizes.
The issues I encountered during different stages of my project are:
 1. Navbar text color contrast issue. While I personally liked more color used for text, to increase accessibility I decided to change color to #040101,
which has contrast ratio 7.38, AA 4.5 ,AAA 7.0 making the website more accessible for diverse needs of users.
 2. Contact form would not display correctly in the landscape mode. As I had contact form wrapped with a `jumbotron`, which had a background image specified to cover 100vh.
This pushed the contact form to the bottom making some parts of form invisible/covered by the footer. Removing 100vh fixed the issue.
 3. Order online buttons were not correctly positioned. After adding different paragraphs of text to wines.html section, it moved all buttons underneath the text to
 different levels of the screen. To fix this issue I had to use position:absolute in CSS which displayed buttons as expected on large and medium screens but created an issue with small sizes 
 screens. Additional fix was to add some bottom margin to paragraphs which provided some breathing space between buttons and text.
 4. In the `navbar`, the company title next to the company logo would not render properly with small screen sizes. As this would push navbar links to the right,
   cutting off some of the links. I decided to hide the company title for small devices. At later stage of testing I noticed that this would not work in the landscape mode on some small 
   size screens and refactored the code to hide title with extra small screen sizes, this resolved the issue.
 5. One of the first Lighthouse reports was showing lower performance,best practices and SEO. Based on that report I refactored the code to add `meta` keywords and description to increase 
   SEO and also `aria-*` attributes to make better user experience for users of screen readers and other assistive technologies.
## Deployment
***

### Credits :
***

 #### Photographers:

 * Pexel images downloaded from the following photogrtapgers:

    > * Elle Hughes
    > * David
    > * Hunt on photos studio
    > * Bruno Cantuária
    > * Balázs Burján
    > * Julia Volk
    > * Ion Ceban
    > * Leo Woessner
    > * Markus Spiske
    > * Ksenia Chernaya

#### Codes copied from external sources:
* Bootsrap 
     * Bootsrap documentation used as a reference for nabar code which was hughely refactored and adjusted to suit 
     my project's requirements.
* Google maps
    * Embeded `iframe` html code copied from Google maps and added to the existing html code. It has been adjusted to fit project's needs.

## Content
***

## Acknowledgements
***
