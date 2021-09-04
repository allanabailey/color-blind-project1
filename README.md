# Allana Bailey - Colour Blind Project with Code Institute

## Brief Overview
This website was created as a project for the Code Institute Diploma in Full Stack Software Development.

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
To be written.



## Technologies Used
To be written.



## Testing
To be written.



## Deployment
To be written.

### Run this Locally in Your Own Repository
To be written.



## Credits and Acknowledgements
To be written.
