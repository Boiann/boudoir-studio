# BOUDOIR STUDIO

Boudoir Studio Wexford is a Project 1 for Code Institute Full-stack development program: HTML/CSS Essentials.
Made with passion for anybody interested in Boudoir Photography and what it represents.

<!-- Add an image of the finished site here.  -->

Visit the live site <a href="https://boiann.github.io/boudoir-studio/index.html" target="_blank">here.</a>

---

## CONTENTS

* [Project Overview](#project-overview)
  * [Business Goals](#business-goals)
  * [Client Goals](#client-goals)

* [User Experience](#user-experience)
  * [User Expectations](#user-expectations)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Structure](#structure)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Specific Features on Each Page](#specific-features-on-each-page)
  * [Other Features](#other-features)
  * [Future Implementations](#future-implementations)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Programs Used](#programs-used)

* [Deployment](#deployment)

* [Testing](#testing)
  * [AUTOMATED TESTING](#automated-testing)
    * [W3C Validator](#w3c-validator)
    * [Lighthouse](#lighthouse)

  * [ACCESSIBILITY](#accessibility)  
    * [Wave](#wave)

  * [MANUAL TESTING](#manual-testing)
    * [Testing User Stories](#testing-user-stories)
    * [Full Testing](#full-testing)

  * [BUGS](#bugs)
    * [Known Bugs](#known-bugs)
    * [Solved Bugs](#solved-bugs)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

## **Project Overview**
Boudoir Studio is a fictional photography studio specialized in Boudoir type photography. It is based in Wexford, Ireland, hometown of the photographer/owner of the business.
The primary purpose of the website is to attract new clients to keep the business profitable. This is achieved with a sleek, clean and gentle look throughout the website. 
The ability to communicate well with potential clients is necessary and this is achieved with social media links on every page, as well as the ability to contact the studio at any time 
through the contact section present on all pages.

Although fictional, the project is a representative example of a real-world business trying to reach out to new clients and maintain profitability. In this day and age, without online presence it is nearly impossible to succeed. The developer of this project tried to put himself in the shoes of the business owner. Having some experience in Boudoir, he tried his best to bring the vision of a proper Boudoir Photography website to fruition. 

This project was made for the first Portfolio Project required to complete Code Institute's Full-stack development program. The main requirements of this project are to build a responsive and static front-end site to present useful information to users using all the technologies learned so far, namely HTML5 and CSS3.

Because this is a project made for educational purposes, the images contained are not *true* representation of Boudoir Photography. The images chosen for the project were intentionally selected as not to offend or cause project refusal on a content itself basis. Although the times are more liberal now, the developer chose to respect any and all persons that will have to review and look at the project in depth, and not to expose them to anything explicit.

### **Business Goals**
  * Attract new clients
  * Fast and direct communication channel to clients
  * Website that truly represents the business model and capability
  * Provide as much basic info as possible
  * Create online presence

### **Client Goals**
  * Find basic information about what Boudoir is, who is it aimed to and what is it's purpose
  * To be able to contact the business in a fast and direct way
  * To be able to see the studio's body of work
  * Find basic info about the people running the business
  * Find answers to basic questions
  * Find what other people say about the business

[Back to top ⇧](#boudoir-studio)

---

## **User Experience**

### **User Expectations**
   * User-friendly website
   * Intuitive navigation
   * Fast performance
   * Accessible to all users
   * Responsive across many different devices and screen sizes 
   * Able to find basic informantion and answers
   * Contact the business directly
   * Find social media associated with the business

### **User Stories**

  #### **First Time Visitor**
   * I want to know what Boudoir Photograpy is
   * I want to navigate the website intuitively
   * I want to find additional information
   * I want to check out the social media of the business

  #### **Returning User**
   * I want to know about the business owner/team
   * I want to see the portfolio of the Studio
   * I want to know what other people said about the experience with the business
   * I want to contact the Studio

  #### **Website Owner**
   * I want to provide basic information about Boudoir Photography and who is it for
   * I want potential clients to be able to reach us quickly
   * I want to provide our body of work
   * I want potential clients to follow us on social media

[Back to top ⇧](#boudoir-studio)

---

## **Design**

### **Colour Scheme**

<!-- Colour Palette img  -->

The colours used in the project are Dark Red and its various opacity setting, Raisin Black, Black and White.

Dark Red is used throughout the site to emphasize and bring attention to text/link.
The various opacity of Dark Red is used as a hover effect and background for text.
Raisin Black is used sparsely, mostly for navigation links and social media icons to soften the colour contrast against hover effect of red. 
Pure Black was used for text across the website.
Pure White is used only for back to top button and for cover text inside hero image to allow for good contrast.

The colour choice was made in early planning stages for the project. The developer felt that black and red on white background will achieve modern, elegant and attractive look.

### **Typography**

<!-- Google Fonts img  -->

The fonts were imported from Google Fonts database, https://fonts.google.com/.
Fanwood Text is used throughout the site (body), and Quattrocento sans is used for the site logo and submit button in the form. 
Both fonts have a back-up font in case the selected doesn't load for the user.
Fanwood Text has a backup of serif and Quattrocento sans has a backup of sans-serif.
The fonts were chosen on the pairing suggested on the website https://www.fontpair.co/all.

### **Imagery**

The main (hero) image used is the same across all pages but it changes in colour. This was a design choice made in early planning stages for the project.

<!-- Hero imb, gif or img of all 3 pages together -->

The goal was to present the index (home) page in black and white, second (gallery) with colour accents and third (about) in full colour.
This gradual colour addition was meant to give a sense of progression through the website and to keep the website dynamic and attractive.
After the developer started with gallery and about.html he realized doing colour accent will be very hard to do because picture used doesn't have high contrast
in the right spots (eyes, lips etc). 
Hero image was changed to black & white for the index.html, slightly muted colour for the gallery.html and rich colour filter applied for the about.html.

Copy of images note from the Introduction part of this readme:

*Because this is a project made for educational purposes, the images contained are not *true* representation of Boudoir Photography. The images chosen for the project were intentionally selected as not to offend or cause project refusal on a content itself basis. Although the times are more liberal now, the developer chose to respect any and all persons that will have to review and look at the project in depth, and not to expose them to anything explicit.*

On account of this being potentially sensitive issue and to explain why is there a difference from the real Boudoir Photography the developer found it necessary to put the above paragraph in the Introduction too.

All of the images except the hero and gallery itself have border-radius applied to them to smooth out the edges. Makes for a "softer" feel of the website.

### **Structure**

  * The Boudoir Studio website is structured in a user friendly and easy to navigate way. 
  * When opening the website, the user sees a navigation bar with the logo on the left-hand side and the navigation links to the right. 
  * The hero image contains simple yet impactful message (cover text) for the potential new client and serves as a call to action.
  * Both the navigation bar and hero image along with cover text are kept consistent in all three pages, exception being the thanks.html.

  * Below the hero image the user will find a simple description of the following 
     content:
    * (index.html) SEE FOR YOURSELF HOW BEAUTIFUL YOU ARE! - serves as an additional motivator to explore the page further
    * (gallery.html) OUR BODY OF WORK SPEAKS FOR ITSELF... - gives a clue to the gallery content that follows
    * (about.html) MEET OUR TEAM, FIND SOME ANSWERS, SEE TESTIMONIALS... - gives a clue to the page content that follows

  * Below the content descriptor the user will find "main" content for the each page:
    * (index.html) What is Boudoir Photography, its history and why should the user consider doing it and why choose this particular Studio
      Serves as immediate source of essential information for the user, short but to-the-point text.
    * (gallery.html) Gallery of 12 images as a representation of the photographer's ability and prowess.
      Serves as an Studio's image portfolio, very important in photography-related businesses.
    * (about.html) Studio team information in a form of short biographies, FaQ section 
      with questions answered and testimonials with one-line reviews.
      Serves as a way for the user to get to know a team a little bit, answer any questions before the user is required to input them in a query 
      and short testimonials from previous clients used to reassure and motivate future clients.

  * Under the "main" content of each page the user will find the contact section that is kept consistent in all three pages, exception being the thanks.html.
    * Form section serves as the way for the user to send their query to the Studio
    * Map and address section with all the necessary info required to find the  
      Studio's location; map, address and open business hours.

  * Under the contact section the user will find footer section with a short call to action message (FOLLOW US ON SOCIAL MEDIA!) along with icon links to the four giants; Facebook, Twitter, Youtube and Instagram.
  The footer and its content is kept consistent in all four pages, including the thanks.html. 

  * Upon successful query submission in the contact form the user is rewarded with a new page thanking the user for the query.
    * Thanks.html contains a time-frame for the Studio's reply so the user knows when to expect it.
    * User's interaction is rewarded with two videos (linked from Youtube) from the Boudoir Photography expert, providing the user with additional info on how does a Boudoir Photoshoot look like and what to expect, the other video serving as a longer testimonial from a client. 
    * The page also features "Back to Home" link so the user is not required to depend on "back" button of the browser or mouse.      
 

### **Wireframes**

Wireframes for the project were developed right after the idea was scribbled on a piece of paper, the program used being Balsamiq.

Wireframes for Assessment Guide and Project Planning & Ux were made before the ones for the content of the pages themselves.

<!-- Assessment Guide and Project Planning & Ux imgs -->

There are three sets of wireframes for the pages, each set corresponding to the level of learning outcome (grade); Pass Performance, Merit Performance and Distinction Performance.

Differences between outcomes were considered early as to allow flexibility when working on the project. Personal, work, family, dependants and health situations were considered to have impact on time available for the project.
Ideally, maximum time was to be taken to finish the project making the scope bigger.

Pass Performance wireframes:

<!-- Pass Performance wireframes imgs -->

Merit Performance wireframes:

<!-- Merit Performance wireframes imgs -->

Distinction Performance wireframes:

<!-- Distinction Performance wireframes imgs -->


[Back to top ⇧](#boudoir-studio)

---

## **Features**

All of the features presented in this sections are fully responsive on all devices and screen widths.

### **General features on Each Page**

* Responsive header section with links to Home (index.html), Gallery (gallery.html) and About Us (about.html), featuring hover effect of colour change and bottom border, all paired with transition effect. When clicked, the website logo also leads back to Home (index.html).
User will know on which page it is currently on, achieved by changing the background colour of the page currently in use.
Contact link will scroll the page to contact section, allowing the user to be able to quickly find it when in need.

  * Hover effects on navigation menu

    <!-- img/gif -->

  * Links working/opening pages

    <!-- img/gif -->

  * Logo click opening Home page   

    <!-- img/gif -->

  * Contact link scrolling to contact section

      <!-- img/gif -->

* Navigation menu turns into hamburger menu below screen size of 900px. This is done to not clutter the header. The hamburger menu links retain their hover and transition effects, as well as retaining active menu background change.

* Hover effects in hamburger navigation menu

    <!-- img/gif -->

  * Links working/opening pages in hamburger menu

    <!-- img/gif -->

  * Logo click opening Home page in hamburger menu  

    <!-- img/gif -->

  * Contact link scrolling to contact section

      <!-- img/gif -->  

* Hero image and cover text "pillow" are fixed in the background, contributing to interesting effect and overall dynamic feel of the page.

<!-- img/gif -->

* Page content descriptor below the hero image is consistent in style and size across the pages

<!-- img/gif -->

* Responsive contact section containing form that the user will use to send the query to the Studio. Features hover background change for the input fields, text area and submit button. The placeholder text inside the text area changes colour on hover as well to allow for good contrast for the user.

<!-- img/gif -->

* On the right to the form section, the map section features responsive map with controls and functions. The user is able to zoom in/out and move the map around.

<!-- img/gif -->

* Lastly, the footer area contains icons for social media links. Each link opens in a separate tab, and has hover background transition, border-radius applied and transition effect applied.

<!-- img/gif -->

### **Specific Features on Each Page**

* Home page (index.html)
  * The Home page's body content consists of three images and four square-areas with text. Divided into three sections, first section has a image on the left and text on the right, second section has an image in the middle with text on both sides (The link provided in the text opens in a new tab) and the last one has an image on the right and the text on the left. This particular layout was chosen to keep the layout dynamic and engaging. Of all the "body" content in between the pages, the home page has the biggest and most adaptive font size. This is to make the first page more impactful and distinct from the rest of the pages/content.

  <!-- img/gif -->

* Gallery page (galley.html)
  * Gallery page contains an image gallery consisting of 12 images, each with hover-magnifying effect applied. The border-radius was not applied to them to keep the photography portfolio more professional. The images themselves are grouped in three columns with four images each to allow for better flex styling.  

<!-- img/gif -->

* About Us page (about.html)
  * About us page has three sections, first being the short description of the Studio staff and the owner/photographer. 

  <!-- img/gif -->

  * The second section is Frequently asked questions with accordion menu styling.
  Each of the questions hides the answer, revealed after the user clicks on the question. The questions have the hover background change paired with soft transition applied along with edge softening.

  <!-- img/gif -->

* Thank You page (thanks.html)
  * Thank you page retains only the footer area from previous pages. The page itself consists of a big thank you message, reply-back promise and time frame. The two video iframes serve as a reward of sort for the user, and they are fully responsive.
  The link provided in the text opens in a new tab.
  Distinct feature of this page is animated text/link that takes the user back to the home page.
  This specific animation was chosen to bring the attention to this "back to home" ability to the user.

    <!-- img/gif -->

### **Other Features**

* Hidden Scrollbar is utilized across all of the pages, design choice coming from desire to center the content as best as possible and for being more aesthetically pleasing.

  <!-- img/gif -->

* Back-to-top Button is made by using Javascript, utilized on all pages but the thanks.html (not required because it is single screen size).
The developer did not intend to use any javascript in this project, but has failed to find an appropriate button using html/css only. The function of hiding the button completely when at the top of the page was just to perfect to miss out on. 
The button has the now familiar hover color change effect paired with smooth transition. The button has low opacity when not in use as not to impede with the user's view of the page, especially on lower resolutions when the button covers text. 

  <!-- img/gif -->

* Smooth scrolling is enabled for the whole website for better user experience, it pairs nicely with other transition effects found in all of the other pages.

  <!-- img/gif -->

* CSS Quick Jump Feature was implemented born out of developer's own frustration when searching for a particular line of code in the style.css. The feature enables future user/reviewer/employer/assessor to find exactly what is needed quickly.

  <!-- img/gif -->

### **Future Implementations**

For the future implementations, the developer would like to make 404 error page and the splash/intro page for this project.

The repository of this project was cloned at an earlier point to facilitate content change. In the future the developer would like to make a website exactly like this one but with image content more closely related to the actual Boudoir Photography.

[Back to top ⇧](#boudoir-studio)

---

## Technologies Used

### Languages Used

Make a note here of all the languages used in creating your project. For the first project this will most likely just be HTML & CSS.

### Programs Used

Add any frameworks, libraries or programs used while creating your project.

[Back to top ⇧](#boudoir-studio)

---

## Deployment

Include instructions here on how to deploy your project. For your first project you will most likely be using GitHub Pages.

[Back to top ⇧](#boudoir-studio)

---

## Testing
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

### AUTOMATED TESTING
#### W3C Validator
#### Lighthouse

### ACCESSIBILITY
#### Wave

### MANUAL TESTING
#### Testing User Stories
#### Full Testing

### BUGS
#### Known Bugs
#### Solved Bugs

### Browser compatibility

[Back to top ⇧](#boudoir-studio)

---

## Credits

The Credits section is where you can credit all the people and sources you used throughout your project.

### Code Used

If you have used some code in your project that you didn't write, this is the place to make note of it. Credit the author of the code and if possible a link to where you found the code. You could also add in a brief description of what the code does, or what you are using it for here.

### Content

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say?

###  Media

If you have used any media on your site (images, audio, video etc) you can credit them here.
  
###  Acknowledgments

If someone helped you out during your project, you can acknowledge them here!

[Back to top ⇧](#boudoir-studio)

***