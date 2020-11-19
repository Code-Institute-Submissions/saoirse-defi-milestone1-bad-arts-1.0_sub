Bad Arts Entertainment Webpage

This webpage has been designed for a Limerick based rap label which represents 8 distinct artist/group of artists.
The objective of the project is to create a one-stop shop for Bad Arts Entertainment which can pull their media from several different websites (tweets, music released on Bandcamp & videos from Youtube).
It will also be used as a promotional tool to advertise album releases, merchandise and previous concerts they have done while also allowing the label to build a community of fans.


UX

Bad Arts Entertainment already have a previously designed logo, an orange smiley face on a black background with red lettering.
Before I started the design process, I wanted to create a user interface which worked in haromony with their logo & brand indentity.
Irish rap music is quite a niche genre and the UX had to engage this small target audience. 
To reflect the tone of the music, I used a black background with the logo's bold orange colouring and an olive green as a secondary colour to balance out the colour scheme.
The main font chosen was Grenze Gotisch which has been used on several prominent rap albums and is now considered to be a part of rap culture.




User Stories

As a fan of Bad Arts Entertainment I want:

1. The ability to easily find music and videos from each individual artist so that I can listen to a specific artist depending on what mood I'm in.
2. A clearly defined navigation bar so that I can move around the site effectively.
3. Information pertaining to each artist and their connections with each other to get a better understanding of the label as a whole.
4. A place to be able to purchase physical merchandise/album releases or digital music files.
5. A way to view their social feed without having to leave the webpage.


As a music venue promoter:

1. A place to review the label's music and videos to see if they are a suitable act for their venue.
2. A way to get in contact with the label in order to book one or several of their artists for concerts.


Existing Features

Homepage:

A navigation bar containing 7 links and the company logo on either side allows users to traverse the website with ease.

A carousel containing 8 items enabling fans to select a specific artist's profile.

A row of 4 cards, each one containing an image, text and a link allows club promoters to view previous press releases.

A footer containing 3 distinct sections: 
Quick links (5 links) which gives site visitors another way of navigating the site without having to scroll to the top of the page, 
The company bio (h2, paragraph & 4 button links) which allows users to find out more about the label as a whole & also giving them links to Bad Arts content on 4 external sites. 
& a contact form (one email input & one text input) giving music promoters a way to reach out to the label.


Artist's page:

A grid layout using 3 columns and 5 rows.

The top column contains an image then an h2 with a paragraph underneath and then an iframe.

The second row contains an iframe across 2 columns and the rest of the bandcamp iframe.

The third row is the same as the second.


Shop:

A H2 header

A grid of image link, 3 columns & 3 rows with a text overlay on hover.


Events:

3 card, each card containing an image, a h2 header and a paragraph underneath.


Social:

An iframe.



Features Left to Implement

Working backend needs to be created for the contact form and merchandise page.

Would like to make the footer collapsable so when there is no content, the footer moves up to meet the last visible piece of content.



Technologies Used

JQuery 
https://jquery.com/ - The Jquery script tag is required in order to load Bootstrap.

Bootstrap
https://getbootstrap.com/ 
Bootstrap was one of the technologies that was requested for us to use for our milestone project. 
I decided to use this framework to implement several features on the site including the navbar, a carousel and a grid containing 4 cards (each having an image, some text and a link).


CSS grid
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
Having learnt about grid layouts from the Bootstrap example, I decided that I wanted to learn how to implement them natively using CSS.
All other grid layouts, such as the footer, artist's profile, shop and videos page have been programmed using CSS grid.

Youtube Video Embedding tool
https://www.classynemesis.com/projects/ytembed/
This technology was used to convert youtube videos into html iframe elements.

Image Resizer
https://picresize.com/
At times, working with images can be a difficult task. This free image resizing website has helped me tremendoulously with my milestone project.

Google Fonts
https://fonts.google.com/
The site used to choose and implement custom fonts.

