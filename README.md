# Ruth Stengård Portfolio

This is my portfolio where I introduce myself, my projects and how to contact me.
Target group: no specific age target 

## Links to this project
- Live site: https://ruth-stengard-portfolio.netlify.app/
- Github: https://github.com/st-ruth/ruth_stengard-portfolio 

## About the project
This project was created as a part of a course in HTML & CSS. 
The focus has been on creating a responsive and user-friendly portfolio with a well-thought-out design and structure.

## How to run locally
1. Clone this repository:
   git clone https://github.com/st-ruth/ruth_stengard-portfolio.git

2. Navigate into the project folder:
   cd ruth_stengard-portfolio

3. Open index.html in your browser  
   (or use Live Server in VS Code for a better development experience)

## NOTES ON STRUCTURE
Some repeated flexbox patterns (e.g centered layouts) are intentionally kept within each component instead of being abstracted into global utility classes. This was a consicious decision to improve readability and make it easier to debug and maintain the code during development. 

## Technique
- HTML5 and semantic structure
- CSS: flexbox & grid
- Mobile first
- Responsive: larger phone (640px) tablet (768px) & desktop (1024px)
- Accessibility: alt texts, structure, aria labels etc

## Content
- Index page
- Project page with selected works
- About page
- Contact page 

## Project 
- *Tinctura*  : concept of a platform that connects artists and buyers, (built with HTML & CSS)
- *Electric Banana Land* : my first website, a fictional zoo page (built with HTML, CSS & JavaScript)
- *Cultural Painter* & *digital illustration* : presentation of my background in painting

## KNOWN PROBLEMS
- *projects page* : At screen resolution 1920x1080, the desktop view gets skewed: margin-left increases unexpectedly, and the footer underlaps the cards. At higher resolutions (2650x1600) it looks fine. Likely related to aspect ratio, but I haven’t had time to investigate further.
- *about page* : Received a validation-warning of missing heading attribute on my `img`. I added a `h4` and used `display:none` to work around this issue, thought I'm not sure if this is the best practice. 