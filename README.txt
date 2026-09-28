SAQHIB PORTFOLIO — QUICK START

1. Open this folder in VS Code.
2. Install the “Live Server” extension if you do not already have it.
3. Right-click index.html → “Open with Live Server”.
4. Scroll from the top to scrub the 134-frame intro animation.

FILES
- index.html: all page content and sections
- styles.css: violet theme, layout, responsive styling and hover effects
- script.js: image-sequence preload/scrub logic, work carousel, progress bar and 3D tilt
- frames/: 134 renamed sequence frames (frame_0001.jpg onward)
- assets/saqhib.png: portrait used in About section

ADD / CHANGE PORTFOLIO LINKS
Open script.js and edit the “projects” array. Duplicate any project object to add more 9:16 cards.

BACKGROUND MATCHING
The sequence canvas uses #f9f9fb to match the light frame edges. The first view is intentionally covered by a dark violet intro overlay so the website never looks like a blank white page when it opens.

VIDEO EMBEDS
The Work section now uses real embedded players:
- Instagram Reels: official instagram.com/reel/SHORTCODE/embed/ iframe
- YouTube Shorts: youtube-nocookie.com/embed/ iframe

Because Instagram is a third-party service, the browser needs internet access when previewing the site. If Instagram asks for login or blocks a reel due to the reel/account privacy settings, the “View original” link under each card still opens the reel directly.