Icons
https://fontawesome.com/
Website used to source footer icons




Bugs Discovered:

Bug #1: Navbar on mobile - The navbar dropdown tile works on every page besides index.html

Bug #1: [FIXED] Dropdown on index.html - After asking help from the tutor team at Code Institute, we found that the issue was arrising due to the z-index of the navbar in relation to the carousel. The navbar has now been given a z-index:10

Bug #2: Navbar on mobile - The navbar dropdown menu had a transparent background and was not pleasing to the eye of the viewer.

Bug #2: [FIXED] Mobile navbar transparent background

Bug #3: Mobile event feed - Cannot get event-single elements to display as block which I believe will look more pleasing on mobile.

Bug #4: All cards not behaving the same #accordion - BMD and Field don't have the expand icon.

Bug #5: Connecting 2 carousels together not working video.html

Bug #5: [FIXED] Wrote a JS script to connect carousel-video to carousel-video-info

Bug #6: Cant stop the carousel automatically transitioning


Credit


General CSS knowledge:

https://www.youtube.com/watch?v=jx5jmI0UlXU&t
https://www.w3schools.com/cssref/css3_pr_background-size.asp
https://www.w3schools.com/css/css_align.asp
https://www.w3schools.com/css/css3_object-fit.asp
These videos and articles helped me understand certain cructial CSS properties such as position, background, object-fit and text-align.

Form Styling:

https://blog.logrocket.com/how-to-style-forms-with-css-a-beginners-guide/
I don't believe that I copied any code directly from this site but it influenced my decisions relating to the footer contact form styling.

CSS Grid:

https://www.youtube.com/watch?v=wfXz8rW_fUs&list=PLOPo1bGrV4htxbQCS3CPZ59O1kpPdE7PK
This video helped me get my head around CSS grid and its power to create more complex layouts. 
Even though I didn't take code directly from this video, it influenced my project greatly.

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Box_Alignment_in_CSS_Grid_Layout
https://stackoverflow.com/questions/43747185/force-css-grid-container-to-fill-full-screen-of-device
These articles helped me with more nuanced issues that weren't covered in the youtube video mentioned above.


Hover text effect associated with shop.html:

https://www.youtube.com/watch?v=ltxxNidblts


Bootstrap Navbar and issues Associated:

https://stackoverflow.com/questions/44988543/bootstrap-navbar-transparent-on-mobile
https://stackoverflow.com/questions/22383547/bootstrap-dropdown-menu-is-not-working
https://stackoverflow.com/questions/19204937/div-doesnt-position-itself-below-bootstrap-fixed-navbar
I used these stackoverflow articles to troubleshoot the bugs outlined in the above section.


Internal Links:

https://www.yourhtmlsource.com/text/internallinks.html
I've implemented for one of the buttons on the navbar to bring you to the bottom of the page, to the contact section.



Media


Bad Arts Entertainment Videos & Images:

This section will cover the majority of videos and images used in this project. 
As this site will be used by a real musical organisation, I was given permission to use any videos or images owned bt Bad Arts Entertainment.


External Images:

In shop.html I have used 5 external images sourced from google images using the search term 'merch'.





Deployment

How to run this project locally:

To clone this project into Gitpod you will need:
1. A Github account
2. Use the Chrome browser

Then follow these steps:
1. Install the gitpod browser extensions for Chrome
2. After installation, restart the browser
3. Log into gitpod with your gitpod account
4. Navigate to the github project repository
5. Click the green 'gitpod' button at the top right corner of the repository
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally


To work on the code within a local IDE such as VScode:
1. Follow this link to the github repository
2. Under the repository name, click 'clone' or 'download'
3. In the clone with the https section, copy the clone URL for the repository
4. In your local IDE, open the terminal
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone', and then paste the URL copied in step 3

git clone https://www.github.com/USERNAME/REPOSITORY

7. Press enter. Your local clone will be created.




Testing