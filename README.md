# Image Gallery with SCSS

A responsive image gallery with hover animation effects built using HTML and SCSS.

🔗 **Demo:** https://image-gallery-with-scss-nkznvf69n-vivek-crews-projects.vercel.app/

## Description

This project creates an interactive image gallery where images expand smoothly on hover.  
The gallery uses Flexbox for layout and SCSS for styling with smooth transitions.

## Features

- Responsive layout using Flexbox  
- Smooth hover animations  
- CSS transitions with cubic-bezier timing  
- Five image sections that expand on hover  
- Mobile-friendly design  

## Technologies

- HTML5  
- SCSS / CSS  
- CSS Flexbox  

## Project Structure

scss/
├── index.html
├── style.scss
├── style.css
└── assets/
├── image1.jpg
├── image2.jpeg
├── image3.jpeg
├── image4.jpeg
└── image5.jpeg

markdown
Copy code

## Setup

1. Clone the repository:  
   `git clone <repository-url>`
2. Navigate to the project folder:  
   `cd scss`
3. Install or use any SCSS compiler (e.g., Dart Sass).  
4. Compile SCSS to CSS:  
   `sass style.scss style.css`
5. Open **index.html** in your browser.

## How it Works

- Flexbox arranges gallery items horizontally.  
- Each item uses `flex-grow` to smoothly expand on hover.  
- Transitions use a cubic-bezier timing function for elegant animation.  
- Background images use `background-position: center` and `background-size: cover`.

## Styling Details

- Reset margins and padding to zero.  
- Full-viewport gallery layout.  
- 10px gap between items.  
- 0.75s smooth transition on hover.  
- Subtle borders and overflow handling for visual polish.

## Browser Support

Supports all modern browsers with Flexbox, CSS transitions, and background image capabilities.
