# Admin Dashboard

A responsive dashboard layout built with modern CSS, focusing on CSS Grid and Flexbox. This project is part of The Odin Project's Full Stack JavaScript curriculum.

[Live Demo](https://admin-dashboard-sigma-nine-51.vercel.app/)

## About The Project

This project was a challenge to build a complex, real-world layout from a design mockup. The primary goal was to practice and solidify advanced CSS layout skills, particularly by creating a robust structure with CSS Grid for the main page and using Flexbox for finer, component-level alignment.

The entire page is built from scratch using semantic HTML5 and vanilla CSS3, without any external libraries or frameworks.

## Features

- **Main Layout:** A two-column structure for the sidebar and main content, built with CSS Grid.
- **Nested Grids:** The main content area is itself a grid, separating the project cards from the announcements and trending sections.
- **Dynamic Card Grid:** The project cards are laid out in a responsive grid that can accommodate a variable number of items.
- **Flexbox for Alignment:** Flexbox is used extensively for aligning items within components, such as the header, sidebar navigation, and card action icons.
- **Semantic HTML:** The structure is built with semantic tags (`<header>`, `<aside>`, `<span>`, etc.) for better accessibility and maintainability.

## Technologies Used

- HTML5
- CSS3
  - CSS Grid
  - CSS Flexbox

## What I Learned

This project was a deep dive into the practical application of modern CSS layout techniques. Key takeaways include:

- **Grid vs. Flexbox:** I gained a much deeper understanding of when to use Grid (for overall page layout and two-dimensional structure) and when to use Flexbox (for one-dimensional alignment of components).
- **Debugging Layouts:** I developed a strong methodology for debugging layout issues, particularly with Grid. Understanding how adding a new element can disrupt the grid flow was a major "aha!" moment.
- **Parent-Child Context:** The project hammered home the importance of context. Solving issues like the "shrinking flex item" (`flex-shrink`) or an item not aligning properly (`align-self` vs. `align-items`) required understanding the properties of both the parent container and the item itself.
- **Clean and Modular Structure:** By breaking down the page into logical components (`.card`, `.sidebar`, `.header`), the code remains organized and easier to manage.

## Acknowledgements

- This project was completed as part of [The Odin Project's](https://www.theodinproject.com/) curriculum.
- Icons provided by [Material Design Icons](https://materialdesignicons.com/).
