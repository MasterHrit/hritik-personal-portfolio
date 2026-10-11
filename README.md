# Hritik's Personal Portfolio

A responsive personal portfolio built with **HTML, Bootstrap 5, custom CSS, and Flask**.

## Features
- Responsive navigation
- About section
- Skills overview
- Professional experience
- Selected projects
- Education
- Contact links
- Bootstrap Icons and Bootstrap CDN

## Run locally

1. Install Python 3.10 or newer.
2. Open a terminal in this project folder.
3. (Recommended) Create and activate a virtual environment:

   **Windows PowerShell**
   ```powershell
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```

   **macOS/Linux**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Start Flask:
   ```bash
   python app.py
   ```
6. Open http://127.0.0.1:5000 in your browser.

## Personalize before publishing
- Replace the LinkedIn and GitHub placeholder URLs in `templates/index.html`.
- Your resume email is already included; optionally add a profile photo.
- Review the project descriptions and experience wording for accuracy.
- For deployment, turn off Flask debug mode and use a production WSGI server.
