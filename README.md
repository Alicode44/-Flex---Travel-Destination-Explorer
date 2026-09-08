# -Flex---Travel-Destination-Explorer
A fully responsive travel website built with pure HTML &amp; CSS. Features a clean design, popular destinations showcase, and a pure CSS hamburger menu — no JavaScript required.
Features
 Fully Responsive — Seamlessly adapts to desktop, tablet, and mobile screens

 Pure CSS Hamburger Menu — No JavaScript, just clean HTML & CSS checkbox hack

 Modern UI Design — Eye-catching hero slider, destination cards, and newsletter section

 Interactive Search Bar — Styled search form with dark theme

 Destination Gallery — Grid layout with overlay cards for popular places

 Newsletter Subscription — Call-to-action section with email input

 Video Section — Play button overlay with hover effects

 Organized Footer — Quick links and contact information
 
Technologies Used

HTML5 — Semantic markup

CSS3 — Flexbox, media queries, transitions, pseudo-classes

Font Awesome — Icons (play button)

No JavaScript — 100% pure CSS interactivity

Responsive Breakpoints
Device	Screen Width	Features
Desktop	> 992px	Full navigation, multi-column layout
Tablet	768px - 992px	Adjusted spacing, flexible forms
Mobile	< 768px	Hamburger menu, stacked layout, full-width cards

Getting Started

Prerequisites

Any modern web browser

Text editor (VS Code recommended)

Installation
Clone the repository

bash
git clone https://github.com/Alicode44/-Flex---Travel-Destination-Explorer.git
Navigate to project folder

bash
cd -Flex---Travel-Destination-Explorer
Open in browser

bash
# Simply open index.html in your browser
Folder Structure
text
flex-travel/
├── index.html
├── style.css (inline in this version)
└── image/
    ├── logo.png
    ├── SEARCH.png
    ├── banner2.png
    ├── newsletter.png
    ├── video.png
    ├── 1.png - 6.png (destination images)
    └── footer_logo.png

    Key Design Decisions
Flexbox Layout — Used throughout for clean, predictable alignment

CSS Checkbox Hack — Hamburger toggle without JavaScript

Mobile-First Approach — Media queries build up from smaller screens

Consistent Color Palette — #1EC6B6 (teal), #ff4A52 (coral), #040E27 (dark)

Accessible Overlays — Semi-transparent overlays on newsletter and video sections

📸 Screenshots
<img width="1400" height="543" alt="picture" src="https://github.com/user-attachments/assets/53ea5676-f0c7-405b-89df-2e75feec3e14" />
🔧 Customization
Colors
Modify these variables in the CSS:

css
:root {
  --primary: #1EC6B6;
  --secondary: #ff4A52;
  --dark: #040E27;
  --light: #f5f5f5;
}
Add New Destination Cards
html
<article class="card">
  <img src="image/your-image.png" alt="Destination">
  <div class="card-overlay">
    <span class="card-title">Place Name</span>
    <a href="#">X Places</a>
  </div>
</article>
🌐 Browsers Support
Chrome	Firefox	Safari	Edge	iOS Safari	Android  ✅
🤝 Contributing
Fork the repository

Create your feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

📝 License
This project is open source and available under the MIT License.

📬 Contact
Project Link:https://github.com/Alicode44/-Flex---Travel-Destination-Explorer.git



Live Demo Link: https://alicode44.github.io/-Flex---Travel-Destination-Explorer/
🙏 Acknowledgments
Design inspiration from modern travel agency layouts

Icons by Font Awesome
Author: Alicode44
	
