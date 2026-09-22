# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

Frontend Mentor challenges help improve frontend development skills by building realistic projects from provided designs.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)

- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)

- [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

The goal of this challenge was to build a blog preview card that closely matches the provided Frontend Mentor design.

Users should be able to:

- View the blog preview card clearly on different screen sizes.
- See the different sections of the card, including the category, title, description, and author information.
- See hover and focus states for interactive elements.
- View the page with a clean and responsive layout.

## My Process

### Built With

- Semantic HTML5 markup
- CSS3
- CSS Flexbox
- CSS Grid
- Responsive design
- Custom CSS styling
- Relative file paths for images and assets

### What I Learned

This project helped me practice creating a simple UI from a design using HTML and CSS.

Some of the main things I practiced include:

#### 1. CSS Grid

I used CSS Grid to structure the main card and control the spacing between its elements.

```css
.card-container {
  display: grid;
  width: 400px;
  padding: 2rem;
  border-radius: 1rem;
}
```

#### 2. Flexbox

I used Flexbox to arrange elements such as the author's image and name horizontally.

```css
.card-icon-img {
  display: flex;
  gap: 1rem;
}
```

#### 3. CSS Spacing

I practiced using properties such as `padding`, `margin`, `gap`, and `padding-block` to control spacing and create a cleaner layout.

```css
.card-section {
  padding-block: 5rem;
}
```

#### 4. Borders and Box Shadows

I learned how to recreate the card's visual appearance using borders, rounded corners, and a solid box shadow.

```css
.card-container {
  border: 1.5px solid hsl(0, 0%, 7%);
  border-radius: 1rem;
  box-shadow: 7px 7px 0 black;
}
```

#### 5. HSL Colors

I used HSL color values to match the colors from the design.

```css
background-color: hsl(47, 88%, 63%);
```

## Continued Development

For future projects, I want to continue improving my understanding of:

- Responsive web design
- CSS Grid and Flexbox
- CSS positioning
- Media queries
- Accessibility
- Semantic HTML
- Creating more complex layouts from designs
- Writing cleaner and more maintainable CSS

I also want to continue building more Frontend Mentor projects to improve my ability to turn designs into functional websites without relying heavily on frameworks.

## Useful Resources

- [Frontend Mentor](https://www.frontendmentor.io/) - The platform used for this challenge.
- [MDN Web Docs](https://developer.mozilla.org/) - Useful reference for HTML and CSS.
- [CSS-Tricks](https://css-tricks.com/) - Helpful CSS guides and explanations.

## AI Collaboration

I used ChatGPT as an AI learning and development assistant while working on this project.

I used it mainly to:

- Understand HTML and CSS concepts.
- Debug CSS issues.
- Understand why particular CSS properties affected the layout.
- Get explanations of Flexbox and Grid.

The goal was to understand the code and concepts rather than simply copy a finished solution.

## Author

- **Name:** Joshua Uko
- **Frontend Mentor:** https://www.frontendmentor.io/profile/Joshuauko
- **GitHub:** https://github.com/Joshuauko

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for providing the challenge and design that I used to practice my frontend development skills.

Thanks also to the developers and educators whose HTML and CSS resources helped me better understand the concepts used in this project.
