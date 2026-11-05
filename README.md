# Hausa Radio

- `index.html`: the app (design and player).
- `stations.json`: all stations. Edit this file to add, remove or fix a station.
- `logos/`: one image per station. Replace an image by uploading a new one with the same file name.

Host the folder on GitHub Pages (Settings > Pages > Deploy from branch > main > / (root)).
Opening index.html directly from a phone or computer file will not load the stations, because browsers block reading stations.json from a file.

## stations.json fields
n = name, s = text under the name, c = tab (labarai, addini, waka, wasanni), loc = 1 shows it in Nearby,
img = logo path, url = https stream link, progs = optional list of programs: ["name", "text", "https link"].
