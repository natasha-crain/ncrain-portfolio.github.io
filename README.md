# Portfolio Website

This is my first project creating a website using HTML, CSS and some JS. It is my personal website that displays my contact details including social media and GitHub links, a short bio, and that will eventually host front end projects, as well as being a project submission for my Front End Development course with The Learning People.

## UX/UI

My website acts as an online portfolio and resume, for recruiters and potential future employers to view my work and easily contact me, either via email, mobile, social media or contact form on the website.

I have designed my website to reflect my creative background in 3D visualisation, taking care to choose fonts that are both readable and more interesting to the viewer, and a scheme that is colourful but not overpowering, with simple animations in the background, navigation bar and page headers acting as points of interest.

The website has five pages in total; one a welcome page, thank you page and three navigational pages:

- About Me, which contains a brief introduction, profile image, contact information as well as links for my GitHub, Facebook and Instagram profiles.

- Portfolio, which is currently empty but will be filled in the future.

- Contact Me, which contains a contact form, which when completed and sent, loads a thank you page.

## Wireframes

To plan my website and put some ideas down to page, I used Balsamiq to create wireframes and to take down draft notes. I have created three wireframes for three different website styles for desktop viewing. However, there is a great difference between my wireframes and my final website. This is due to visuals preferences and finding inspiration for a [background animation.](https://codepen.io/joyanna/pen/NWGYLNW) The links to the files are below: 

- **[website wireframe draft 1](https://github.com/ncrain-boop/ncrain-boop.github.io/blob/main/static/wireframes/website%20wireframe%20draft%201.pdf)**

- **[website wireframe draft 2](https://github.com/ncrain-boop/ncrain-boop.github.io/blob/main/static/wireframes/website%20wireframe%20draft%202.pdf)**

- **[website wireframe draft 3](https://github.com/ncrain-boop/ncrain-boop.github.io/blob/main/static/wireframes/website%20wireframe%20draft%203.pdf)**

## Features

### All Pages

- **Animated background** - A simple animated background using div elements, transition CSS styles and keyframes, to interest and appeal to the viewer.
- **Page transitions** - simple transitions between each page using CSS and JavaScript.

### All Pages (excluding index.html)

- **Navigation links** - Allows users to navigate to other areas of my website by clicking on the different navigation link, which then redirects them to the relevant page.
- **Website logo** - Allows users to navigate back to the homepage (index.html), which is not available from the main navigation bar.
- **Footer** - a footer displaying my name and the year the website was created.

### All Pages (excluding index.html, portfolio.html and thankyou.html)

- **Page header** - An animated page header, confirming to the user which page they have navigated to, from the navigation links.

### index.html

- **welcome link** - a link that the user can click to redirect them to about.html and from there can navigate to the rest of the website.

### about.html

- **bio paragraph** - a short paragraph about me and my background
- **contact details** - information containing my email and mobile phone number for the user to contact me in they wish
- **social media links** - links to my Facebook, Instagram and GitHub pages for the user to view and also contact me if that is their preference. 

### portfolio.html

*this page is currently empty but will display projects in the future*

- **portfolio message** - a short message detailing to the user that more content is on the way

### contact.html

- **contact form** - a working contact form the user can fill out to contact me. It contains an entry for a name, email, subject and then a `textarea` for the user to write their message. The name and email have been made `required`, so that I am able to reply to their message.  As I do not currently know any backend languages, I used [formsubmit.co](https://formsubmit.co/?utm_source=formsubmit.co&utm_medium=site%20link&utm_campaign=submission%20page) and followed their instructions to link my contact form with their form endpoint. I also disabled the reCAPTCHA  by setting the `value="false"`, as I thought this would be annoying to viewers and I am not concerned too much about spam currently.

### thankyou.html

*this page can not be navigated to, from the navigation links and can only be viewed if the user submits a message from contact.html*

- **thank you message** - a short message to the user, thanking them for their message and that I will strive to return their message as soon as possible. By default, [formsubmit.co](https://formsubmit.co/?utm_source=formsubmit.co&utm_medium=site%20link&utm_campaign=submission%20page) has a default thank you page, so I created a simple one for the website as it was more appropriate and added it to the form in contact.html. Once the website is deployed and if the user sends a message, this page will appear.

## Features to implement

These features require back-end languages to development, such as JavaScript, therefore once I have a better understanding of these, I will add and develop to existing features in my website,

- **Navigation links (mobile)** - I will add a feature to the burger button, to animate it to an 'X', once the burger icon is clicked and the dropdown menu is displayed.

- **Contact form** - I will add a tailored working submit form once I have learned more about back-end development and its languages, instead of relying on an external endpoint.

- **Page transitions** - I will recreate my own page transitions, instead of relying on other online [tutorials](https://www.youtube.com/watch?v=ckJ7gdIeebc).

## Technologies

This project was created with:

- **[Balsamiq](https://balsamiq.com/)** - I used Balsamiq to create draft wireframes.
- **[HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)** - I used HTML5 to create the content and structure of my website.
- **[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)** -  I used CSS3 to add styles to the content of my website.
- **[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)** - I used JavaScript to add functionality to some of the website elements.
- **[FontAwesome](https://fontawesome.com/v4.7/icons/)**  - I used FontAwesome for the chevron icon and social media links.
- **[Google Fonts](https://www.w3schools.com/howto/howto_google_fonts.asp)** - I used Google Fonts to stylise the text more suitable for my website.
- **[FormSubmit.co](https://formsubmit.co/?utm_source=formsubmit.co&utm_medium=site%20link&utm_campaign=submission%20page)** - I used FormSubmit to add functionality to my contact form in place of my own code.
- **[VS Code](https://code.visualstudio.com/)** - I used VS Code as the software to develop and write the code for my website.
- **[Git Bash](https://git-scm.com/downloads)** - I used Git Bash to connect my remote desktop to my repository and to add and commit changes made from VS Code.
- **[GitHub](https://github.com/)** - I used GitHub as a remote repository to push and then store any committed changes to my website from Git, and then to eventual deploy my website live.

## Testing

### Responsive/Mobile testing

I used Google Chrome's development tools to test each page and change made to my website, adjusting and correcting where needed so that it displayed in the desired way on many different screen sizes (multiple mobile sizes, tablet and desktop). Where the code broke, I then used `@media queries` with the appropriate screen sizes to adjust the content. 

### HTML and CSS Validation

To validate and debug my code, I used ***[W3C HTML Validator Tool](https://validator.w3.org/)*** to validate my HTML code, and the ***[W3C CSS Validator Tool](https://jigsaw.w3.org/css-validator/)*** to validate my CSS code.

## Bugs/Problems

- **Website logo** - whilst the logo does technically work and redirects the user to the homepage (index.html), the code used isn't clean and instead of using `a href` and nesting the `img` within and making the logo a hyperlink, inline JavaScript is used instead. The reason for this is the transitions.js script blocking a hyperlink from working correctly. To fix this issue in the future, once I have learned back-end development,  I will recreate my own page transitions and ensure it is more compatible with the existing code.
- **Social media links** - the same issue seems to be the same for the social media links as the website logo, in that the transitions.js script is blocking the hyperlinks from working correctly as a regular `a href` and instead inline JavaScript is needed as a work-around. Once I have learned more about back-end development and languages, I will be able to understand these issues better and why an unrelated script is affecting them.

## Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

1. Create a new repository on GitHub.
2. Open Git Bash.
3. Initialise the local directory as a Git repository. `$ git init`
4. Add files to the new local repository, that stages them for the first commit. `$ git add .`
5. Commit the files that have been staged in the local repository. `$ git commit -m "First commit"`
6. In the GitHub remote repository, copied the HTTPS or SSH key.
7. In the Git Bash terminal, added the remote repository `$ git remote add origin main` and pasted the key. `$ git remote add origin ''https://github.com/ncrain-boop/ncrain-boop.github.io.git"`
8. Push the changes from the local repository to the remote repository `$ git push origin main`
9. Entered my GitHub username and password.
10. Pushed many commits through the project `$ git commit`
11. This brings up another window in which to add a more detailed commit, with the first line being the header of the commit
12. Once the commit is written, `esc` button is pressed and then `:wq` to exit the window and back to the main terminal.

### Repository Link

https://github.com/ncrain-boop/ncrain-boop.github.io.git

Running Code Locally

To run my code locally, users can follow these steps:

- Go to my [***GitHub repository***](https://github.com/ncrain-boop/ncrain-boop.github.io)
- Click on '***code***'
- Click on ***Download ZIP***, or ***Open with GitHub Desktop*** if installed.
- If *download via ZI*P, extract the ZIP files content and the website can be run locally.
- If *Open with GitHub Desktop* has been used, click Open GitHubDesktop.exe on the pop-up window
- Choose the local path with which to clone the repository and click **'Clone'**
- Once the repository has been cloned, the website can be run locally.

## Credits

### Other sources

- Inspiration for my background animations, and learning how to animate with CSS and elements was found from CodePen here: (https://codepen.io/joyanna/pen/NWGYLNW)
- The animation for the page header was found and adapted from here: https://codepen.io/blackjacques/pen/GrNMxv
- The online tutorial for creating a responsive navbar was adapted from here: https://www.youtube.com/watch?v=8QKOaTYvYUA
- The CSS and JavaScript used for the page transitions was found here: https://www.youtube.com/watch?v=ckJ7gdIeebc
- How to create a working contact form from an external endpoint was found here: https://www.youtube.com/watch?v=YBUMHRL1fmo&list=PLR8vUZDE6IePk_KvVxrFwesjz8qspsIhd&index=17

### Acknowledgements

A big thank you to my mentor, [Sunny Hebbar](https://github.com/hebs87). His guidance and feedback were invaluable, especially on how to start my project, bugs and what to include in my README.md. I would have been very lost otherwise.