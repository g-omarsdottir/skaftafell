# Skaftafell

Skaftafell Nature Reserve is located in the south-west of Iceland at the foot of the largest glacier in Europe, Vatnajökull. This website offers English speaking people, who are interested in hiking in Iceland, an overview of hiking trails in Skaftafell, that are possible to hike without climbing gear. Images depicting the highlight of each trail complement the detailed trail descriptions.

![Am I Responsive](documention/am-I-responsive.png)

[View Skaftafell live project here](https://g-omarsdottir.github.io/skaftafell/)

![last-commit](https://img.shields.io/badge/last_commit-january_2024-green)
![contributors](https://img.shields.io/badge/contributors-1-ff69b4)
![languages](https://img.shields.io/badge/languages-2-yellow)
![html-percentage](https://img.shields.io/badge/html-99.3%25-blue)
![w2c-validated](https://img.shields.io/badge/w3c-validated-orange)




## Table of Contents

### [User Experience (UX)](#user-experience-ux-1)
- #### [Key Information](#key-information-1)
- #### [First Time Visitors Goals](#first-time-visitors-goals-1)
- #### [Returning Visitors Goals](#returning-visitors-goals-1)
- #### [Frequent Visitor Goals](#frequent-visitor-goals-1)

### [Design](#design-1)
- #### [Color Scheme](#color-scheme-1)
- #### [Color Contrast Check](#color-contrast-check-1)
- #### [Typography](#typography-1)
- #### [Imagery](#imagery-1)
- #### [Wireframes](#wireframes-1)

### [Features](#features-1)
- #### [Existing Features](#existing-features-1)
- #### [Features Left to Implement](#features-left-to-implement-1)

### [Accessibility](#accessibility-1)

### [Technology Used](#technology-used-1)
- #### [Languages Used](#languages-used-1)
- #### [Frameworks, Libraries, and Programs Used](#frameworks-libraries-and-programs-used-1)

### [Testing](#testing-1)
- #### [Validator Testing](#validator-testing-1)
- #### [Manual Testing](#manual-testing-1)

### [Bugs](#bugs-1)
- #### [Known Bugs](#known-bugs-1)
- #### [Resolved Bugs](#resolved-bugs-1)

### [Deployment and Local Development](#deployment-and-local-development-1)
- #### [Github Pages](#github-pages-1)
- #### [Local Clone](#local-clone-1)

### [Credits](#credits-1)
- #### [Content](#content-1)
- #### [Media](#media-1)
- #### [Imagery](#imagery-1)
- #### [Acknowledgements](#acknowledgements-1)

## User Experience (UX)

### Key Information
- A selection of hiking trails that do require neither experience nor climbing gear.
- Detailed trail descriptions supported by images of one of the highlights of each hiking trail and a map of the area.
- A selection of photographs from the area to give an impression of what the nature reserve has to offer.
- A contact form to allow users to ask questions about the nature reserve and the hiking trails, as well as contribute their own photographs to be displayed on the website.

### First Time Visitors Goals
- To gather information about Skaftafell and its hiking trails.
- To be able to ask questions about the area, the level of difficulty of the trails, necessary equipment and clothing, the weather conditions, and possible dangers regarding hiking near to glaciers.
- To enjoy scenic photographs of the landscape.

### Returning Visitors Goals
- Check for new or updated trail descriptions.
- Review the photo gallery for any unseen photos or check if their own contributed photos have been included.

### Frequent Visitor Goals 
- Check for new or updated trail descriptions.
- Review the photo gallery for any unseen photos or check if their own contributed photos have been included.

## Design

### Color Scheme
- The primary color used as main background color was detected from the hero image and complementary colors were chosen for the color scheme. The following color palette displays the colors used for this website:

![Colors Used](/documention/design-colors-used.png)

- #ECF7FB as primary background color
- #594E52 as footer background color
- #AC989D as decorative box-shadow
- #13181A as font color of body text element 
- #27322C as font color of heading elements
- #ECF7FB as font color for text elements in footer

### Color Contrast Check
Testing results of color contrast check for readability and web accessibility are as follows:

- #13181A as font color of body text elements: [Link to Coolors Color Contrast Checker report](https://coolors.co/contrast-checker/13181a-ecf7fb)

![Font color body element](/documention/color-contrast-13181A-on-ECF7FB.png)

- #27322C as font color of heading elements: [Link to Coolors Color Contrast Checker report](https://coolors.co/contrast-checker/27322c-ecf7fb)

![Font color heading elements](/documention/color-contrast-27322C-on-ECF7FB.png)

### Typography
- Roboto fonts were used for paragraphs.
- Nunita fonts were used for headers. 
- Fontawesome was used to create a visually clear, minimalistic content and to add a playful touch.

### Imagery
- All images were used with the permission of the owners or by a purchased license. The owner is credited in the alternative text for each photo on the website’s gallery page as well as aria-labels on the homepage. All photographers are credited in the credit section. 

- To keep structure and layout separated, the images on the homepage were applied using the CSS stylesheet. The attributes (Role=”img”) and “aria-label” were added. An alternative text was provided for all image elements instead of a title.

### Wireframes
- Wireframes were created for desktops using the website [balsamiq](https://balsamiq.com/?gad_source=1&gclid=Cj0KCQiAtaOtBhCwARIsAN_x-3IqIhBtaldBdPKw1vdzHDLfNzwSUMhR0FZJWFcy9QNYXi6CTAbcnE4aAhhUEALw_wcB).

- The mobile version of the website was developed first and gradually developed towards the wireframes for desktops. Screen sizes smaller than 320 were not considered in the design.

#### Wireframe for Homepage: 

![Homepage](/documention/wireframe-homepage.png)

#### Wireframe for Gallery Page:

![Gallery page](/documention/wireframe-gallery.png)

#### Wireframe for Contact Page:

![Contact page](/documention/wireframe-contact-page.png)

#### Wireframe for Thank-you-for-your-message Page:

![Thank-you page](/documention/wireframe-thank-you-feedback.png)

## Features

- The website is responsive on all device sizes.
- Visitors can navigate to homepage, gallery page and contact page using the navigation bar. 
- The Header of the website is linked to the homepage on the gallery page and the contact page. The link was removed from the header on the homepage since it is unnessecary and disturbed the reading flow when using screen readers.
- A pseudo-link:active was added to all links give users feedback in size and color when clicking the links.


### Existing Features

#### Interactive Elements

- Header
    - The heading element in the header is linked to the homepage on all pages, except the homepage itself, for easy and convenient navigation.

    ![Header](/documention/features-header.png)

- Navigation bar 
    - It is identical on all three pages, except that the location of the current page is indicated visibly with an underline, and as visibly hidden text for screen readers only.
    
    - Displayed a toggled drop-down menu on the mobile version:

        ![Navbar toggled](/documention/navbar-toggled.png)

    - Displayed in a row without toggle for the desktop version.

        ![Navbar untoggled](/documention/navbar-untoggled.png)

    - When actively clicked:

        ![Navbar activated](/documention/navbar-activated.png)

    - Allows easy navigation from page to page without using the reverse function of the web browser.

- A link to a PDF file of a map of the area on the homepage.
    - PDF file opens in a new tab.

        ![PDF map](/documention/pdf-map.png)

- A contact form to send a message and option to upload and send images.
    - Contact form is visibly seperated with a decorative boarder.

![Form](/documention/form-interactive.png)

#### General Features of Each Page

**Homepage**

- The homepage includes a brief introduction of the Skaftafell Nature Reserve with basic facts about history, geology, geography, flora, and facilities as well as a link to a map of the area. 

    The hiking trail section offers an overview of hiking trails accessible without additional gear. Each trail contains a detailed description, indication of distance and duration, supported with an image depicting a viewpoint from the trail.

![homepage screenshot](/documention/gen-feat-homepage.png)

**Gallery Page**

- The gallery page offers a selection of scenic photographs depicting the contrasting landscape of the area to give users an idea of what to expect and prepare for their visit in Skaftafell.

![gallery screenshot](/documention/gen-feat-gallery.png)

**Contact Page**

- The contact page includes a short invitation to use the contact form to ask questions, share their stories and submit photographs to be displayed on the gallery page. The contact form was created using the method GET. 

![contact screenshot](/documention/gen-feat-contact.png)

**Thank-you Page, Confirmation of Message Received**

- Users receive feedback after successfully sending an enquiry or files with a thank-you page displaying a thank you note with a background image of me in Skaftafell. The navigation bar and footer are included on the page for users to return easily to homepage or go on discovering using the social media platforms linked in the footer.

![thank-you screenshot](/documention/gen-feat-thank-you.png)

**Footer**

- Social media links for Facebook, Instagram and Flickr are included in the footer for visitors to gather information without having to use the contact form (for more reserved people) and to stay in touch. The links open a new tab and lead to the general websites since social media accounts do not exist for this website, at least yet. 

### Features Left to Implement

- Add a section with climbing routes using special equipment. 
- Add a comment section or section with user stories of hiking adventures.
- Improve Accessibility further:
    - Parkinson: enlarge the navigation buttons. After manually testing the website using the disability simulator in Google Chrome extension, adding this feature would be an improvement. Due to lack of time, this could not be implemented before submission of this project.

## Accessibility 

The aspect of web accessibility gradually increased in importance during the development, partly due to my ever growing interest. My goal was to achieve accessibility by:

- Using semantic HTML elements to structure the content

- Applying alternative text (or aria-label) to all images.

- To improve the flow of speech when using screen readers:

    - The link of the header to navigate to homepage was removed from the homepage

    - Decorative icons as well as abbreviations were hidden by applying the aria-hide: “true” attribute as per guidelines of [WebAim](https://accessibleweb.com/tips-tools-tutorials/font-awesome/). Instead of the icon, a visibly hidden text was added for more detailed description and replacing abbreviations visually supported by icons (e.g., an icon of a clock and “2h”) by using [this code](https://webaim.org/techniques/css/invisiblecontent/) provided by WebAim. This code allows interactive visibly hidden elements to be focusable when using keyboard commands instead of a mouse. 

    - A [Skip Navigation link](https://webaim.org/techniques/skipnav/]) to skip to main content was included on each page.
 
- Justifying text was avoided to improve user experience of persons with reading disorders.

- Color contrast tests was performed on all text elements on their background colors.

- Use of aria-label
    - On the navigation bar indicates the current page and whereto the navigation bar buttons navigate. 

    - On all links explaining the process of where the link will lead to and how it will open. All external links open in a new tab using target=”_blank”, all internal links in navigation bar open directly in the same window. 

    - For background images that have meaning for the content.

- Labels were applied to all input elements of the form on the contact page.

- Language attributes

    - Because the website describes hiking trails containing language specific characters of the Icelandic alphabet, the language attribute was applied directly to each element containing Icelandic words by using a span element to isolate from the main language, Englisch, as per the [World Wide Web Consortium’s (W3C) guideline on internationalization](https://www.w3.org/International/questions/qa-html-language-declarations#:~:text=When%20the%20page%20contains%20content,Usage%22).

    - Language attributes were applied to improve accessibility and to avoid scramble results of language specific characters on various browsers.

    - The language code was retrieved from the website [IANA Language Subtag Registry, the official registry](https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry) for all subtags available for use in language tags.
 
## Technology Used

### Languages Used

- HTML5
- CSS3
- Markdown for this README

### Frameworks, Libraries, and Programs Used

- [Gitpod](https://www.gitpod.io/) 
    - as code editor   

- [Github](https://github.com/) 
    - for storing files
    - for deployment of the website

- [Git](https://git-scm.com/) 
    - for version control: 

- [Code Institute template for this README](https://github.com/Code-Institute-Org/gitpod-full-template)

- Google Chrome dev tools

- [Google Fonts Roboto](https://fonts.google.com/?query=roboto) and [Google Fonts Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans?query=nunit)

- [Am I Responsive](https://ui.dev/amiresponsive?url=https://g-omarsdottir.github.io/skaftafell/)

- Accessibility: 
    - [The World Wide Web Consortium (W3C)](https://www.w3.org/) 
    - [WebAim](https://webaim.org/)

- [Iana Language subtag registry](https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry)

- [Photo optimizer Optimizilla](https://imagecompressor.com/)   

- Converter to WEBP format: [Pixelied](https://pixelied.com/convert/jpg-converter/jpg-to-webp)

- [Fontawesome](https://fontawesome.com/)  

- [Favicon mountain](https://www.freefavicon.com/freefavicons/icons/iconinfo/mountain-15-152-260771.html)  

- Wireframes: [Balsamiq](https://balsamiq.com/?gad_source=1&gclid=Cj0KCQiAtaOtBhCwARIsAN_x-3IqIhBtaldBdPKw1vdzHDLfNzwSUMhR0FZJWFcy9QNYXi6CTAbcnE4aAhhUEALw_wcB) 

- Images:
    - [iStock](https://www.istockphoto.com/de)
    - [Pixabay] (https://pixabay.com/de/) 
    - [Freeimages.com](https://www.freeimages.com/)  
    - [Flickr](https://www.flickr.com/)

- Color Palettes:
    - [Colors Artylick](https://colors.artyclick.com/color-names-dictionary/color-names/coral-blue-color)
    - [icolorpalette.com](https://icolorpalette.com/)

- Informative, decorative static badges for README.md from [Schield.io](https://shields.io/badges)

## Testing

### Validator Testing

- #### HTML
    - No errors were detected when passing through the official [World Wide Web Consortium (W3C) validator for HMTL](https://validator.w3.org/) for
    - index.html

        ![Test results HTML index](/documention/html-validator-index.html.png)
    - gallery.html

        ![Test results HTML gallery](/documention/html-validator-gallery.html.png)
    - contact.html

        ![Test results HTML contact](/documention/html-validator-contact.html.png)
    - thank-you.html

        ![Test results HTML thank-you](/documention/html-validator-thank-you.html.png)

- #### CSS 
    - No errors were detected when passing through the official [World Wide Web Consortium (W3C) Jigsaw validator for CSS](https://jigsaw.w3.org/css-validator/):
        ![Test results CSS](/documention/css-validator.png)

- #### Lighthouse Report
    - Desktop analysis
        - Homepage (desktop):

            ![Lighthouse report homepage desktop](/documention/lighthouse-report-homepage-desktop.png)

        - Gallery page (desktop):

            ![Lighthouse report gallery page desktop](/documention/lighthouse-report-gallery-desktop.png)

        - Contact page (desktop): 

            ![Lighthouse report contact page desktop](/documention/lighthouse-report-contact-desktop.png)

        - Thank-you page, confirmation of message received (desktop):

            ![Lighthouse report thank-you page desktop](/documention/lighthouse-report-contact-thank-you-desktop.png)

    - Mobile analysis
        - Homepage (mobile):

            ![Lighthouse report homepage mobile](/documention/lighthouse-report-homepage-mobile.png)

        - Contact page (mobile): 

            ![Lighthouse report gallery page mobile](/documention/lighthouse-report-gallery-mobile.png)

        - Contact page (mobile)

            ![Lighthouse report contact page mobile](/documention/lighthouse-report-contact-mobile.png)

        - Thank-you page, confirmation of message received (desktop)
            
            ![Lighthouse report thank-you page mobile](/documention/lighthouse-report-contact-thank-you-mobile.png)
        



    - Mobile devices analysis:
        - Homepage

            ![Lighthouse report mobile](/documention/lighthouse-report-homepage-mobile.png)

        - I do not have the knowledge yet to fix all indicated errors and warnings in the lighthouse report for mobile devices.

- #### WAVE Web Accessibility Evaluation Tool
    - [Link to full report](https://wave.webaim.org/report#/https://g-omarsdottir.github.io/skaftafell/)

    - Summary of report:

        ![Summary report](/documention/wave-webaim-summary.png)
    
    - Excerpt from report on index.html
    
        ![Excerpt index.html](/documention/wave-webaim-homepage.png)

    - Excerpt from report on gallery.html

        ![Excerpt from report on gallery.html](/documention/wave-webaim-gallery.png)

    - Excerpt from report on contact.html

        ![Excerpt from report on contact.html](/documention/wave-webaim-contact.png)

    - See more on error and warning notifaction in section "Known Bugs", below.

### Manual Testing

- Responsiveness on all device sizes was achieved by using flexbox.
- Responsiveness was tested manually.

- #### Testing User Stories
    - Manual testing on finalized website was performed by by, friends, and family.
    - No errors were detected.

- #### Full Testing
    - Test on various browsers (Firefox, Chrome, Opera, Safari, Microsoft Edge) 
    - Test on various devices (including but not limited to iPhone, Nokia, Samsung)
        - Test if links are working - external links, map and Social Media
        - Make sure the website is responsive by using Google Chrome dev tools
    - Testing using screen reader (Windows 11 extension)
    - [Chrome Extension Spell Checker](https://chromewebstore.google.com/detail/spell-checker-for-chrome/jfpdnkkdgghlpdgldicfgnnnkhdfhocg)
    - [Chrome Extension Disability simulator](https://chromewebstore.google.com/detail/web-disability-simulator/olioanlbgbpmdlgjnnampnnlohigkjla)

## Bugs

### Known Bugs

- Error notification from WAVE Web Accessibility Evaluation:

    - The error is caused due to workaround to add a toggled dropdown menu for the navigation bar with CSS. Since I do not have the knowledge yet to solve this with Javascript, this error cannot be fixed.

    ![Error empty form](/documention/wave-error-empty-form-label.png)
    ![Error empty form reference](/documention/wave-error-empty-form-label-reference.png)
    ![Error empty form toggle code](/documention/wave-empty-form-label-toggle-menu-code.png)

- Warning notification WAVE Web Accessibility Evaluation:

    ![Warning redundant link](/documention/wave-warning-redundant-link.png)
    ![Warning redundant link reference](/documention/wave-warning-redundant-link-reference.png)
    ![Warning redundant link code](/documention/wave-warning-redundant-link-code.png)

### Resolved Bugs

- Visibly hide content, which is focusable for keyboard users without using a mouse and detectable for screen readers
    - The following attempts to visibly hide content, yet make focusable and detectable for screen readers are not detected by screen readers:
        - "Display: none;" as suggested in the 
        - or "visibility: hidden;" and/or "line-height: 0;"
    - Resolved with a [CSS style code from WebAim](https://webaim.org/techniques/css/invisiblecontent/).

## Deployment and Local Development

### Github Pages

-	Log into GitHub and navigate to repository [skaftafell](https://github.com/g-omarsdottir/skaftafell)
-	Navigate to settings of the repository on top navigation menu.
-	Navigate to Pages on the left sidebar navigation menu.
-	In the section "Build and deployment, go to Source and select "Deploy from a branch" from the navigation dropdown menu
-	Go to "Branch" and select the following from the dropdown menus: "Main", "Root" and click "Save". 
-	The link to the deployed website will appear at the top of the section as soon as processed. 
-	The link is accessible from the main page of the depository on the right navigation menu under “Deployments”.

### Local Clone

-	Log in to GitHub and navigate to repository [skaftafell](https://github.com/g-omarsdottir/skaftafell)
-	Click on the green "Code" button, select "Clone with HTTPS, SSH or GitHub CLI" and copy the link shown.
-	Open Git Bash.
-	Change the current working directory to the location where you want the cloned directory to be made.
-	Type "git clone" and then paste the URL copied on GitHub in step 2.
-	Press "Enter" and your local clone will be created.

## Credits

### Content
- The content for this project was written by me, Gudrun Omarsdottir, and my sister, Malfridur Omarsdottir, Geographer and Specialist in Geothermal Energies. We are both former Park Rangers in Skaftafell. 

- The description of the campsite and location of the nature reserve was provided by the [official website of Vatnajökull National Park](https://www.vatnajokulsthjodgardur.is/en/areas/skaftafell).  

- Parts of the hiking trails descriptions were provided by the website [nat.is](https://nat.is/hiking-skaftafell-national-park/). 
 
### Media
- [The template for this README.md](https://github.com/Code-Institute-Solutions/readme-template)

Map of the Skaftafell area is from the [official website of Vatnajökull National Park](https://vatnajokulsthjodgardur.cdn.prismic.io/vatnajokulsthjodgardur/bf427e20-bf4a-48b5-a919-9432dd2aa4d6_SKAFTAFELL_MAP_60x32cm_enska_2022_LOKA.pdf).
 
### Imagery
- [iStock](https://www.istockphoto.com/de)
    - The hero image by photographer Vladislav Mavrin was purchased on iStock.

- Free images from:
    - [Pixabay](https://pixabay.com/) from users:
        - [Jens](https://pixabay.com/de/users/fritz_the_cat-2101387/)
        - [KStreck](https://pixabay.com/de/users/kstreck-10728261/)
        - [Laurette Chapuis](https://pixabay.com/de/users/laloublue-142381/)
        - [Patricia van den Berg](https://pixabay.com/de/users/pvdberg-1838397/)
        - [Ronile](https://pixabay.com/de/users/ronile-126846/)
        - [Vilve Roosioks](https://pixabay.com/de/users/pohjakroon-165862/)
    - [Freeimages](https://www.freeimages.com/) from users:
        - criscris1
        - wopstah
    - Flickr from user:
        - [Mariejirousek](https://www.flickr.com/photos/mariejirousek/sets/72157645744730184)
    - Fred Schalk, friend, used with his agreement and watermark.
    - My own personal collection.

### Acknowledgements

- My mentor Mitko for guidance, encouragement, valuable advice on reliable online resources, information, and patience.
- My sister, Malfridur, for providing content and engaging in testing the website in all aspects on various devices at home and at her workplace.
- The Slack community for information and encouragement.
- Inspiration and information from official guidelines for web accessibilities:
    - WebAim
    - World Wide Web Consortium (W3C)
- Inspiration from various tutorials and platforms including but not limited to:
    - Dave Gray on [YouTube](https://www.youtube.com/watch?v=n4R2E7O-Ngo) and [FreeCodeCamp](https://www.freecodecamp.org/).
    - This guide on [How to Write a Git Commit Message](https://cbea.ms/git-commit/).
    - Kera Cudmore for [examples](https://github.com/kera-cudmore/readme-examples) and an informative [presentation](https://docs.google.com/presentation/d/19_7r_To5bu7UjnZD87hrzWQi63Ij0YpaRH1XFnPZZe8/edit#slide=id.g1551aff15c5_1_108) on creating a README.
- The inspiration for fonts that go well together is from [Fontpair](https://www.fontpair.co/all).
