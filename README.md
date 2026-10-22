# js_core_practice

Day-by-day JavaScript exercises and small apps: DOM basics and events, closures, prototypes, a to-do list, a drag-and-drop page, a Chrome extension and more.

**Live:** https://harshaannihal.github.io/js_core_practice/

## Layout

- `Day-N .../` holds one day's exercises. Most contain an `index.html` you can open directly in a browser.
- `practice/` holds extra practice projects such as a quiz game, a Trello clone and a movie database.
- `platformgame16/` and `checkbox prob/` are standalone experiments.

Plain HTML, CSS and JavaScript, with no build step, unless noted below.

## Projects that need a build

`Day-23 Geolocation/js-starter` is a [Parcel](https://parceljs.org/) app that imports Sass from its JavaScript and needs a Google Maps API key in `index.html`. Run it locally:

```sh
cd "Day-23 Geolocation/js-starter"
npm install
npm start
```

`node_modules/`, `.cache/` and `dist/` are not tracked. Run `npm install` in a project to restore its dependencies.

## The index page

`index.html` at the repo root lists every page and is generated. After adding or moving an exercise, regenerate it:

```sh
python3 tools/build_index.py --title "JavaScript Core Practice" --blurb "Day-by-day JavaScript exercises and small apps, grouped by folder." --repo https://github.com/harshaanNihal/js_core_practice --runnable practice/KlassyMovieDataBase/js-starter
```
