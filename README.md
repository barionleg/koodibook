

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/barionleg/koodibook/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/barionleg/koodibook/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<script src="https://polyfill.io/v3/polyfill.min.js?features=default"></script>
<style type="text/css">
  /* Always set the map height explicitly to define the size of the div
       * element that contains the map. */
  #map {
    height: 100%;
  }

  /* Optional: Makes the sample page fill the window. */
  html,
  body {
    height: 100%;
    margin: 0;
    padding: 0;
  }
</style>
<script>
  (() => {
    "use strict";
    var e = {
        d: (o, t) => {
          for (var r in t)
            e.o(t, r) &&
              !e.o(o, r) &&
              Object.defineProperty(o, r, { enumerable: !0, get: t[r] });
        },
        o: (e, o) => Object.prototype.hasOwnProperty.call(e, o),
        r: (e) => {
          "undefined" != typeof Symbol &&
            Symbol.toStringTag &&
            Object.defineProperty(e, Symbol.toStringTag, { value: "Module" }),
            Object.defineProperty(e, "__esModule", { value: !0 });
        },
      },
      o = {};
    let t;
    function r() {
      t = new google.maps.Map(document.getElementById("map"), {
        center: { lat: -34.397, lng: 150.644 },
        zoom: 8,
      });
    }
    e.r(o), e.d(o, { initMap: () => r });
    var n = window;
    for (var l in o) n[l] = o[l];
    o.__esModule && Object.defineProperty(n, "__esModule", { value: !0 });
  })();
</script>

<div id="iframe-contents">
  <div id="map"></div>

  <!-- Async script executes immediately and must be after any DOM elements used in callback. -->
  <script
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyB41DRUbKWJHPxaFjMAwdrzWzbVKartNGg&callback=initMap&v=weekly&channel=1"
    async
  ></script>
</div>
