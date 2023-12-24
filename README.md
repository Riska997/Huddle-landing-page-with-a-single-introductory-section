# Frontend Mentor - Huddle landing page with single introductory section solution 

  

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

  

## Table of contents 

  

- [Overview](#overview) 

  - [The challenge](#the-challenge) 

  - [Screenshot](#screenshot) 

  - [Links](#links) 

- [My process](#my-process) 

  - [Built with](#built-with) 

  - [What I learned](#what-i-learned) 

  - [Continued development](#continued-development) 

  - [Useful resources](#useful-resources) 

- [Author](#author) 

- [Acknowledgments](#acknowledgments) 

  

  

  

## Overview 

This README provides insights into the development of the Huddle Landing Page. The landing page is designed to promote a community-building platform and engage users with its visually appealing and responsive interface. 

This project is a landing page for Huddle, a platform that re-imagines the way we build communities. The landing page emphasizes creating connections with users through genuine discussions. 

  

### The challenge 
The challenge was to design and implement an engaging landing page that effectively communicates the core features and benefits of Huddle. 
Users should be able to: 
- View the optimal layout for the page depending on their device's screen size 
- See hover states for all interactive elements on the page
- 
### Screenshot 

  

### Links 

- https://github.com/Riska997/Huddle-landing-page-with-a-single-introductory-section.git 

-  https://riska997.github.io/Huddle-landing-page-with-a-single-introductory-section/

  

## My process 

 In developing the Huddle Landing Page, I followed a systematic process to ensure a cohesive and visually appealing result. 

### Built with 

The project is primarily built with the following technologies:  

- HTML: The HTML file follows a standard structure with meta tags, links to external stylesheets, and a body divided into header, main content, and footer sections. 

 - CSS: The styling is defined in "style.css," incorporating custom styles, imported fonts, and media queries for a responsive design. 

- [Font Awesome] (https://fontawesome.com/) for icons 

  

### What I learned 

Effective Landing Page Design: 

The project allowed me to delve into the principles of effective landing page design. I learned how to structure content to create a visually appealing and user-friendly interface. This included considerations for layout, color schemes, typography, and the strategic placement of interactive elements. 

Understanding the importance of creating a seamless and intuitive user experience was a key takeaway. This involved optimizing the visual hierarchy, ensuring a responsive design for various screen sizes, and implementing best practices for readability and accessibility. 

User Engagement Strategies: 

I explored strategies to enhance user engagement on the landing page. This encompassed creating compelling and concise copywriting, using captivating visuals, and implementing hover states for interactive elements. Learning how to strike a balance between informative content and an aesthetically pleasing design was a crucial aspect of this experience. 

Additionally, I gained insights into the significance of clear calls-to-action (CTAs) and how they contribute to guiding users through the desired interactions on the page. Implementing these strategies was a valuable lesson in creating a landing page that not only informs but also encourages user interaction. 

Integration of External Libraries: 

During the development process, I had the opportunity to integrate external libraries to enhance the functionality and visual appeal of the landing page. Specifically, the project involved the use of Font Awesome for including iconic elements seamlessly. Understanding how to incorporate and customize external libraries expanded my toolkit and provided a hands-on experience in leveraging third-party resources effectively. 

This experience deepened my understanding of how to explore and integrate external tools to complement the project requirements, showcasing the versatility and efficiency of utilizing established libraries. 

 

 ```html 

<div class="container"> 

    <div class="wrapper"> 

      <div class="header"> 

        <img src="images/logo.svg"> 

      </div> 

      <div class="main"> 

        <!-- ... other content ... --> 

      </div> 

      <div class="footer"> 

        <!-- ... social icons ... --> 

      </div> 

    </div> 

</div> 

 

``` 

```css 

.container { 

  max-width: 1320px; 

  margin: 0 auto; 

  height: 100vh; 

} 

  

.wrapper { 

  display: flex; 

  flex-direction: column; 

  justify-content: space-between; 

  height: 90%; 

  padding-top: 40px; 

  padding-bottom: 40px; 

  margin: 0 2rem; 

} 

  

.header img { 

  width: 170px; 

  padding-bottom: 20px; 

} 

  

.main { 

  display: flex; 

  align-items: center; 

  justify-content: space-between; 

  gap: 40px; 

} 

 

``` 

```html 

<div class="text_main"> 

  <h1>Build The Community Your Fans Will Love</h1> 

  <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. 

    Create connections with your users as you engage in genuine discussion.</p> 

  <a href="#">Register</a> 

</div> 

``` 

 

```css 

.text_main h1 { 

  color: #fff; 

  font-family: "Open Sans", sans-serif; 

  font-size: 36px; 

  line-height: 1.7; 

  margin-bottom: 20px; 

} 

  

.text_main p { 

  color: #fff; 

  font-family: "Poppins", sans-serif; 

  line-height: 1.8; 

  margin-bottom: 30px; 

} 

  

.text_main a { 

  display: inline-block; 

  font-family: "Poppins", sans-serif; 

  background: #fff; 

  padding: 13px 50px; 

  border-radius: 25px; 

  text-decoration: none; 

  box-shadow: 0 8px 17px -8px rgba(0, 0, 0, 0.8); 

  transition: all 0.3s ease; 

} 

  

.text_main a:hover { 

  background-color: hsl(300, 69%, 71%); 

  color: white; 

} 

``` 

```html 

<div class="footer"> 

  <a href="#"> 

    <i class="fab fa-facebook-f"></i> 

  </a> 

  <a href="#"> 

    <i class="fab fa-twitter"></i> 

  </a> 

  <a href="#"> 

    <i class="fab fa-instagram"></i> 

  </a> 

</div> 

``` 

```css 

.footer a i { 

  color: #fff; 

  position: relative; 

  font-size: 18px; 

  transition: all 0.3s ease; 

} 

  

.footer a:not(:first-child) { 

  margin-left: 2rem; 

} 

  

.footer a i::after { 

  content: ""; 

  position: absolute; 

  height: 40px; 

  width: 40px; 

  border-radius: 50%; 

  border: 2px solid white; 

  left: -14px; 

  bottom: -13px; 

  transition: all 0.3s ease; 

} 

  

.footer a:hover i { 

  color: hsl(300, 69%, 71%); 

} 

  

.footer a i:hover::after { 

  border-color: hsl(300, 69%, 71%); 

} 

``` 

 

   

### Continued development 

To further enhance the Huddle Landing Page, I plan to implement additional features, refine the user interface, and optimize performance. 

  

### Useful resources 

During the development process, the following resources proved valuable:  

- [Google Fonts](https://fonts.google.com/) for Open Sans and Poppins fonts  

- [Font Awesome](https://fontawesome.com/) for icon integration 

 

## Author 

  

- Ris [GitHub Profile] (https://github.com/Riska997/Huddle_landing-page-with-a-single-introductory-section)  

## Acknowledgments 

  

I would like to acknowledge the following:  

- The Huddle team for inspiration  

- Online communities for valuable insights  

- Font Awesome for providing a rich set of icons  

- [Mr Coder's YouTube Channel]( for helpful tutorials and guidance 

 
