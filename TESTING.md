# **Boudoir Studio - Testing** 

[Main README.md file](/README.md)

[View live project](https://boiann.github.io/boudoir-studio/index.html)

[View GitHub repository](https://github.com/Boiann/boudoir-studio)

---
## **Contents**
* [Automated Testing](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)

* [Accessibility](#accessibility) 
  * [WAVE WebAim](#wave-webaim) 

* [Manual Testing](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)
    * [Features](#features)
    * [Responsiveness](#responsiveness)

* [Bugs](#bugs)
  * [Known Bugs](#known-bugs)
  * [Solved Bugs](#solved-bugs)

* [Browser Compatibility](#browser-compatibility)      

---

## Automated Testing

### **W3C Validator**
The [W3C Markup Validator](https://validator.w3.org/) service was used to validate the HTML and CSS code used.

Results of the HTML test of [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page"):

![Validator home page test result image](assets/images/readme_images/testing/validator/validation_index.png)

Results of the HTML test of [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"):

![Validator gallery page test result image](assets/images/readme_images/testing/validator/validation_gallery.png)

Results of the HTML test of [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page"):

![Validator about us page test result image](assets/images/readme_images/testing/validator/validation_about.png)

Results of the HTML test of [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page"):

![Validator thank you page test result image](assets/images/readme_images/testing/validator/validation_thanks.png)

Results of the CSS test of [style.css](assets/css/style.css "Link to main style.css file"):

![Validator main css file test result image](assets/images/readme_images/testing/validator/validation_main_css.png)

Results of the CSS test of [thanks_page_style.css](assets/css/thanks_page_style.css "Link to thanks_page_style.css for Thank You Page"):

![Validator thank you css file test result image](assets/images/readme_images/testing/validator/validation_thanks_css.png)

### **Lighthouse**
The performance test of all the pages was done with Lighthouse through Google Chrome Developer Tools, both for desktop and mobile devices.

Lighthouse test results for [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page"):

* Desktop:

![Lighthouse test result image for home page on desktop device](assets/images/readme_images/testing/lighthouse/index_desktop.png)

* Mobile:

![Lighthouse test result image for home page on mobile device](assets/images/readme_images/testing/lighthouse/index_mobile.png)

Lighthouse test results for [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"):

* Desktop:

![Lighthouse test result image for gallery page on desktop device](assets/images/readme_images/testing/lighthouse/gallery_desktop.png)

* Mobile:

![Lighthouse test result image for gallery page on mobile device](assets/images/readme_images/testing/lighthouse/gallery_mobile.png)

Lighthouse test results for [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page"):

* Desktop:

![Lighthouse test result image for about us page on desktop device](assets/images/readme_images/testing/lighthouse/about_desktop.png)

* Mobile:

![Lighthouse test result image for about us page on mobile device](assets/images/readme_images/testing/lighthouse/about_mobile.png)

Lighthouse test results for [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page"):

* Desktop:

![Lighthouse test result image for thank you page on desktop device](assets/images/readme_images/testing/lighthouse/thanks_desktop.png)

* Mobile:

![Lighthouse test result image for thank you page on mobile device](assets/images/readme_images/testing/lighthouse/thanks_mobile.png)

---

## **Accessibility**
### **WAVE WebAim**
The [WAVE WebAIM](https://wave.webaim.org/ "Link to WAVE WebAIM home page") web accessibility evaluation tool was used to check for accessibility standards. All pages pass with zero errors.

Results of the evaluation test of [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page"):

![WAVE WebAim test result image for home page](assets/images/readme_images/testing/wave/wave_index.png)

Results of the evaluation test of [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"):

![WAVE WebAim test result image for gallery page](assets/images/readme_images/testing/wave/wave_gallery.png)

Results of the evaluation test of [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page"):

![WAVE WebAim test result image for about us page](assets/images/readme_images/testing/wave/wave_about.png)

Results of the evaluation test of [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page"):

![WAVE WebAim test result image for home page](assets/images/readme_images/testing/wave/wave_thanks.png)

---

## **Manual Testing**
### **Testing User Stories**

#### **First Time Visitor**
  * **I want to know what Boudoir Photography is**
    * The [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page") contains the needed info even without the user interaction. As soon as the page loads the cover text in the hero image will tell the user what is the Studio about: "Unleash your beauty, celebrate your femininity, discover the new you." This is enough to spark interest in the user and when scrolling down, the user is greeted with a banner text "See For Yourself How Beautiful You Are!" This is another short motivator, followed by a section that explains exactly what Boudoir Photography is. Users interested in more content can learn about Boudoir history and why its benefits, as well as why should the user consider using this business.
  * **I want to navigate the website intuitively**
    * The navigation bar is clearly defined and discernable. As per industry standards, it is located in the upper right section of the header. Hovering over the links in the navigation bar will change in colour and transform in size slightly, adding to the interaction. When selecting another page the user will be shown the active one with changed background. The "Back to Top" button will also appear when the user scrolls down enabling the user to quickly navigate to the top of the page. The button will present itself with a low opacity as to appear non-intrusive to the user, but when hovered over and/or used, it will transition into high opacity colour. The contact link in the navigation bar is present in all pages and quickly leads the user to the contact form.   
  * **I want to find additional information**
    * Using intuitive navigation between all of the pages of the website the user will have access to all the basic information about Boudoir Photography and the business itself. The [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page") acts as a information about Boudoir, the [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page") serves as a photography portfolio expected in this type of business, and the [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page") page is about the team, testimonials and past clients with a FAQ section answering even more questions. The whole website is set up in a way that will enable the user to make an informed decision to use the Studio's services, requiring only a contact to set up the shoot or to ask more questions should the potential client have one. The FAQ is presented in accordion style menu to to increase interaction and aesthetics.
  * **I want to check out the social media of the business**
    * As per industry standards the social media links/icons are present in the bottom/footer area in all of the website pages, enabling the user to quickly discern between the four options; Facebook, Twitter, Youtube and Instagram. All of the links open in a separate tab, and have hover background transition effect to increase interaction and aesthetics.

#### **Returning User**
  * **I want to know about the business owner/team**
    * Users interested in the team behind the business will easily and intuitively navigate to [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page") page where the short biographies and descriptions of the team can be found. To make the team appear more friendly and approachable all of them have a photo of themselves above the bio.  
  * **I want to see the portfolio of the Studio**
    * Users interested in the portfolio of the business will easily and intuitively navigate to [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page") where the gallery consisting of twelve photographs can be found.
   All of the photographs have a slight hover effect applied to them to increase interaction with the user and aesthetics.
  * **I want to know what other people said about the experience with the business**
    * Users interested in testimonials will easily and intuitively navigate to [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page") page where short one-line reviews/testimonials can be found. The testimonials section is indicated to the user in a text banner below the hero image, "Meet our Team, Find Some Answers, See Testimonials..." Testimonials themselves serve to connect the idea of doing Boudoir Photography with real-life former clients with various jobs, age and appearance. This is to put the potential new client at ease and show that Boudoir is truly for all women.
  * **I want to contact the Studio**
    * The contact form is easily navigable using the Contact link in the navigation bar that will automatically scroll to the form section of the page. This feature is present on all the pages. The form requires correct inputs from the user, not allowing the user to submit query without submitting their name and surname, email and text. Upon submitting, the user is rewarded with [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page") page where their query is acknowledged and feedback about reply timeframe is given. There are also two videos to further put the potential client at ease and inform them about Boudoir Photography shoot process. 

#### **Website Owner**
  * **I want to provide basic information about Boudoir Photography and who is it for**
    * The whole website is made with providing all of the info necessary for the potential client to make an informed decision on using this business.
  * **I want potential clients to be able to reach us quickly**
    * The contact process is made to be quick to find, easily accessible and rewarding to the user.
  * **I want to provide our body of work**
    * Whole page, [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"), is dedicated to provide the user with photography portfolio of the business. 
  * **I want potential clients to follow us on social media**
    * The footer section present on all pages serves to provide user with links to the social media of the website.

### **Full Testing**

#### **Features**

**Testing features present on all pages of the website:**

* Navigation bar links hover effect:
![Navigation bar links hover effect gif](assets/images/readme_images/shared/hover_nav.gif)

* Navigation bar links opening pages:
![Navigation bar links opening pages gif](assets/images/readme_images/shared/links_opening.gif)

* Logo link opening and hover effect:
![Logo link opening and hover effect gif](assets/images/readme_images/shared/logo_click.gif)

* Navigation bar contact link scrolling to contact section:
![Navigation bar contact link scrolling to contact section gif](assets/images/readme_images/shared/contact_click.gif)

* Navigation hamburger menu opening and hover effect:
![Navigation hamburger menu opening and hover effect gif](assets/images/readme_images/shared/ham_hover.gif)

* Navigation hamburger menu opening pages:
![Navigation hamburger menu opening pages gif](assets/images/readme_images/shared/ham_click.gif)

* Navigation hamburger menu logo working:
![Navigation hamburger menu logo working gif](assets/images/readme_images/shared/ham_logo_click.gif)

* Navigation hamburger menu contact link scrolling to contact section:
![Navigation hamburger menu contact link scrolling to contact section gif](assets/images/readme_images/shared/ham_contact_click.gif)

* Hero image fixed effect:
![Hero image fixed effect gif](assets/images/readme_images/shared/hero_fixed.gif)

* Contact section hover effect:
![Contact section hover effect gif](assets/images/readme_images/shared/form_hover.gif)

* Map section interaction with the map:
![Map section interaction with the map gif](assets/images/readme_images/shared/map_use.gif)

* Social media icons hover effect:
![Social media icons hover effect gif](assets/images/readme_images/testing/features/general/footer_hover.gif)

* Social media icons opening in a new tab:
  * Facebook:
  ![Facebook opening in a new tab gif](assets/images/readme_images/testing/features/general/open_facebook.gif)

  * Twitter:
  ![Twitter opening in a new tab gif](assets/images/readme_images/testing/features/general/open_twitter.gif)

  * Youtube:
  ![Youtube opening in a new tab gif](assets/images/readme_images/testing/features/general/open_youtube.gif)

  * Instagram:
  ![Instagram opening in a new tab gif](assets/images/readme_images/testing/features/general/open_instagram.gif)

* Back to top button appearing, dissapearing, hover effect
  ![Back to top button appearing, dissapearing, hover effect gif](assets/images/readme_images/shared/back_to_top_working.gif)

**Testing features present on specific pages of the website:**

 * [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page"):
   * Wiki link for named artist in Boudoir History opening in a new tab
   ![Wiki link opening in a separate tab gif](assets/images/readme_images/testing/features/specific/index_link_opening.gif)

* [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"):
  * Gallery images hover effect:
  ![Gallery images hover effect gif](assets/images/readme_images/testing/features/specific/gallery_hover_effect.gif)

* [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page"):
  * FAQ section accordion and hover effect:
  ![FAQ section accordion and hover effect gif](assets/images/readme_images/testing/features/specific/faq_accordion_working.gif)

* [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page"):
  * Controls present and no autoplay on videos, back to home link animation and opening home page working:
  ![Thank you page video controls, animation and link opening gif](assets/images/readme_images/testing/features/specific/thanks_content.gif)

#### **Responsiveness**

Responsiveness of the whole website was thoroughly tested for devices up to 320px wide. 
The website still works on a device 230px wide, with visible problems with footer social media icons below that width.

Responsiveness test for each page:
* [Home page](https://boiann.github.io/boudoir-studio/index.html "Link to Boudoir Studio home page"):
  ![Home page responsiveness image](assets/images/readme_images/testing/responsive/responsive_index.gif)

* [Gallery page](https://boiann.github.io/boudoir-studio/gallery.html "Link to Boudoir Studio gallery page"):
  ![Gallery page responsiveness image](assets/images/readme_images/testing/responsive/responsive_gallery.gif)   

* [About Us page](https://boiann.github.io/boudoir-studio/about.html "Link to Boudoir Studio about us page"):
  ![About us page responsiveness image](assets/images/readme_images/testing/responsive/responsive_about.gif)  

* [Thank You page](https://boiann.github.io/boudoir-studio/thanks.html "Link to Boudoir Studio thank you page"):
  ![Thank you page responsiveness image](assets/images/readme_images/testing/responsive/responsive_thanks.gif)

---

## **Bugs**

### **Known Bugs**

* Bug reported by Boris B. (developer's brother):
On his mobile phone Samsung Galaxy A30s there are no pop-up warnings about missing name/surname/email/text when trying to submit contact form.
The form is still working as expected (not allowing submission) but the notifications are absent.
Upon about it the developer spent time on Google and Stack Overflow but has failed to come to a satisfactory answer/fix. 

The bug however, is not present on any other devices used to check the form: Samsung Galaxy A50, Samsung Galaxy A51, Samsung Galaxy S8+.
The bug is also absent when using Chrome Developer Tools Device Toolbar.

Due to the nature of the bug, the developer feels it is safe to proceed with finalization of the project. 

### **Solved Bugs**

There were many bugs/issues encountered during the development of this website. The major ones are listed below.
All of them were solved with [Google](https://google.com/ "Google home page") and in most cases with the help of the community on [Stack Overflow](https://stackoverflow.com/ "Stack Overflow home page") website.

* Images display issue with images not displayed properly or distorted. 
* Map issue with trying to have the interactive map working and display properly.
* Video embedding issue when trying to have it working and display properly. Problem was caused mostly with the design choice by the developer choosing to have two videos side by side.
* Images not loading when the website was published, fix visible from commits for this project repository named "Fix image paths for website deployment." The bug was was caused by not investigating the issue properly and multiple attempts to fix the issue were made without refreshing the cache and resetting internet connection.
* Bug with Javascript integration in the project. The developer was writing the Javascript code into the head of the HTML files, thinking that is where it belongs. Numerous hours later, tens of Javascript code tryouts and finally investigating in Chrome Developer Tools the developer found out the script should be at the bottom of the HTML code, at the end of the body section. The solution was found here: https://bobbyhadz.com/blog/javascript-cannot-read-property-style-of-null#:~:text=To%20resolve%20the%20%22Cannot%20read,the%20getElementById%20method%20returns%20null%20.
* Issue raised when using [WAVE WebAIM](https://wave.webaim.org/ "Link to WAVE WebAIM home page") tool to check the website accessibility. The test showed one error: missing label for the text area in the form. The developer applied a quick fix without properly investigating the issue, visible from multiple commits needed. After proper investigation correct label was implemented and styled into the website.
* Issues raised by Kate L_5P from slack community when presenting this project for peer review:
"This is a nicely styled site, really clean. My only feedback would be that the images take a little while to load so you might find (if you haven't done it yet) that your lighthouse scores for performance might be affected. Maybe think about converting them to webp files?
I really like the burger menu on smaller devices too but I think maybe there could be a tad more spacing between the background shadow and the burger menu icon (see pic)."
The spacing was corrected and the images converted to webp format as per advice.
---

## **Browser compatibility**
The website was tested on the following browsers with no issues found:

* Google Chrome:
![Chrome browser in use image](assets/images/readme_images/testing/browsers/chrome.png)

* Mozzilla Firefox:
![Firefox browser in use image](assets/images/readme_images/testing/browsers/firefox.png)

* Microsoft Edge:
![Edge browser in use image](assets/images/readme_images/testing/browsers/edge.png)

* Opera Browser:
![Opera browser in use image](assets/images/readme_images/testing/browsers/opera.png)

---

[Back to top ???](#boudoir-studio---testing)