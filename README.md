OJOGBONN Real Estate Website
Overview
The OJOGBONN Real Estate website is a responsive, mobile-first web application designed to help users find their ideal property. It features a clean and modern design with sections for property listings, frequently asked questions (FAQ), contact information, and social media links. The website is built using HTML and CSS, with a focus on accessibility, responsiveness, and user experience.
This project was developed as part of a coding exercise to demonstrate skills in front-end web development, including responsive design, CSS grid/flexbox layouts, and SVG integration for icons.
Features
Responsive Design: The website is fully responsive and works seamlessly on mobile, tablet, and desktop devices.

Property Listings: A section to display featured properties with images, prices, and details.

Search Form: A form to search properties by location, type, and price range (non-functional, for design purposes).

FAQ Section: A frequently asked questions section with a two-column layout on larger screens.

Social Media Links: Circular buttons with SVG icons linking to various platforms (Zoom, Discord, Dropbox, Slack, Stripe, Airbox, Twitter (X), and Facebook).

Contact Section: Contact information and a newsletter signup form.

Accessibility: Includes aria-label attributes for screen readers and tooltips for better usability.

Modern Styling: Uses the Poppins font, a teal color scheme, and subtle hover effects for interactivity.

Technologies Used
HTML5: For the structure of the website.

CSS3: For styling, including flexbox, grid, and media queries for responsiveness.

Google Fonts: Poppins font for typography.

SVGs: Inline SVGs for social media icons in the button-wrapper section.

Setup Instructions
Prerequisites
A modern web browser (e.g., Chrome, Firefox, Safari, Edge).

A code editor (e.g., Visual Studio Code) for making changes to the files.

(Optional) A local development server (e.g., Live Server extension in VS Code) to view the website locally.

Installation
Clone or Download the Repository:
If using Git, clone the repository:
bash

git clone https://github.com/your-username/ojogbonn-real-estate.git

Alternatively, download the project files as a ZIP and extract them.

Navigate to the Project Directory:
bash

cd ojogbonn-real-estate

Open the Website:
Open the index.html file in a web browser:
bash

open index.html

Alternatively, use a local development server (e.g., Live Server in VS Code) to view the website at http://localhost:port.

File Structure

ojogbonn-real-estate/
│
├── index.html         # Main HTML file containing the website structure
├── styles.css         # CSS file for styling the website
└── README.md          # Project documentation (this file)

index.html: Contains the HTML structure of the website, including sections for the header, home, properties, FAQ, contact, and footer.

styles.css: Contains all the CSS styles, including responsive design rules using media queries.

README.md: This file, providing an overview and setup instructions.

Usage
Navigation: Use the navigation bar at the top to access different sections (Home, Features, Pages, Blog, Contact). Note: Links are non-functional and for design purposes only.

Search Properties: The search form in the home section allows users to filter properties by location, type, and price (non-functional, for design purposes).

View Properties: The "Find Your Perfect Home Today" section displays a list of properties with images and details.

Social Media Links: Hover over the circular buttons in the button-wrapper section to see tooltips with platform names. Note: Links are non-functional and for design purposes only.

FAQ: The FAQ section provides answers to common questions in a responsive two-column layout on larger screens.

Contact: The contact section includes addresses, phone numbers, and a newsletter signup form (non-functional, for design purposes).

Customization
Replacing SVG Icons
The social media icons in the button-wrapper section are currently placeholder SVGs. To use official logos:
Source official SVGs from each platform's brand guidelines:
Zoom: Zoom Brand Guidelines

Discord: Discord Brand Assets

Dropbox: Dropbox Brand Guidelines

Slack: Slack Brand Guidelines

Stripe: Stripe Brand Assets

Airbox: Replace with a relevant platform if needed.

Twitter (X): X Brand Guidelines

Facebook: Facebook Brand Resources

Replace the inline SVGs in the index.html file under the button-wrapper section with the official SVGs.

Adding Functional Links
To make the social media buttons functional:
Wrap each button in an <a> tag with the appropriate href attribute:
html

<a href="https://zoom.us" aria-label="Zoom" title="Zoom">
  <button>
    <!-- SVG here -->
  </button>
</a>

Repeat for each platform with its respective URL.

Styling Adjustments
Colors: Modify the teal accent color (#26a69a) in styles.css to match your brand.

Typography: Change the font by updating the Google Fonts import in index.html and the font-family in styles.css.

Button Sizes: Adjust the width and height of the .button-wrapper button in styles.css to change the size of the social media buttons.

Known Issues
Placeholder SVGs: The social media icons are currently placeholders and should be replaced with official SVGs for production use.

Non-Functional Links: The navigation links, search form, social media buttons, and newsletter form are for design purposes only and do not have backend functionality.

Image Performance: Images are loaded from external URLs, which may affect load times. Consider hosting images locally for better performance.

Future Improvements
Add Interactivity: Implement JavaScript to make the search form, navigation links, and newsletter form functional.

Accordion for FAQ: Add JavaScript to create an accordion effect for the FAQ section, where answers are hidden by default and toggle on click.

Optimize Images: Host images locally and compress them to improve load times.

Custom Tooltips: Replace the default title tooltips with styled CSS tooltips for a better user experience.

Backend Integration: Add a backend (e.g., Node.js, Express) to handle form submissions and property data.

Contributing
Contributions are welcome! To contribute:
Fork the repository.

Create a new branch for your feature or bug fix:
bash

git checkout -b feature-name

Make your changes and commit them:
bash

git commit -m "Add feature-name"

Push to your branch:
bash

git push origin feature-name

Create a pull request with a description of your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, please contact:
Email: ajayiolaoluwa88@yahoo.com.com

GitHub: oluwaseunolaoluwaajayi

