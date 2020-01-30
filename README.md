
   # Trade Safe TM Milestone Project One
   
   ## Welcome to my Trade Safe website Milestone 1 Project.
   
#### This is a subject I love and the imaginary client who strangely resembles me is what I would love to be in another life: a seasoned market trader! This all came from my own experiences with brokers poor advise and some overpriced training programmes that didn't give much in return. I actually completed the featured Diploma in Technical Analysis (on the Home page as a poloroid) so I could be my own expert; and its that drive to give people the same opportunity to learn real life (and safer) trading, but without rip off prices, that gave life to this website.
#### Assuming potential clients have been Googling key phrases such as "safe share trading methods" and "technical analysis" for example, with some good content marketing they should come across this site. It starts with some hook lines on the home page then flows through a sequence of what training is provided, the booking form for individuals and groups, an embeded YouTube video giving a snippet of the training provided and a general contact form for any other information. I kept the legal information separate in the end as I didnt want to distract potential customers from the main thrust of signing up for training. They can still access it via a dropup menu on the footer which diverts them to a new page from which they can link back to any section of the main website. The aim is to create trust then if they are interested give them a bit more information, then the opportunity to book a place. And if that isn't enough they get to sample the training content and then ask questions if need be. The site offers free external links for more market information to cement trust via additional free knowledge based content.



# UX

#### Being old school I have created the BACKSTORY and WIREFRAMES with pen and paper, so apologies in advance if there are any readability issues! You can view them via this link : 
<https://github.com/Oldboycypher/Milestone-Project-One/tree/master/Wireframes>
#### To add to the above introduction, my client wants a lot from the site, but as it will be mobile first, some scaling back on his (my!) ambitions has had to occur.
#### Some of the original ideas never made it to the final version as I either did not have the skill or they made the site too congested on smaller screens and needed simplification to improve overall UX. The optional Testimonial section was left out as the design required JavaScript and I wanted to keep the project within the scope of current learnings which meant limiting the site to HTML and CSS only ( apart from jquery via the link).
#### The type of user is interested in trading the share market. They may never have traded before or have done so but want more training as they are not happy with their results. All users would be aware that large gains can be made but that equally large risks are involved and are seeking the safest methods to minimise losses and increase gains. As a result of the marketing target sector and my clients main desire to gain more students and create stand apart credibility, i have created a single page site for the main information body with sections. These flow through the sales process: opening hook lines and my clients story and profile, outline of learnings, option to sign up as individual or group, if more info needed an embedded video of some training follows and then another section with a general contact form if the prospect needs to ask other questions. 
#### The flow of the first page coupled with brief but reasonably detailed information should be sufficient for the serious prospect to have their interest grabbed. The Header links make it easy to navigate throughout the site and return to the top via Home or clicking the brand name. Also, the links on the header nav go direct to the appropriate section of the main page. 
#### The footer has a Legal Stuff dropup that links to a separate page and covers all other items such as GDPR, cookie policies and disclaimers etc. All links in the Legal Stuff dropup on the footer link directly to the appropriate section within that page. There are also links to all social media accounts on the footer.


# Existing Features

#### Here is a brief list of key features found on the site in sequence from top to bottom as would be seen during normal scroll down:
### 1. Header Nav Bar. 
   - #### This is always on top and visible during scrolling. 
   - #### This always shows the company logo to the left.
   - #### Larger screens show 6 clickable headings for Home, Training, Booking, Excerpt, Contact and Links. Links also contains a dropdown menu to 3 external sites.
   - #### All 6 headings have hover effects.
   - #### The first 5 are linked directly to the corresponding section of the landing page.
   - #### Scales on smaller screens to a toggle link with dropdown menu and second dropdown menu (when External Links is hovered over).
   - #### Logo also shrinks for screens below 420px.
