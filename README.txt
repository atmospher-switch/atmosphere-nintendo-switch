╔══════════════════════════════════════════════════════════════════════════╗
║                    ATMOSPHERE SWITCH WEBSITE                             ║
║                   Professional Multi-Page Website                        ║
║                          Setup & Guide                                   ║
╚══════════════════════════════════════════════════════════════════════════╝

═══════════════════════════════════════════════════════════════════════════
TABLE OF CONTENTS
═══════════════════════════════════════════════════════════════════════════
1. Project Overview
2. File Structure
3. How to Run Locally
4. Customization Guide
   4.1 Changing Colors
   4.2 Updating Links
   4.3 Modifying Content
   4.4 Changing Keywords
5. Features
6. Responsive Design
7. Browser Compatibility
8. Credits & License
9. Support


═══════════════════════════════════════════════════════════════════════════
1. PROJECT OVERVIEW
═══════════════════════════════════════════════════════════════════════════
This is a professional, modern, responsive multi-page website built with 
HTML, CSS, and JavaScript. The website is designed for Atmosphere Switch, 
featuring a clean and elegant design with smooth animations and interactive 
elements.

Design Philosophy:
- Modern and professional appearance
- Clean, balanced layout
- Smooth transitions and animations
- Fully responsive for all devices
- SEO-friendly structure
- Easy to customize


═══════════════════════════════════════════════════════════════════════════
2. FILE STRUCTURE
═══════════════════════════════════════════════════════════════════════════
atmosphereswitch3/
│
├── index.html          (Home page with hero section and keyword links)
├── about.html          (About page with mission and vision)
├── contact.html        (Contact page with Google Form button)
├── download.html       (Download page with download button)
├── style.css           (All styling and responsive design)
├── script.js           (JavaScript for interactivity)
└── README.txt          (This file - setup instructions)


═══════════════════════════════════════════════════════════════════════════
3. HOW TO RUN LOCALLY
═══════════════════════════════════════════════════════════════════════════
METHOD 1: Direct Opening (Simple)
-----------------------------------
1. Navigate to the project folder
2. Double-click on "index.html"
3. The website will open in your default browser

METHOD 2: Using a Local Server (Recommended)
----------------------------------------------
Option A - Using Python (if installed):
   1. Open terminal/command prompt in project folder
   2. Run: python -m http.server 8000
   3. Open browser and go to: http://localhost:8000

Option B - Using VS Code Live Server:
   1. Install "Live Server" extension in VS Code
   2. Right-click on index.html
   3. Select "Open with Live Server"

Option C - Using Node.js http-server:
   1. Install: npm install -g http-server
   2. Run: http-server
   3. Open the URL shown in terminal


═══════════════════════════════════════════════════════════════════════════
4. CUSTOMIZATION GUIDE
═══════════════════════════════════════════════════════════════════════════

4.1 CHANGING COLORS
-------------------
Open "style.css" and find the :root section (around line 10):

:root {
    --primary-color: #5982D6;      /* Main blue color */
    --secondary-color: #FAFAFA;    /* Light background */
    --accent-color: #7534F7;       /* Purple accent */
    --text-color: #FFFFFF;         /* White text */
}

Simply change the hex values to your preferred colors.
Example: Change --primary-color: #5982D6; to --primary-color: #FF6B6B;


4.2 UPDATING LINKS
------------------

A. Google Form Link (Contact Page):
   File: contact.html (around line 53)
   Find: https://docs.google.com/forms/d/e/1FAIpQLScQfW5_cmuD6E85Dh0GEeyvJUUYjRMA-_inEbviXO1_xx_-BA/viewform?usp=header
   Replace with: Your new Google Form URL

B. GitHub Repository Link:
   Files: All HTML files (in navigation)
   Find: https://github.com/atmospher-switch/AtmoSphere-Switch
   Replace with: Your GitHub repository URL

C. Download Page Link:
   File: download.html (around line 64)
   Find: https://atmosphereswitch.com/download/
   Replace with: Your download page URL

