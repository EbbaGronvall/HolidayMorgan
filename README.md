
# Holiday Morgan Website


The Holiday Morgan website is intended for people who want a coverband for their wedding and people who want to know more about the band.

On the website the user will be able to find information about the band and what they are offering, links to their socialmedia and their contactinformation.

For all the text on the site I used s google font called 'Lexend'.

https://ebbagronvall.github.io/HolidayMorgan/index.html



### The website on different screensizes
![Screenshot of the website on different screens](dokumentation\screenshotresponsive.PNG)
### The color scheme
![The colors used for the website](dokumentation\colorpalett.png)

## Features

### Favicon
- Next to the title of the page I have a favicon that is a microphone with notes besides it.
![Favicon](dokumentation\favicon.PNG)

### Navigation
- To the left in the navigation-bar the user can see the bands name: Holiday Morgan and that links to the homepage (index.html).
- Located to the right in the nav-bar they have links to all the pages of the website. This list of links becomes a "hamburger"-icon on screens smaller than 768px to save space.
- The text is a really light blue and the background is dark blue and this makes it easy to read.
- When the user navigates between the different pages the active page becomes underlined to make it easier for them.
- When the screen becomes wider than 992px the link you hover over gets a border around it.

![Navigation bar screen under 768px](dokumentation\nav-bar-under-768px.PNG)
![Navigation bar screen over 992px](dokumentation\nav-bar-over-992px.PNG)

### Homepage
- In the background of this page there is a picture of the band and the div containing the text has a pink semi-transparent background and the text is the same dark blue as the nav-bar.
- On this page the user gets information about what the band offers.
- The picture in the background has position:relative; so when the screen gets wider so does the picture.

![Homepage](dokumentation\homepage.PNG)

### About the band
- At the top of this page there is a picture of the band. This picture has the same style rule as the background of the homepage to make it wider as the screen gets bigger.
- Under the picture we have five different divs that contain information about how the band first got together and a short presentation of each of the members.
-The divs have a class attribute to give them all the same style rules.

!['About the band' page](dokumentation\about-the-band.PNG)

### Contact us!
- This page contains a form for the user to fill out to contact the band.
- The background of the page is a picture of the band and the section containing the form has a pink semi-transparent background.
- First the user is asked to fill out first and last name, their email-adress, their phonenumber and the date of the wedding.
- Next the user has to check the radio-buttons to answer which wedding-package they want and how far from Stockholm the wedding is held.
- To submit the information the user clicks on the "Let's Party!"-button and this will take them to the thankyou.html-page.
- Underneath the form there is a div with contactinformation if the user where to have any questions that did not get answered on the website.

![Top part of contact page](dokumentation\contactpage-top.PNG)
![Bottom part of contact page](dokumentation\contactpage-bottom.PNG)

### Thank you
- When the user have clicked the "Let's Party!"-button they are redirected to a page with a thank you-message that says that the band will get back to you ASAP.
- The page has a picture from the stage in the background and the div with the text stretches across the middle of the page and har the same color as the other divs of the website.

![Thank you page](dokumentation\thankyou.PNG)


### Error 404
- If something is wrong in the URL you will be redirected to a page with an error message.
- The page has a purlple background and the div has a pink background that stretches along the width of the page.

![Error 404 page](dokumentation\error404.PNG)

### Footer
- Fixed to the bottom of all the pages there is a footer.
- The footer has the same colors as the nav-bar at the top.
- The footer contains one h3 element and three anchor elements.
- The anchors are links to the bands different socialmedia.
- The footer has style rules that makes the anchors space evenly as the screen gets wider.

![Footer on smaller screens](dokumentation\footer-small.PNG)
![Footer on wider screens](dokumentation\footer-wide.PNG)


## Testing

- I checked to see that the website works on the browsers: Chrome, Microsoft Edge and Safari.
- By using devtools I confirmed that the pages of the website are responsive and looks good on standard screen sizes.
- I checked that the whole website is readable and easy to understand by running it through https://wave.webaim.org/.
- I have confirmed that the form works by trying to submit it without required information and without an @ in the email-input.
- By submitting a correct form I confirmed that when doing so the user is redirected to the "thank you"-page.
- I confirmed that the 404.html page works by changing the URL. 

### Bugs
#### Solved bugs 
- Initialy I had some problems with my footer. I did not get it to stick to the bottom. Upon further investigation me and my mentor Graeme noticed that the footer element was inside the main element. Moving it so it was bellow the main element but still inside the body element fixed the problem.
- I also had an issue with the contact.html styling. Whatever I did I had to scroll horizontally on smaller screens because the content did not fit. When I removed the really long email address and replaced it with mailto-link followed by an icon of an envelope this resolved the issue as it took up less space. 

### Validator Testing

- HTML 
  - No errors were found when passing the code of every page through https://validator.w3.org/nu/ 
- CSS
  - No errors were found when passing the stylesheet through https://jigsaw.w3.org/css-validator/ 
- Accessibility 
  - I confirmed my websites accessibility by testing it in Lighthouse.

### Results in lighthouse 
### index.html
- Desktop
![Result index.html on desktop](dokumentation\score-index-desktop.PNG)
- Mobile
![Result index.html on mobile](dokumentation\score-index-mobile.PNG)

### about.html
- Desktop
![Result about.html on desktop](dokumentation\score-about-desktop.PNG)
- Mobile
![Result about.html on mobile](dokumentation\score-about-mobile.PNG)

### contact.html
- Desktop
![Result contact.html on desktop](dokumentation\score-contact-desktop.PNG)
- Mobile 
![Result contact.html on mobile](dokumentation\score-contact-mobile.PNG)

### thankyou.html
- Desktop
![Result thankyou.html on desktop](dokumentation\score-thankyou-desktop.PNG)
- Mobile
![Result thankyou.html on mobile](dokumentation\score-thankyou-mobile.PNG)

### 404.html
- Desktop
![Result 404.html on desktop](dokumentation\score-404-desktop.PNG)
- Mobile
![Result 404.html on mobile](dokumentation\score-404-mobile.PNG)

### Unfixed Bugs
No unfixed bugs.


## Deployment

- I deployed the site to GitHub pages early in the process.
- To deploy the website one has to:
   - Go to the settings tab in the GitHub repository
   - On the left side click on "Pages"
   - In the Source drop-down menu you select "Deploy from branch"
   - You then select the main branch and the root folder
   - The website is now live!

The live link to the website: https://ebbagronvall.github.io/HolidayMorgan/index.html

## Credits 
### Content 
- The code to the nav-bar was taken from the CI Love Running Project.

### Media
- All the pictures were provided to me by the band.
