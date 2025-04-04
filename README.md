Tools for OpenStreetMap and geospatial tasks

- [osmx-rs]:
  a Rust port of [OSMExpress](https://github.com/protomaps/OSMExpress/), a fast database file format for OpenStreetMap 
- [osm-cli]:
  fetch data or subscribe to edits from OpenStreetMap
- [overpass-cli]:
  use the Overpass query language to fetch OpenStreetMap data
- [shapely-cli]:
  transform GeoJSON using Python one-liners with the help of the [shapely](https://shapely.readthedocs.io/en/stable/manual.html) library
- [usfs-to-osm] and [nps-to-osm]: scripts to convert official USFS and NPS datasets to an OSM-compatible schema

General-purpose CLI tools

- [xpath-cli]:
  evaluate [XPath](https://en.wikipedia.org/wiki/XPath) expressions on XML documents using [libxml2](https://gitlab.gnome.org/GNOME/libxml2/-/wikis/home)
- [ngrams]:
  computes the frequency of sequences of characters ([n-grams](https://en.wikipedia.org/wiki/N-gram)) in a text file
- [barchart]:
  prints barcharts in the terminal, helpful for commands that output lists of numbers
- [uu]:
  show the Unicode code points, names, categories, etc of each character in a given text
- [gh-log]:
  a `log` command for the [`gh`](https://cli.github.com/) CLI to remind you what you did last week

Web development things

- [postcss-minify]: a CSS minifier in 50 lines of code (it's [surprisingly effective](https://www.jakelow.com/blog/introducing-postcss-minify))
- [remark-sectionize]: wrap headings and the content that follows them in `<section>` elements

Miscellaneous stuff

- I made some explorables with [d3](https://d3js.org/) and [Observable](https://observablehq.com/@jake-low),
  like a [satellite ground track visualizer](https://observablehq.com/@jake-low/satellite-ground-track-visualizer)
  and a [Web Mercator tile visibility demo](https://observablehq.com/@jake-low/web-mercator-tile-visibility)
- I wrote about [how to use Hobby's algorithm](https://www.jakelow.com/blog/hobby-curves) to make nice looking Bézier splines
 
[barchart]: https://github.com/jake-low/barchart
[gh-log]: https://github.com/jake-low/gh-log
[ngrams]: https://github.com/jake-low/ngrams
[nps-to-osm]: https://github.com/jake-low/nps-to-osm
[osm-cli]: https://github.com/jake-low/osm-cli
[osmx-rs]: https://github.com/jake-low/osmx-rs
[overpass-cli]: https://github.com/jake-low/overpass-cli
[postcss-minify]: https://github.com/jake-low/postcss-minify
[remark-sectionize]: https://github.com/jake-low/remark-sectionize
[shapely-cli]: https://github.com/jake-low/shapely-cli
[usfs-to-osm]: https://github.com/jake-low/usfs-to-osm
[uu]: https://github.com/jake-low/uu
[xpath-cli]: https://github.com/jake-low/xpath-cli