D. Official Website Link:
   Files: Multiple locations (hero button, footer, etc.)
   Find: https://atmosphereswitch.com/
   Replace with: Your official website URL


4.3 MODIFYING CONTENT
----------------------

A. Hero Section (Home Page):
   File: index.html (around line 45)
   Edit:
   - <h1 class="hero-title"> - Main headline
   - <p class="hero-subtitle"> - Subtitle text
   - Button text and links

B. Page Titles and Meta Descriptions:
   In each HTML file's <head> section:
   - <title> - Browser tab title
   - <meta name="description"> - SEO description

C. Footer Information:
   All HTML files (bottom section)
   - Company name
   - Copyright year
   - "Designed & Developed by" text

D. About Page Content:
   File: about.html
   - Mission cards (around line 67)
   - Vision section (around line 99)
   - Values section (around line 112)


4.4 CHANGING KEYWORDS & LINKS
------------------------------
The home page (index.html) contains three focus keywords with links:

1. "atmosphere nintendo switch" → https://atmosphereswitch.com/
   Location: Line 92 (What is Atmosphere Nintendo Switch section)

2. "how to hack nintendo switch" → https://atmosphereswitch.com/hack-your-nintendo-switch-oled/
   Location: Line 109 (Getting Started section)

3. "how to check atmosphere version" → https://atmosphereswitch.com/how-to-update-switch-atmosphere-firmware/
   Location: Line 125 (Stay Updated section)

To change keywords:
- Find the <a> tag with class="inline-link"
- Update the text between <a> and </a>
- Update the href="" attribute with new URL


═══════════════════════════════════════════════════════════════════════════
5. FEATURES
═══════════════════════════════════════════════════════════════════════════
✓ Fully Responsive Design (Mobile, Tablet, Desktop)
✓ Smooth Scroll Animations
✓ Interactive Hover Effects
✓ Mobile-Friendly Navigation with Hamburger Menu
✓ Scroll-to-Top Button
✓ Animated Card Elements
✓ Gradient Backgrounds
✓ Modern Typography (Inter Font)
✓ SEO-Friendly HTML Structure
✓ Cross-Browser Compatible
✓ Fast Loading Speed
✓ Accessible Design (ARIA labels)


═══════════════════════════════════════════════════════════════════════════
6. RESPONSIVE DESIGN
═══════════════════════════════════════════════════════════════════════════
The website is fully responsive and tested on:

Desktop:  1920px and above
Laptop:   1366px - 1919px
Tablet:   768px - 1365px
Mobile:   320px - 767px

Breakpoints are defined in style.css:
- @media (max-width: 768px)  - Tablets and smaller
- @media (max-width: 480px)  - Mobile phones


═══════════════════════════════════════════════════════════════════════════
7. BROWSER COMPATIBILITY
═══════════════════════════════════════════════════════════════════════════
✓ Google Chrome (Latest)
✓ Mozilla Firefox (Latest)
✓ Safari (Latest)
✓ Microsoft Edge (Latest)
✓ Opera (Latest)
✓ Mobile Browsers (iOS Safari, Chrome Mobile)


═══════════════════════════════════════════════════════════════════════════
8. ADDING YOUR OWN IMAGES
═══════════════════════════════════════════════════════════════════════════
Currently, the website uses icon placeholders. To add images:

1. Create an "images" folder in the project directory
2. Add your images to this folder
3. Replace the placeholder divs with <img> tags

Example:
Replace:
    <div class="image-placeholder">
        <div class="placeholder-icon">🎮</div>
    </div>

With:
    <img src="images/your-image.jpg" alt="Description">


═══════════════════════════════════════════════════════════════════════════
9. DEPLOYMENT OPTIONS
═══════════════════════════════════════════════════════════════════════════

A. GitHub Pages (Free):
   1. Create a GitHub repository
   2. Upload all files
   3. Go to Settings > Pages
   4. Select main branch
   5. Your site will be live at: username.github.io/repo-name

B. Netlify (Free):
   1. Sign up at netlify.com
   2. Drag and drop your project folder
   3. Your site goes live instantly
   4. Get a custom domain