### 2. Main Body.
   - #### Is divided into sections with either a background colour or image in alternating pattern of dark then light with contrasted text.
   - #### The use of columns with an inset on a separate div to the section background keeps the text central and above the background  where opacity can be changed to support text contrast against the image for better UX. An example of this is the Home section.
### 3. Home Section.
   - #### Contains contrasted background image of share market chart and data. Removed for smaller screens.
   - #### Larger screen hover effect of expanding and skewed polaroid style images. Effect can still be seen via touch on small touch screen devices.
### 4. Training Section.
   - #### Larger screens have CSS created Checkmarks. This is removed for smaller screens.
   - #### All 5 images have border shadow enhanced hover effects.
   - #### This section ends with a skewed and coloured section divider.
### 5. Booking Section.
   - #### Contains contrasted background image of London. Removed for smaller screens.
   - #### Features booking request form for prospect to submit.
### 6. Course Excerpt Section.
   - #### Contains contrasted background image 
   - #### Includes an embedded YouTube training video which is scaled 3 times for small, medium and large screen viewing.
### 7. Contact Section.
   - ####  Contains contrasted background image of contact being made via electronic devices.
   - #### Features another submission form for any additional information a prospect may have.
### 8. Footer Nav Bar.
   - #### Is fixed to the bottom of site and only visible once scolling has reached the bottom. 
   - #### Contains 4 social media links.
   - #### Features Legal Stuff hoverable link with dropup menu.
   - #### Each menu link goes directly to the corresponding section of the Legal page. The Legal page opens in a separate tab. From here you can link back to any section of the main website i.e. Home, Training, Bookings etc.
   - #### Legal Stuff and it's dropup links plus all social media icons have hoverable effects.

# Features Left to Implement

   - #### The optional Testimonials section. This requires JavaScript and would have several images and text continuously self rotate from the right to left with pause on each.
   - #### The top navbar disappearing on scroll down except for the toggle icon ( Hamburger menu ) for navigation. The footer navbar to appear on scroll up.
   - #### All images in Training section, when hovered over, reveal card with course details and costings instead of lengthy text before static images.
   - #### Both modal forms, when data submitted, to post a confirmation form on same page.

# Technologies Used
#### HTML5:  <https://www.w3schools.com/html/default.asp>  
#### This is the first language covered in the course and fundamental to the projects site structure. 
#### CSS3: <https://www.w3schools.com/css/default.asp>
#### This is the second language covered in the course and fundamental to the projects site styling of the basic HTML structures. Any CSS frameworks supplied via Bootstrap Classes were either used unabridged or modified with CSS in the style.css file. CSS @media queries were used to improve site and responsiveness on various sized screens.
#### Bootstrap 3.3.7: <https://getbootstrap.com>
#### I decided to use a framework instead of pure CSS after viewing course feedback on real world applications of coding languages at the commercial level.
#### jquery: <https://getbootstrap.com/docs/3.3/javascript/>
#### As an extension to Bootstrap and link found on its site, I used this for the 2 modal submission forms included in 2 of the sections. I refrained from using any other JavaScript syntax as this has not yet been covered in the course and wanted to keep the project within current learning parameters.

# Testing

#### As discussed in the introduction and UX sections above, the user story has been met by this site. The prospective customer/s can easily navigate the site, find details about the founder/trainer and a good list of key course learnings. They can view a training video and have access to other free content which validates the site, adds trust but never leads the prospect to the competition. They have an application form which is easy to complete. They have a contact form as well if they have remaining questions. All of this is on one scrollable page to maximise ease of navigability and prospects signup rate.
#### The site was thoroughly tested throughout the build process. Every change was first checked for scaling and responsiveness in Dev Tools for all screen sizes and devices. All links were constantly checked and fixed/updated if required, for example when changing a background image.
#### Dev Tools testing covers screen sizes in pixels from 320 x 569, 375 x 569, 425 x 569, 768 x 569, 1024 x 758, 1440 x 875 to 2560 x 1625.
#### Dev Tools Responsive testing covers the following devices: Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 5/SE, iPhone 6/7/8, iPhone 6/7/8 Plus, iPhone X, iPad and iPad Pro.
#### Real life testing occured at the middle and end stage of project completion. This included testing on various devices by myself and 5 others.
### Devices used and their browser types:
  - #### iPhone 5/SE using Safari browser.
  - #### MacBook Pro using Google Chrome browser.
  - #### iPad using Safari browser.
  - #### iPhone 7 using Chrome version 70.0.3945.73.
  - #### HP laptop with 15" screen using Chrome.
  - #### Samsung S8 using Google Chrome.
