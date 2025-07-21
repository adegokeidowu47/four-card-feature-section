# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The Gridchallenge](#the-grid-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with HTML & CSS](#built-with-HTML-&-CSS)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- Responsiveness is one of the important things to take note while designing a website across every screen that can access it. And the View of the optimal layout for the site depending on their device's screen size. 
  This  challenge enlighten me more on how to use Grid layout to present a good and responsive website. I learnt a lot.


### Screenshot

![](images/Screenshot%202025-07-20%20at%2017-26-09%20Frontend%20Mentor%20Four%20card%20feature%20section.png)
![](images/Screenshot%202025-07-20%20at%2017-35-18%20Frontend%20Mentor%20Four%20card%20feature%20section-mobile.png)




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- Mark up with HTML5, How the web will look like and its contents
- Styles with Cascading Style Sheets(CSS).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned


```css
.content-container {
        display: grid;
        grid-template: 290px 1fr 1fr / 1fr 1fr 1fr;
        grid-row-gap: 15px;
        grid-column-gap: 20px;
    }

    header {
        margin: 0 auto;
        grid-row: 1 / 2;
        grid-column: 1 / 4;
    }

     .supervisor {
        grid-row: 2 / 4;
        grid-column: 1 / 2;
    }

    .Calculator {
        grid-row: -1 / -3;
        grid-column: 3 / 4;
    }
```


### Useful resources

- [Resource 1](https://www.frontendMentor.com/learning-path) - Thier article has helped me a lot, especially the reference tutorial materials gave me more insight. I really liked this pattern and will use it going forward.

- [Resource 2](Niederst Robbins, Jennifer - Learning Web Design _ A Beginner’s Guide to HTML, CSS, JavaScript, and Web Graphics-O’Reilly Media (2018)) - This is an amazing textbook which helped me finally understand the usage of Grid propery and their respective values. I'd recommend it to anyone still learning this concept.


## Author
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Adegokeidowu20](https://www.twitter.com/Adegokeidowu20)
