# MindFlip

MindFlip is a memory card matching game that runs entirely in the browser. Flip two cards at a time, find every matching pair, and try to finish in as few moves and as little time as you can. It is a single HTML file with its own CSS and JavaScript, so there is nothing to install, build or download from elsewhere.

You can choose between three difficulty levels: Easy has six pairs, Medium has eight, and Hard has twelve. The game counts your moves, times each round, and remembers your best result for each level using the browser's local storage. The cards are drawn with inline SVG, the layout adapts to phones and desktops, and the colors follow your system's light or dark setting. Animations are turned off for people who have reduced motion enabled, and the cards can be played with a keyboard.

To play locally, open the HTML file in any modern browser. To host it on GitHub Pages, name the file index.html, commit it to your repository, and turn on Pages in the repository settings. If you want to change the card symbols, edit the list of SVG paths at the top of the script. Adding a path adds a new symbol, and the Hard level uses the first twelve.
