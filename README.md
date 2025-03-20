# Tattoo Studio Website
----------
The purpose of this project was to create a static front-end site to present useful information to fictional users, using all the technologies that I've have learned so far:
* Required: HTML, CSS
* Optional: Bootstrap and/or other CSS libraries/frameworks.


Visit the deployed site [here](https://ceri-jane.github.io/milestone-project-one/index.html) on GitPages 

1. Home page

![Mockup screenshot on different devices - home page](assets/images/multi-device-mockup-home.png)

2. Artists page

![Mockup screenshot on different devices - artists page](assets/images/multi-device-mockup-artists.png)

3. Gallery page

![Mockup screenshot on different devices - gallery page](assets/images/multi-device-mockup-gallery.png)

4. Booking page

![Mockup screenshot on different devices - booking page](assets/images/multi-device-mockup-booking.png)

5. Success page

![Mockup screenshot on different devices - success page](assets/images/multi-device-mockup-success.png)

Contact page

![Mockup screenshot on different devices - contact page](assets/images/multi-device-mockup-contact.png)

----------
## Contents
----------

* [User experience](#user-experience)
    * [User stories](#user-stories)
    * [Site structure](#site-structure)
    * [Wireframes](#wireframes)
    * [Design](#design)


* [Features](#features)
    * [Navigation bar](#navigation-bar)
    

    

* [Technologies Used](#technologies-used)

* [Testing](#testing)

* [Deployment and Development](#deployment-and-development)
    * [Deploying the Site](#deploying-the-site)
    * [Forking the Repository](#forking-the-repository)
    * [Cloning the Repository](#cloning-the-repository)

* [Credits](#credits)
    * [Content](#content)
    * [Code](#code)
    * [Media](#media)

----------
## User experience
----------

### <u>User stories</u>
1. As a first-time visitor, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.
2. As a potential customer, I want to see high-quality images and engaging descriptions of the studio and artists and their work, so I can decide if it's the right place for me to visit.
3. As a prospective Customer, I need to find essential information such as location, contact details, and opening hours clearly and concisely, so I can easily plan my visit or get in touch with the studio.
4. As a customer, I want to book a session using a simple booking inquiry form, so I can easily contact the studio.
5. As a new/existing customer, I want to find clear information about pricing so I can plan my visit within my budget.
6. As a prospective customer, I want to read testimonials and reviews from other customers, so I can gauge the experiences of others and feel more confident about visiting the studio.
7. As a prospective customer, I want to be able to access social media pages for the studio so I can see more artist work and keep up-to-date with the studio events.

----------
### <u>Site structure</u>

1. <u>The navigation bar.</u>

The navigation bar sticks to the top of each page of the Tattoo Studio website with the studio logo and helpful links to navigate through the site.

2. <u>The home page.</u>

The home page is the first and main page of the website and also the 1st link in the navigation bar. The home page holds the primary information along with a photo of the front of the studo, services offered by the studio and customer testimonials. 
For ease of access, users can use the 2nd link in the navigation bar to access the services section on the home page and the 3rd link in the navigation bar to access the testimonials section, also on the home page.

3. <u>The artists page.</u>

The artists page can be accessed by clicking the 4th link on the navigation bar. The user will be taken to a page about the tattoo artists that work at Tattoo Studio. Within this page, the user can find photos and information about each artist, along with their individual social media links. 

4. <u>The gallery page.</u>

The gallery page can be accessed by clicking the 5th link in the navigation bar. The user will be taken to a page with artwork from the artists, along with some information about the artwork.

5. <u>The booking page.</u>

The booking page can be accessed by clicking the 6th link on the navigation bar. The user will be taken to a booking page with a short form to fill out with their details and pick which service the want to book, along with a message or question(s) they may have.

6. <u>The success page.</u>

The success page will appear once the user has successfully submitted their form. This page cannot be accessed by the navigation bar or by any other way other than submitting the booking form successfully. This page has a button to direct the user back to the home page and will automatically re-direct back to the home page after 10 seconds.

7. <u>The contact page.</u>

The contact page can be accessed by clicking the 7th and final link on the navigation menu. The user will be taken to a page with contact details for Tattoo Studio, an embeded and interactive map and opening times, along with a photo of the front of the studio to remind the user what the studio looks like from the outside.

8. <u>The footer.</u>

The footer can be found at the bottom of each page of the Tattoo Studio website. The footer contains links to the studios social media links and holds the studios copyright information.

----------
### <u>Wireframes</u>

Balsamiq was used to created basic wireframes to help plan the layout of each page, and how I wanted it to look across different screen sizes.

1. Home page

![Wireframe screenshot on different devices - home page](assets/images/wireframe-home.png)

2. Artists page

![Wireframe screenshot on different devices - artists page](assets/images/wireframe-artists.png)

3. Gallery page

![Wireframe screenshot on different devices - gallery page](assets/images/wireframe-gallery.png)

4. Booking page

![Wireframe screenshot on different devices - booking page](assets/images/wireframe-booking.png)

5. Success page

![Wireframe screenshot on different devices - success page](assets/images/wireframe-success.png)

6. Contact page

![Wireframe screenshot on different devices - contact page](assets/images/wireframe-contact.png)

----------
### <u>Design</u>

1. <u>Font</u>

![Font familes used for website](assets/images/font-family.png)

The primary font used for the logo and headings is "Rye" with "Cormorant Garamond" as secondary font used for other text.
Rye resembles a common font used for 'old-school' scripture and Cormorant Garmond compliments this well.

2. <u>Colour palette</u>

![Colour palette for website](assets/images/colour-palette.png)

The colour palette was picked using the Tattoo Studio front image along with imagecolorpicker.com.

* Light pink (#bb2e52) is the primary colour used for the navigation bar and footer background colour, along with the Tattoo Studio logo text, main headings and buttons.
* Dark purple (#400a5a) is the secondary colour used for sub-headings, star ratings in the testimonials section, opening times, contact information, social media links and copyright information.
* Cream (#efc8aa) is the colour chosen for the website background.  
* White (#FFFFFF) was used for the background colour in cards to display services, testimonials and artist information - to match the background colour of the Tattoo Studio logo in the navigation bar and the background of the form input areas. 
* Black (#000000) was used for paragraph and navigation text, text in the form, along with the icons used in the contact information area to highlight address, phone number and email.

----------
## <u>Features</u>
----------

### <u>Navigation bar</u>

fixed to the top of all pages is the fully responsive navigation bar which collapses into a hamburger menu on smaller screens. It includes links to each of the pages on the website and internal links within the home page.
It is contained in the header element which is fixed to the top of the viewport, meaning it is accessable to the user, wherever they are on the page/site.

1. Navigation bar on larger screens

![Navigation bar on large screens](assets/images/01-navbar-large.png)

2. Navigation bar hamburger on mobiles device screens

![Navigation bar on mobile device](assets/images/02-navbar-mobile.png)

3. Navigation bar hamburger drop-down on mobile device screens

![Navigation bar on mobile device dropdown](assets/images/03-navbar-mobile-dropdown.png)

4. Navigation bar hamburger on tablet screens

![Navigation bar on tablets](assets/images/04-navbar-tablet.png)

5. Navigation bar hamburger drop-down on tablet screens

![Navigation bar on tablets dropdown](assets/images/05-navbar-tablet-dropdown.png)









