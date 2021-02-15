# Milestone Project 1: Digital CV

This User centric front-end project was completed as part of the full stack developer course with Code Institute. It was the first opportunity to showcase the technical skills and technologies I have learnt thus far. This front-end digital CV was created using HTML5 and CSS as well as Bootstrap libraries.

 
## UX
 
User Experience Design is the process of creating a product that is useful, usuable and provides value to the targeted user. It follows a process known as User Centered design. This process consists of 5 design planes that essentially perform as the 'make-up' of a valuable product.

### STRATEGY 
The aim of this project is to build an online portfolio that can be later updated as I strengthen my technical skills whilst on the course. Making a career switch, an online portfolio felt the most obvious place to start. This is being built with potential employers and recruiters in mind, as well as fellow developers that may want to collaborate on future projects. My strategy is to market myself and showcase my skills building a product that is useful, valuable, responsive and follows the mobile first design approach.
My intention is to build a product that has a clean,classic and professional aesthetic.

### SCOPE
User Stories:
* As an employer or recruiter, a key point of intrest would be the skills and technologies the devloper possess, previous work the developer has completed, as well as educational background information and possibly a traditonal CV with contact information.
* As a future collaborator my main focus would be to grasp a feel for the devlopers creativity, a showcase of the projects they've worked on and contact details to get in touch.
* As a client my main intrests are previous work completed by the developer, contact details and possible testimonials from previous clients that can vouch for the developers customer service etc. 

### STRUCTURE
I want the structure of this product to be as simiple as possible but still effective. I have identified 5 key pages that I feel will best relay the information necessary.
* Home - This is the first page the user encounters with a brief introduction to what the product is and navigation links to other pages as well as social links.
* About - The About page holds Information regarding the devloper, work experience, possibly educational background and skillset.
* Projects - The project page includes the most recent work of the developer.
* Contact- The contact page will consist of a form that will stimulate a call to action.
* Download- This will be a link to a pdf of the devlopers traditonal CV.

Here is a site map of the product:
![Image of site map](assets/wireframes/Site-map.pdf)
### SKELETON
To continue with the planning process, wireframes were created of each page to get a basic feel of the layout and elements featured. Using a software called Balsamiq, suggested by Code Institute, low-fidelity mock-ups were generated to include wireframes of each page across three different devices.
These wireframes will help visulaise how different features would appear on different screen sizes before implementing any code.
* [HOME PAGE](assets/wireframes/home.pdf)
* [ABOUT PAGE](assets/wireframes/about.pdf)
* [PROJECTS PAGE](assets/wireframes/projects.pdf)
* [CONTACT PAGE](assets/wireframes/contact.pdf)

