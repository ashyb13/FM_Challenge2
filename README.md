# Frontend Mentor - QR code component solution
This is a solution to the [Blog Preview Card Component](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview
This project is a Frontend Mentor challenge solution where the goal was to build a simple, responsive webpage that displays a Blog Preview card. The card includes a vector graphic image with a hyperlink-heading and short descriptive text underneath. The focus of the project was on HTML structure, and CSS styling.
The project also demonstrates basic Git and GitHub workflow, including adding and updating files such as HTML, CSS, and images.
This simple project is a great exercise in layout, styling, and design precision, making it ideal for practicing frontend fundamentals.


### Screenshot
Here is a link to the images of my final solution:

- [Desktop View](images/final-desktop.png)
- [Mobile View](images/final-mobile.png)


### Links
Live Site URL: 
(https://fm-challenge2-coral.vercel.app)


## My process
- I started off with adding HTML to the document. This was a quick and simple process as it only required a few short sentences, link the CSS to the HTML, adding an image, and using semantic elements.
- I then moved on to my CSS. Compared to last time that I did this challenge, it went a lot smoother.
- Finally, I put it all together to be the final solution (seen in the links above).

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Queries


### What I learned
This time around my challenge to myself was to learn Flexbox, and integrating/applying throughot the solution (as seen below in my 'body' and 'container'):

```css
body{
margin: 0;
padding: 0;
line-height: 1.6;
word-spacing: 1.4px;
display: flex;
...(removed excess to shorten)
}

.container{
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1rem;
}
```

I finally learnt how to center-align my elements (the blog card and the image). And because I used flexbox it was so much easier this time around. In addition to aligning it in the center, I also learnt to set the height of the page:

```css
body{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

I learnt about media queries to allow the page to be responsive to certain widths of the page, and you can see below I also learnt to have the font responsive:

```css
@media (max-width: 375px) {
  #blog-card {
    width: 90%;      
    height: auto;    
  }

  h2 {
    font-size: 1.1rem;
  }

  #subtitle {
    font-size: 0.9rem;
  }
}
```


### Continued development
I really enjoyed this challenge, especially using flexbox. I really want to focus on developing that side of it, I'm more comfortable now with CSS grid, but I prefer using flexbox - in all honesty (lol). 
I heard about two new forms of CSS:
- Bootstrap
- Tailwind

And so those are things I want to look into learning, so I'm quite excited.


### Useful resources
- [Master Media Queries And Responsive CSS Web Design Like a Chameleon!](https://www.youtube.com/watch?v=K24lUqcT0Ms) - This was a great brief intro into media queries and a responsive webpage.
- [Designing in Mobile First](https://www.youtube.com/shorts/K7vT9DAnqdE) - Helped me understand a bit more about media queries
- [Learn Flexbox CSS in 8 minutes](https://www.youtube.com/watch?v=phWxA89Dy94) - Another great brief intro into Flexbox
- [How to Take the Right Approach to Responsive Web Design](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/) - Good documentation on the "mobile-first" approach when it comes to responsiveness


## Author
- LinkedIn - [Ashton Blaze Berridge](https://www.linkedin.com/in/ashton-berridge-6ba4ab255/)
- Frontend Mentor - [@ashyb13](https://www.frontendmentor.io/profile/ashyb13)
- GITHUB - [@ashyb13](https://github.com/ashyb13)


## Acknowledgments
I took this project on my own, but I do give credit to one of my friends who actually helped me review my solution, fix it, and also let me know about the two other forms of CSS. And, so I'm grateful for that  
