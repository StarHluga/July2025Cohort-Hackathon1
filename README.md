# July 2025 Cohort Hackathon 1: Portfolio Challenge 🚀  

## Portfolio Documentation

🗂 **Overview**
This project is a responsive, personal portfolio website built with HTML and CSS (no JavaScript), designed to showcase your skills, resume, projects, and contact information in a clean and structured format.

## Website link
- https://starhluga-portfolio.netlify.app/

🌐 **Page Breakdown**
1. index.html – Home
  - Purpose: Welcome page of the portfolio.

   **Contents:**
    - Brief introduction or tagline.
    - Navigation menu (global).
    - Visual emphasis on your name and role (e.g., “Software Developer”).
    - Call to Action (CTA) button to "Learn more about me" (linking to about.html).

2. about.html – About Me
    Purpose: Personal background and interests.
   **Contents:**
   - Profile picture with introductory text wrapped to the right and continued below.
   - Skills section in grid layout with:
   - Skill icon
   - Skill name
   - Proficiency bar
   - Interests section with list or paragraph format.
   - Shared global navigation and styling.

3. resume.html – Resume
    Purpose: Timeline of academic and professional experience.
   **Contents:**
   - Vertical timeline using a styled .timeline component.
   - Bullet points under each timeline item for responsibilities or achievements.
   - Dates, titles, and short descriptions
   - Styled to match overall design (green accents, dark background).

4. projects.html – Projects
    Purpose: Highlight personal or academic projects.
   **Contents:**
   - Project cards in a grid layout.
   - Each card contains:
   - Project image
   - Title & description
   - Optional: link to GitHub or live demo

5. contact.html – Contact Me
     Purpose: Allow users to reach out to you.
   **Contents:**
   - Contact form:
   - Name, Email, Subject, Message
   - Styled input and textarea fields
   - Submit button with hover effects
   - Optional social media links/icons section

🧭  **Navigation**
     All pages use a global sidebar menu controlled by a toggle input (#menu-toggle) and styled with position: fixed.
    **Menu items:**
   - About
   - Resume
   - Projects
   - Contact

🎨 **Design & Styling**
   - Fonts: Cascadia Code
   - Color Palette:
   - Background: #0b0f0e
   -  Primary Accent: #00cc66 (green)
   - Text: darkgreen, #ccc

   **Layout:**
    - Max width: 900px container centered
    - Sidebar with shadow and border
    - All content designed to be mobile-responsive

