# games

Small daily games, served at [denizbuldum.org/games](https://denizbuldum.org/games/).

- [Plates](https://denizbuldum.org/games/plates/): make a word from the license plate. Use its three letters in order; rarer words drive farther.
- [Halfway](https://denizbuldum.org/games/halfway/): name the city halfway between two others along the shortest flight route.
- [Brim](https://denizbuldum.org/games/brim/): fill the glass with countries by land area without spilling.

Each game is a single self-contained `index.html` with its data inlined, so there is no build step to host it. Puzzles rotate daily at midnight US Eastern, and progress is kept in the browser's localStorage.

Data: word frequencies from [wordfreq](https://github.com/rspeer/wordfreq), word lists from [word-list](https://github.com/sindresorhus/word-list) and Webster's 2nd (via english-words), places from [GeoNames](https://www.geonames.org/) (CC BY 4.0) and [world-countries](https://github.com/mledoze/countries), map shapes from [world-atlas](https://github.com/topojson/world-atlas) / Natural Earth, map projection from [d3-geo](https://github.com/d3/d3-geo).
