# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### Screenshot

![](./assets/images/Screenshot%202026-05-07%20225154.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned


```html
<h2>Nutrition</h2>
    <p>The table below shows nutritional values per serving without the addition.</p>
    <table class="nutrition-table">
      <tr>
        <th>Calories</th>
        <td><strong>277 kcal</strong></td>
      </tr>
      <tr>
        <th>Carbs</th>
        <td><strong>0 g</strong></td>
      </tr>
      <tr>
        <th>Protein</th>
        <td><strong>20 g</strong></td>
      </tr>
      <tr>
        <th>Fat</th>
        <td><strong>22 g</strong></td>
      </tr>
    </table>
```
```css
hr {
      border: none;
      border-top: 1px solid hsl(30, 18%, 87%);
      margin: 20px 0;
    }

    table {
      width: 100%;
      margin-top: 10px;
    }

    table th,
    table td {
      text-align: left;
      padding: 10px;
    }

    table td strong {
      color: hsl(14, 45%, 36%);
    }
```

### Continued development

- Responsive design: I want to keep improving my ability to make layouts adapt seamlessly across mobile, tablet, and desktop. While this project works well at 375px and 1440px, I’d like to refine intermediate breakpoints for smoother scaling.

- Accessibility (WCAG): I plan to focus more on semantic HTML, ARIA labels, and color contrast checks to ensure my projects are usable by everyone.

- Typography systems: I’d like to get more comfortable with pairing fonts and managing consistent line-heights, weights, and spacing across sections.

- Reusable components: Instead of writing one-off CSS, I want to practice structuring my styles into reusable utility classes or using a methodology like BEM.

- Advanced CSS techniques: I’d like to refine transitions, animations, and grid/flexbox layouts to make my designs more polished and interactive.

## Author

- Frontend Mentor - [@buildwithtaku](https://www.frontendmentor.io/profile/buildwithtaku)
- Twitter - [@withTakuJ](https://www.twitter.com/withTakuJ)
