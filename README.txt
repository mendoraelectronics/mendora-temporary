MENDORA WEBSITE — HOSTING GUIDE

This is a standalone static website. No build tools, Node.js, database or ChatGPT login are required on your own hosting.

Files:
- index.html: complete page, styling and menu JavaScript
- assets/: logo, tablet image and team photographs

HOSTINGER / CPANEL
1. Open the file manager for mendoraelectronics.com.
2. Back up any existing website files before replacing them.
3. Upload this ZIP into the domain's public_html folder (or its configured document root).
4. Extract the ZIP so index.html and assets sit directly inside that folder.
5. If your host already has another index file, make sure it serves this index.html.
6. Open your domain and refresh the browser cache.

Keep the assets folder next to index.html. HTTPS can be enabled through your hosting panel.

EDITING
Open index.html in any text editor. CSS is in the style tag and menu JavaScript is at the end. Replace images in assets while retaining the filenames, or update their paths in index.html.

The email contact opens the visitor's email application. No contact form backend is needed.