#### Final testing with multiple devices showed issues such as:
  - #### 'TRADE' part of logo name needed colour change due to poor nav contrast.
  - #### Margins were needed around polaroid images and some text to give better distance between them and other content. Changes to padding, min size and adding object-fit:cover to img improved aspect ratio when viewing polaroids.
  - #### Even with @media removal of images for smaller screens, some background images ( Home and Bookings ) were still pixelated or aspect was skewed on iPad between 420px and 768px. Attempted @supports to correct this but syntax seems closer to JavaScript and did not work so removed it. Added background-attachment:scroll, background-size:contain with a background-color:black as a means to fix this. Appears corrected in dev Tools emulators but may still be noticable on some real devices.
  - #### Heading font too large on smaller screens so used @media to reduce size along with a reduction in size of the topnav.
  - #### The Burger Menu (I've been calling it a Toggle-Button in my CSS classes as was unaware of this name for it) when clicked or touched a few times will disappear and reappear if its location space is clicked/touched again. Thinking this may be a JavaScript fix and as such have not rectified it yet.
  - #### While the idea of the Checkmark in Training was good, positioning relative to text was an issue not rectified. Used @ media to limit its visibility thus removing it from smaller and very large screens.
#### I have ignored some warnings in the W3 HTML Validation process as they appeared irrelevent to the site/code as created. All other errors and syntax improvements were implemented and on final check all html and css files were error free.
 
# Contact form:
#### The site uses 2 forms. One in the Booking section and one in the Contact section. Each form is formatted for the same same user responses.
#### When submitting, if a field is left empty, an error message will appear asking for the field to be completed. If the email section fails to contain an '@' symbol, an error message will appear asking for this to be included.
#### When the valid form is submitted the user is taken to the CI site for <https://formdump.codeinstitute.net/>. Here a message will display saying "Congratulations! If you can read this, you have prepared and submitted your form correctly."

#### The forms were tested on all virtual screen sizes and responsive layouts. Also testing was done on all devices mentioned in testing. On the smallest screen being iPhone 5, the form fills the screen but no width overlap. Larger devices the form sits central and uses on average 1/3 to 1/2 the view width of the screen.

# Deployment
#### This project and all files are located in a repository on GitHub. To view the files follow the link below:
#### Project files on GitHub: <https://github.com/Oldboycypher/Milestone-Project-One>
#### The site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.
#### Deployed Site on GitHub Pages: <https://oldboycypher.github.io/Milestone-Project-One/index.html>
#### This site was built in the GitPod IDE which acts as an extension of or link to your GitHub repository. To deploy a project directly into GitPod from GitHub or its URL;
 - #### Simply access the project above via its GitHub link i.e. <https://github.com/Oldboycypher/Milestone-Project-One>
 - #### Add the following prefix to the URL: gitpod.io/#
 - #### You should now have a new URL like this; gitpod.io/#https://github.com/Oldboycypher/Milestone-Project-One
 - #### Click link or copy and past new URL into your browser and click enter. This will take you to the project files in a newly created work environment within GitPod.
 - #### Here you have a screen divided horizontally in two with a section to the left containing all the project files. You can open these by clicking on them. Each one will open in a new tab within the top half of the central screen. The bottom half of the screen is the terminal.
 - #### To preview the site from here or open in a new browser, click in the terminal next to the $. Then type: python3 -m http.server
 - #### Click enter. A message box saying 'A service is listening on port 8000 but is not exposed' will appear. Click on 'Expose" button.
 - #### Two new buttons appear. You now can chose to click on 'Open Preview" which will open project within the GitPod screen to the right. Alternatively click on 'Open Browser' for project to be deployed on a new page in your devices browser.
