WeatherWise AI Website
What is this?
WeatherWise AI is a website showcasing Immaculate Kamusiime's research on improving weather forecasts in Uganda using AI and physics. The site is professional, easy to navigate, and works on all devices (phones, tablets, desktops). It includes a sliding mobile menu, a dynamic hero slider, and pages about the research, journey, and supervisors.

Website: weatherwiseai.com (set up with your domain provider)

Features
Responsive: Looks great on any screen size.
Mobile Menu: Slides in from the left on phones for easy navigation.
Hero Slider: Shows weather images with text using Owl Carousel.
Pages:
Home: Introduces WeatherWise AI and Immaculate’s work.
Research: Explains the weather prediction model with a PDF download.
The Journey: Shares Immaculate’s education, skills, and experience.
My Supervisors: Highlights the research mentors.
Design: Blue weather theme with clear text and social media icons.
Technologies
HTML: Builds the site’s structure.
CSS:
Bootstrap: For layout and responsiveness.
Tailwind CSS: For custom styles.
FontAwesome: For icons (e.g., LinkedIn, email).
JavaScript:
jQuery: Needed for the slider.
Owl Carousel: Powers the hero slider.
Bootstrap JS: Handles menu and other features.
Folder Structure
text

Copy
weatherwiseai/
├── index.html          # Home page
├── research.html       # Research page
├── journey.html        # The Journey page
├── supervisors.html    # Supervisors page
├── css/
│   └── styles.css      # Custom styles
├── js/
│   └── scripts.js      # Custom JavaScript
├── assets/
│   ├── images/         # Place images here
│   └── pdfs/           # Place PDFs here
├── README.md           # This file
How to Set Up
Get the Code:
Download or clone the project:
bash

Copy
git clone https://github.com/your-repo/weatherwiseai.git
cd weatherwiseai
Add Images and PDFs:
Put weather images and profile photos in assets/images/.
Add the research PDF to assets/pdfs/.
Update placeholders in HTML files (e.g., YOUR_IMAGE_LINK_1, YOUR_PDF_LINK) with real links.
Run the Site:
Open index.html in a browser, or use a local server:
bash

Copy
python -m http.server 8000
Visit http://localhost:8000.
Dependencies:
The site uses online libraries (Bootstrap, Tailwind, etc.), so you need an internet connection.
Check HTML files for CDN links (e.g., Bootstrap, Owl Carousel).
Customization
Images: Replace placeholders with your images (use WebP, <500KB).
Links: Update social media links (e.g., YOUR_LINKEDIN_LINK).
Colors: Change the blue theme in css/styles.css (e.g., #1e40af).
Width: Containers are set to 1200px max; adjust in css/styles.css if needed.
Deployment
Host: Use Netlify, Vercel, or GitHub Pages.
Netlify: Drag and drop the folder.
GitHub Pages: Push to a gh-pages branch.
Domain: Link weatherwiseai.com to your host via your domain provider.
Assets: Host images/PDFs on Google Drive or a similar service and update links.
Testing
Check the site on phone, tablet, and desktop.
Test the mobile menu (slides from left, closes on click).
Ensure the hero slider works (autoplay, arrows, dots).
Verify all links (social media, PDF, navigation) work.
Questions?
Contact: Immaculate Kamusiime
Email: 
LinkedIn:
Open an issue on GitHub or email for help.

License
MIT License (see ).
