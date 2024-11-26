
# Table of Contents #
- - - -
# Project Goals #
## 1. User goals

- The users goal is to gather information about popular rural travel destinations in Wales

- The users goal is to being able to navigate the website quickly and efficently to our content

- The users goal is to use our information presented to make their travel decisions 

- The users goal is to find their rural destination and research more about events, food, local history and location
    
## 2. Site Owner Goals
- The site owner goal is to provide unbiased comprehensive rural travel-related content

- The site owner goal is to increase rural tourism to Wales

- The site owner goal is to take feedback from users and provide better travel experiences & information to the public
- - - -
# Features #

## Index Page
### Carousel
The site features a way to display information on how to best tour Wales, it’s home page prominently features a carousel of hero images that can display the best that Wales has to offer. 
### Cards
Below that are 3 cards that feature guides available with a short snippet of information and you can quickly choose the guide you wish rather than browsing the entire guide page. Selecting the guide you want will send you to the correct section of the guides page via an ID.  The cards are responsive going into a single column on a small screen and showing as a row of 3 on medium and larger screens.
Below that is some information regarding Welsh rules on wild camping.

## Guides Page
The guides page is multiple pages in one and can be expanded downwards with further guides. It is responsive showing as a single column on smaller screens and two on medium and larger screens. The order on smaller screens is image > text > image > text however on medium and larger screens it will alternate to make the site more visually interesting and balanced. The guides have an accordion element from bootstrap that can be used to store extra information, a map iframe has been used as an example.

## Contact page
This page has used the min() function to fluidly size for many screen sizes at and between breakpoints to ensure a consistent view, the body is size to the viewport to ensure the footer remains at the bottom of the page without using a fixed position as fixed position cause issues with overlapping of the form and footer at smaller screen sizes

- - - -
# UX/UI #

   ## 1. Target Audience
   
  - People looking to travel rurally
  - People specifically looking for Wales based rural trips
  - Users looking for rural travel tips in Wales
  - Users already in the destinations looking for events or points of interest
  - The Welsh travelling community 

 ## 2. User Stories
  - As a first time user, I want a navbar to easily navigate to the content I want.
  - As a first time user, I want an introduction, blurb or image to easily understand the main purpose of the site.
  - As a first time user, I want a guide/article to get a general rundown on the location. (i.e Transport, accommodation, events, food/drink, local history)
  - As a  first time user, I need a map of the location.

  - As a returning user, I want to contact the organisation to provide feedback
  - As a returning user, I want to leave a review

  - As a site owner I want a logo in order to help identify the brand.
  - As a site owner, I want users to find the visually pleasing travel content easily.
  - As a site owner, I want users to be able to book or find out more on the respective websites mentioned in the content
  - As a site owner, I want to display an engaging carousel of hero images so that users are more likely to book tours
- - - -
 ## 2. Design Choice
 
 ##  Colour Scheme

 - A earthy/rural palette was picked by the team in fitting with the outdoors nature and rural travelling to align with our target audience 
 - Inspired by https://coolors.co/cc3f0c-72705b-0f1a20-a1cca5-fffdf7
 
 ##  Fonts
 
 ### Main Content 
 - Didact Gothic
 ### Home Title & Wild Camping  
 - Wales Sans Headline
 
 ## Wireframes
    
  - Home Page Wireframe
  <div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/2dba9214-6f88-4ed3-97f6-741d84b9ec33" alt="Main page wireframe">
</div>

  - Your Course Page Wireframe

  <div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9896a627-c591-4829-b0ab-add8ffb007bf" alt="Wireframe">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9f047ef6-5fb3-4394-8fae-22f964d49008" alt="Wireframe">
  </div>

  - Connect Page Wireframe

  <div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9896a627-c591-4829-b0ab-add8ffb007bf" alt="Wireframe">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9f047ef6-5fb3-4394-8fae-22f964d49008" alt="Wireframe">
  </div>
  

  - Contact Page Wireframe
<div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/ba3ef148-a6e7-43c1-af73-962268604127" alt="Wireframe">
</div>

 ## Logo

- Image taken from Pexels.com and resized with squoosh photo editor to make the correct size. 
- File is in the assets folder, and subolder images. 

- - - -
# Testing #

## HTML Validation
- Initial HTML Validation was performed using the W3C Mark up service and the results can be found in this document. https://docs.google.com/document/d/1bpeozgiIdqKK1ukf-Le-pkrP0iTv6WHeWEdsZ5wpVN4/edit?usp=sharing
- The has been resolved.
- No Issues with 
  