C. Vercel (Free):
   1. Sign up at vercel.com
   2. Import from GitHub or upload files
   3. Automatic deployment on push

D. Traditional Web Hosting:
   1. Purchase hosting (e.g., Bluehost, HostGator)
   2. Upload files via FTP
   3. Point your domain to hosting


═══════════════════════════════════════════════════════════════════════════
10. CUSTOMIZATION TIPS
═══════════════════════════════════════════════════════════════════════════
✓ Keep the color scheme consistent across all pages
✓ Use high-quality images (optimized for web)
✓ Update meta descriptions for better SEO
✓ Test on multiple devices before deploying
✓ Compress images to improve loading speed
✓ Keep content concise and scannable
✓ Use meaningful alt text for images
✓ Update copyright year annually


═══════════════════════════════════════════════════════════════════════════
11. TROUBLESHOOTING
═══════════════════════════════════════════════════════════════════════════

Q: Mobile menu doesn't work
A: Make sure script.js is properly linked in all HTML files

Q: Colors not showing correctly
A: Clear browser cache and refresh (Ctrl+F5)

Q: Layout looks broken
A: Ensure style.css is in the same folder as HTML files

Q: Smooth scrolling not working
A: Check that script.js is loaded after the HTML content

Q: Links not working
A: Verify all href attributes have correct URLs


═══════════════════════════════════════════════════════════════════════════
12. PERFORMANCE OPTIMIZATION
═══════════════════════════════════════════════════════════════════════════
✓ Minify CSS and JavaScript for production
✓ Optimize and compress images
✓ Use WebP format for images
✓ Enable browser caching
✓ Use a CDN for faster delivery
✓ Defer non-critical JavaScript
✓ Reduce HTTP requests


═══════════════════════════════════════════════════════════════════════════
13. SEO TIPS
═══════════════════════════════════════════════════════════════════════════
✓ Each page has unique title and meta description
✓ Use semantic HTML (header, nav, section, footer)
✓ Add alt attributes to all images
✓ Create a sitemap.xml file
✓ Submit to Google Search Console
✓ Use descriptive URLs
✓ Add Open Graph tags for social sharing
✓ Include schema markup


═══════════════════════════════════════════════════════════════════════════
14. MAINTENANCE CHECKLIST
═══════════════════════════════════════════════════════════════════════════
□ Update copyright year annually
□ Check all external links monthly
□ Update content regularly
□ Monitor website performance
□ Back up files regularly
□ Test on new browser versions
□ Update meta descriptions
□ Refresh images periodically
□ Review and update keywords


═══════════════════════════════════════════════════════════════════════════
15. CREDITS & LICENSE
═══════════════════════════════════════════════════════════════════════════
Design: Professional Web Studio
Font: Inter (Google Fonts)
Icons: SVG inline icons
Framework: Vanilla HTML/CSS/JavaScript

License: Free to use and modify for personal and commercial projects.


═══════════════════════════════════════════════════════════════════════════
16. SUPPORT & CONTACT
═══════════════════════════════════════════════════════════════════════════
For questions or support:
- Visit: https://atmosphereswitch.com/
- GitHub: https://github.com/atmospher-switch/AtmoSphere-Switch
- Contact Form: Use the contact page on the website


═══════════════════════════════════════════════════════════════════════════
QUICK REFERENCE GUIDE
═══════════════════════════════════════════════════════════════════════════

Change Colors:       style.css (lines 10-15)
Update Links:        Search for URLs in all HTML files
Modify Content:      Edit text in HTML files
Add Images:          Replace placeholder divs with <img> tags
Change Font:         Update Google Fonts link in HTML <head>
Customize Animation: Modify script.js
Edit Footer:         Update footer section in all HTML files
Change Layout:       Modify grid and flexbox in style.css

═══════════════════════════════════════════════════════════════════════════

Thank you for using Atmosphere Switch Website Template!
Built with ❤️ for the Nintendo Switch community.

═══════════════════════════════════════════════════════════════════════════