#### To run locally, you can clone this repository directly into the editor/IDE of your choice by pasting 'git clone <https://github.com/Oldboycypher/Milestone-Project-One.git>' into your terminal. To cut ties with this GitHub repository, type 'git remote rm origin' into the terminal.


# Credits

#### Several credits and acknowledgements ( which can also be found on the site by clicking on Legal Stuff then Credits) need mention for support in making certain elements of this website as below:

#### 1. For support with overiding Chrome defaults on Nav dropdown links ( CSS line 165 ) found code on <http://www.medium.com/@hassadee>. This removed blue border for header links btn. The code was modified for my site.

#### 2. For more support with the above Chrome defaults issue, this time removing blue border from header business name, found code on <http://www.stackoverflow.com> CSS line 170. Code not modified.

#### 3. All hover effects are thanks to Ian Lunn at <https://ianlunn.co.uk/> via Cloud Flare <https://www.cloudflare.com/> ( CDNJS Libraries ). Code not modified.

#### 4. In the Training section used a CSS Checkmark Icon with code found at <http://www.boylesoftware.com>. ( CSS lines 477-511 ). Code was modified for site.

#### 5. All written content is mine. The 2 polaroid photos in the Home section are of myself and my Diploma and therefore credited to me. The YouTube video is thanks to <https://www.chartguys.com/>. The video can be seen here <https://youtu.be/rlZRtQkfK04>. All other images are from various sites and were found via Advanced Google search. Below are all images and their source.
  - #### bgcharts.jpeg sourced from <http://www.aljanh.net>
  - #### technical.png sourced from <https://www.markettraders.com>
  - #### trading-psychology.png sourced from <https://www.optionstradingiq.com>
  - #### moneyman.jpg sourced from <https://www.meteofinanza.com>
  - #### package-121.jpg sourced from <https://www.sjr-heidelberg.de>
  - #### package-group.jpg sourced from <https://www.lean-expert.com>
  - #### bookings.jpg sourced from <https://www.dailymail.co.uk>
  - #### excerpt-background.jpeg sourced from <https://www.pexels.com>
  - #### contact.jpg sourced from <https://www.pixabay.com>

#### 6. CI/Haley Schafer for the <a href="https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/README.md">README</a> and some wording in the <a href="https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/README.md#deployment">Deployment</a> section. 

# Authors Final Note:

#### There have been several learnings and reveals along the way, a few I think I should touch on briefly below.
#### This project has taken me much longer than anticipated. Firstly, and maybe due partly to my age, was my own slowness to come to terms with even basic technology, as prior to this course I had been labeled a technophobe, so coming up to speed has been a hurdle. Secondly was the loss of nearly six months to a family illness. This gave me first hand experience of how difficult it is to progress meaningfully when your study blocks are short and often interrupted. Understanding and progress seem directly linked to large blocks of uninterrupted time. I think this is what is meant by 'deep learning'.
#### I am not a natural designer and this was a challenge for me. There were constant little changes to make the site more user friendly, visually appealing and uncluttered. The final site is not perfect but I will perservere and continue learning design skills and improving upon them.
#### The big reveal for me was how certain habits and personallity traits when placed in a coding/study context become deleterious. These are perfectionism and overthinking. No detail required here; apply these traits to learning and problem solving and you get slow progress and time delays. Being aware of this I can now focus on personal improvement in these areas and become more effective at pace.
#### And finally, just a quick note for anyone reading this file and viewing the site: This site is not for commercial use and was built as part of a course of study. That said, I really hope you enjoy my site and I look forward to any feedback.


 