## CSS Validation
- Initial W3C CSS style sheet validation link https://docs.google.com/document/d/1PLn-LXFHKpIaeiYMOUwEe_7h6ZVjw1cCxucjCS2Kp-w/edit?usp=sharing
- Test W3C Validation CSS style sheet validation https://docs.google.com/document/d/1t1xgVG540joh549TvAwI0CXQ889QDUD3y8Qt0xqJFtU/edit?usp=sharing
- The style.css form passed with only one issue that was with a newer feature that some browsers do not support just yet. We have left this in as the browsers still work as intended.

## Accessibility
- We entered our website through AccessScan to check we were compliant with with ADA standards. Our website is ADA-compliant as shown below:
![image]()

## Device Testing

I tested the site with the following devices:

- Android Google Pixel 8
- Desktop
- Chrome Developer Tools (Simulating for all available device options)
  
## Browser Testing

Testing has been done on the following browsers:

- Chrome (& Developer tools)
- Safari

## Testing Breakdown
- We completed the following tests on all mentioned devices and browsers including the steps & outcomes from said tests. Any noted bugs are explained below.
  
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/bb6a250c-5003-462c-a133-506bd18537bf)

## Testing user stories

We tested our site vs the user stories: 

1. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e52c926b-713d-4ba0-823e-1f58e58e711b)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e0ad468c-ac68-40ef-a7ef-3a08fbedf058)
--
2. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/2561b52a-af2b-4239-a386-f87a8ab0c498)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/b590ea37-34a5-4404-a1ed-fb8745a28e9e)
--
3.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/649049fb-25a6-4035-8e80-49bb07d24543)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/30c82c1e-28ea-4403-8b10-3371da297aff)
--
4.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/14cdc8b8-7450-46d2-bde5-673bbe6a3ecc)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e9ecbba4-dd1c-43a4-b6a1-be45d7c765cd)
--
5. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/79e8300a-3523-485e-8304-147c1d4a3e81)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e0ad468c-ac68-40ef-a7ef-3a08fbedf058)
--
6.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/3e4f9313-b077-40a9-bd7f-c287907d2e2d)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/89967414-9cbc-4e35-a16c-7bcc879abb2e)
--
7.
- This user story combines the Must Have User Stories for Outsourcing content, YHA Booking Link & Hyperlinking Content
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/0f8cf269-4724-478c-b033-4228330d7cc1)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/8977ba5d-0f7b-4c43-9946-1ae94c78ff7e)
--
8.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e7e29e5f-ee27-4c50-bd9c-176bc30fd820)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/0b6c59b5-dc37-4144-b349-e00e06ab50e0)

## Known Bugs

## During development, we found these bugs and fixed them:

### Nav bar dropdown shifting to the right hand side on smaller devices

- On smaller devices, in the connect.html and index.html pages the navbar burger logo to indicate the nav bar would switch sides and throw everything on there out of line.
- To fix this issue, I checked the code in the other pages and texted them wjhere it worked fine. The issue was due to the logo which i had in the first pages. I copied across the code, resized the logo and this worked. 

### Images resizing on smaller devices

- The cards resized poorly when on smaller devices, meaning the images went out of shape and were hard to view. 
- To fix this issue, I looked into the code and the bootstrap 5 container system, i edited them so that they would fill the screen on smaller devices and drop down below one another. 

### Cards seeming too large on page

- The cards and images inside them were originally 2 across the page with 2 below. I found that while testing this was not condusive to a good UX as they seemed too large. 
- To fix this issue I made sure that the cards were smaller and all on one line of the page, meaning that the user could more easily see and navigate the page, and it was a calmer experience. 

### Poor Font for User

- When deploying and testing the site I found that the font that was being used was not a good fit for the User. It was too clinical and i felt it needed a rounder and calmer font. To fix this i did some more research and found that a good fit was the Poppins font. 

## During development and testing, these are the current bugs:

### Images not sizing correctly on Cards 

- This was an issue which was ongoing through my project - It was tricky to get the images to be the correct size for my cards. They would either bee too small/big, or not the same size as others. 
- To fix this issue originally I spoke with Roo, who guided me to try using max height for the images, however i then found that when on smaller devices the images stretched out of shape. 
- I then fixed this further by resizing and shaping all of the images in question so that they fitted well into the cards. 

### =on smaller devices

