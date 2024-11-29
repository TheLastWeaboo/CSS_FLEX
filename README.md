# CSS_FLEX Project
## Overview
This project demonstrates the application of CSS Flexbox to create visually appealing and responsive layouts for different types of web pages. Flexbox is a powerful layout module in CSS that simplifies alignment, spacing, and distribution of elements within a container, even when their sizes are dynamic.

The project contains several examples of real-world use cases, including:

Electronic Product Cards
Employee Profile Cards
Student Profile Cards
Gallery Layout
Pricing Cards
Each page showcases the flexibility and ease of use that Flexbox provides for creating structured, responsive designs.

## How Flexbox is Used in This Project
### 1. Product Cards Layout
We used Flexbox to create a responsive grid for displaying electronic product cards. The cards adjust their placement and spacing dynamically based on the screen size.

Key Flexbox Properties Used:

display: flex;: Enables Flexbox on the parent container.
flex-wrap: wrap;: Allows items to wrap to the next row if there's not enough space.
justify-content: center;: Centers the cards horizontally.
gap: 20px;: Adds consistent spacing between cards.
### 2. Employee Profile Cards
The layout arranges employee profiles in rows, and the cards expand or shrink to fit the available space.

Key Flexbox Properties Used:

display: flex;: Activates Flexbox on the container.
flex-direction: row;: Ensures the items are laid out in rows.
justify-content: space-around;: Evenly distributes cards with equal space between and around them.
### 3. Student Profile Cards
For this layout, the Flexbox properties allow equal spacing between rows and alignment to the center of the container.

Key Flexbox Properties Used:

align-items: center;: Vertically centers the content within the container.
flex-wrap: wrap;: Ensures the cards wrap to new rows if necessary.
gap: 10px;: Adds spacing between rows and columns.
### 4. Gallery Layout
A gallery layout showcases images arranged neatly in a responsive grid. The Flexbox properties ensure that the images are evenly spaced and wrap to the next row when necessary.

Key Flexbox Properties Used:

display: flex;: Enables Flexbox on the parent container.
flex-wrap: wrap;: Allows images to wrap onto multiple rows.
justify-content: space-evenly;: Distributes images with equal spacing between and around them.
gap: 15px;: Adds spacing between images.
### 5. Pricing Cards
The pricing cards layout uses Flexbox to align different card components vertically and ensures uniform spacing between them. It also centers the cards on the screen for better visual appeal.

Key Flexbox Properties Used:

display: flex;: Activates Flexbox for the card container.
flex-direction: column;: Aligns items vertically within each card.
align-items: center;: Centers content within the card.
gap: 10px;: Adds space between card components (e.g., title, price, and features).
