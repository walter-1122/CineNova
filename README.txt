CINENOVA MULTI-PAGE STARTER

Files:
- login.html: login/create-account demo screen
- index.html: home page
- movies.html: movie catalogue layout and search/filter UI
- genres.html: genre page
- watchlist.html: saved titles
- about.html: about page
- contact.html: contact form UI
- assets/style.css: shared theme and responsive layout
- assets/app.js: navigation, demo gate, watchlist and search behaviour

IMPORTANT LOGIN LIMITATION
The current login is only a front-end demonstration. It stores the signed-in email in localStorage and is not secure authentication. GitHub Pages is static hosting; for real protected accounts, configure Supabase Auth or another backend. Do not use this demo gate for private data.

MOVIE CATALOGUE LIMITATION
Movie cards are placeholders. No live movie API is connected yet. Connect a permitted movie metadata API and authorized streaming links in a later step. CineNova does not host full-length films. Verify rights and regional availability for each external title.

INSTALL
Upload the contents of this folder to the root of your GitHub Pages repository, keeping the assets folder and its files. Ensure index.html is at the repository root. Commit changes and allow GitHub Pages to redeploy.
