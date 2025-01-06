# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS 
- Flexbox


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | QR code component</title>
  <!-- adding custom css -->
  <link rel="stylesheet" href="./style.css">
  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>

  </style>
</head>
<body>
  <!-- card section -->
  <section id="card">
    <main>
      <div class="card-section">
        <!-- card item -->
        <div class="card-item">
          <!-- card image -->
          <div class="card-image">
            <img src="./images/image-qr-code.png" alt="qr-code-img">
          </div>
          <!-- card description -->
          <article>
            <h3>Improve your front-end skills by building projects</h3>
            <p>Scan the <span>qr</span> code to visit Frontend Mentor and take your coding skills to the next level</p>
          </article>
        </div>
      </div>
    </main>
  </section>
  <!-- attribution -->
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
    Coded by <a href="https://github.com/rakib-hasan-78">Md Rakibul Hasan</a>.
  </div>
</body>
</html>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');
/* basic style */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

img{
    width:100%;
    height:100%;
    object-fit:cover;
}
body{
    background-color:hsl(212, 45%, 89%);
    width:100%;
    min-height:100vh;
    display:flex;
    flex-wrap:wrap;
    flex-direction: column;
    align-content: space-around;
    gap:3rem;
    align-items:center;
    justify-content:center; 
    font-family: "Outfit", serif;
}
main{
    width:90%;
    margin: 0 auto;
}
/* card section design */
#card{
    width:100%;
    height:auto;
}
.card-section{
    width: 100%;
    display:flex;
    align-items:center;
    justify-content: center;
    margin-top:1%;
    margin-bottom:1%;
}
/* card item or single card started */
.card-item{
    width:25%;
    padding: 1%;
    background:hsl(0, 0%, 100%);
    border-radius: .9375rem .9375rem .9375rem .9375rem;
    transition: transform 0.3s;
}
.card-item:hover {
    transform: scale(1.05);
}
/* card image  */
.card-image img{
    border-radius: 10px;
}
/* card title  */
article h3{
    color:hsl(218, 44%, 22%);
    text-align:center;
    font-weight:700;
    font-size:1.4rem;
    padding: .9375rem 0 ;
}
/* card paragraph  */
article p{
    text-align:center;
    font-weight:400;
    color:hsl(216, 15%, 48%);
    padding-bottom:.9375rem;
    font-size:1rem;
}
.attribution { 
    font-size: 11px; text-align: center; 
}
.attribution a { 
    color: hsl(228, 45%, 44%); 
}

/* Responsive Design */

/* Mobile (up to 375px) */
@media (max-width: 375px) {
    .card-item {
        width: 85% !important;
        padding:2%;
    }

    article h3 {
        font-size: 1.2rem;
    }

    article p {
        font-size: 0.9rem;
    }
}

/* Tablet (up to 768px) */
@media (max-width: 768px) {
    .card-item {
        width: 45%;
        padding:2%;
    }

    article h3 {
        font-size: 1.3rem;
    }

    article p {
        font-size: 1rem;
    }
}

/* Desktop (1440px and above) */
@media (min-width: 1440px) {
    .card-item {
        width: 25%;
    }

    .card-section {
        gap: 3rem;
    }

    article h3 {
        font-size: 1.6rem;
    }

    article p {
        font-size: 1.1rem;
    }
}
```


## Author

- Git Hub - [Md Rakibul Hasan](https://github.com/rakib-hasan-78)
- Frontend Mentor - [Md Rakibul Hasan](https://www.frontendmentor.io/profile/rakib-hasan-78)



## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
