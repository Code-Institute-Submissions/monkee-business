# Stream One Project - Monkee Business #

The purpose of this project is to create a frontend only website for a 60's band using technologies learnt as part of Stream One of the Full Stack Web Developer Course.  The Band have been in circulation for 50 years and wish to highlight their availability to perform at various events, attract new fans and retain current fans by providing access to their news, music and history. 


## UX ##

This website is a platform for fans and newcomers to communicate with the Band, learn about them and engage them to perform at special events.  User Stories are as follows:

* As a user, I want to click on a button to find out more about the band
* As a fan, I want to sign up to a newsletter to stay up to date with the current affairs of the Band
* As a fan, I want to click on a button to hear samples of the band's music
* As a fan, I want to complete a contact form to hire the band or get in touch with them.

## Features ##

I used my learnings from the Code Institute Whiskey Drop and Resume lessons as a basis for this project. In building this website, I decided on a 4-page structure as follows:

1. A Home page with a simple call to action to encourage users to find out more about the band.  A video is playing in the background to give a flavour of what to expect and they click on a button with a link to the actual Monkees website.
2. An About page which introduces users to members of the Band and gives them the opportunity for further information via 'read more'buttons
3. A Music page which consists of a timeline illustrating the longevity of the Band, and their musical achievements spanning 5 decades.  I chose random albums sourced from wikipedia and have used the 4 mp4 tracks interchangeably just to demonstrate the functionality of the audio elements.
4. A Contact page containing a contact form to allow users communicate with the band with a view to hiring them for special events.

The Header and Footer are identical on all pages; the header contains the logo, site name and navigation bar and the footer contains links to the contact form and social media sites such as Facebook, Twitter and YouTube.  The footer also has a newsletter sign up feature which links back to that page on submit as the site is front end only.


### Existing Features ###

* A jumbotron with a video playing on a muted loop as a background and containing a button which allows users to access further information on a click.
* A form allowing users to input their email address to join a mailing list for the newsletter
* A timeline containing audio elements which allows fans to hear the band's music on a click
* A contact form allowing users to input their contact and event details and click the submit button

## Technologies Used ##

* [HTML](https://en.wikipedia.org/wiki/HTML)

The project uses HTML to create the webpages for the website.

* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

The project uses CSS to style the content of the website using layouts, colours and fonts.

* [Bootstrap](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))

The project uses Bootstrap to provide navigation and a grid layout for the website.  It is also used as a source of representational icons (Font Awesome) for ease of navigation. Hover.css is also used to apply special effects to the navigation bar.

* [Google Fonts](https://en.wikipedia.org/wiki/Google_Fonts)

The project uses Google Fonts to achieve a certain look.  I chose the "Concert One, cursive" font to be in tune with the relaxed, fun-loving arty side of the band.

* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

The project uses JavaScript for the interactive aspects of the website, i.e. the contact forms.

## Testing ##

This project was a pain-staking process as I literally tested every change to both HTML and CSS. I began with the header and ran into problems with the logo.  I had initially chosen an image of the band as the logo but this did not respond well when resizing to mobile so I resolved the issue by substituting an image of the Monkees guitar logo. Chrome developer tools were helpful when designing the footer as the content appeared out of line with the rest of the page.  This was resolved by creating a wrapper (footer-container) with 0 padding. I tested that the link to the contact form in the footer was working and ensured there was email validation in the newsletter sign up section.  I verified that links to Social Media were functioning correctly.



## Deployment ##

I went through the process of publishing my site on GitHub pages via the settings in my Monkee-Business repository.

## Credits ##

I would like to thank my mentor, Jim Richmond for his patience and helpful advice.

### Content ###

* The text for the About section was copied from the Wikipedia articles on the Monkees band members and links to these pages are contained therein.  The text for the timeline was obtained from the Wikipedia article on the Monkees discography.
* The jumbotron on the Home page was adapted from a pen by Jacob Lett
* The timeline on the Music page was adapted from a Timeline snippet on [Bootsnipp](https://bootsnipp.com/snippets/k7KxQ)
* The Contact form on the Contact page was adapted from the Code Institute resume project


### Media ###

* The images used in this site were obtained from Code Institute's GitHub Repo and Wikipedia articles relating to the Monkees.
