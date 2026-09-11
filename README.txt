MILTON NYBERG PORTFOLIO

HOW TO TEST IT LOCALLY
======================

EASIEST:
1. Unzip the folder.
2. Double-click index.html.
3. It should open in your browser.
4. Click PROJECTS to test the second page.
5. Click the section buttons to test smooth scrolling.

BETTER TEST (OPTIONAL):
If you have Python installed:
1. Open PowerShell in this folder.
2. Run:
   python -m http.server 8000
3. Open:
   http://localhost:8000

WHAT TO REPLACE
===============
Search for:
- PROJECT TITLE
- YOUR_EMAIL@example.com
- YOUR_USERNAME
- href="#"

Replace those placeholders with your real information.

PROJECT IMAGES
==============
Replace the placeholder divs with your own screenshots later.
For example:

<img class="project-image" src="images/project1.png" alt="Screenshot of Project 1">

Create an images folder next to index.html and put your screenshots there.

HOSTING
=======
This is a static website. It can be hosted free on GitHub Pages,
Cloudflare Pages, Netlify, Vercel, or another static host.
