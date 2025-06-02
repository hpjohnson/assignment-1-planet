# Perfect Planet

![Perfect Planet - Project Banner](/readme/project-banner.webp)

<p align="center"><a href="https://hpjohnson.github.io/assignment-1-planet/" target="_blank">Live Project</a></p>

## Introduction
Perfect Planet is my first portfolio project, developed following the Code Institute Full Stack Development Bootcamp using HTML, CSS, and Bootstrap. It was developed following a set of guidelines, and topic chosen from a list of four.

## Project Outline
Perfect Planet was developed as a mental health awareness website, appropriate for all ages. General advice is given, a list of resources which should encompass people of all ages, and a form allowing the user to contact the website creators for questions. 

The website follows modern accessibility standards, and is responsive to devices of all screen sizes.

## Table of Contents

* [Perfect Planet](#perfect-planet)
    - [Introduction](#introduction)
    - [Project Outline](#project-outline)
    - [Table of Contents](#table-of-contents)
* [UX Design](#ux-design)
    - [User Stories](#user-stories)
    - [Colours](#colours)
        - [Colours Used](#colours-used)
    - [Imagery and Theming](#imagery-and-theming)
    - [Font](#font)
    - [Wireframes](#wireframes)
* [Features](#features)
    - [General Features](#general-features)
        - [Navigation](#navigation)
        - [Hero](#hero)
        - [Information Cards](#information-cards)
        - [Resource Links](#resource-links)
        - [Positive Affirmations](#positive-affirmations)
        - [Buttons](#buttons)
        - [Footer](#footer)
    - [Contact Page](#contact-page)
    - [Responsive Design](#responsive-design)
* [Deployment and Tools](#deployment-and-tools)
    - [Deployment](#deployment)
    - [Tools](#tools)
        - [Languages](#languages)
        - [Libraries and Frameworks](#libraries-and-frameworks)
* [Testing and Validation](#testing-and-validation)
    - [Index](#index)
    - [Contact](#contact)
    - [Success](#success)
    - [CSS](#css)
* [AI Usage and Implementation](#ai-usage-and-implementation)
    - [AI Code Generation](#ai-code-generation)
    - [AI Debugging](#ai-debugging)
    - [AI Optimisation](#ai-optimisation)
    - [Reflection on AI Usage](#reflection-on-ai-usage)
* [References and Credits](#references-and-credits)
# UX Design

## User Stories
As the website owner, I want a website that is accessible to all.

As a visitor to the website, I want to have some basic introductory information so that I may learn about mental health.

As a parent, I want to be able to find resources appropriate for my child.

As a *person of certain age* I want to be able to find resources that I will be able to use.

As a person who is interested in learning more about mental health, I want to be able to contact the owner so that I can ask them more questions.

As a person who is interested in contacting the owner, I want to be certain that no data I send will be shared with third parties. 

## Colours

I wanted to choose a calming colour scheme, as mental health can be a tricky subject to navigate. Therefore, I chose a website where all the main content used nice, muted, pastel colours. Going along with the theme of planets and space, I chose blues, purples, and pinks, with green for highlights. In order to make meta content (ie the header, footer and buttons) stand out from the main content, I chose more saturated colours. Considering the content of the website and its contact section, I thought it best to include a warning that it is not appropriate to contact the website in case of emergency, and instead you should contact an appropriate agency. To make this stand out, I chose a fairly bright red.

The website passes the [WAVE](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) contrast checker on all pages, as well as the [Colour Contrast Checker](https://colourcontrast.cc/).

### Colours Used

- Russian Violet `#3d1047`
- Oxford Blue `#060348`
- Uranian Blue `#b7e1ff`
- Mint Green `#a1ffb2`
- Mauve `#dfa9ff`
- Pale Purple `#f7eeff`
- Pink Lace `f0d5f6`
- Cinnabar `#e0463b`

![Colour Contrast Checker Results](/readme/contrast-check.gif)

## Imagery and Theming

The primary reason I chose a space theme was simply because it was the first theme I though of. However, I do think it is appropriate in the sense that staring up and looking to the stars is quite relaxing - which is a theme I wanted for the website due to mental health being a heavy topic. I chose a nice image of some planets for the banner, and astronaut characters elsewhere, as they seemed appropriate. 

I used [paint.net](https://www.getpaint.net/) to change the background colour of the images for consitency, and [Squoosh](https://squoosh.app/) to compress and convert the images to webp.

The images were sourced from [Freepik](https://www.freepik.com/), following their [attribution policy](https://support.freepik.com/s/article/Attribution-How-when-and-where?language=en_US).

## Font

I chose a single rounded font for the website that matches up with the rounded corners on all the main content, called [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand), sourced from [Google Fonts](https://fonts.google.com/).

 The font is consistent for all the text on the website. The titles are distinguished by being larger, having a higher font weight, and the text colour having a slight gradient.

 ## Wireframes

 Wireframes were designed using [Balsamiq](https://balsamiq.com/). The final design of the website is slightly different than that of the wireframes, primarily in that the section background colours do not extend to the edges of the page, and the removal of a central image for extremely large screens. The changes were made as I think the website looks nicer this way.

 <p><a href="/readme/wireframes.webp" target="_blank">Click to view wireframes</a></p>

# Features

## General Features

Features were added following the rubrick as guidance, with deviations as appropriate. [Boostrap](https://getbootstrap.com/docs/5.3/getting-started/download/) was used for responsive design, and for a couple of useful components.

### Navigation

A standard [Bootstrap navbar](https://getbootstrap.com/docs/5.3/components/navbar/) is used for navigation, as it has a familiar layout which is good for user experience.

### Hero

The hero image does not use a [Bootstrap jumbotron](https://getbootstrap.com/docs/5.3/examples/jumbotron/) as requested, rather a custom implementation. Instead of including a positive message here, I moved it to the end of the page and combined it with the positive affirmations outlined. In its place is an appropriate tagline for the website. 

### Information Cards

As requested, [Boostrap cards](https://getbootstrap.com/docs/5.3/components/card/) were used to display content about symptoms and tips.

### Resource Links

[Boostrap cards](https://getbootstrap.com/docs/5.3/components/card/) were used for the links to external resources, as they are simple to use. Big, contrastful buttons that stand out are placed on each card that link to the appropriate page.

### Positive Affirmations

Instead of a list of commonly used quotes or generic positive messages that have lost all meaning, I chose to merge the encouraging message requested in the hero section with this section. On the website, this section is titled "Words of Encouragement".

### Buttons

Buttons and clickable icons are coloured to contrast with the background. They have a simple hover effect in which they change colour and enlarge slightly.

### Footer

The footer contains links to social media websites, a link to the creators github, and the required credit for the stock images.

## Contact Page

The website includes a contact form on a seperate page, as its content is markedly different than the rest. There is a link to the contact page in the header in the index, and later in the page. The contact button turns green when on the contact page. A message outlining that the form is not for emergency contact along with a red warning is included, as well as a statement reassuring the user that none of the information they enter will be shared with outside parties.

The form has HTML validation ensuring it is filled, and once successfully submitted a new page is opened letting the user know their inquiry has been successful. The success page includes a button to return to the main page.

## Responsive Design

[Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/download/) was used to make the website responsive to a modern standard on all screen sizes.

I used some custom media queries to fix issues with padding and margins arising from text lengths, along with hiding images on smaller screens where they only serve to make the website take longer to scroll.

# Deployment and Tools

## Deployment

The website uses [GitHub Pages](https://pages.github.com/) for hosting, and was coded using [VSCode](https://code.visualstudio.com/).

## Tools

### Languages
![Static Badge](https://img.shields.io/badge/HTML5-Language-grey?logo=html5&logoColor=%23ffffff&color=%23E34F26)
![Static Badge](https://img.shields.io/badge/CSS3-Language-grey?logo=css3&logoColor=%23ffffff&color=%231572B6)

### Libraries and Frameworks
<a href="https://getbootstrap.com/docs/5.3/getting-started/download/" target="_blank">![Static Badge](https://img.shields.io/badge/Bootstrap-v5.3.6-grey?logo=bootstrap&logoColor=%23ffffff&color=%237952B3)</a>
<a href="#" target="_blank">![Static Badge](https://img.shields.io/badge/Font_Awesome-Icons-grey?logo=fontawesome&logoColor=%23ffffff&color=%23538DD7)</a>
<a href="#" target="_blank">![Static Badge](https://img.shields.io/badge/Google_Fonts-Fonts-grey?logo=googlefonts&logoColor=%23ffffff&color=%234285F4)</a>

# Testing and Validation

Testing was done during project creation using the [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) addon for obvious bugs, and Chrome Dev Tools as necessary (for example, where a specific amount of pixels of padding/margin were needed).

I used the following [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/#validate_by_uri) validators to check for any problems with my code, and [Autoprefixer](https://autoprefixer.github.io/) to ensure all browser Compatibility. [WAVE](https://wave.webaim.org/) was used for accessibility, and Google's Lighthouse built into Chrome dev tools for best practices and optimisation.

## Index

![Index HTML](/readme/index.PNG)
![Index WAVE](/readme/index-wave.PNG)
![Index Lighthouse](/readme/index-lighthouse.PNG)

## Contact

![Contact HTML](/readme/contact.PNG)
![Contact WAVE](/readme/contact-wave.PNG)
![Contact Lighthouse](/readme/contact-lighthouse.PNG)

## Success

![Success HTML](/readme/success.PNG)
![Success WAVE](/readme/success-wave.PNG)
![Success Lighthouse](/readme/success-lighthouse.PNG)

## CSS

![CSS Validation](/readme/css.PNG)

# AI Usage and Implementation

As requested by Code Institute, I have to include a statement on how AI was used in this project. 

AI was not used in this project for the reasons stated below.

## AI Code Generation
This website is very simple in terms of code, and as such using AI to generate any part of it was slower than just manually writing it with the usage of [Emmet](https://emmet.io/). I tested this myself, by first creating one of the sections (the "Introduction to Mental Health Information" section) manually with all the necessary styles, and then creating a second section (the "External Resources" section) using copilot. It took far longer to formulate a prompt that would create the design I wanted and make any necessary changes than it took me to make the other section manually.

## AI Debugging
In order to not leave myself with large amounts of bugs to fix after all content was implemented, I fixed bugs as I noticed them whilst coding. With the usage of the [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) addon this was simple, and it would have been far slower to ask AI to do it for me. Chrome dev tools were used to get exact pixel amounts for padding adjustment. [WAVE](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) quickly pointed out any accessibility issues, and these were all simple to fix manually. 

## AI Optimisation
After uploading the project to GitHub and using GitHub Pages for hosting, I used Google's Lighthouse tool built into dev tools to check for optimisation issues. There were no optimisation issues. Therefore AI was not needed here.

## Reflection on AI Usage

AI was useless for this project. It was unnecessary, unwieldy, and slow for my use case. Prompts took longer to create than just writing the code manually. For a topic as important and personal as mental health, using AI to generate the website content is incredibly innapropriate - and on a personal level I do not wish to contribute to the rising amount of AI slop dumped onto the internet. Non-AI generated images were chosen for the website, as AI generated images look unprofessional and cheap, along with their method of generation being of dubious morality. In additon, I know plenty of people that will immediately close a website if they suspect AI usage, however no person is going to use a website specifically because it was AI generated. Therefore, I had good reason to use real artwork by real artists for my project.

# References and Credits

- Project brief and learning materials by [Code Institute](https://codeinstitute.net/)
- [Bootstrap 5.3 Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Stock images from [Freepik](https://www.freepik.com/)
- Favicon generated by [favicon.io](https://favicon.io/)
- Colour palatte partially created with help from [Coolors](https://coolors.co/)
- README badges by [Shields.io](https://shields.io/badges/static-badge) and [Simple Icons](https://simpleicons.org/)