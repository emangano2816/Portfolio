# Homework Assignment 2: Portfolio

## URLs
1. Deployed application: https://emangano2816.github.io/hw2_portfolio/
2. GitHub Repository: https://github.com/emangano2816/hw2_portfolio

## User Story
```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

```
## Acceptance Criteria
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport

```
## Achieving Acceptance Criteria

To meet the acceptance criteria provided above, the following functionality was included:

1. Upon loading my portfolio page, the employer will see my name and the following links: About Me, Work, and Contact Me in the header section of the page.  Additionally, a current photo of myself is included in the About Me section of the page.
2. Upon clicking the following links: About Me, Work, and Contact Me the page will scroll to the corresponding section of the page.
3. Upon clicking the 'Work' link, the employer will be taken to the 'Work' section of the page.  In this section, the employer will find 5 images titled App 1, App 2, App 3, App 4, and App 5.  Since I do not have work to link to currently, these serve as placeholder titles for applications that will be linked to when available.
4. Upon viewing the 'Work' section of the page, the employer will find that 'App 1' is larger than the other application images displayed in the section.
5. Upon clicking the application images, the user will remain on the page, as I do not currently have applications to link to.  In the future, when I do have applications to link to, then I will update the href attribute for each of the images to include the path to the developed application.  Once this update is made, then when the employer clicks on the images, they will be redirected to my developed application pages.
6. Upon resizing the page/view the employer is presented with a responsive layout that adapts to the viewport.  Scroll down for screenshots of the various page designs when the screen has a max-width larger than 992px, greater than 576px and less than or equal to 992px, and less than or equal to 576px.

## Meeting Application Quality

To exceed expectations and include functionality resembling the mock-up, the following was inlcuded:

1. Included a transition when the employer hovers over the navigation links and contact links.  The background color red fills from bottom to top and the text color changes to white.
2. Included a transtion when the employer hovers over the 'Work' section images.  The employer will see the image change color upon hovering over each image.

## Screenshots and Video
### Full Screen View
![screenshot](/assets/images/)

### Media Screen @ max-width 992px
![screenshot](/assets/images/)

### Media Screen @ max-width 576px
![screenshot](/assets/images/)
