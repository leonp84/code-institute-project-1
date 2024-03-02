# SmokeStack Society

Welcome to the Readme file for the business website of **SmokeStack Society**, based in Linz, Austria.

## Table of Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Features](#features)
  - [Existing Features](#existing-features)
    - [Site Logo](#site-logo)
    - [Header and Navigation Bar](#header-and-navigation-bar)
    - [Hero Section](#hero-section)
    - [Motivational Boxes](#motivational-boxes)
    - [Information Boxes](#information-boxes)
    - [Footer](#footer)
    - [Sign Up Page](#sign-up-page)
    - [Customer Testimonials](#customer-testimonials)
  - [Future Ideas](#future-ideas)
- [Testing](#testing)
  - [Validator Testing](#validator-testing)
  - [Accessibility Testing](#accessibility-testing)
  - [Bugs](#bugs)
      - [Fixed](#fixed)
      - [Unfixed](#unfixed)
- [Deployment](#deployment)
  - [Links](#links)
- [Credits](#credits)
  - [Content](#content)
  - [Media](#media)


## Overview

SmokeStack Society is the business website of a (fictional) for-profit cooking class hosted in Linz, Austria. The site is designed with prospective customers in mind, with the primary purpose of convincing visitors to **sign up for a cooking class**. The entire site funnels visitors towards the sign-up page and the various layouts were designed, and content written, to motivate visitors to sign up.

## Screenshots

The site is responsive across all screen sizes, the primary break point for layout adjustment is 768px. The site looks most visually appealing in cell phone and tablet (portrait) format.

![alt text](assets/images/readme-images/website-mockups.webp)

## Features

The site consists of a main landing page and two additional pages.

### Existing Features

#### Site Logo

The site logo was designed by myself using the Impact Font, an online image (all mentioned images are credited [below](#credits)) and artistic effects included in Microsoft PowerPoint.

![alt text](assets/images/readme-images/readme-logo.webp)

#### Header and Navigation Bar

The simple header uses a dark background, inline with the site colour palette, with the logo positioned left, and a simple text navigation bar, positioned oi the right. The Header is fully responsive.

![alt text](assets/images/readme-images/readme-navbar.webp)

#### Hero Section

The Main (Hero) image forms the basis for the site’s colour palette, and the image is employed to be as salient for prospective customers as possible. The wording in the tagline serves a similar purpose.

![alt text](assets/images/readme-images/readme-hero.webp)


#### Motivational Boxes

The four motivational boxes contain images and text to again motivate customers to take part in the cooking class. The various benefits of class participation are outlined clearly. 

![alt text](assets/images/readme-images/readme-motivation-boxes.webp)


#### Information Boxes

Unlike the motivational boxes, the information boxes (further down the main landing page) contain only snippets of information about the class and signup procedure. This was done to address the most immediate objections/questions that customers might have to signing up.

![alt text](assets/images/readme-images/readme-information-boxes.webp)


#### Footer

The footer contains the (fictional) business’ social media links that each open in a new browser window to prevent the prospective customer from navigating away from the site, before signing up. Copyright text is also included at the bottom of the footer. The Footer is fully responsive.

![alt text](assets/images/readme-images/readme-footer.webp)


#### Sign Up Page

The sign-up page is where the critical transaction will hopefully take place. This page uses a unique background to create a positive impression of the potential desirable experience a customer can expect when signing up. The sign-up form is not bloated but asks the prospective customer for minimal information. The form uses validation to prevent spam or false signups.

![alt text](assets/images/readme-images/readme-signup-page.webp)


#### Customer Testimonials

Testimonials of past (fictional) customers are presented on a separate page to further encourage visitors to sign up. An additional sign-up button is presented at the bottom of the page, after the testimonials have been read.

![alt text](assets/images/readme-images/readme-stories-page.webp)


### Future Ideas

Adding photos of said customer next to his/her testimonial would further enhance the effectivity of the tactic, but fell outside the scope of this project. Future implementation remains viable.

## Testing

The site was extensively tested among varies screen sizes of different heights/widths to check for layout breakage. All internal and external links were checked to be working.

### Validator Testing

- HTML
No errors were returned when passing through the official W3C validator. The results for the individual HTML files are below.
  - [index.html HTML Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleonp84.github.io%2Fcode-institute-project-1%2F)<br>
  - [cooking-class-sign-up.html HTML Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleonp84.github.io%2Fcode-institute-project-1%2Fcooking-class-sign-up.html)<br>
  - [cooking-class-testimonials.html HTML Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleonp84.github.io%2Fcode-institute-project-1%2Fcooking-class-testimonials.html)<br>

- CSS
No errors were returned when passing through the official W3C (Jigsaw) validator.
  - [style.css Jigsaw Validator Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fleonp84.github.io%2Fcode-institute-project-1%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Accessibility Testing

The site was checked with [Web Accessibility Checker](https://websiteaccessibilitychecker.com/checker/index.php) and two known problems were presented, which were ignored since they were deemed insignificant. These were:

1.   i (italic) element used
2.   Anchor contains no text


### Bugs

#### Fixed

The major bug that took the most time to correct was that the `main` sections of each page was not responding properly when screen *height* was adjusted. I tried dealing with this through a variety of solutions, but ended up using the layout design of the [Love Running Walkthrough]( https://github.com/Code-Institute-Solutions/love-running-v3/blob/main/3.2-add-stylesheet-with-starter-styles/assets/css/style.css) Project from Code Institute, by using flexbox styling in the `body` section of the pages and adding the following code (copied from the above project) to the `main` sections of the page:

`flex: 1 o auto;`

#### Unfixed

On specific non-standard screen widths (around 650px) the testimonial page layout is not optimal since the sign-up button jumps to the right of the final testimonial, instead of staying below. This was deemed minor enough to be left unfixed since it does virtually no disservice to the page’s purpose.

## Deployment

The site was deployed using GitHub pages and a live version is available for viewing. The GitHub repository contains a history of the commits made during development.

### Links

Deployed Website: https://leonp84.github.io/code-institute-project-1/ <br>
GitHub Repository: https://github.com/leonp84/code-institute-project-1

## Credits

### Content

-	General design and content inspiration from the [Love Running Walkthrough Project](https://github.com/leonp84/love-running) from Code Institute.
-	General design inspiration from [Jim & Nicks Community BBQ]( https://www.jimnnicks.com/baby-back-ribs/) restaurant site.
-	The following fonts were provided by [Google Fonts]( https://fonts.google.com): "Bebas Neue", "Josefin Sans", "Roboto"
-	Website Colour Palette generated with [coolors.co](http://www.coolors.co)
-	Readme file layout and table of contents inspired (and partially adapted) from a project I completed on [FrontendMentor](https://github.com/leonp84/fm3-recipe-page/blob/main/README.md?plain=1)

### Media

-	Favicon image from [deviantart.com]( https://www.deviantart.com/superawesomevectors/art/Barbecue-Grill-Flat-Vector-643400962) (Creative Commons Licence) 
-	Favicon image and data Generated with [favicon.io](https://favicon.io/favicon-converter/)
-	SmokeStack Society Logo: My own design using the Impact Font, an [online product image]( https://m.media-amazon.com/images/I/51RnO8pxLxL._AC_UF350,350_QL80_.jpg) (licence unknown) and Artistic Effects provided by Microsoft PowerPoint.
-	Social Media icons (footer) and icons in the information boxes on index.html provided by [Font Awesome](http://www.fontawesome.com)
-	All images in `assets/images` were (except for `logo.png`) were purchased and adapted from [Adobe Stock]( https://stock.adobe.com/at/)





