# wonders-of-the-world

This project is a website containing information about each of the modern wonders of the world.

## Use of HTML

### Header

On each page of the website, I included a header with the title of the website on the left, and a link back to the main home page on the right.
```
<div class="header">
    <h1>The Seven New Wonders of the World</h1>
    <a id="home-btn" href="index.html">Home</a>
</div>
```

### Link buttons

On the home page of the website, I added buttons that grow when they are hovered over, each one linking to a different page with information about one of the wonders.
```
<div class="link-btns">
    <button class="grow" id="giza-btn" onclick="window.location.href='giza.html'">Great Pyramid of Giza</button>
    <button class="grow" id="wallofchina-btn" onclick="window.location.href='wallofchina.html'">Great Wall of China</button>
    <button class="grow" id="petra-btn" onclick="window.location.href='petra.html'">Petra</button>
    <button class="grow" id="colosseum-btn" onclick="window.location.href='colosseum.html'">The colosseum</button>
    <button class="grow" id="chichenitza-btn" onclick="window.location.href='chichenitza.html'">Chich&eacuten Itz&aacute</button>
    <button class="grow" id="machupicchu-btn" onclick="window.location.href='machupicchu.html'">Machu Picchu</button>
    <button class="grow" id="tajmahal-btn" onclick="window.location.href='tajmahal.html'">Taj Mahal</button>
    <button class="grow" id="christtheredeemer-btn" onclick="window.location.href='christtheredeemer.html'">Christ the Redeemer</button>
</div>
```

### Footer

The home page of the website also contains a footer, which links to the source code on github.
```
<div class="footer">
    <div class="footer-content">
        View source code and read about how I made the website <a href="https://github.com/elidgdg/wonders-of-the-world" target="_blank">here</a>
    </div>
</div>
```

### Images

On each of the information pages, I included an image.
```
<img src="img/machupicchu-img.webp" alt="Machu Picchu"> 
```

## Use of CSS

I used CSS throughout my website to improve appearance and readability.

### Flexbox

To arrange the items on each of my pages, I used Flexbox.
This is the CSS for the main container div that all the HTML elements were children of. This allows me to arrange all the elements in my page vertically, one on top of the other.
```
.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    background-color: #e1be86;
}
```