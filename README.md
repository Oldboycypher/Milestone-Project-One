
   # Trade Safe PTY Milestone Project
   
   ## Welcome to my Trade Safe website Milestone 1 Project.
   
   ##### What can I say, this is a subject I love and the imaginary client who strangely resembles me is what I would love to be in another life: a seasoned market trader! This all came from my own experiences with brokers bad advise and overpriced training programmes that didn't give much in return. I actually did the featured Diploma in Technical Analysis so I could be my own expert; and its that drive to give people the same opportunity to learn real life (and safer) trading, but without rip off prices, that gave life to this website.
   ##### Assuming potential clients have been Googling key phrases such as "safe share trading methods" and "technical analysis" for example, with some good content marketing they might come across this site. It starts with some hook lines on the home page then flows through a sequence of what training is provided, the booking form for individuals and groups, an embeded YouTube video giving a snippet of the training provided and a general contact form for any other information. I kept the legal information separate in the end as i didnt want to distract potential customers from the main thrust of signing up for training. They can still access it via a dropup menu on the footer which diverts them to a new page from which they can link back to any section of the main website. The aim is to create trust then if they are interested give them a bit more info, then the opportunity to book a place and if this isn't enough they get to sample the training content and then ask questions if need be. The site offers free external links for more market information to cement trust via more free knowledge based content.



## UX

##### Being old school I have created the backstory and wireframes with pen and paper, so pardon some scrappy writting! You can view them via this link : 
<https://ide.c9.io/oldboycypher/milestone-project-safe-trade/wireframes/backstory-and-wireframes.pdf>
##### To add to the above introduction, my client wants a lot from the site, but as it will be mobile first, some scaling back on his (my!) ambitions would most probably occur.
##### Some of the original ideas never made it to the final version as i either did not have the skill or they made the site too cluttered and needed simplification to improve overall UX. The optional Testimonial section was left out as the design required JavaScript and I wanted to keep the project within the scope of current learnings which means limiting the site to HTML and CSS only ( apart from jquery via the link).
##### The type of user is interested in trading the share market. They may never have traded before or have done so but want more training as they are not happy with their progress. All users would be aware that large gains can be made but that equally large risks are involved and are seeking the safest methods to minimise losses and increase gains. As a result of the user type and my clients main desire to gain more students and create stand apart credibility, i have created a single page with sections that flow through the sales process: opening hook lines and my clients story and profile, outline of learnings, option to sign up as individual or group, if more info needed an embedded video of some training follows and then another section with a general contact form if the prospect needs to ask other questions. 
##### The top nav also includes links to credible external sites and more videos to further support credibility and give a free offering of more information.
##### The footer has a legal dropup that links to a separate tab and covers all other items such as GDPR, cookie policies and disclaimers etc. All links on header nav go direct to the appropriate section of home page. All links in legal dropup on footer go direct to appropriate section on separate legal tab. There are also links to all social media accounts on footer.


## Existing Features

##### Here is a brief list of key features found on the site in sequence from top to bottom as would be seen during normal scroll down:
#### 1. Header Nav Bar. 
   - ##### This is always on top and visible during scrolling. 
   - ##### This always shows the company logo to the left.
   - ##### Larger screens show 6 clickable headings for Home, Training, Booking, Course Excerpt, Contact and Links. Links also contains a dropdown menu to 3 external sites.
   - ##### All 6 headings have hover effects.
   - ##### The first 5 are linked directly to the corresponding section on this page.
   - ##### Scales on smaller screens to a toggle link with dropdown menu and second dropdown menu when External Links is hovered over.
   - ##### Logo also shrinks for screens below 420px.
#### 2. Main Body.
   - ##### Is divided into sections with either a background colour or image in alternating pattern of dark then light with contrasted text.
   - ##### The use of columns with an inset on a separate div to the section background keeps the text central and above the background  where opacity can be changed to support text contrast against the image for better UX. An example of this is the Home section.
#### 3. Home Section.
   - ##### Contains contrasted background image of share market chart and data.
   - ##### Larger screen hover effect of expanding and skewed polaroid style images. Can still be seen via touch on small touch screen devices.
#### 4. Training Section.
   - ##### Larger screens have CSS created Checkmarks along with greater detail of training given. This is removed for smaller screens.
   - ##### All 5 images have border shadow enhanced hover effects.
   - ##### This section ends with a skewed and coloured base divider.
#### 5. Booking Section.
   - ##### Contains contrasted background image of London.
   - ##### Features booking request form for prospect to submit.
#### 6. Course Excerpt Section.
   - ##### Contains contrasted background image 
   - ##### Includes an embedded YouTube training video which is scaled 3 times for small, medium and large screen viewing.
#### 7. Contact Section.
   - #####  Contains contrasted background image of contact being made via electronic devices.
   - ##### Features another submission form for any additional information a prospect may have.
#### 8. Footer Nav Bar.
   - ##### Is fixed to the bottom of site and only visible once scolling has reached the bottom. 
   - ##### Contains 4 social media links.
   - ##### Features Legal Stuff hoverable link with dropup menu.
   - ##### Each menu link goes directly to the corresponding section of the Legal page. The Legal page opens in a separate tab. From here you can link back to any section of the main website i.e. Home, Training, Bookings etc.
   - ##### Legal Stuff and it's dropup links plus all social media icons have hoverable effects.

## Features Left to Implement

##### I would have loved to have included a Testimonials section which was in the original wireframes for this site as an option. 
##### The poloroid picture CSS would have been implemented again but the whole section idea was based around 5-8 testimonials self rotating right to left one after the other with a pause of say 10 seconds on each before the next one appeared. This was a self activated section with no need for mouse hover etc. 
##### But due to the JavaScript involved I will be leaving this till I have learned enough to create it.

## Technologies Used
#### HTML5:  <https://www.w3schools.com/html/default.asp>  
This is the first language covered in the course and fundamental to the projects site structure. 
#### CSS3: <https://www.w3schools.com/css/default.asp>
This is the second language covered in the course and fundamental to the projects site styling of the basic HTML structures. Any CSS frameworks supplied via Bootstrap Classes was either used unabridged or modified with CSS in the style.css file.
#### Bootstrap: <https://getbootstrap.com>
I decided to use a framework instead of pure CSS after viewing course feedback on real world applications of coding languages at the commercial level. As frameworks are generally used to build efficacy into projects I decided this was the best place to start and to work with a common workplace framework, as well as discover the advantages and difficulties/limitations involved. 
#### jquery: <https://getbootstrap.com/docs/3.3/javascript/>
As an extension to Bootstrap and link found on its site, I used this predominantly for the 2 modal submission forms included in 2 of the sections. I refrained from using any other JavaScript syntax as this has not yet been covered in the course and wanted to keep the project within current learning parameters.








## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:




## Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.




## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.



## Credits

##### Several credits and acknowledgements ( which can also be found on the site by clicking on Legal Stuff then Credits) need mention for support in making certain elements of this website as below:

##### 1. For support with overiding Chrome defaults on Nav dropdown links ( CSS line 165 ) found code on medium.com/@hassadee. This removed blue border for header links btn. The code was modified for my site.

##### 2. For more support with the above Chrome defaults issue, this time removing blue border from header business name, found code on Stack Overflow. CSS line 170. Code not modified.

##### 3. All hover effects are thanks to Ian Lunn via Cloud Flare ( CDNJS Libraries ). Code not modified.

##### 4. In the Training section used a CSS Checkmark Icon with code found at boylesoftware.com. ( CSS lines 477-511 ). Code was modified for site.


## Authors Final Note:


   