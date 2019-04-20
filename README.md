# Maxx Cafe Website
A static (front-end only) website for a cosy cat cafe located in Bath, UK.

A live demo can be found [here](https://normancheng88.github.io/ci-milestone-project1/).

![alt text](https://github.com/normancheng88/ci-milestone-project1/blob/master/assets/images/website-display.jpg "Website Preview")


## UX


### Objectives
- Increase the customer numbers
- Create an online presence
- Share workshop information

### Users
- Cat lovers who enjoy cafe culture

### Stories
- A user wants to know where Maxx Cafe is located
  - Ability to see the address of Maxx Cafe and a clear pin location on the map

- A user wants to know the details of Maxx Cafe's workshops
  - Ability to subscribe and get the latest workshop information

- A user wants to view the photos of the cats and the interior of the cafe
  - Ability to view the photos in "About Us" and "Our Team" sections

- A user has a general enquiry about the food and drinks menu
  - Ability to call the cafe or fill in and submit an enquiry form online

### Wireframes
- Mobile version: [Home](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/home-mob.jpg), [Home with menu](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/home-menu-mob.jpg), [About Us](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/about-us-mob.jpg), [Our Team](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/our-team-mob.jpg), [Workshop](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/workshop-mob.jpg), [Contact Us 1](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/contact-us1-mob.jpg), [Contact Us 2](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/mobile-version/contact-us2-mob.jpg)
- Desktop version: [Home](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/pc-version/home-pc.jpg), [About Us](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/pc-version/about-us-pc.jpg), [Our Team](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/pc-version/our-team-pc.jpg), [Workshop](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/pc-version/workshop-pc.jpg), [Contact Us](https://github.com/normancheng88/ci-milestone-project1/blob/master/wireframes/pc-version/contact-us-pc.jpg)

### Font
- [Roboto](https://fonts.google.com/specimen/Roboto?selection.family=Roboto) - for all the text on the site

![alt text](https://github.com/normancheng88/ci-milestone-project1/blob/master/assets/images/roboto-sample.jpg "Robot Font Sample")

### Colours
- #fafafa: for titles and text
- #343a40: for "Our Team" section, navigation bar and footer
- #dc3545: for staff names and buttons

![alt text](https://github.com/normancheng88/ci-milestone-project1/blob/master/assets/images/colour-list.jpg "Colour list for Maxx Cafe's site")

## Features

#### Existing Features
- Mobile first
- Navigation bar
  - **Fixed navigation bar at the top:** users can easily reach the navigation menu to return to home or other sections without a need to click on the return button of the browser. 
  - **Hamburger menu:** the navigation bar menu will convert to a hamburger menu when users visit the website on mobile phones or smaller devices. It enhances users' visual experience and users are able to view the information on the website clearly.
  - **Hamburger menu collapse:** When users click on any items in the menu, it will navigate to the selected section and the menu will be collapsed. It provides a great user experience as users can read the information on the website without an extra tap/click to close the menu.
  - **Active link indicator feature:** The item in the menu will be highlighted to indicate which section users are located at on the site.
  - **Smooth scrolling feature:** When users click on any items in the navigation menu, it will smoothly take users to the selected section with a great visual experience instead of the default anchor "jump".

- Carousel
  - A slideshow at the home section to display professional cat photographs to users. Users can view the previous/following photos by clicking on the left/right arrows. The photos will also automatically change to the next one every five seconds.

- Subscription form
  - Users can simply subscribe and get the latest workshop information by submitting their email addresses via the subscription form.

- Enquiry form
  - If users have any questions about the cafe or its workshops, they can fill in and submit an enquiry using the form in the Contact Us section.

- Social media buttons
  - By clicking on the social media button at the footer, users will be directed to the relevant social media page of the cafe, so they can follow the café’s page and read the latest feed.

- Embedded Google Maps
  - In order to help users find the cafe's location easily, the cafe's custom icon has been added on the embedded Google Maps in the Contact Us section. Users can interact by zooming in/out on the map or by enlarging the map.

#### Features Left to Implement
- Reservation feature
  - Users will be able to make a reservation on the site directly.
- Instagram feed
  - Users will be able to see the latest Instagram feed on the website.

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

### UX

Fulfil what users need:
- Able to navigate to each section of the site smoothly without demand of clicking the return button
- Able to view the photos of Maxx cafe and its resident cats
- Able to subscribe for the latest workshop information
- Able to see the contact information for Maxx Cafe and interact with the embedded map
- Able to submit their questions via the Enquiries form
- Able to follow Maxx Cafe on a variety of social media pages
- Able to see the background and mission statement of Maxx Cafe
- Able to see workshop information

### Code

This site was checked with W3C HTML and CSS validators, and no issues were found in the CSS validation. However, after the HTML validation, one issue had been found for the value attribute of the submit and subscribe buttons. The value attribute had been provided correctly but the equals sign was missing for both value attributes, ```value "subscribe"``` and ```value "submit"```. Once I had updated the ```value="subscribe"``` and ```value="submit"``` attributes and ran the HTML validation, the issue was resolved and no other issues were found.  

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

### Features

1. Navigation bar:
- Click on the company icon: it scrolls back to the home section 
- Click on each icon: the website scrolls up/down to take users to the specified section
- The navigation bar converts into a "hamburger menu" when the website is being viewed on mobile or smaller devices
- "Hamburger menu": click on each item to ensure that it brings users to the specified section of the site and the menu automatically collapses
- Active link indicator feature: scroll up/down to each section and verify that the correct item at the navigation bar is active and in white colour

2. Subscription form in Workshop section and Enquiries form in Contact Us section:
- Try to submit the empty form and make sure that an error message about the required fields appears
- Try to submit the form with an invalid input/email address (such as 22222 and norman"gmail.com) and ensure that a relevant error message appears
- Try to submit the form with all the valid inputs and confirm that a success message appears

3. Embedded Google Maps in Contact Us section:
- Desktop
  - Click on the cat icon and verify that the details of Maxx Cafe appears
  - Click on zoom in/out button and verify that the map is zoomed in/out accordingly
  - Click on the enlarge button and verify that a new window showing the large size map is open and displays with a cat icon
- Mobile
  - Tap on the cat icon and verify that the details of Maxx Cafe appears
  - Tap on zoom in/out button and verify that the map is zoomed in/out accordingly
  - Try to zoom in/out with two fingers and verify that the map is zoomed in/out accordingly

4. Social media icons in the footer:
  - Hover over each social media icon and ensure the hover feature is active and the colour of each icon changes to match the official logos
  - Click on each social media icon and verify that each icon opens the link of the relevant social media page in a new tab using ```target="_blank"```

### Browsers and devices

This site was tested across different browsers and on different devices to ensure that this site is responsive and compatible. During testing, I noticed that ```background-attachment: fixed``` for the background photo was not compatible with mobile devices. On Safari in iOS, the background photos appeared blurry and without the feature of ```background-attachment: fixed```. However, it is working properly and compatible with all the browsers in desktop. This bug will be resolved in the future implementation.
During the testing on iPhone XS, the site was fitted on its screen, but two photos in the "About Us" section kept refreshing themselves. I tried to comment out the transition and filter properties in CSS but the bug still persisted. After further investigation, I noticed that there was a language translate plugin installed on my friend's iPhone XS. The bug was fixed and photos now display correctly when the plugin is disabled.

When testing on iPad in Chrome's Developer Tools, the site was working properly but all the text, icons and photos were too small. To resolve this issue, I have added 'media query' to each section with 'min-width: 768px' and different CSS properties to resize the text, icons, photos, padding, etc. to ensure that features are more user-friendly and all text is readable. 


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
This site is coded in Cloud9 IDE, a local Git directory was used for version control. It is
hosted by using GitHub, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named ```index.html```.


## Credits

### Content
The content in all sections of the site are written by me.

### Media
All photos, including background photos, were taken from [Pexels](https://www.pexels.com/).


### Acknowledgements
The smooth scrolling and active link indicator features were found [here](https://www.youtube.com/watch?v=x0YnVwAuNQI) in this tutorial.

The media query for different device sizes were found [here](https://gist.github.com/gokulkrishh/242e68d1ee94ad05f488).

The wireframes were created through [Marvel](https://marvelapp.com/).