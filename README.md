# developerPortfolio
## A responsive professional developer portfolio for developers
![](gif/folio.gif)

Feel free to change or customize as much as you want

It sound awesome if you have a much better ideas to improve this

Do contribute and share your ideas with all other developers so that
they can take advantage of your customization

Table of Content
================

* * * * *

-   [Sections](#)
-   [Getting started](#)
-   [How to get files](#)
-   [Change and Customization](#)
-   [Deployment](#)

Sections
========

* * * * *

1.  Intro
2.  Projects
3.  Experties
4.  Contact detail

Getting Started
===============

* * * * *

These instructions will get you a copy of the project and running on
your local machine for development and testing purposes

You will need [Git](https://git-scm.com/downloads) and [Node.js](https://nodejs.org/en/download/)

How to get files
================

* * * * *

When you have done with installation!

Go to your required directory . and open GIT command line as shown below

![contact page](images/guide%20pics/GITBASH.jpg)

Commands to clone the files on your local computer

```git
\$ git clone https://github.com/fahadhassan1213/developerFolio.git 

```
Change and Customization
========================

* * * * *

Just change the `index.html` and `style.css`

For customizarion you have to follow the following instruction to get
your own personal portfolio ready!

### Nav bar changings

```html
</div>
  <div class="col my-1">
   <a href="#my-project-heading" class="portfolio text-decoration-none"><small>Work</small></a>
   </div>
   <div class="col my-1">
   <a href="#" class="contact text-decoration-none"><small>Blog</small></a>
   </div>
   <div class="col my-1">
   <a href="#contact-heading" class="contact text-decoration-none"><small>Contact</small></a>
   </div>
</div>

```

change the text in the `small` tags

### Social Medai links of Intro Page

```html
 <!-- Main intro -->
        <div class="intro-container">
            <div class="main-heading">             
            <!-- My social Media -->
            <div class="socailMedia">
                <a href="https://github.com/fahadhassan1213" target="_blank"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/fahad-hassan-70060320b/" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                <a href="https://twitter.com/FahadHa51773545" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://web.facebook.com/fahad.hassan.9847867" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://www.instagram.com/fahad_malik_0/" target="_blank"><i class="fab fa-instagram"></i></a>
            </div>

```
change the links in `href` attributes

### Picture of Into page

```css
.my-photo {
  background-image: url(images/myphoto.png);
  background-size: cover;
  background-repeat: no-repeat;
  border: 1px solid var(--sec-color);
  border-bottom-left-radius: 20%;
  height: 84%;
  width: 28%;
  position: relative;
  top: 7%;
  left: 10%;
}
```
To change the picture, got to `style.css` file and check `.my-photo`
class selector and just change the url path of `background-image`
property to the image. and add the path of your image

### Name

```html
<div class="my-photo"></div>
<div class="name-heading">
 <h1 class="fname-heading font-weight-bolder display-1 ">fahad<span style=" margin-left:5px; background-color: #F26C4F; border-radius: 50%;display: inline-block;"</span</h1> 
</div>
</div>

```

Just change the text _fahad_ in `h1` tag

### Intro Page description about you

```html
<div class="aboutMySelf">
     <div class="style-pic"></div>
        div class="aboutmyself-description">
           <div class="div-1">
               <small class="tagline px-4">A mint of creativity</small>
               <h3 class="aboutMySelf-heading px-4 my-3">I'm a full stack web developer and graphic designer.</h3>
            </div>
            <div class="div-2">
                <p class="quote px-4">
                        A successful website does three things:
                        It attracts the right kinds of visitors.
                        Guides them to the main services or product you offer.
                        Collect Contact details for future ongoing relation.
                </p>
                <p class="Contact-text px-4 my-1">Email : fahad.hassan607@gmail.com</p>
                <p class="Contact-text px-4 my-0">Phone : +923344291213</p>
        </div>

```

From line number _98 to 109_ change the text of the tags according to
your own desirability


### Background images of Projects page

```css
.p1{
  background-image: url(images/dev-quiz.svg);
  background-size: cover;
  background-repeat: no-repeat;
}
.p2{
  background-image: url(images/todo-project.svg);
  background-size: cover;
  background-repeat: no-repeat;
}
.p3{
  background-image: url(images/dev-quiz.svg);
  background-size: cover;
  background-repeat: no-repeat;
}

```

To change the background images, got to `style.css` file and check
`.p1` , `.p2` , `.p3` class selector 

and just change the url paths of`background-image` property to the image. and add the path of your image


### To change the text of My Experties page

```html
 <!-- My Exp Section -->
        <section class="myexp-section d-flex" style="background-color: #1f1f1f;">
           <div class="myexp-div">
            <div class="exp-description container">
                <h1 class="text-white display-6 pt-5">My Experties</h1>
                <hr style="width: 18%;height:3px; color: #F26C4F;">
                <p class="fs-5 fw-lighter" style="color: #F26C4F;">Exploring and producing elegant, performant, and accessible digital experiences</p>
                <h3 class="fs-3 fw-lighter text-white mt-5">What I do :</h3>
                <p class="fs-6 fw-lighter" style="color: gray;">- Develop highly interactive Front end / User Interfaces for your web and mobile applications</p>
                <p class="fs-6 fw-lighter" style="color: gray;">- Can Design where imagination can meets creativity</p>
           </div>

```

Change the text of the tags form line _157 to 162_ acoording to your need



### To change the icons of My Experties page

```html
<!-- Experties Icons -->
  <i class="fab1 fab fa-html5"></i>
  <i class="fab1 fab fa-css3-alt"></i>
  <i class="fab1 fab fa-js-square"></i>
  <i class="fab1"><span class="fab2 iconify" data-icon="file-icons:adobe-illustrator" data-inline="false"></span></i>
  <i class="fab1"><span class="fab2 iconify" data-icon="file-icons:adobe-xd" data-inline="false"></span></i>
```

Icons are picked from [www.fontawesome.com](https://www.fontawesome.com)

to add new icons you just have to change classes of the icons

(Note: make sure change and pickup correct classes to change the icons)



### Modify the Contact detail

```html
    <!-- Contact Section -->
    <section class="contact-section">
        <div class="contact container">
            <div class="contact-description">
                <h2 id="contact-heading" class="contact-heading display-6 mb-1 text-white" >Contact me</h2>
                <hr class=" mb-5" style="color:#F26C4F; width:15%; height: 3px;">
                <h1 class="letswork-heading text-white display-6 mb-3">Lets work on <span style="color: #F26C4F;text-decoration: underline #F26C4F;">projects</span> together</h1>
                <div class="lets-work">
                    <input type="email" placeholder="joen@example.com">
                    <a href="#" class="share-icon">
                        <i class="far fa-share-square"></i>
                    </a>
                </div>
                <!-- Social Media Icons -->
                <div class="socialMediaLinks display-6 text-white mt-4 pt-2">
                    <a href="https://github.com/fahadhassan1213" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://www.linkedin.com/in/fahad-hassan-70060320b/" target="_blank"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://twitter.com/FahadHa51773545" target="_blank"><i class="fab fa-twitter"></i></a>
                    <a href="https://web.facebook.com/fahad.hassan.9847867" target="_blank"><i class="fab fa-facebook"></i></a>
                    <a href="https://www.instagram.com/fahad_malik_0/" target="_blank"><i class="fab fa-instagram"></i></a>
                </div>
            
            </div>
            <div class="contact-decoration">
                <div class="contact-photo"></div>
                <div class="photo-bg"></div>    
            </div>
        </div>
    </section>

```

change the links in `href` attributes

To change the picture, got to `style.css` file and check
`.contact-photo` class selector

and just change the url path of `background-image` property to the image. and add the path of your image

```css
.contact-photo {
  height: 288px;
  width: 215px;
  background-image: url(images/aboutme-photo.PNG);
  border: 8px solid #2f2f2f;
  background-size: cover;
  background-repeat: no-repeat;
  position: relative;
  top: 10%;
  left: 34%;
  z-index: 2;
}

```


### To change the color theme of portfolio

```css
@charset "utf-8";

:root{
  --main-color: #f26c4f;
  --sec-color:whitesmoke;
}

```
Go to `style.css` file and on the top you see the `:root` selector, change the color of --main-color.
You will get your own portfolio with your own color theme 

Deployment
========================
When you have done with the setup you should host your site online

You can use [NETLIFY](https://www.netlify.com/) for deployment of your

for more information please read [hosting on Netlify](https://create-react-app.dev/docs/deployment/#netlify)
