# World Philosophy Timeline

An interactive timeline of key philosophers from the Greek & Western, Indian, and Chinese & East Asian traditions, from c. 1500 BCE to the present.

**Live site:** https://mobiledge.github.io/philosophy-timeline/

- People, texts and ideas are colour-coded (blue, amber, teal).
- Every chip links to its Wikipedia article.
- Search across names, texts and ideas; toggle traditions and hide texts or ideas.
- Jump between eras; responsive down to phone width, with light and dark themes.

## Run it

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Editing the data

All entries live in the `D` array inside `index.html`:

```js
[era, tradition, person, dates, [texts], [ideas]]
```

`KEY` controls which entries are shown, and `W` maps chip labels to Wikipedia article titles where they differ.