### SURFACE
The surface plane is the final plane of user centered design and focuses on the look of the product.
#### Colour scheme
As previously mentioned, I wanted the product to have a clean, simple and professional aesthetic. To achieve this, I decided to keep the colour scheme as minimal as possible using only three colours.
* Rich Black (#0A0A0A) - This colour was used as the background colour for all pages.
* White (#FAFAFA) - This colour was used mainly for text, certain headings and navigation links.
* Light Steel Blue (#AABDD0) - This colour was used as an accent colour for borders, as well as certain headings and buttons.

![Colour Palette](assets/images/colour-p.pdf)
#### Typography
For the sake of simplicity and to allow for a cohesive product, I decided to use Cabin across the whole site, with some differentiation in text transform. In the case Cabin was not accessible, sans serif was set as a fall back font.
#### Imagery
Images are important to capture users and keep them engaged. To personalise the product, the logo image allows the user to know the developer without meeting them. Images can be also seen in the cards on projects page. Minimal imagery adds to the aesthetic of the site.

## Features
Here are the features that appear in the site.

### Existing Features
- Navigation bar - Implemented using Bootstrap, Allows the user to navigate through the site and appears on every page. 
- Footer - This appears on every page and includes a short statement about the site, a download link to a traditional CV and social links.
- Progress bar - Implemented using Bootstrap, this appears on the 'about' page in the skills section.
- Cards - Cards with image-tops appear on the projects page for a visual aid to each project. This was implemented using Bootstrap.
- Contact form - A form appears on the contact page, implemented using Bootstrap, to evoke a call to action.



## Technologies Used

All the technologies used are listed below:

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Balsamiq](https://balsamiq.com)
    - This software was used to create wireframes of the proposed pages of the site.
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
   - This is the main language used to create the site.
- [CSS](https://en.wikipedia.org/wiki/CSS)
   - This is the main language used to style the site.
- [GitHub](https://github.com)
   - This is a platform used by all developers and a directory to store code that was been pushed from GitPod.
- [GitPod](https://gitpod.io/workspaces/)
  - This is an online editor used to create and edit code.
- [Bootstrap v4.5](https://getbootstrap.com/)
  - This is a framework library that consists of pre-written code, and is used to assist in the creation of responsive web development.
- [Google Fonts](https://fonts.google.com/) 
  - This is used to import Typography.
- [Font Awesome](https://fontawesome.com)
  - This is used to add icons to the code


## Testing
- All HTML code was tested using [W3C HTML Validator](https://validator.w3.org/)
- All CSS styling was tested using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

### User stories

1. As an employer or recruiter, a key point of intrest would be the skills and technologies the devloper possess, previous work the developer has completed, as well as educational background information and possibly a traditonal CV with contact information.
 - As soon as an employer or recruiter visits the site, the footer gives a snippet of the devlopers skills. Going on to the About and Project pages will give further insight into the devlopers skills and educational background. A traditional CV is available via the download page in the navigation bar and the download icon in the footer. 
2. As a future collaborator my main focus would be to grasp a feel for the devlopers creativity, a showcase of the projects they've worked on and contact details to get in touch.
 - The Projects page fulfils the needs of a future collaborator with external links to each project to further grasp the developers creatvity levels. The contact page evokes a call-to-action with a form ready to be filled out. Social links are also available via links in the footer.
3. As a client my main intrests are previous work completed by the developer, contact details and possible testimonials from previous clients that can vouch for the developers customer service etc. 
 - As a client, the projects page fulfils the needs and questions. Contact details are available via the contact page and socials links in the footer. Although testimonals aren't seen on the site, the social links, especially linkedin, is a great way to see the developers reliabilty and endorsements.

### Bugs
Whilst building the site these are the bugs I encountered and how I went about fixing them:

- The navigation bar would overlap my name tag/logo. To rectify this I used Bootstraps responsive navigation and styled the margin-left to auto.
- When viewing the site in mobile view, the footer was overlapping the content. To fix this I added media queries and mad the position of the footer relative.
- On the Projects page, the cards all had different heights. This was amended by making all the card images the same height and width and then using a height calculation.

### Known Bugs 

Whilst some bugs could be easily resolved, some needed more time to figure out but couldn't be done before submisson due to time.

- The name tag/logo was due to appear in the top left corner but was hidden when the Navigation bar was made responsive.
- The footer on the projects page overlaps the content on screens 992px and up.


## Deployment

This project was deployed to GitHub pages, using the following steps.
1. After all the code was written on GitPod it was pushed to my repository on GitHub.
2. On the project repository page, the 'settings' option was located.
3. When the 'settings' option was clicked, I scrolled down until I reached a section which read 'GitHub Pages'
4. On this section it had a drop down menu to select a branch. I clicked on this menu and selected the option 'master' and clicked save.
5. After saving, I refreshed the page and scrolled backed down to the 'GitHub Pages' section, where a link to my project appeared.

To run locally:
1. On the project repository page there is a 'Code' drop down menu.
2. It gives the option to Clone which provides a url link that allows the project to be worked on without tampering with the original.
3. Or a Download zip file that can be downloaded onto your respective  work station.



## Credits

### Content
All content was written by the developer.

### Code
Most of the code was obtained from Bootstrap's library. This was used mostly for responsive elements i.e. contact form, nav bar etc.

### Media
- All images used on the projects page was obtained from google images. The direct sources are linked below.
1. [Gym weights](https://www.absolute-snow.co.uk/S/Training__Fitness_Aids/Weights_Dumbbells__Kettlebells(1250).aspx)
2. [Thought bubble](https://www.pinterest.co.uk/pin/532128512200427192/)
3. [Digital CV](https://digitalmarketinginstitute.com/blog/digital-marketing-cv-every-recruiters-dreams)
4. [Digital Cookbook](https://www.jesselanewellness.com/healthy-homemade-soups-sandwiches/)

The background image on the About Page belongs to the developer.

Inspiration was drawn from [Apple](https://www.apple.com)

### Acknowledgements

- Thank you to  my mentor for all his help on my first project.
- Thank you to the slack community!
- Thank you to student support for answering my many doubts and questions.
