Google Clone Project Documentation
Overview
The Google Clone project is a simple implementation of a Google homepage replica using HTML, CSS, and JavaScript. The project replicates key elements of the Google homepage, such as the navigation bar, search bar, buttons, and footer.

Project Structure
The project is organized into three main files:

index.html: Defines the structure of the webpage, including the header, content section, and footer.
style.css: Provides the styling for the HTML elements, creating a clean and visually appealing layout.
main.js: Implements functionality for the search bar, allowing users to perform a Google search by pressing the "Enter" key.
Styling Choices
Global Styling
Box Model Reset: The * selector is used to reset the margin, padding, and box-sizing properties for all elements, ensuring a consistent layout.
Header Styling
Navbar: The navigation bar (navbar) is styled with a background color, padding, and a flex layout. Links (a) in the navbar are styled with a margin and color, and the hover effect is applied to the .link:hover selector.

Icons: Menu and user icons have a circular shadow effect on hover, creating a visually appealing interaction.

Content Styling
Logo: The Google logo (logo-img) is styled with a specific width and margin.

Search Bar: The search bar (search-bar) is styled with rounded corners, a box shadow on hover, and icons for search, keyboard, and microphone.

Buttons: Search buttons (google-search-btn and lucky-search-btn) have specific styling for height, font size, and background color.

Language: The language section (language) has a margin-top and font size applied.

Footer Styling
Footer Content: The footer (footer) has distinct upper and lower sections. Links in the lower footer have a hover effect.
Responsive Design
Media Queries: Media queries are used to adjust styles for smaller screens (max-width: 650px). This includes changes to font sizes, logo width, search bar dimensions, and adjustments to the footer layout.
JavaScript Functionality
Search on Enter: The JavaScript code listens for the "Enter" key event on the search input (#search-input) and triggers the search function. The search function constructs a Google search URL based on the input value and navigates to the search results.
Usage
To use the Google Clone project:

Clone the repository.
Open the index.html file in a web browser.
Feel free to customize the project, including the logo, links, and search functionality, according to your needs.
