# Maxx Cafe Website
A static (front-end only) website for a cozy cat cafe located in Bath, UK.

A live demo can be found [here](https://normancheng88.github.io/ci-milestone-project1/).


## UX


## Features

#### Existing Features
- Mobile first
- Navigation bar
  - **Fixed navigation bar at the top:** users can easily reach the navigation menu to return to home or other sections without a need to click on the return button of the browser. 
  - **Hamburger menu:** the navigation bar menu will convert to a hamburger menu when users visit the website on mobile phones or smaller devices. It enhances users' visual experience and users are able to view the information on the website clearly.
  - **Hamburger menu collapse:** When users click on any items in the menu, it will navigate to the selected section and menu will be collapsed. It provides a great user experience that users can read the information on the website without an extra tap/click to close the menu.
  - **Active link indicator feature:** The item in the menu will be higlighted to indicate which section users is located at on the site.
  - **Smooth scrolling feature:** When users click on any items in the navigation menu, it will smoothly take users to the selected section with great visual experience instead of the default anchor "jump". 

- Carousel
  - A slideshow at the home section, to display professional cat photography to users. Users can view the previous/next photos by clicking the left/right arrows. The photos will also automatically change to the next one after every few seconds.

- Subscription form
  - User can simply subscribe and get the latest workshop information by submitting their email addresses in the subscription form.

- Enquiry form
  - If users have any questions about the cafe or workshop, they can fill in and submit the enquiry form at the contact us section.

- Social media buttons
  - By clicking on the social media button at the footer, it will direct users to the certain social media page of the cafe, so users can follow the cafe's page and read the latest feed.

- Embedded Google Maps
  - In order to let users to find the cafe location easily, cafe's custom icon has been added on the embedded Google Maps at the contact us section. Users can interact by zooming in/out on the maps or enlarge the maps.

#### Features Left to Implement
- Reservation feature
  - Users will be able to make a reservation on the site directly.
- Instagram feed
  - Recent Instagram feed will be displayed in a new section, Gallery, of the website.

## Technologies Used
- HTML5
- CSS3
- [Bootstrap 4](https://getbootstrap.com/)
  - Site layout, navigation and photos
- [jQuery](https://jquery.com/)
  - Smooth scrolling feature
  - Active link indicator feature
- [Font Awesome](https://fontawesome.com/)
  - Used for all the icons on the site
- [Google Fonts](https://fonts.google.com)
- Bash
- Ubuntu
- Git
- GitHub
- Google Chrome developer tools
- Cloud9 IDE

## Testing

This site was checked with W3C HTML and CSS validators, no issues were found in the CSS validation. However after the HTML validation, one issue had been found for the value attribute of the submit and subcribe buttons. The value attribute had been provided correctly, however the equal sign was missing for both value attrbiutes, ```value "subscribe"``` and ```value "submit"```. After updated them to ```value="subscribe"``` and ```value="submit"``` and run the HTML validation, this issue was resolved and no other issues found.  

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

1. Navigation bar:
  - Click on the company icon: it scrolls back to the home section 
  - Click on each icon, each icon scrolls up/down to take user to the specified section
  - The navigation bar converts into a "hamburger menu" when the screen reaches to smaller size or mobile size
  - "Hambrger menu": click on each item will bring you to the specified section of the site and the menu automatically collapses.

### Browsers and devices

This site was tested across different browsers and on different devices to ensure that this site is responsive and compatible. During the testing, I noticed that ```background-attachment: fixed``` for the background photo was not compatible with mobile devices. On Safari in iOS, the background photos appeared blurry and without the feature of ```background-attachment: fixed```. However, it is working properly and compatible with all the browsers in desktop. This bug will be resolved in the future implementation.

During the testing on iPhone XS, the site was fitted on its screen, however I realised that there were two photos at the "About Us" section kept refreshing themselves. I tried to comment out the transition and filter properties in CSS but the bug still persisted. After further investigation, I noticed that there was a language translate plugin installed on my friend's iPhone XS. The bug was fixed and photos were displaying correctly when that plugin was disable. 

When testing on iPad in Chrome's Developer Tools, the site was working properly but all the text, icons and photo were too small. To resolve this issue, I have added 'media query' to each section with 'min-width: 768px' and different CSS properties to resize the text, icons, photos, padding, etc. to ensure that those are displaying in a good structure and readible. 


#### Devices:
- Chrome / Android 7 / Huawei P8 Lite
- Chrome / Android 7 / Sony Xperia XA
- Safari / iOS 12 / iPhone SE 
- Safari / iOS 12 / iPhone 6s Plus
- Safari / iOS 12 / iPhone XS
- Safari / iOS 12 / iPad Air 2
- Opera / iOS 12 / MacBook Pro
- Firefox / Windows 10 / MSI Notebook
- Edge / Windows 10 / Dell Notebook
- Safari / macOS Mojave / iMac

## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.


## Credits

#### Content
The content in all the sections of the site are written by me.

#### Media
All photos including background photos were taken from [Pexels](https://www.pexels.com/).


#### Acknowledgements
The smooth scrolling and active link indicator features were found through this tutorial [here](https://www.youtube.com/watch?v=x0YnVwAuNQI).

The media query for different device sizes tutorial were found through [here](https://gist.github.com/gokulkrishh/242e68d1ee94ad05f488).

The wireframes were created through [here](https://marvelapp.com/).



**This is for educational use.**