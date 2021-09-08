# Allana Bailey - Colour Blind Project with Code Institute

## Brief Overview
This website was created as a project for the Code Institute Diploma in Full Stack Software Development. The deployed site can be found [here](https://allanabailey.github.io/color-blind-project1/index.html)

![Responsive Display Across Devices](/assets/images/features/responsive.jpg)

### Description
A website for people to visit who would like to know more about colour blindness, with clear visual representations of how different forms of colour blindness alter vision. The website also provides information on ways to design web applications in a more inclusive manner for people with colour blindness.

### Features
The website features a home page with a brief scientific overview of colour blindness, a footer containing links to useful external sources such as colour blind tests and articles, and some fun facts. There are then pages for each main type of colour blindness, a page on design considerations for web developers and anyone creating graphic illsutrations to create more inclusive applications for visually impaired and colour blind users. The final page contains a form that users can submit to help the site gather information on the most desireable colours, what type of user is visiting the site, and to collect details for future correspondence. 

### Goals
Website Goals
* Raise awareness of colour blindness.
* Provide interactive forms of learning and visalisation for different learning types.
* Showcase inclusive design options for web developers and other graphical designers.
* Link to other useful information and articles on the web.

Personal Goals
* Create a website as part of my online portfolio.
* Produce a responsive design suitable for all screen sizes.
* Improve my understanding of colour blindness through research.
* Discover ways to make my own work more inclusive for those with visual impairments.



## Users
Users would visit this website to:
* Find out more about colour blindness.
* Understand a small amount of science behind colour blindness.
* Witness the differences in colour for each type of colour blindness.
* Find out about design considerations that could create a more inclusive web application or graphic.

### User Stories
* As a user who is researching colour blindness, I want to easily see information about colour blindness, so that I can gain more knowledge on the subject.
* As a user with a family member who is colour blind, I want to be able to visualise what they see, so that I can understand their visual deficiency more. 
* As a user who is colour blind, I want a website I can easily see, so that colours don’t prevent me from reading the content.
* As a web designer, I want information on how to create an accessible application, so that all users can enjoy my creations. 



## Planning and Wireframes/MockUps

### Planning Process
I attempted to plan the project in line with the 5 planes of User Centric Design to optimise the User Experience and ensure I didn't fall foul of issues such as scope creep. 

I began by thinking of what content could be useful to web developers and had a keen passion for inclusion and diversity, which led to the idea of creating a website around accessible design. Focussing this further due to limited time and resources, I decided to focus on colour blindness, or colour vision deficiency, as the main focal point of the website. 

I then began to conisder the content that could be achieved which was then scaled down slightly. Originally, there was also going to be an interactive colour picker which showcased how the different colours appeared in each type of colour blindness, but opted to provide a static palette collection and images that could be compared instead.

Following this, I sketched my ideas with pen and paper to logicalise the layout of the site and the priority of content, eventually deciding on Home > Types > Design > Contact with the main content in the pane below. Originally I had the footer information appearing in a customised sidebar for each page, however felt this detracted from the main content and did not always contain vital information important to the page content beside it. Therefore, as it was a lower priority, this information was placed in the footer of the website. This way it was still accessible, but did not take priority over the other content and offered a more modern look to the site.

Following on from this, I used Balsamiq to create wireframes of the different pages to visualise more clearly the location and priority of elements which I then gathered feedback on and adjusted as per feedback.

With regards to the choice of colours and images, it was essential to make the colours accessible and colour blind friendly. Therefore I created a palette of 6 colours which would be suitable and utilised these across the site, with the occasional use of rainbow coloured images to highlight the topic of colour throughout.

### Wireframes
On creating the wireframes, some small changes occurred as a result the difference purposefully shown below. As seen in the images below, originally there was going to be a "Palettes" tab and no "Contact" tab. Having an interactive palettes page was beyond the scope of this project and required technologies not yet covered. Therefore, a decision was made to replace the "Palettes" page with a "Contact" page to prevent overcrowding in the footer and ensure there was an interactive element present.

Wireframes were not created on Balsamiq for responsive screen sizes, but adjusted on paper as they were simplistic changes such as stacking content rather than displaying them in columns.

#### HOME PAGE
![Home](/assets/images/wireframes/home.png)

#### TYPES HOME PAGE
![Types Home Page](/assets/images/wireframes/types-home.png)

#### TYPES TEMPLATE FOR RED-GREEN, BLUE-YELLOW AND MONO
![Types Template](/assets/images/wireframes/types.png)

#### DESIGN
![Design Home Page](/assets/images/wireframes/design.png)

#### PALETTES - NOT INCLUDED IN FINAL DESIGN
![Palettes](/assets/images/wireframes/palettes.png)


## Features
* Logo
    * Every page has an **interactive logo** placed at the top of the screen to allow the user to easily return to the home page. The logo uses the **same colour scheme** as the site for consistency. It is placed in a conventional position of top left for desktops, and center top for mobiles for continuity and best practice.
![Logo](/assets/images/features/logo.png)

* Nav Bar
    * Every page also has an **interactive nav bar** placed at the top of the screen which is the convention in web design. The nav bar **changes state** by highlighting in a different colour when **active or hovered over** to provide feedback for the user and clarification of which page they are currently viewing.
![Nav Bar](/assets/images/features/navbar.png)

* Title
    * There is the main website title that appears at the **top of every page**, however below the nav bar, in the content window, each page has its **own title** in a reduced header size to showcase that it is a subtitle and inform the user of the page title.
![Title](/assets/images/features/title.png)

* Footer
    * Every page has a footer which is split into **two sections**. One section containes **extra information** such as online colour blind tests, fun facts and useful articles, whilst the lower section of the footer contains **copyright information**. Initially social media links were also going to be added, but this did not seem suitable for the website as there is no central social media presence for this content.
![Footer](/assets/images/features/footer.png)


### Home
The home page features a **rainbow hero image** which has a zoom transition to entice to reader into the site. The hero image is purposefully a bright rainbow colour in **contradiction to the colour scheme** of the website to highlight the topic of colour. On a mobile a smaller portion of the image is displayed to maintain the aspect ratio.

Below the hero image is the main **content section** which goes into detail about some of the science of colour blindness, statistics on who it affects by proportion of population, and finally distinguishes the difference types of colour blindness by ‘nopia’ and ‘nomaly’.

There was some use of **icons by Font Awesome** to highlight the topic areas such as science and statistics as well as **corresponding images** placed either beside the text on desktop, or stacked on top of the content for smaller screen sizes.


### Types
On the landing page for the **Types** nav bar link, the user finds themselves with **three re-coloured versions of the logo**. These three logos represent the three main types of colour blindness whilst providing consistency for the user. To showcase that the images are clickable, a **border appears and the image zooms in** when the user hovers over them. These images are then direct links to the pages on the different types of colour blindness.

On a desktop these images are **displayed in 3 columns side by side**, however on a mobile this would make the images too small and so they are instead **stacked on top of each other** so the user can scroll and select one.


### Types - RG/BY/Mono
On clicking of one of the images in the Types homepage, they are redirected to more in depth information about each type of colour blindness which **all follow the same structure and template** for consistency. The main page title remains at the top of the content and **subheadings appear on the left** outlining the scientific name for each type of colour blindness. Each type of colour blindness then has a corresponding **picture of an eye with the pupil coloured to represent the colour affected** which is the same across all types. Underneath the content, two images are shown **side by side for comparison for regular vision and the type of colour blindness**.

Whilst the aspect ratio is affected on a mobile site for the images, it was decided to **keep the images side by side** to allow for better comparison. Please see future implementations for a suggestion in the future to replace these images. The other content stacks on top acting similarly to the other pages above.


### Design
At the top of the page, there is a **small blurb about inclusive and accessible design** which almost acts as an introduction to the content on the page. Below the blurb are **three large icons** which represent the three design topics of icons, contrasting colours, and clickable elements. An icon style image was purposefully chosen to highlight the use of icons, but also draw focus to the design considerations as opposed to having distracting images unnecessarily. 

Below the images is an **inclusive colour palette suggestion**. Whilst the top palette has the colours as seen by someone with regular vision with the corresponding **hexadecimal and rgb values**, the palettes beneath show how these colours would appear for people who have the different types of colour blindness. The hexadecimal and rgb values were not required for these palettes as they are a visual representation of how the colours would appear, as opposed to values and colours that should be used.

On a desktop screen the **design icons appear side by side in a column of three** for consistency with other pages. On a **mobile or smaller screen** these icons and pieces of information become **stacked on top of each other** where the user scrolls to see the content. Originally smaller palettes were going to be created, however on testing this in the **edvelop3er console** the titles and colours remained **clear and legible** and so a decision was made to keep this images as they were, just resizing them based on the screen size and resolution.


### Contact
The ‘Contact’ page purposefully has a **bright rainbow background image** to highlight the topic of colour again, and to also repeat a similar use of the **home page hero image** for consistency and continuity being the first and last link in the navbar. The form is then placed on a **semi-transparent dark grey background** to ensure readability and make the content stand out.

The input fields are then **styled in line with the colour scheme** of the website to match the header and footer of the website seen across the other pages. By making the whole **text area highlight** it ensures the user is aware of the box they are going to action next and their progress within the form. The form also **validates the input** to ensure that all fields are filled in, as well as checking the content, such as an email being in the correct format. The **submit button uses inverted colours** to highlight the status of hovering and clicking on it. In the future this would also redirect the user to a success page, please see future implementations.

The page is fully scalable meaning that on **smaller screens** the form natural changes its width based on a percentage to ensure it is still readable and that all content can be found by simply scrolling further on a smaller screen.



## Future Implementations
Due to the time and resource constraints of the project, certain implementations could not be achieved in the first release. However the following are being considered as future implementations:
* Create a **success.html page** where on submission of the form in contact.html, users are redirected to a page highlighting the successful submission of the form. This page could also **contain a summary of the information submitted** for the user with an option to resubmit. Could potentially be a pop up as opposed to an entirely new page. This would require JavaScript.
* On the pages for the specific types of colour blindness, there could potentially be a different way of showing the difference in regular vision and the representation of the same image for someone with the correspnding form of colour blindness. Potentially could include a **user file upload option** which then alters the image to display how it would appear for someone with colour blindness. A **change of images for smaller screen sizes** could also prevent the issue with aspect ratio ocurring.
* Potential for **drop down menu** being created for the three types of colour blindness as a sub menu of "Types". I would want to conduct some more user research on this before implementing it and currently all content can be accessed within two clicks, keeping within the **3-click standard**.
* In the inital wireframes created following the concept creation, an **interactive palette / colour picker** was considered whereby the user could select a colour from either an HTML colour picker or pre selected group of colours, and the way these colours appear to the four main forms of colour blindness would appear beside this. This would require potential extensions and the use of JavaScript to achieve.
* On the user submitting their favourite colour in the form on contact.html, it could **create an inclusive colour palette of six colours including their favourite colour** similary to the way that https://palett.es/fdfdfd-f25cbe-2a4147-d5a85b-202020 achieves this, with a contrast and accessibility check such as Adobe Color. This would be a major new implementation with a great deal of development effort and is something that already exists on the web, so would be the lowest priority to implement.



## Technologies Used
* Programming LanguageS: HTML and CSS.
* [GitPod](https://gitpod.io)
    * GitPod was used as the IDE to develop and write the project and was then pushed to GitHub.
* [Google Fonts](https://fonts.google.com/)
    * Google Fonts was used as a way to style and customise the fonts and appearance of the website content.
* [Font Awesome](https://fontawesome.com/)
    * Font Awesome was used to add icons to the home page to represent the content topic.
* [Paint 3D](https://www.microsoft.com/en-gb/p/paint-3d/9nblggh5fv99?activetab=pivot:overviewtab)
    * Paint 3D was used to alter the colours of the logo images for types.html.
* [TinyPNG](https://tinypng.com/)
    * TinyPNG was used to compress image files for a better performance and loading speed.



## Testing
Manual testing took place in this project to ensure the validity and security of links, the correct functioning of the website, and checking that the user feedback was as expected.
* Nav Bar: On each page, every link was clicked in the nav bar to ensure that all pages could be accessed regardless of the current page that the user was on.
* External Links: The only external links are within the footer on each page. On each page each of these links were clicked to ensure that they worked and opened a new tab.
* Responsive Design: The ebsite was tested for responsiveness down to a screen width of 320px. Most of this was completed throught the use of Google Chrom developr tools and clicking on the various device types and altering the screen width. Further information can be found in the section below titled "Responsive Design".

### Bugs and Fixes
* Rename Image Files: Some images were hyphenated whilst some were not. Renaming completed for cinsistency.
* Missing target="_blank" on a footer link was added.
* rel="noopener": On running a lighthouse report, the "Best Practice" analysis highlighted the lack of security for some of the links and so rel="noopener" was added.
* Nav Section: in the nav section of the header, "id(#)" was being used for multiple occurrences so this was changed to "class(.)" for elements such as menu.
* Clearing Floats: The website was not being responsive on index.html and the various types.html pages due to image sizing and floating left. Clears were added and element selection in the developer tools allowed for the identification of the issue. As well as clearing floats, new heights and widths were added to the images at different breaking points to prevent overflow and sizing affecting the nav bar and footer.

### Validation
All HTML code was passed through the [W3C Validator](https://validator.w3.org/) via direct input, and the CSS through [W3C JigSaw Validator](https://jigsaw.w3.org/css-validator/). Reports for each seen below. The only warnings present were the lack of heading for two sections: The hero image section and the footer. These sections do not require a heading and can thus be ignored.
* index.html
![index.html Validation](/assets/images/testing/index-test.png)

* types.html
![types.html Validation](/assets/images/testing/types-test.png)

* types-rg.html
![types-rg.html Validation](/assets/images/testing/types-rg-test.png)

* types-by.html
![types-by.html Validation](/assets/images/testing/types-by-test.png)

* types-mono.html
![types-mono.html Validation](/assets/images/testing/types-mono-test.png)

* design.html
![design.html Validation](/assets/images/testing/design-test.png)

* contact.html
![contact.html Validation](/assets/images/testing/contact-test.png)

* style.css
![style.css Validation](/assets/images/testing/css-test.png)

### Lighthouse Reports
A lighthouse report was run for each page on the deployed github page. Initially the performance and best practice was in the 80s for some of the pages. Following compressing the images and adding rel="noopener" to the external links, these all increased to the 90s. types-rg.html was the only specific types page that a lighthouse report was generated for as they follow the same structure, template and types-rg has the most content with two types.
* index.html
![index.html Lighthouse](/assets/images/testing/index-lighthouse.png)

* types.html
![types.html Lighthouse](/assets/images/testing/types-lighthouse.png)

* types-rg.html
![types-rg.html Lighthouse](/assets/images/testing/types-rg-lighthouse.png)

* design.html
![design.html Validation](/assets/images/testing/design-lighthouse.png)

* contact.html
![contact.html Validation](/assets/images/testing/contact-lighthouse.png)

### Responsive Design
To test the responsiveness of the website for smaller screen sizes, the developer console within the Google Chrome browser was utilised to identify the **breaking points** where media queries needed to be created. I then proceeded to use the responsive. There is one remaining bug where the sub titles on index.html occasionally appear split between 474 and 510px. The website was checked on a few main devices as options in the developer console:
* iPad and iPad Pro
* Moto G4
* Galaxy S5
* iPhone 5/SE
* iPhone 6/7/8
* iPhone 6/7/8+
* iPhone X


## Deployment
This project was developed in [GitPod](https://gitpod.io) where everything was committed and pushed to [GitHub Repository](https://github.com/allanabailey/color-blind-project1) using the built in capabilties. The Code Institute offered a [template](https://github.com/Code-Institute-Org/gitpod-full-template) which could then be pulled and used for the main structure of the repository, and created into a GitPod repository by clicking the green "GitPod" button. Please see the process followed below for deployment:
1. Go to the [GitHub Repository](https://github.com/allanabailey/color-blind-project1) home page.
2. Click "Settings" in the ribbon of links below the title of the project.
3. Click "Pages" on the side bar.
4. Select "Branch: main" where it asks for the source.
5. Hit "Save" and wait for a few minutes.
6. Refresh the page and click the green link with the [deployed page](https://allanabailey.github.io/color-blind-project1/index.html).

### Run the Project Locally
Once you have a [GitHub](https://github.com) account and installed the [GitPod Chrom Extension](https://www.gitpod.io/docs/browser-extension/) follow the steps below to clone this project into your own repository:
1. Log in to your [GitPod](https://gitpod.io) account.
2. Open the [project repository](https://github.com/allanabailey/color-blind-project1) in a new tab.
3. Click on the green "GitPod" button to the top right of the project.
4. This will automatically create a new GitPod workspace for you to work on. You can type in any name of your choosing.


## Credits and Acknowledgements
The inspiration for creating the website around this topic came from a smaller group-project that was assigned whilst studying my degree at the **University of Kent** where we were tasked with altering the colours for a piece of software to show how it would appear for different forms of colour blindness.

I would also like to thank my mentor **Miguel Martinez** at Code Institute for all of the support and calls throughout the duration of the project and providing feedback throughout.

I would also like to thank **Code Institute** for providing a brilliant course and to all of the **fellow students** for their additional support and encouragement.

### Images
[Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/) - For free images available online to use.
[Am I Responsive](http://ami.responsivedesign.is/#) - Creating the image displaying the website preview on all devices at the top of the README.

### Code
[Code Institute](https://codeinstitute.net/) - For the 5-Day Coding Challenge and Diploma in Full Stack Software Development which have both been a vital learning resource for HTML and CSS.  
[W3 Schools](https://www.w3schools.com/) - For the lessons and resolutions found, most notably asistance with displaying elements using flex for responsive design.  
[CSS Tricks](https://css-tricks.com/) - Multiple helpful articles for different CSS styling tactics.  
[Stack Overflow](https://stackoverflow.com/) - Articles and posts helping resolve many issues, especially with the responsive design elements and errors in GitHub and GitPod.  

### Research
[NHS - Colour Vision Deficiency](https://www.nhs.uk/conditions/colour-vision-deficiency/) - Facts about Colour blindness and statistics for who it affects.  
[Colour Blind Awareness](https://www.colourblindawareness.org/colour-blindness/) - An organisation for raising awareness of colour blindness with an incredibly informative website.  
[National Eye Institute](https://www.nei.nih.gov/learn-about-eye-health/eye-conditions-and-diseases/color-blindness/types-color-blindness) - A website publishing the research around colour blindness.  
[EnChrome](https://enchroma.co.uk/) - A provider of glasses to help with colour blindness, but also contains good scientific information about the way different colours are perceived dependent on the type of colour blindness.  

### Interactive Websites/Applications
[Pilestone](https://pilestone.com/pages/color-blindness-simulator-1) - Used to alter images to represent colour blindness through a file upload.  
[Medium Article by Allie Ofisher](https://medium.com/cafe-pixo/inclusive-color-palettes-for-the-web-bbfe8cf2410e) - Informative website on inclusive design with suggested colour palettes which inspired the use of the two main colours for the scheme of this project.  
[palett](https://palett.es/fdfdfd-f25cbe-2a4147-d5a85b-202020) - Inclusive colour palette generator.  
[Adobe Color](https://color.adobe.com/create/color-accessibility) - Used to check the contrast and accessibility of colours in a palette.  
[coolors](https://coolors.co/e03f42-62a3d1-5d7b8b-2a4147-bdd9c0) - Identify the hex and rgb values of the palette created and check its appearance as per type of colour blindness.  


