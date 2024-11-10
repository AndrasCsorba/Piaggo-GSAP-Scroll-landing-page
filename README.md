

Scroll GSAP Piaggio Website! 
Just Desktop version, becouse the GSAP amination.
LIVE DEMO ==>>https://andrascsorba.github.io/Piaggo-GSAP-Scroll-landing-page/

Overview:

The Scroll GSAP Piaggio Website project is an interactive web page showcasing the Piaggio Liberty 150 scooter. Using animations and scroll-based transitions powered by GSAP (GreenSock Animation Platform) and ScrollTrigger, this project offers a visually engaging experience where users can explore the model’s specifications and features as they scroll.

Project Structure
This project consists of three main files:

index.html: The HTML structure of the webpage.
style.css: Stylesheet for layout and design.
script.js: JavaScript animations using GSAP and ScrollTrigger.
Technologies Used
HTML5 and CSS3
JavaScript
GSAP and ScrollTrigger libraries (loaded via CDN)
File Breakdown
index.html
The HTML structure includes:

Header: SVG icons for styling and branding.
Panel: Displays the Piaggio Liberty 150 model with details and rotating view.
Specifications and Characteristics: Lists displaying model features.
Outro: Concludes with pricing and a "Learn More" button.
style.css
Defines the styling and layout:

Fonts: Uses Bebas Neue and Oswald for a modern look.
Background: Subtle patterned background to enhance contrast.
Containers and Layouts: Centered container with styled panels, headers, and footers.
Outro: Styled footer section with pricing and CTA button.
script.js
Uses GSAP and ScrollTrigger to create scrolling animations. Key animation timelines include:

Intro: Initial animations for the logo, main image, and headers.
Part 1-5: Transitions through various sections, displaying scooter model, specifications, and features.
Outro: Final animations for price and "Learn More" button.
Each timeline controls animations based on scroll position, creating an interactive experience as the user scrolls.

Installation and Usage
To view and interact with this project:

Download or clone the repository to your local machine.

Ensure all files are in the same directory.

Install Required Resources:

Fonts:

The project uses Bebas Neue and Oswald fonts from Google Fonts. To install these fonts:
Go to the Google Fonts website.
Search for "Bebas Neue" and "Oswald".
Download the fonts, extract the files, and place them in a fonts directory inside your project folder.
Update the style.css file if necessary to point to the downloaded fonts (e.g., @font-face with src: url('/fonts/FontName.woff2');).
Images: The project references specific images:

Piaggio logo (piaggio-logo.svg): This image is hosted externally, but you can download it from Piaggio’s official site or an authorized logo source.
Liberty 150 image (liberty-150.png): Also hosted externally. To use it locally:
Download the image.
Place it in a folder named images within your project directory.
Update the image paths in index.html to reflect the local directory.
Run: Open index.html in a modern web browser.

Prerequisites
Internet connection is required for GSAP and ScrollTrigger if using the CDN links. Alternatively, you can download these libraries and include them locally:
GSAP: Download from GreenSock’s official website.
ScrollTrigger: Available as a plugin on the same site.
Usage Guide
Simply scroll through the webpage to trigger animations for each section, showcasing various details about the Piaggio Liberty 150 scooter.

Troubleshooting
Animation not working: Verify that GSAP and ScrollTrigger libraries are loaded correctly. If using local copies, ensure the paths are correct.
Missing images or fonts: Check that paths are correct and that images or fonts are present in the specified directories.

License
This project is licensed under the MIT License.
