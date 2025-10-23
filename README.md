[README.md](https://github.com/user-attachments/files/23078708/README.md)
Juan Franco - Professional Profile Webpage
Overview
This is a modern, professional profile webpage for Juan Franco, an AI-Native Software Engineer and Pursuit Fellow. The design is inspired by contemporary portfolio templates with a clean, sleek aesthetic.
🎨 Design Features

Modern Hero Section: Gradient background with animated profile photo
Responsive Design: Looks great on desktop, tablet, and mobile
Smooth Animations: Subtle hover effects and transitions
Clean Typography: Easy to read with clear visual hierarchy
Professional Color Scheme: Purple gradient theme (easily customizable)

📁 Files Included

juan-franco-profile.html - Complete HTML with Juan's actual information
styles.css - Modern, responsive styling
README.md - This guide

✅ What's Already Done
The webpage is 95% complete with all of Juan Franco's information already integrated:
Completed Sections:

Navigation - Smooth scrolling menu
Hero/Home - Professional introduction with tagline
About Me - Comprehensive background covering:

Technical background (Aviation & Audio)
AI-Native Software Engineering at Pursuit
What connects his experience
What he brings to the table


Experience - Three detailed positions:

Owner & Lead Audio Engineer @ Primetime Recording Studio (2010-Present)
Driver @ Uber for Business (2014-Present)
Avionics Technician @ Panasonic Avionics (2006-2007)


Skills - Organized by category:

Web Development (JavaScript, React, Node.js, Express, HTML5, CSS3)
Databases (PostgreSQL, MongoDB)
AI Tools (GitHub Copilot, Cursor IDE, ChatGPT/Claude)
Tools & Platforms (Git, GitHub, VS Code, Python)
Audio Engineering (Pro Tools, Logic Pro, Ableton Live, etc.)
Aviation Systems
Professional Skills


Contact - Professional call-to-action with links
Footer - Clean with social links

🔧 What You Need to Do
Step 1: Add Profile Photo (Required)

Save Juan's photo as profile-photo.jpg
Place it in the same folder as the HTML file
Recommended size: At least 400x400 pixels
Format: JPG, PNG, or WebP

Step 2: Update Email Address (Optional)
Currently set to: juan.franco@example.com
Find and replace in the HTML file:
html<!-- Line 31 and 217 -->
<a href="mailto:juan.franco@example.com">
Replace with Juan's actual email address.
Step 3: Customize Colors (Optional)
To change the color scheme, edit the CSS file (lines 11-13):
css:root {
    --primary-color: #6366f1;  /* Main purple/blue */
    --primary-dark: #4f46e5;   /* Darker shade */
    --accent-color: #8b5cf6;   /* Purple accent */
}
Popular Color Schemes:

Professional Blue: #0077b5, #005885, #0088cc
Tech Green: #10b981, #059669, #34d399
Creative Orange: #f59e0b, #d97706, #fbbf24
Modern Teal: #06b6d4, #0891b2, #22d3ee

🚀 Deployment
Option 1: GitHub Pages (Recommended - Free)

Create a GitHub account at https://github.com
Create a new repository called juan-franco-portfolio
Upload these files:

juan-franco-profile.html (rename to index.html)
styles.css
profile-photo.jpg


Go to Settings > Pages
Select "Deploy from main branch"
Your site will be live at: username.github.io/juan-franco-portfolio

Option 2: Netlify (Free)

Sign up at https://www.netlify.com
Drag and drop your folder
Get instant hosting with custom URL
Automatic HTTPS

Option 3: Vercel (Free)

Sign up at https://vercel.com
Import from GitHub or drag/drop files
Lightning-fast hosting

📱 Testing Checklist

 View on desktop browser (Chrome, Firefox, Safari)
 Test on mobile device
 Check all navigation links work
 Verify smooth scrolling
 Test all external links (LinkedIn)
 Confirm email link works
 View at different screen sizes
 Check profile photo displays correctly

💡 Optional Enhancements
Add Projects Section
Between Skills and Contact, add:
html<section id="projects" class="section">
    <div class="container">
        <h2>Projects</h2>
        <!-- Add project cards here -->
    </div>
</section>
Add Testimonials
Include quotes from clients or colleagues from the recording studio.
Add Resume Download
html<a href="juan-franco-resume.pdf" download class="social-btn">
    Download Resume
</a>
Add Contact Form
Use a service like Formspree or Netlify Forms to add a working contact form.
Add Google Analytics
Track visitors by adding Google Analytics code before </head>.
🎯 SEO Optimization
Add these meta tags in the <head> section:
html<meta name="description" content="Juan Franco - AI-Native Software Engineer, Pursuit Fellow with 15+ years technical expertise in aviation and audio engineering">
<meta name="keywords" content="software engineer, AI developer, full-stack developer, React, Node.js, NYC">
<meta property="og:title" content="Juan Franco - AI-Native Software Engineer">
<meta property="og:description" content="Pursuit Fellow | 15+ Years Technical Expertise">
<meta property="og:image" content="profile-photo.jpg">
🐛 Troubleshooting
Profile photo not showing?

Ensure file is named exactly profile-photo.jpg
Check that it's in the same folder as the HTML file
Try using absolute path or different image format

Colors look different?

Some browsers may render colors slightly differently
Test in multiple browsers (Chrome, Firefox, Safari)

Layout broken on mobile?

Clear browser cache
Ensure you're using the latest CSS file

📞 Support Resources

HTML Tutorial: https://www.w3schools.com/html/
CSS Tutorial: https://www.w3schools.com/css/
Responsive Design: https://web.dev/responsive-web-design-basics/
GitHub Pages: https://pages.github.com/

📝 License
Free to use and modify for personal use.

Created: October 2025
Version: 2.0
Design Style: Modern Portfolio (Presume-inspired)
Status: Production-ready - just add profile photo!
