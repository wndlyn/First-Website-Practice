# Simple HTML Portfolio

This is a simple HTML portfolio project created as part of the Application Development subject. This project showcases my first experience in web development, where I built a webpage displaying multiple images and names.

## Project Description

This project is a basic HTML page featuring several images with names displayed beneath them. The page uses external CSS for styling, layout, and visuals. The images are aligned in a grid layout to create a simple yet visually appealing structure.

### Features:
- Displays four images with titles.
- A clean and simple layout with basic styling.
- Responsive design using Flexbox.

## Technologies Used

- **HTML**: For the basic structure of the webpage.
- **CSS**: For styling the page, including Flexbox for layout.
- **Flexbox**: For creating a responsive, grid-based layout.

## Installation

To use this project, follow these steps:

1. **Clone or Download the Repository:**
   - If using Git:
     ```bash
     git clone <repository_url>
     ```
   - Alternatively, download the HTML and CSS files directly from the repository.

2. **Open the Project in a Browser:**
   - After downloading or cloning, open the `index.html` file in any modern web browser.

## How to Use

1. **Viewing the Page:**
   - Open the `index.html` file to view the webpage. It will display the images with the name "Wendelyn Paller" under each one.
   
2. **Customizing the Content:**
   - To change the images or names:
     - Modify the `<img src="image_url">` tags with your image URLs.
     - Change the text inside the `<h3>` tags to update the names.

### Example HTML Structure

```html
<div class="container">
    <div class="image">
        <img src="image_url" alt="Just a photo">
        <h3 style="color: #e41595">Wendelyn Paller</h3>
    </div>
    <!-- Repeat for other images -->
</div>
