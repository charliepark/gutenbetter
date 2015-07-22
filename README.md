# gutenbetter
A bookmarklet for making Project Gutenberg pages more legible and appealing

1. Just drag this link — [Gutenbetter]() — to your bookmarks toolbar.
2. Right-click on the bookmarklet in your toolbar, hit “edit”, and insert this into the URL field:
```
javascript:(function(){
  var css = document.createElement("style");
  css.type = "text/css";
  css.innerHTML = '*{font-family: "Avenir Next", avenir, sans-serif;line-height:1.65}h1,h2,h3,h4,h5,h6{color: #444;margin: 1rem 0;}hr{border:0;background: none;border-bottom: 1px solid #eee;}h3 + hr{margin-bottom: 2rem}p + hr{margin-top: 4rem;}p{text-align: left}.stanza{background-color: #F6F6F6;border-radius: 10px;box-sizing: border-box;padding: 1rem 1.5rem;}p,pre,.poem .stanza{line-height:1.65;margin: 1em auto 1.65em;max-width:36em;}';
  document.body.appendChild(css);
})();
```

When you’re on a page on Project Gutenberg (like [Around the World in 80 Days](https://www.gutenberg.org/files/103/103-h/103-h.htm)), poke the bookmarklet and it’ll make the page far more attractive and legible.

#### Example:

**Before:**
<img width="1280" alt="before" src="https://cloud.githubusercontent.com/assets/22547/8819071/907a4758-2ffd-11e5-8f36-d8b319e7494c.png">

**After:**
<img width="1280" alt="after" src="https://cloud.githubusercontent.com/assets/22547/8819072/907d3aee-2ffd-11e5-87b5-6040c82c86b2.png">
