

# **CBBridge Website**

This website is designed for a ficticious Bridge Club called CBBridge. Bridge is a popular card game played by many people but suffers from a poor image The idea was to promote the CBBridge club in a contemporary and user-friendly way and to recruit students and players.
![CBBridge mainpage](assets/images/screenshot-calloutpage.png)

[View the deployed site here](https://conacbreslin.github.io/CBBridge/)


## User Experience (UX)
A visitor to this page would be a person interested in learning bridge, or an existing bridge player looking for somewhere to play bridge.  
On visiting the site they should be able to 

- Understand the purpose of the site
- Understand the content/layout of webpage from the main page
- Easily navigate to find out information about Bridge in general
- Easily navigate to find out information on Bridge classes and sign up for them
- Easily navigate to information on Bridge play and sign up to play
- Easily navigate to the Contact form and send information from there
- Easily return to the main page from all sections


## Strategy

A search of existing Bridge club websites shows there are very many bridge clubs with websites, but the vast majority are created with a generic template from an organisation called <a href="https://www.bridgewebs.com/">Bridgewebs.com</a>. This provides a simple and easy way to create a webpage from a generic template which is tailored to the needs of most bridge clubs but has resulted in an overwhelming sameness of the sites and this bridge club wanted to create something different.
Following background research with both bridge players and non-bridge players [see results here](assets/pdfs/background-research.pdf). It was felt that the website needed to cover the following 3 areas. 

- Addressing the barriers to starting bridge.
- Providing information on classes and the ability to sign up
- Providing information on play and the ability to signup.

In addition it was felt that the site would need interactive features to encourage visitors to engage with the site and return to the site in the future.
The websites opportunities to meet these needs and the feasibility of achieving them were quantified and plotted to help decide what would be included in the initial release [(see them here)](assets/pdfs/importance-feasibility.pdf)

Consequently the opportunities to be included in the first release included

- Creating an online presence
- Addressing barriers to starting bridge<
- Providing information on lessons/play
 -Providing an opportunity to recruit students and players	

Objective Requirements;         The user will want to enrol in Bridge classes or Bridge play.<br>
Functional requirements; 	    To achieve this the website will provide them with relevant information that takes into account the research findings and the site will include the ability to sign up to the club from website. <br>
Non functional requirements; 	The level of interactivity and complexity of the site will be limited by both the skill set of the person compiling the website and the likelihood that a significant proportion of people seeking bridge classes/play may be mature and may not have the technological skills of a younger demographic.<br>
Business rule requirements;     The site will conform to data protection regulations


## Structure

As the quantity of information on the website was not extensive a single page linear structure was planned. Users will be a given a navigation bar at the start and a return to home button as the page scrolls down. The contact/submission form will collect minimal information and have dropdown menus to help people include their ability level and buttons to select if they are interested in classes, play or both.</p>

## Skeleton
The page starts with an alert banner and navigation bar followed by a simple hero image with immediate links to classes and play. This is followed by sections addressing each opportunity identified and finally a form for signing up. The footer has additional information links, social media links and a map. These are laid out in three Balsamiq wireframes for [mobile](assets/wireframes/mobile)
, [mediumscreens](/assets/wireframes/balsamiq-medium-view.bmpr),  and [desktop](/assets/wireframes/balsamiq-desktop-view.bmpr”)
The site has a modal addressing the adaption of the club during COVID-19 restrictions.

## Surface/Design

- Imagery; The hero image was a key aspect of the site it was found in [unsplash.com](https://unsplash.com/) and was chosen to convey a contemporary, modern feel.
- Colour scheme; [IMAGECOLORPICKER.com](https://imagecolorpicker.com/) was used to find the hex value of the backgound colour in the hero image and this was used in [coolor.co](https://coolors.co/)) to generate [this colour palette](assets/images/colour-palette.png) which was felt to be contemporary and subtle.
- Typography; The Comfortaa font was selected in [Google fonts](https://fonts.google.com/) for its clarity and contemporary feel and Google fonts suggested Montserrat as an accompanying font and its simplicity was appealing.


## Features

- Responsiveness on all device sizes.
- The Alert banner disappears on small screens.
- The Navbar collapses and dismisses on tap on small screens.
- The homepage is clear with obvious links to all sections and conveys the image of a modern club that is also sociable and fun.
- The About Bridge Section gives a brief outline the game of bridge and provides links to more in-depth information.
- The Learn Bridge with Us section gives information on all aspects of classes.
- The Play Bridge with Us section gives information on all aspects of play.
- The Sign Up section collects user information and allows the user to sign up, and has a Modal to alert visitor to changes due to Covid restrictions.

## Future features

In the future it would be anticipated that the site would
- Have less text in sections that can be truncated with an ellipsis and a ‘read more’ option
- Provide a members’ section that could be logged in to
- Provide an online discussion forum for bridge problems
- Provide interactive bridge hands and quizzes

## Languages used
HTML5

CSS3

## Frameworks, Libraries and online resources used
- [Balsamiq](https://balsamiq.com/wireframes/)was used to create the wireframes
- Gits's [gitpod](https://www.gitpod.io/) was used for writing and editing code
- [GitHub](https://github.com/) was used for storing the code after being pushed from Git
- [Bootstrap 4.6.1](https://getbootstrap.com/) was used to help keep design responsive and to help styling.
- [jQuery](https://jquery.com/) came with Bootstrap to make the navbar response
- [Google Fonts](https://fonts.google.com/) was used to import the ‘Comfortaa’ and ‘Montserrat’ fonts into the style.css file.
- [zyro.com](https://logo.zyro.com)  was used to create the logo
- [Bootstrap icons](https://icons.getbootstrap.com/) was used to import the icons
- Photos were used from [unsplash.com](https://unsplash.com/)
- Photos were used from [pexels.com](https://www.pexels.com/) 
- [online-image-editor.com](https://www.online-image-editor.com/) was used to edit images
- [tinypng.com](https://tinypng.com/") was used to resize images
- Pixillion image conversion software from [nchsoftware.com](https://www.nchsoftware.com/imageconverter/index.html) was used to create the favicon
- <a href="https://www.101computing.net/html-how-to-add-a-favicon/">101computing.net</a> was used to help insert the favicon
- code from [ourcodeworld.com](https://ourcodeworld.com/articles/read/307/how-to-create-a-responsive-table-with-css) was used to make the tables responsive
- code from [css-tricks.com](https://css-tricks.com/) was used to import the background image
- code from [codeply.com](https://www.codeply.com/go/PqIBtz3HPL) was used to create	dismiss-on-tap
- code from [stackoverflow.com]() was used for media object and finding fixes for bugs
- code was formatted using [webformatter.com](https://webformatter.com/html)

## Testing

Testing User Stories from User Experience (UX) Section

## Manual Testing

The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
The website was viewed on a variety of devices. Links were repeatedly tested. Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues. THe code was submitted fro peer-review in slack.com (LINK)
[Log of manual testing]()

## Code Validation.

The site’s html validation was tested repeatedly by direct input into
[validator.w3.org](https://validator.w3.org/) and the results of these logs and fixes are documented [here]()


## Style validation

The site’s css validation was tested repeatedly by 
[jigsaw.w3.org](https://jigsaw.w3.org/css-validator/ttps://validator.w3.org/") and the results of these logs and fixes are documented [here]()


## Lighthouse Audits

The site’s Performance, Accessibility, Best Practices and SEO were auditted repeatedly by 
[Chrome Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk) and the results of these logs and fixes are documented [here]()

## Changes over course of development

It was decided to use a sticky navbar which removed the need to 'return to top' buttons in all sections.
The modal was temporarily abandoned as complicating the submit procedure but was then simplified and reinstated.

## Known Bugs
There is a paragraph inside the iframe to advise users if their browser does not support it, validator.w3.org calls this an error as it says says  text is not allowed in the iframe.Howeverr Code Institue teaching and [stackoverflow.com](https://stackoverflow.com/questions/13523260/javascript-and-iframe-not-supported-in-browsers-other-than-ie/13523382#13523382) permit this.

## Deployment

GitHub Pages
The project was deployed to GitHub Pages in the following way. 
1.	Log in to GitHub and locate the [GitHub](https://github.com/)   
2.	At the top of the Repository locate the "Settings" Button on the menu.
3.	Scroll down the Settings page to the "GitHub Pages" Section.
4.	Under "Source", click the dropdown called "None" and select "Master Branch".
5.	The page automatically refreshes.
6.	Scroll back down through the page to locate [link to the published site](“ https://conacbreslin.github.io/CBBridge/”)  in the "GitHub Pages" section.
Forking the GitHub Repository
The  GitHub Repository can be forked to make a copy of the original repository on the GitHub account to view and/or make changes without affecting the original repository in the following way.
1.	Log in to GitHub and locate the [GitHub Repository](https://github.com/ConacBreslin/CBBridge) 
2.	At the top of the Repository (not top of page) above the "Settings" Button and over to the left locate the "Fork" Button.
3.	You should now have a copy of the original repository in your GitHub account.

Making a Local Clone
1.	Log in to GitHub and locate the [GitHub Repository](https://github.com/ConacBreslin/CBBridge) 
2.	Under the repository name, click the dropdown button marked “Code” and then select "Clone or download".
3.	To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4.	Open Git Bash
5.	Change the current working directory to the location where you want the cloned directory to be made.
6.	Type git clone, and then paste the URL copied in Step 3.
7.	Press Enter and the local clone will be created

## Credits

- Background image:	Photo by Jarosław Kwoczała on Unsplash
- Lady-one photo: 	Photo by Kayla Farmer on Unsplash
- Man-one Photo: 	Photo by Can yılmaz on Unsplash
- Lady-two photo:  	Photo by Anderson Guerra from Pexels
- Man-two photo; 	Photo by Italo Melo from Pexels

## Content

All content was written by the developer

## Acknowledgements

I would like to thank my mentor Chris Quinn for sound advice and support
I would like to thank many tutors in Code Institute for being unfailingly helpful and nice, in particular Alan, Mikos, Tim, Jo, Igor and Fatima.
I would like to thank Stephen Seagrave for his [excellent presentation](https://us02web.zoom.us/rec/play/zZzrdRcJ1Gz9isoaRTUcHNhB1VEqzkhcI4kkOUXEbTGTShtMaNQEpxYE7dW214K5X2OWveSRPLL-oWtA.5EMQT2YvoO2ZLIox?autoplay=true) on MS1 projects that I referred to repeatedly
Finally I would like to thank my family and friends for support and feedback and in particular the hilarious [comments about bridge](assets/pdfs/background-research.pdf) that always made me laugh!

