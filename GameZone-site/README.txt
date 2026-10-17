GAMEZONE WEBSITE — SETUP GUIDE

Files:
- index.html: complete self-contained GameZone website.

TEST LOCALLY
1. Open index.html in a modern browser (Chrome, Edge, Firefox, or Safari).
2. Search, filter categories, favorite games, and try the built-in mini-games.
3. Use “Add game” to add a game URL and optional thumbnail. Custom games and favorites are saved in this browser's local storage.

FREE HOSTING WITH GITHUB PAGES
1. Sign in to https://github.com/ and create a new PUBLIC repository, for example: gamezone.
2. Upload index.html to the top/root of the repository (not inside another folder).
3. Open the repository's Settings tab, then Pages.
4. Under Build and deployment, choose “Deploy from a branch”.
5. Choose branch “main” and folder “/(root)”, then Save.
6. Wait for deployment, then use the URL shown on the Pages settings screen. Project URLs typically look like https://YOUR-USERNAME.github.io/gamezone/.

NOTES
- GitHub Pages is static hosting. This website needs no server or build step.
- Favorites, recent games, custom game entries, and play counts are stored in each visitor's browser, not shared between visitors.
- To add a game for everyone, edit the builtInGames array in index.html and add an object matching the existing entries. For custom images, set thumbnail to an HTTPS image URL you are allowed to use.
- The game player uses an iframe for external games. Some game sites intentionally block embedding; use game URLs that permit it.
- Only host or embed games and images you own or have permission to use, and follow each provider's terms.
