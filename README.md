## Project Title

Jake Howdeshell; Fullstack Portfolio

## Project Description

AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

The following acceptance criteria was created in order to meet the provided user story.

GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

Utilizing HTML the developers name was added as an h1 element, recent phot as an image element and the nav bar was created using the hyperlink element.

WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section

WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications

These both were achieved in HTML by linking the href to id's placed as the start of each section. The titled images were created using CSS flex and position functions so they would adjust properly with the expansion of the page.

WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others

The larger image was created by breaking adding a seperate class to the first image and adjusting the sizing accordingly.

WHEN I click on the images of the applications
THEN I am taken to that deployed application

This was achieved by adding a hyperlink function around all the elements that made up the image. By adding an href that linked to those deployed applications addresses the viewer is then navigated there.

WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport

By adding a @media querie set for differnt pixles and adjusting the content to display correcty below that max pixel range the viewer is able to see presentable content on a desktop tablet or mobile device.

There were also some additional features added using CSS. when hovering over the contact me content the viewer will see the color of the lettering change and a custom emoji appear. Also when hovering over images in the work section the color of the background for each image will change color. 

## Screenshots

For desktop: https://share.getcloudapp.com/DOuKA1Rb & https://share.getcloudapp.com/bLuZjvz0

For tablet: https://share.getcloudapp.com/5zuOXoZQ & https://share.getcloudapp.com/12ukNjxr

For mobile: https://share.getcloudapp.com/X6u7ojOK & https://share.getcloudapp.com/JrueLZLk

## Deployed Website

https://jakehowdeshell.github.io/professional-portfolio/
