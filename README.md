# Project One - Portfolio Website

This website is one I have created for myself as an online portfolio and CV to show my abilities as a full stack web developer. I intend for this wesbite to be used by employers wishing to check my credentials and ability, or possibly prospective clients seeking to see what I am capable of achieving for them, or both. 
On this site, people will be able to read a short biography about me, see what relevant education I have had, download a soft copy of my CV, and contact me using an online form or by an email address provided.



## UX
---

This website is primarily for informational and professional use, not entertainment. As such, there is no audio or video. It is supposed to contain all the relevant information a prospective employer or client would need to decide whether to contact me, either as a candidate for employment, or as a contractor.

**User Stories**

- As the manager of a development company, I would like to see if this person would be a good fit for my team and would be capable of fulfilling the role I have in mind
- As a small business owner, I am looking for someone who could create a responsive website for my business
- As an artist, I am looking for someone who could create an online store where I could showcase my work and sell items
- As a UI/UX designer, I am looking for a developer who could turn my designs into working websites
- As a front end developer, I am looking for someone who could turn my front end into a fully functioning website by coding the back end
- As a back end developer, I am looking for someone who could do the client side part of a website I have been asked to create


**Wireframes**

Being old fashioned at heart, all my original skecthes for the basic outline and design of my website were done with pencil and paper, by hand. I have since discovered Figma, however, and will probably use this in future as a second step after I have done the initial sketches on paper. My orginal design is basically kept, although colours have been altered and the design has been tweaked to accomodate mobile devices



## Features
---

**Existing Features**


(All pages):
- Collapsible nav menu into hamburger icon for mobile devices
- Responsive text and images that resize depending on screen size
- Aria labels, keyboard navigation and semantic HTML to allow for ease of navigation for users with assistive technology
- Dropdown nav menu to allow for discrete hiding of extra links until they are needed

Qualifications page:
- Button which triggers download of .docx version of my CV

Contact page:
- Contact form with submit and clear buttons
- Form dropdown selection list
- Radio buttons
- Phone number link which, on mobile phones or devices capable, will offer to ring me
- Email link that will open in the users default mail service


**Features Left to Implement**

- Overhaul of the UI design so as to make it look less amateurish
- Form validation in JavaScript
- Entire backend
- Slideshow of portfolio which can be made static for users who find animations overwhelming/distracting
- Portfolio to be added to as I complete projects




## Technologies Used
--- 

- [Bootstrap V 5.1.3](https://www.getbootstrap.com)
    - I used Bootstrap as a framework to quickly add responsiveness to my webpage

- [HTML5](https://html.com/html5/)
    - I used HTML5 to provide the DMO for my webpage, the basic contents and layout

- [CSS3](https://css3.com/)
    - I used CSS3 to provide the styling and "look" of my website (colours, fonts etc.). Bootstrap also has its own CSS file

- [JavaScript](https://www.javascript.com)
    - The Bootstrap library includes JavaScript files to enable and enhance its functionality

- [VSCode](https://code.visualstudio.com/)
    - I used Visual Studio Code as my IDE to write the code for my website

- [Git](https://git-scm.com)
    - I originally used git to add, commit and push my files, until I made a giant cock-up (recorded further down). However, I have rectified this now

- [GitHub](https://github.com)
    - I used GitHub as the online repository for my files, and to host my website (using GitHub Pages)

- [Formspree](https://formspree.io)
    - I used Formspree to make my contact form functional


## Testing
---

I used Google Chromes development tools to see what my webpage would look like on a tablet, phone etc. This was very helpful to iron out some problems in my design.
I also used guinea pigs (people I know) to navigate through my website, test it for ease of use and any problems. My guinea pigs were of varying ages and had varying levels of computer literacy, so I was able to confirm that my website is easy to use and clearly laid out for people who may not be used to computers.

**HTML and CSS Validation**

 - I used the [W3C Markup Validator Tool](https://validator.w3.org/#validate_by_input) to test for the validity of my HTML5 files
 - I used the [W3C CSS Validtor Tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to test for the validity of my CSS3 file

 **Accessibility**

 - I used the [WCAG guidelines](https://www.w3.org/TR/WCAG21/) at w3.org to go over my code and check for its accessibiltiy for people with disabilties and/or using assistive technology. My original design included some animation, which I removed after reading the guidelines. I also made sure everything had a reasonable level of contrast, that aria labels etc. were used and that overall it complies with the WCAG guidelines




## Problems addressed
---

- I had brief issues with media queries in CSS until I remembered Cascading Style Sheets are read from top to bottom. I simply moved the code I wanted to have greater precedence to the bottom

- I stupidly used the online GitHub site to commit my work once, instead of the command line interface. After doing this, it refused to commit from the CLI again, insisting that the branches were unrelated and it couldn't merge the changes (even though it was the exact same project). This was a big problem because I wanted to put in folders, which I can do with the CLI but am not sure if you can do with the website. I attempted to solve this by cloning my work with the CLI, changing it, and committing it again that way. Didn't work. I genuinely have no idea how to solve this.

## Deployment
---

I used GitHub pages to host my website. I mentioned above that I ran into an issue when it turned out that, after committing your work via the website, you can no longer commit via the command line interface because the two branches don't recognise each other, even if you attempt to clone the project and start from there. 

This has meant that my files have to all be in the same "folder" as you cannot commit folders except through the command line interface. Lesson learned for next time!

Interestingly, I did use the command line interface and `git init` to start my repository, but then added the first file through the webpage whilst I was there.

I didn't know how to fix this, didn't want to start over, so proceeded to do all my commits through the webpage.

I then went into settings -> pages -> and deployed my code into Github Pages.

## Respository Link:

https://mimsysith.github.io/Mimsy-portfolio/

To run my code locally, you can follow these steps:

1. Go to the [github website](https://github.com)
2. Go to [my repository](https://github.com/MimsySith/Mimsy-portfolio)
3. Click on 'clone or download'
4. Download Zip file
5. Once extracted, extract the zip files to the desired location on your computer and run the website locally.

## Credits
---

**Content**

- The photos that are placekeepers in my portfolio were taken from stock photos from the website at [pexels.com](https://www.pexels.com)
- All other photos were taken by me
- All original artwork (background picture etc.) was done by me. No copyright has been broken.
- Some code, as indicated in comments, was found at [w3 Schools](https://www.w3schools.com)
- Bootstrap CSS files and JavaScript files were taken from the Bootstrap website, mentioned above.

**Acknowledgements**

After struggling horribly with the design aspect of my website, thanks to the people at Udemy and one of their UI/UX design courses. 

Inspiration for the black background and black and white head shot came from another developer's website, which I can't seem to find again because I suspect he updated it. Possibly it was Jack Jeznach.

Also, thanks to my mentor in this course, Sunny Hebbar, who told me about various extra websites and tips/tricks.








