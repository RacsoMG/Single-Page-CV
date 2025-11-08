https://roadmap.sh/projects/single-page-cv
# Single-Page CV

This is a simple single-page CV (curriculum vitae) built with plain HTML/CSS/JS. The project lives in this folder and can be served statically.

Project page URL (GitHub Pages template)
------------------------------------------------
If you publish this repository to GitHub Pages the URL will generally be:

		https://<github-username>.github.io/<repo-name>/

Replace `<github-username>` and `<repo-name>` with your GitHub username and repository name. Example (replace with your actual username):

		https://your-username.github.io/Single-Page-CV/

How to run locally
-------------------
There are several easy ways to run or preview the site locally:

- Open directly in a browser
	- Double-click `index.html` in the `Single-Page CV` folder or open it from your browser (File → Open). This works for basic static pages.

- Use VS Code Live Server (recommended for development)
	- Install the Live Server extension in VS Code.
	- Open the folder `Single-Page CV` in VS Code, open `index.html`, then click "Go Live" (bottom-right) or right-click → "Open with Live Server".

- Use Python's simple HTTP server (if you have Python 3 installed)
	- Open PowerShell in the project folder and run:

		python -m http.server 8000

	- Then open http://localhost:8000 in your browser.

- Use a lightweight Node server
	- Install http-server (if you have Node.js):

		npm install -g http-server

	- Run it from the project folder:

		http-server -p 8080

	- Then open http://localhost:8080.

Publishing to GitHub Pages
-------------------------
1. Create a new repository on GitHub and push this project (or push this folder to a branch in an existing repo).
2. In your repository on GitHub, go to Settings → Pages (or the Pages section in the sidebar).
3. Select the branch (for example `main`) and the folder (`/ (root)`), then Save.
4. GitHub Pages will show the published site URL. It may take a few minutes to become active.

Troubleshooting
---------------
- If assets (images, fonts) don't load when opening `index.html` directly, use a local HTTP server (Python/Live Server) as some browsers block local file requests.
- Make sure relative paths in your HTML/CSS match the file layout (this project's `index.html` expects assets to be in the same folder or subfolders listed in the project).

Notes
-----
URL https://github.com/RacsoMG/Single-Page-CV
- This repository contains only static files; no build step is required.
- If you want, I can add a simple `package.json` and a start script (e.g., `serve` or `http-server`) to make running a local server one command.

Credits
-------
Generated/edited README on request.
