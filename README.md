# User-Centric-Frontend-Milestone-Project

The Link to the deployed page is [User-Centric-Frontend-Milestone-Project](https://craigf20.github.io/User-Centric-Frontend-Milestone-Project/)

This is my first webpage and my idea was to make an online Portfolio/ Resume for my wife. The overall idea for the website is to promote her in a way where she is able to get hired for work within the Journalism world. It is aimed to promote her work and skillset to potential employers with scope for people to get in touch with her too.

The fonts are coming from Google Fonts which can be seen across all pages.

The smybols are coming from Font Awesome for all pages that use them.

<hr>

<h3>About Page:</h3>

- The (About) page/ first page is designed to be an introduction to the person which contains their current job, full name and a little bit of information about them. The first box contains this information along with an profile image, however, this doesn't currently have the actual persons photo. 

- Not far below the profile page is the links to Social Media, these do not take the user directly to the persons Social Media pages but to the login pages, this has been done intentionally. The links work and have been tested to make sure they fuction as well as the colour changing when a user hovers over them with the mouse. The symbols for the Social Media links have come from Font Awesome. 

- Just below the Social Media links there is a contact form. This has been designed so that whoever opens the page and wishes to get in touch then they will be able to do so. The input boxes have been desgined so they change colour to make it clear to the user where their mouse is or which field they are in. The name fields as well as the email field has been made "required" before the form can be submitted, now the form will not go anywhere in particular as of yet, but it is set up ready for that functionality. There is a small break between the title for the contact form and the actual fields, this has been coded and designed in the css file.

- The About page is the code in the "index.html" file and is pulling the styling from the "style.css" file. This was the first page I created for the website, I cannot say I ran into many if any difficulties when it came to creating any of the elements on this page. 

<hr>

<h3>Experience Page:</h3>

- Now the "Experience" page follows a similar design to that of the "About" page with the same background and same layout of the Social Media links and container. The "Experience" page has been designed to show the skills and qualifications the person has and what they can bring to a new job within their field of work. 

- I put the page title in its own box just to clarify for people which page they are on just in case, following the same colour scheme and design as the rest of the page.

- From here I moved on to moving the profile image to the left of the container and making it smaller to keep the same design layout but also to remind the user who's profile they are looking at. In the first box I decided to put the persons' educational history to show where they went to get their qualifications but also the projects they were invloved in when there. 

- Box beneath is the timeline box which contains the 'Work Experience' to show their previous history of working within that field. I liked the timeline look and thought I would impliment it within my page coming out with the current result. This was interesting to make and I believe having this information set out in this way is useful for both the user and the one who is made for. 

- Next is the "Awards" box, this is small snippet of information given to me to promote the intended person better as these are transferable awards. This box followed the design layout made in the wireframes along with the same design as the other boxes. Having the "Awards" box at the bottom keeps the other information easily readable and the reader sees the key information first, then the extras. Again the symbols are coming from Font Awesome. 

- Overall this page is using the code in the "Experience.html" file and pulling the styles from the css file called "style-experience.css". I thought it would be easier to just create a second css stylesheet for this page as it prevents conflicts with the original stylesheet. With this it allows me to style the second page without ruining the first page.

- The Social Media links/ container has the same settings as the About page. They take the user to the same things across the board. 

<hr>

<h3>Portfolio:</h3>

- The "Portfolio" page is designed with the user being able to go straight to some articles written by the person to demonstrate some actual previous work. 

- I have followed the same layout and styles from the first two pages, keeping it in line with having a scrollable website. It mainly follows the same design as the "Experience" page in having a title followed by three containers with information. 

- Each of the containers have the titles of the businesses previously worked at along with the names of the articles and working links to those pages. Followed by a button within the container that takes the user to the work profile of whom I'm trying to promote. I set it out this way because it is simplistic, so there isn't an overload for the user and as well as this it presents the person has a nice portfolio behind them already that should be displayed. 

<hr>

<h4>Problems encountered & solutions:</h4>

My first problem was creating effective 'Media Queries'. The issue at hand was making sure the webpage will fit on all screen sizes but every method I tried the page didn't display correctly when on a smaller device. 

- Now the solution was a simple fix that is down to memory, it was a simple matter of putting the bigger screen queries first then working down in size, 1024px in width down to 300px. It wasnt until I had written the whole code for each screen size did I remember that the code is read from top to bottom, last thing read is the last to be displayed, so I swapped how I had originally had laid it out and the problem was no more.

Another issue I had, which didn't take as much time to work out as the first one was getting a functioning button to take the user from my webpage to the associated website without closing the original. 

- The solution to this that I used was to make the button using the "METHOD and ACTION" form. It worked well and didn't take long to figure out. 

One of the other issues I came accross was having the elements sit correctly on the page based upon the designs I had created. 

- Solution to this was re-visit the margins lessons and check over my notes about padding and position classifications. It was a matter of re-freshing my memory on these elements. Once I had made the connections on how to do this on the first page it was easily transferable to the other two, no issues after that. 

<hr>

<h4>Testing and Deployment:</h4>

Testing for me has been continuous when it came to putting this site together. So after writing a segment of code either in the css stylesheets or actually on the page I would check how it looked in the live-view to guage how it looks in reality. 

Doing it this way I realised was somewhat time consuming so I decided to begin editing the code within the live-view system, for me it was the Google Chrome Developer tools, which made it quicker for me to see how the changes would affect the overall layout and design. Now testing the site this way allowed me to see how things would look on a laptop screen as well as the sizes smaller, like tablets and phones. 

Using this I was able to design the site to be viewed on smaller screens in comparision to just laptops, in doing so I hope I have been able to make a responsive website. 

Having the website open when coding it and just refreshing the page when something new was added was a great help and as well as this it allowed me to test my Social Media links straight away. I tested each one during making them one after another, then tested them on all the following pages. With each working I was happy they are reliable enough to use. 

The buttons on the navigation system of course was tested in a similar process, write the code and then see if they work on the preview version of the site. With each page being made I made sure they worked in all three. As well as this, they needed to allow the user to go between all pages otherwise they are redundant, gladly all working fine. 

The later buttons within the "Portfolio" page was tested the most to make sure they fully wokred. To test correctly I would write the code, refresh the preview version and click them to see if they did as they were supposed too. After getting one right it was a matter of copying and pasting, just changing the desired URL in each afterwards then making sure it took me there without closing the original page. All working well. 

<hr>

<h4>Future Developments:</h4>

Animated images

- The images on the website could be looked at to be made animated as I think this could add another aspect of design overall. Having some kind of animation on the images might be a good idea to allow users to get a better experience overall with the website and get a better understanding as to who they are looking at. 

More pages 

- There is possible scope to add extra pages as things may change in future years. The possibility of extra pages is down to if I want to upload the persons' Resume for it to be downloaded, previews of social media pages, images etc. 

Actual User images

- I can change the stock image for the profile to the actual user I am attempting to promote as this will of course affect hireability. This could also give me room to put more than one image there if the user would want that. 