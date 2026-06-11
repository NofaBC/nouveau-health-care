Nouveau Health Care Landing Page
A modern, responsive, and conversion-optimized landing page for Nouveau Health Care (NHC) — a state-licensed home health care provider serving all of Maryland.
🚀 Live Demo
Deployed on Vercel: [Coming Soon — Deploy after setup]
📋 About the Project
This landing page was built to showcase Nouveau Health Care's mission, services, and values while driving consultation requests from families seeking compassionate home health care for their loved ones.
Key Features
Fully Responsive — Optimized for desktop, tablet, and mobile devices
Smooth Scroll Navigation — Seamless section transitions
Scroll Reveal Animations — Elements animate in as you scroll
Working Contact Form — Consultation request form with success feedback
Realistic Stock Imagery — Professional caregiver and senior care photos
Brand-Aligned Design — Warm teal and gold palette reflecting trust and compassion
SEO-Ready — Meta tags, semantic HTML, and accessibility best practices
Fast Performance — Single-file HTML with inline CSS and minimal JS
🛠️ Tech Stack
Table
Technology	Purpose
HTML5	Semantic markup structure
CSS3	Custom styling with CSS variables, flexbox, grid, and animations
Vanilla JavaScript	Navbar scroll effect, scroll reveal, form handling, mobile menu
Google Fonts	Playfair Display + Inter typography
Font Awesome	Icons throughout the page
📁 Project Structure
plain
nouveau-health-care/
├── index.html          # Main landing page (single-file, self-contained)
├── README.md           # This file
└── .gitignore          # Git ignore rules
Note: This is a single-file landing page. All styles and scripts are embedded in index.html for easy deployment without build tools.
🚀 Deployment Guide
Option 1: Deploy to Vercel (Recommended)
Push to GitHub
bash
git init
git add .
git commit -m "Initial commit: Nouveau Health Care landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nouveau-health-care.git
git push -u origin main
Deploy on Vercel
Go to vercel.com and sign in
Click "Add New Project"
Import your GitHub repository
Vercel will auto-detect it as a static site
Click "Deploy"
Your site will be live at https://nouveau-health-care.vercel.app
Connect Custom Domain (Optional)
In Vercel dashboard → Project Settings → Domains
Add your custom domain (e.g., nouveauhc.com)
Follow DNS instructions to point your domain to Vercel
Option 2: Deploy to Netlify
Drag and drop the index.html file into Netlify Drop
Or connect your GitHub repo via Netlify's Git integration
Option 3: Local Preview
Simply open index.html in any modern web browser:
bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
🎨 Customization Guide
Colors
Edit CSS variables in the <style> section:
css
:root {
  --primary: #1a6b5e;        /* Main brand color */
  --primary-dark: #145548;     /* Darker shade */
  --primary-light: #e8f5f2;    /* Light background */
  --secondary: #c9a84c;        /* Accent gold */
  --secondary-light: #f5efe0;  /* Light gold bg */
}
Contact Information
Update the phone, email, and address in the Contact Section and Footer:
HTML
<!-- Phone -->
<a href="tel:+12405551234">(240) 555-1234</a>

<!-- Email -->
<a href="mailto:info@nouveauhc.com">info@nouveauhc.com</a>

<!-- Address -->
123 Health Care Way<br>Rockville, MD 20850
Images
Replace image URLs in the HTML with your own. All current images use publicly available stock photos.
Services
Add or modify service cards in the Services Section:
HTML
<div class="service-card">
  <div class="service-icon"><i class="fas fa-icon-name"></i></div>
  <h3>Service Name</h3>
  <p>Service description...</p>
</div>
Testimonials
Update testimonials with real client feedback:
HTML
<div class="testimonial-card">
  <p>"Client quote here..."</p>
  <div class="testimonial-author">
    <img src="avatar-url" alt="Name">
    <div>
      <h4>Client Name</h4>
      <span>Relationship, Location</span>
    </div>
  </div>
</div>
📱 Responsive Breakpoints
Table
Breakpoint	Layout Changes
> 1024px	Full desktop layout (2-column grids)
768px – 1024px	Tablet layout (2-column services, stacked hero)
< 768px	Mobile layout (single column, hamburger menu, compact cards)
🔗 External Resources Used
Logo: Nouveau Health Care Logo
Hero Image: NurseRegistry – In-Home Nursing Care
Caregiver Images: iStock – Home Health Aide
Team Image: ElderLife Financial – Help at Home
Fonts: Google Fonts – Playfair Display + Inter
Icons: Font Awesome 6.5.1
📝 Future Enhancements
[ ] Add Calendly or booking integration button
[ ] Connect contact form to backend (Firebase, Formspree, or email API)
[ ] Add Google Analytics for tracking
[ ] Implement cookie consent banner
[ ] Add FAQ accordion section
[ ] Create blog/news section for SEO
[ ] Add multi-language support (Spanish, etc.)
[ ] Implement dark mode toggle
[ ] Add video testimonials section
[ ] Integrate with CRM for lead management
📄 License
This landing page was created for Nouveau Health Care. All rights reserved.
🤝 Credits
Design & Development: Built for Nouveau Health Care
Brand: Nouveau Health Care
Stock Photography: Various royalty-free sources
📞 Support
For questions or updates to this landing page, contact the development team or open an issue in this repository.