- The content when deployed on a smaller device reshuffles the image to the bottom of the container.
- The text in the last paragraph changes to the default font rather than our applied styling in the CSS folder. This is specific to Android.

- - - -
# Deployment #

How I deployed this site : 

- In the GitHub repository, I navigated to the Settings tab, then chose Pages from the left hand menu 
- From the source section drop-down menu, selected main branch
- Once the main branch had been selected, the page was automatically refreshed with a detailed ribbon display to indicate the successful deployment
- Any changes pushed to the main branch take effect on the live project

- The live link is here: https://isaacnicholls1.github.io/MH-P1-IsaacN/

- I used an agile methodology by using early deployment, I made sure the project was deployed after the first few pages were created. This ensured that I could see every change on a live site, which greatly aided the coding and development process.
- ![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/cad5ad9d-e0df-491f-982b-198d6f917797)

- - - -
# Sources #

## Media
 - The images that were usedn throughout the project were all used from the site https://www.pexels.com/
 - I went through a range of images until I decided on the correct ones, I wanted to get the right feel for the site so this was very important. I decided to use all images of a certain type. 
 - The following photos were used in the content: [Content Section sources.docx](https://github.com/IsaacNicholls1/MH-P1-IsaacN/tree/main/assets/images)
 - Some images were edited with: https://squoosh.app/editor - this was to reduce their size and get them the correct shape, therefore providing a better UX when visiting the site.

## HomePage Content. 
-  I wanted to keep Homepage content to a minumum as I was aiming for a calm and easy user experience, so i felt that I didnt want to provide over stimulating information to the user. 
-  Text for the homepage was generated using Co-Pilot, but had to be greatly re-fined and rewritted by me for the purpose of the project and specific user. 
- I used sites such as https://www.mind.org.uk/need-urgent-help/using-this-tool/ and https://www.nhs.uk/nhs-services/mental-health-services/ to generate information and text ideas. 

## Content
- The colour scheme was helped with the use of: https://coolors.co - I went through a bit of testing with my different colours as the first ones I used i was not happy with, as they did not seem to suit the calm user experience that i was aiming for and were too bold. This led me to choosing the specific color palette that i did. 
- The fonts were imported from Google Fonts. Originally I selected a font of Roboto sans, but it didnt not load properly and when it did, after testing the site i decided that it was not the correct font for my target audience. I eventually then tested some fonts and after some research decided on the font Poppins. 
- Font awesome was used to add icons for UX purposes auch as social media icons. 
- Balsamiq was used to create the wireframes during the design process, as this was the first time of using the tool it took a bit of getting used to and developing these. I tweaked them as i went along and made slight changes to my actual site. 

## Code
- The HTML & CSS uses Bootstrap Version 5.3: https://getbootstrap.com/docs/5.3/getting-started/introduction/ - this was loaded intto my page as one of the first steps and it was used greatly to create my site. 
- I used other coding tools and resources such as snippets of code from my previous CI projects to guide and aid me when i needed reminding about the correct way to use the code.
- I utilised AI in this project in the form of CoPilot. This helped me to create basic HTML structures and to edit parts of code that needed it. I found it very useful overall and saved me a great deal of time, however I found when using, it needed a close eye kept on it as it seems to add in exra closing tags and code that is sometimes not needed. Overall a very useful tool when used in the correct context. 


# What could I add for future features? #
- If i had more time for this project i wopuld have liked to add another "About Us" page, which i think would have been useful to the site visitor and would explain a little more about what we do. 
- I would have liked to add an email button at the bottom of each page for the user to enter their email and receive a monthly newsletter. 
- I would have liked to possibly implement some more texture to the background using https://www.transparenttextures.com/, however this is something that I have not looked into so would have needed a bit more time to learn and implement. 
- One extra thing would have been to add in a search bar at the top in the navbar as this would provide a better UX, giving the user the ability to find what they need from anywhere in the site. 
- Something that I started doing but ran out of time for was the re-sizing of pictures using the site https://squoosh.app/editor
  I woild have liked to edit all of them and change them to PNG to give an overall faster loading site and better UX. 
- I would have very much liked to create a more interesting and more responsive readme file, with images and tools to help the UX, this is something I wish to develop for future projects. 

###  Acknowledgments
- I would like to thank my wife Jacqui for helping to test my site and to provide feedback on the look, feel and content. 
- I would like to thank Roo at CI as when i was a little stuck on a tricky aspect I spoke with him and this helped to figure the problem out. 
- - - -
