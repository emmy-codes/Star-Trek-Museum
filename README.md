# Star Trek Museum - Project 1

The Star Trek Museum is an imaged museum detailing the exhibitions available for fans of the franchise.

 ((( Add an image of the finished site here on https://ui.dev/amiresponsive )))

((( Add a link to the live site here upon completion )))

(( If you want to add optional [shields.io](https://shields.io) badges to your README, I like to add them to this section. ))

---

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)
    * [New Users](#new-users)
    * [Experienced Users](#experienced-users)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
    * [Homepage](#homepage)
    * [Page: Star Trek Crews](#page-star-trek-crews) 
    * [Exhibition: Starships](#exhibition-starships)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

### User Stories

#### New Users:

The landing page will more geared towards new visitors and / or those new to Star Trek and wanting to know more. There will be clean and inviting information on what the visitor can expect to experience by visiting the museum by following the CTAS / links provided, as well as an image from each of the exhibitions to cultivate curiosity to learn more.

#### Experienced Users:

By experienced users I mean those that have visited the museum before and / or are fans of the Trek franchise and need less guidance on the page.

The other areas of the site will start with a short blurb about what the visitor will find on this page, followed by a couple of images from the museum alongside a short text. The idea is to pique the visitor's interest so they want to visit the museum. 

* Both pages will have short pieces of text, so as to help the visitor digest the information without being overwhelmed.

* Too many images can slow the loading of the webpage, so I will be limiting to one per paragraph/section.

* Each page will have a CTA that leads to the "how to get here" page to help steer traffic towards visiting the museum.

## Design

### Colour Scheme

The colour scheme is pre-determined with a variety of colours, I shall try to pick a few main colours from this large list that will be both UX/accessibility friendly but making the page look as Trek as possible.

This large colour palette is the LCARS (or Library Computer Access/Retrieval System) is the operating system used on most Trek series so any visitor familiar with the franchise will instantly recognise it. The challenge will be to make it as friendly for non Trek visitors/take into account any accessibility needs.

<div align="center">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/d85bec30-3a3c-4284-ab35-57810db8e2a8" width="" height="" alt="Star Trek LCARS colour palette with 36 colours">
</div>

### Typography

Doing some research I discovered a Tweet that Mike Okuda, the graphic designer who created the LCARS theme, said that the Swiss 911 font was chosen although he preferred Helvetica Ultra Compressed.

<div align="center">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/cb0853e5-fc06-4231-8475-72f2edb41fdf" width="300" height="250" alt="Tweet from Mike Okuda confirming the use of Swiss 911 font for LCARS">
</div>

I had a look at these two fonts and agree that the Helvetica looks better as it is not as thick as Swiss 911, but the letters are very close together which is how they are on the LCARS system but for the sake of accessibility and UX I think they should have more spacing between them.

Seeing as this is not a regular font most people will have on their computers, I researched what Google Font could be a suitable alternative and have decided to use Antonio. This will ensure the page has a proper Trek feel to it without people needing special font packages installed. 

Taking a look at the example LCARS screen below, I decided 700 weight could be good for main titles, while 400 works nicely in sizes 48px for headings, and 21px and 16px for paragraphs/other text.

<div align="center">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/ae757fa7-9171-4c85-bc84-9e2125893738" width="" height="" alt="Example of an LCARS interface from the Engineering department">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/d9d344b4-3ca1-4135-91ad-b16f012e73f2" width="" height="" alt="Antonio font 700 weight, size 48 pixels">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/fd5c89d1-e2d4-4d7c-901c-08a4d6ffc062" width="" height="" alt="Antonio font 400 weight, size 48 pixels">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/10b38372-9863-4938-9d09-e90d9170ab71" width="" height="" alt="Antonio font 400 weight, size 21 pixels">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/4c4369ac-8636-4c15-9d85-1eedcf87f84f" width="" height="" alt="Antonio font 400 weight, size 16 pixels">
 </div>

### Imagery

During my research I came across a favicon of a Star Trek badge that I plan on using on each page: <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/65ab9634-8241-4687-b2b9-5a961057c6be" width="50px" height="50px" alt="Pixelated favicon of a gold and white Star Trek badge">

#### Homepage


<img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/58808344-6591-4ad4-ac8b-6b0f8a1f4f09" width="" height="" alt="Star Trek Pride selection of starships with various pride flags">

#### Page: Star Trek Crews

This page will have 3 of the many different Trek crews due to time constraints, so I went researching to find 3 images as similar to oneanother as possible. Luckily through [IMDB](https://www.imdb.com/ "IMDB main page") each of the 3 Trek pages have identical crew artwork which will help improve the UX/UI of the page. On this page, there is the possibility to link the other pages onto here. (in the blurb for one crew there could be links to the starship exhibition)

<div align="center">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/999e3d8e-5de5-43a3-ad79-a08129b2cdc2" width="250" height="300" alt="Crew of Star Trek: Voyager">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/969309a6-0c91-4fe6-b1ee-28b8e438ada3" width="250" height="300" alt="Crew of Star Trek: Deep Space Nine">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/79987d51-d90b-4b87-abac-499051bc2a75" width="250" height="300" alt="Crew of Star Trek: The Next Generation">
</div>

#### Exhibition: Starships

Similar to the crews page there will be details on the ship exhibition at the museum:

<div align="center">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/7fa1ab64-6bf5-4b36-8976-ab70577c9b7d" width="300" height="250" alt="Starship Voyager">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/f310ba4f-dd88-4c56-9861-1ca1d0acd66d" width="300" height="250" alt="Space station Deep Space Nine">
 <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/1331361a-e1f1-4a47-b24b-7f2f1370496b" width="300" height="250" alt="Starship Enterprise">
</div>

### Wireframes

<img src="" width="" height="" alt="">

## Features

👩🏻‍💻 View an example of a completed user experience section [here](https://github.com/kera-cudmore/TheQuizArms#Features)

This section can be used to explain what pages your site is made up of.

### General features on each page

If there is a feature that appears on all pages of your site, include it here. Examples of what to include would the the navigation, a footer and a favicon.

I then like to add a screenshot of each page of the site here, i use [amiresponsive](https://ui.dev/amiresponsive) which allows me to grab an image of the site as it would be displayed on mobile, tablet and desktop, this helps to show the responsiveness of the site.

### Future Implementations

What features would you like to implement in the future on your site? Would you like to add more pages, or create login functionality? Add these plans here.

### Accessibility

Be an amazing developer and get used to thinking about accessibility in all of your projects!

This is the place to make a note of anything you have done with accessibility in mind. Some examples include:

Have you used icons and added aria-labels to enable screen readers to understand these?
Have you ensured your site meets the minimum contrast requirements?
Have you chosen fonts that are dyslexia/accessible friendly?

Code Institute have an amazing channel for all things accessibility (a11y-accessibility) I would highly recommend joining this channel as it contains a wealth of information about accessibility and what we can do as developers to be more inclusive.

## Technologies Used

👩🏻‍💻 View an example of a completed Technologies Used section [here](https://github.com/kera-cudmore/Bully-Book-Club#Technologies-Used)

### Languages Used

Make a note here of all the languages used in creating your project. For the first project this will most likely just be HTML & CSS.

### Frameworks, Libraries & Programs Used

Add any frameworks, libraries or programs used while creating your project.

Make sure to include things like git, GitHub, the program used to make your wireframes, any programs used to compress your images, did you use a CSS framework like Bootstrap? If so add it here (add the version used).

A great tip for this section is to include them as you use them, that way you won't forget what you ended up using when you get to the end of your project.

## Deployment & Local Development

👩🏻‍💻 View an example of a completed Deployment & Local Development section [here](https://github.com/kera-cudmore/TheQuizArms#Deployment)

### Deployment

Include instructions here on how to deploy your project. For your first project you will most likely be using GitHub Pages.

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

Place instructions on how to fork your project here.

#### How to Clone

Place instructions on how to clone your project here.

## Testing

Start as you mean to go on - and get used to writing a TESTING.md file from the very first project!

Testing requirements aren't massive for your first project, however if you start using a TESTING.md file from your first project you will thank yourself later when completing your later projects, which will contain much more information.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

## Credits

👩🏻‍💻 View an example of a completed Credits section [here](https://github.com/kera-cudmore/BookWorm#Credits)

The Credits section is where you can credit all the people and sources you used throughout your project.

### Code Used

If you have used some code in your project that you didn't write, this is the place to make note of it. Credit the author of the code and if possible a link to where you found the code. You could also add in a brief description of what the code does, or what you are using it for here.

### Content

Who wrote the content for the website? Was it yourself - or have you made the site for someone and they specified what the site was to say? This is the best place to put this information.

###  Media

If you have used any media on your site (images, audio, video etc) you can credit them here. I like to link back to the source where I found the media, and include where on the site the image is used.
  
###  Acknowledgments

If someone helped you out during your project, you can acknowledge them here! For example someone may have taken the time to help you on slack with a problem. Pop a little thank you here with a note of what they helped you with (I like to try and link back to their GitHub or Linked In account too). This is also a great place to thank your mentor and tutor support if you used them.
