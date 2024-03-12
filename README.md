# Portfolio Project 1 - Culinary Classroom



The Culinary Classroom Website is designed to promote a course that I been working as a chef for the last 10 months. The goal in this project is to prove my knowledge that I been practicsing during my course in HTML and CSS.

[Screenshot from iam responsive] (.doc)

---

## Live Site

[Culinary-Classroom] (https://miguelmurillog.github.io/culinary-classroom/index.html)

---
# Features


My project consists of three webpages:

- Home page
- Photo page
- Sign up page.

### - The Navigation Bar

- A responsive navigation bar facilitates easy access to different sections of the website, including Home, Photos and  Sign up.

![Screenshot of the Navigation Bar](assets/images/screenshot_navigation.png)

### - The Home Page

- Home page, displays the main image of the culinary clasroom team, this is located on the top of the website. it aims to give the user a first time view experience 
- The user will find short description of the course and also details for when has to be enrolled . This section is also supported by the footer social media links.

![Screenshot of the Home Page](docs/home_landing_page.png)

### - The Photos Page

- Gallery page, highlights various images of the artist work, some of them are sketches and some are personal projects for use of his portfolio.

![Screenshot of the Gallery Page](docs/gallery_page_new.png)

### - The Sign up Page

- Contact page, encourages the users to send their details to enrol into the program
- The sign up form collects details of the user such as name, last namel and email adress.

![Screenshot of the Contact Page](assets/images/Contact_Page.png)


- I tested the sign up form with a succesful result.

![Screenshot submitted contact form](assets/images/contact_form_submitted.png)

- I tested the validation on the contact form and works very well, name, email and phone fields are mandatory preventing the user of leaving this black or without the required information.

![Contact form validation](docs/contact_form_validation.png)

### - The Footer

- The footer section includes links to social medias.

![Screenshot of the Gallery Page](assets/images/Footer_Social_Media.png)

## Testing
---

- I tested this page in different web browsers such as: Chrome, Firefox, Safari on desktop and mobile phones respectively.
- I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the DevTools device toolbar.
- I confirmed that the navigation, header, home, profile, gallery, and contact text are all readable and easy to understand.
- I confirmed that the form works. It requires entries in every field (excluding the message), will only accept an email in the email field, and the submit button works.

### Google Chrome Browser

![Google Chrome Browser](docs/Google_Chrome_browser.png)

### Safari Browser

![Google Chrome Browser](docs/Safari_browser.png)

### Firefox Mobile Browser

![Google Chrome Browser](docs/Firefox_Mobile_browser.jpeg)


## Bugs

### Solved bugs

- While testing the navegation menu before deploying my project to github, I noticed there was a problem when clicking on the profile menu from the contact one; instead of taking me to the correct destination, it took me to the home page instead.
- I discovered this was due when I copied the initial index.html file to the contact one, I forgot to update the href to "profile.html" within the anchor element.

![Screenshot of the anchor element](assets/images/anchor_code.png)

- The box I created for the profile page was out alignment at top, this due the "float left" I applied to the logo/header in my css file.
- I solved this by applying "clear left" to the box profile ID:

![Screenshot of the box id](assets/images/CSS_Profile_Box.png)

- The "Home" image was a little heavy and affected somehow the score for performance in lighthouse for this section of the website, I fixed this by converting the file to jpeg and reducing the size.

### Unfixed Bugs

- Due to time constraints I could not test the site for all type of mobile phones, the site works very well in most mobile standard devices, laptops and desktop computer.


## Validator Testing

### HTML

- The first time I run the html in W3C, it returned with a few errors encountered in the title of the images, I fixed this by renaming the images title by using underscore to eliminate any existing space from the name; run the html files again and this time no errors were returned when passing through the official W3C validator.

![W3C HTML Validator Home Screenshot](assets/images/W3C_HTML_Validator.png)

![W3C HTML Validator Profile Screenshot](docs/WC3_html_profile.png)

![W3C HTML Validator Galley Screenshot](docs/WC3_html_gallery.png)

![W3C HTML Validator Contact Screenshot](docs/WC3_html_contact.png)

### CSS

- No errors were found when passing through the official (Jigsaw) validator.

![W3C CSS Validator screenshot](assets/images/W3C_CSS_Validator.png)

### Accessibility

- I confirmed that the colors and fonts chosen are easy to read and accessible by running lighthouse in DevTools.

### Desktop

![lighthouse Images Home Desktop](docs/home_page_lighthouse_desktop.png)

![lighthouse Images Profile Desktop](docs/profile_page_lighthouse_desktop.png)

![lighthouse Images Gallery Desktop](docs/gallery_page_lighthouse_desktop.png)

![lighthouse Images Contact Desktop](docs/contact_page_lighthouse_desktop.png)

### Mobile

![lighthouse Images Home Mobile](docs/home_page_lighthouse_mobile.png)

![lighthouse Images Profile Mobile](docs/profile_page_lighthouse_mobile.png)

![lighthouse Images Gallery Mobile](docs/gallery_page_lighthouse_mobile.png)

![lighthouse Images Contact Mobile](docs/contact_page_lighthouse_mobile.png)

### Deployment

The site was deployed to GitHub pages. The steps to deploy are:

- In the GitHub repository, navigate to the Settings tab.
- On the GitHub Pages section clicked on the pages settings dedicated tab link.
- From the source section drop-down menu, select the Main Branch click on seve.
- Once the Main Branch has been selected and saved, the page provided the link to the completed website.

The live link ca be found here: [Cristian Leon - 3D Artist](https://henryl74.github.io/3d-artist-personal-website/)

----
# Credits


## Content

- The idea for this project was based in the challenge of Love Running project. I don't have any previous experience in coding it was challenging. 
- The icons in for the footer were taken from [Font Awesome](https://fontawesome.com/)
- A big thank you to my brother Cristian Leon, for allowing me to use his images and content profile, I must say his passion for what he does has inspired me to pursue this new path in web development.

## Media

- All images in my website project were provided by Cristian Leon (the artist).

## Acknowledgements

- The README template provided y Code Institute on the sample project README.md from "Project Portfolio 1"
- The online tutors for all their help.
- The Code Institute slack community.
- Online tutorials about HTML and CSS.
- My new mentor Chris Quinn, thank you for all your positive feedback and guidance given. 
- Last but not least Code Institute student support team, for listening to my concerns and for all their encouragement given.
-