https://kimpea.github.io/

FIRST MILESTONE PROJECT

Author: Kimberley Pearton
Date: 31/07/2018

Introduction:
This is my first milestone project for the user centric front-end development module.
I have decided to use the materials provided by Code Institute and therefore my project is a website for The Monkees, a 1960s rock band,
that provides information to their fans including mini biographies of band members, past and upcoming concert dates, newsletter subscription,
a Spotify widget, soundtracks and a music video, and a contact form for users to hire the band for events. The website consists of five webpages.
I have used Bootstrap 3 to help make the website responsive with all screen sizes and also to take a mobile-first approach. 

Each page has a header and a footer, with a means of navigation in both, allowing the user to navigate the site at ease.

"Home" includes:
    - Link to Amazon allowing the user to buy the album that is displayed above the link button.
    - Link to music.html for soundtracks
    - Link to contact.html for bookings
    - Newsletter subscription form
    - 'Daydream Believer' music video
    
"News" includes:
    - Information on past concerts with links to the venues that they took place in
    - An image (credit: George Bekich II/Las Vegas News Bureau via Getty Images) taken when the members performed at Green Valley Ranch on Aug. 10, 2013 in Las Vegas, Nevada
    - Newsletter subscription form
    - Information on upcoming concert dates with links directing user to the venue website that sells the tickets
    
"Music" includes:
    - Soundtracks provided by Code Institute, including 'Daydream Believer', 'Last Train To Clarksville', 'I'm A Believer' and 'Steppin Stone'.
    - Information on each soundtrack including an album cover
    
"About" includes:
    - Mini biographies on each member of The Monkees - Davy Jones, Micky Dolenz, Michael Nesmith and Peter Tork.
    - Research has been collected from IMDB biographies, IMDB quotes, www.biography.com, www.allmusic.com and member websites.

"Contact" includes:
    - A form that users can complete to hire The Monkees to perform at a certain event.
    
UX DESIGN:

Strategy - The website is targeted towards fans of The Monkees and therefore must contain information regarding upcoming concert dates, soundtracks and music video to listen to/watch, a means of hiring the band for events and a way of keeping up to date with the band.

Scope - Features navigational links, links to external websites, form for newsletter, audio and video, images, form for hiring band, Spotify widget and social media links.

Structure - Contains header with logo and core navigational links, and a footer with navigational links, a Spotify widget and social media links. These will remain in the same position on each webpage. Each page contains section of content in the middle, with "boxes" differing in sizes (with Bootstrap grid system) to contain the content.

Skeleton - Header contains navigational links to 'Home', 'News', 'Music', 'About' and 'Contact' that do not open an external browser window. <section> in 'Home' contains an external link to Amazon displaying an album that is available for the user to buy if they wish to. It also contains a link to 'Music' and 'Contact'. Footer contains core navigational links, a Spotify widget and social media links.
    
Surface - Bootstrap 3 is being used to make sure the website remains responsive across all device screen sizes. Media queries have been used to fix minor issues with main content in <section> on each page. I have decided to maintain a minimalistic yet classic style to the website to enhance the theme of a 1960s rock band. All content is visually easy to access according to testers of different age groups. 

Fixes have been documented through Git commits, however, throughout the project I mainly encountered general issues with making my website responsive on most popular device screen sizes.

WIREFRAME/MOCKUPS:
I did start using Pencil to help me visualise how I wanted my website to look, however, I chose to plan the layout on pen and paper as this was quicker and easier for me to write down notes and add in new ideas.

BOOTSTRAP/CODE SAMPLES:
Throughout the project, I had to carry out research on web layouts that I wanted to implement into my website, but did not know how to. With the help of Bootstrap 3 and Bootsnipp, I was able to do this. For example, I researched the code for a header and footer on Bootsnipp that I felt would be suitable for my website, and I learned how this code worked whilst styling it to my own needs. As the project went on, I was using less research from Bootsnipp, and using more of my own code as my understanding of Bootstrap became clearer. 
    
TESTING THE PROJECT:
I tested out my project by using the Google Chrome developer tools - with this, I was able to see how my website responded on different screen sizes, and as a result of this, I was able
to fix several issues I was having with specific devices. I was also able to edit my CSS within the developer tools to see a live preview of my website before amending the CSS in style.css.
From the design brief provided, I researched The Monkees and found that my target audience would be in the age group of 50+, however, I did not exclude other age groups in the planning process.
To test the website fairly, I had three users of different age groups navigate through all of the web pages - as a results of this, a few bugs were found and fixed, including the images throughout
the web page not being responsive and the .box size also not being responsive.

USER STORIES:
User 1 (age 26) stated that the website is very simple and easy to use, with no feelings of confusion of misunderstanding when navigating the site and using the features available. This user liked the Spotify widget in the footer and also the social media links that were available. One suggestion was that the website should have more vibrant colours, however, with the chosen background image, this was not entirely necessary.

User 2 (age 58) stated that the website text was easy to read, and enjoyed the variety of images available. This user enjoyed the soundtracks and music video on the website, and also the newsletter subscription form that appears on multiple pages.

User 3 (age 78) stated that the website catered to all of their needs when it came to being able to listen to the soundtracks, watch a music video and read the mini biographies. This user was also interested in the 'News' page which contained information on upcoming concert dates.

Overall, all three users enjoyed the website's features in different ways, and therefore I believe this website fulfils the needs of all age groups wherever necessary. 
    
DEPLOYMENT:
This website was deployed on 31/07/18. I would like to mention that before this website was deployed, the project was on a different repository (project-one), therefore any fixes/bugs before deployment will have been recorded on that repository (due to difficulties I was having with GitHub pages that are now fixed). However, I did not take action on the majority of bugs until AFTER deployment - this means that the commits for this project are for most of the bugs that I encountered throughout the development stage. 

Additional comments:
Throughout this project I have overcome various challenges, including trying to understand the Bootstrap grid system and how media queries work. Although I have not yet started the Javascript Fundamentals module, I have included Javascript within the <head> of my project to allow the dropdown menu to work on mobile devices. 
