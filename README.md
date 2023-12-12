# Week2-Challenge-Portfolio

## Description

This repository serves to showcase my work in completing the Module 2 Challenge of my edX Bootcamp. 

The challenge was to create a site to host my portfolio as a web developer. 

As shown in the following Demo screenshot: 

![Demo](Week2-Challenge-Portfolio/images/Screenshot_1.png)

![Demo](Week2-Challenge-Portfolio/images/Screenshot_2.png)

Required features of the site were as follows:
When the page is loaded the page presents your name, a recent photo or avatar, and links to sections about you, your work, and how to contact you
When one of the links in the navigation is clicked then the UI scrolls to the corresponding section
When viewing the section about your work then the section contains titled images of your applications
When presented with the your first application then that application's image should be larger in size than the others
When images of the applications are clicked then the user is taken to that deployed application
When the page is resized or viewed on various screens and devices then the layout is responsive and adapts to my viewpor

## Table of Contents 

- Usage
- Credits
- License

## Usage

To view my work on this challenge, you can review the sections of this repository and my refactored version of the site which is deployed at https://aireytf.github.io/Week2-Challenge-Portfolio/ 

## Credits

I utilised the resources at w3schools.com in the README provided for this challenge, to apply appropriate semantic and logical structure, and to follow accessibility standards for this site. 

I had difficulty deploying this application, as only this README from my repository was being shown on the live site. I researched the issue on stackoverflow.com and found a solution there that worked, which was to use the deployment option of GitHub Actions in Pages and using Jekyll to change the source for the site from [./] to [./starter/] , to redirect inside the subfolder 'Starter' that I initally pushed to GitHub with the starter code for this challenge. This meant that the index.html inside the 'Starter' folder was being deployed to the site, as needed. 

## License

As per the contents of this repository, this project is under an MIT license. As I initially created this repository without a license, I took the opportunity to figure out how to add one after a respository has already been created. This was as simple as adding a new file to the repository and selecting a license template (having given the new file the name LICENSE). 
