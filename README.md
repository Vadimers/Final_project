# Final Project

## Project Overview

This project is a fully functional, responsive web application built based on a provided Figma design. It demonstrates proficiency in SCSS, responsive design, and JavaScript for interactive elements. The website includes a homepage, about section with tabs, services slider, and a contact form, all styled and optimized for various devices.

## Features

- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile devices using media queries.
- **SCSS Styling**: Utilizes variables, mixins, and nesting for maintainable and scalable CSS.
- **Interactive Elements**:
  - Hamburger menu for mobile navigation.
  - Tabbed content in the About section.
  - Slider for showcasing services.
- **Cross-Browser Compatibility**: Tested on Chrome, Firefox, and Safari.
- **HTML/CSS Validation**: Code adheres to W3C standards, validated using online tools.
- **Accessibility**: Ensures content is accessible with semantic HTML and proper ARIA attributes.

## Technologies Used

- **HTML5**: For semantic structure.
- **SCSS**: For advanced CSS styling with variables and mixins.
- **JavaScript**: For interactive features like tabs, slider, and hamburger menu.
- **Figma**: For design reference and layout planning.(https://www.figma.com/design/Xzmk5hBhdY8HsmcBkiuo1B/grid-template?node-id=1-2&p=f)

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Vadimers/Final_project.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Final_project
   ```
3. Install dependencies (if using a CSS preprocessor like Sass):

   ```bash
   npm install
   ```
4. Compile SCSS to CSS (if not pre-compiled):

   ```bash
   npx sass styles.scss styles.css
   ```
5. Open `index.html` in a browser or use a local server:

   ```bash
   npx live-server
   ```

## Project Structure

- `index.html`: Main HTML file with the website structure.
- `styles.scss`: SCSS file containing all styles, compiled to `styles.css`.
- `README.md`: Project documentation.

## Implementation Details

- **SCSS Organization**: Uses variables for colors and fonts, mixins for reusable styles, and nesting for clarity.
- **Responsive Design**: Media queries handle layouts for screens below 768px (tablet) and 480px (mobile).
- **Interactivity**: JavaScript manages the hamburger menu toggle, tab switching, and slider navigation.
- **Validation**: HTML and CSS were validated using W3C validators to ensure compliance.
- **Optimization**: Images (if used) are optimized, and CSS is minified for production.

## Running the Project

- Ensure `styles.css` is compiled from `styles.scss`.
- Open `index.html` in a modern browser.
- Test responsiveness by resizing the browser or using developer tools' device emulation.

## Future Improvements

- Add form submission handling with a backend.
- Implement lazy loading for images.
- Enhance accessibility with more ARIA landmarks.

## Author

Vadim 

