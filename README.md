# gutenbetter
A bookmarklet for making Project Gutenberg pages more legible and appealing

1. Just drag this link — [Gutenbetter]() — to your bookmarks toolbar.
2. Right-click on the bookmarklet and hit "edit", and insert this into the URL field:
```
javascript:(function(){var css = document.createElement("style");css.type = "text/css";css.innerHTML = '*{font-family: "Avenir Next", "avenir next", avenir next, avenir !important;line-height:1.65}h3{color: #444;margin: 1rem 0;}hr{border:0;background: none;border-bottom: 1px solid #eee;}h3 + hr{margin-bottom: 2rem}p + hr{margin-top: 4rem;}p{margin: 0 auto 1.65em;max-width: 36em;text-align: left}.poem .stanza{background-color: #F6F6F6;border-radius: 10px;box-sizing: border-box;margin: 1em auto;max-width: 36rem;padding: 1rem 1.5rem;}';document.body.appendChild(css);})();
```

When you're on a page on Project Gutenberg (like [Around the World in 80 Days](https://www.gutenberg.org/files/103/103-h/103-h.htm)), poke the bookmarklet and it'll make the page far more attractive and legible.
