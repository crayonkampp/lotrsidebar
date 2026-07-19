The Shire — LOTR-style Chess Sidebar

Files added:
- examples/The Shire.html  (single-file interactive sidebar)
- docs/The Shire.html      (demo wrapper for GitHub Pages)

Usage
- Host the contents of `examples/The Shire.html` (or use GitHub Pages via the `docs/` folder) and embed or link it from your chess.com club sidebar. Embedding via an iframe from GitHub Pages is the most reliable way to allow the widget to fetch live member data from chess.com.

Customization
- To change the MP3, edit the <audio> source in the HTML file.
- To change the club slug (if your club URL differs), update the `clubSlug` constant in the script.

Notes
- Chess.com may strip scripts/styles when pasting raw HTML into club notes. For live member avatars to work, host the file and embed as an iframe from the hosted origin (GitHub Pages works well).
