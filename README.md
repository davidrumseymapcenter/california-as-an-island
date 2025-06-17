# Thinking Spatially Toolkit

This repo is meant be a landing page for learning about starting your work using spatial information at Stanford Libraries.

Inspired by: https://dh.sites.gettysburg.edu/toolkit/

Uses the [Chulapa Jekyll theme](https://github.com/dieghernan/chulapa).

## Prerequisites
- Ruby
- Git
- Git Bash (if on Windows)
- Code editor such as VScode 

## Initial Setup for a new user
```
cd /path/to/desired/folder
git clone https://github.com/J-ok-git/thinking-spatially-toolkit.git
cd thinking-spatially-toolkit

# Install gems from Gemfile including Jekyll
bundle install
```

## How to serve the website locally?
1. Run `bundle exec jekyll serve --watch --incremental` in Git bash in the repository root
2. Open http://127.0.0.1:4000 in your browser

Since we are running this with the `--watch` flag, it will automatically update the ;local website in your browser when you make a change.

The `--incremental` flag enables incremental compilation which makes it faster to update the website when you make a change as it only recompiles the files that changed.


What I wrote for the table with thumbnails and not with links:

<table style="border: none">
  <tr>
    <th style="border: none"><img src="/esplandian.png" alt="Las Sergas de Esplandián by Garci Rodriguez de Montalvo - Wikipedia Commons" style="width:200px;"></th>
    <th style="border: none"><img src="/1597 Granata Nova.png" alt="1597 Cornelis Wytfliet, Granata Nova et California" style="width:900px;"></th>
    <th style="border: none"><img src="/1622 Antonio de Herrera y Tordesillas.png" alt="1622 Antonio de Herrera y Tordesillas, DESCRIPTIO INDIÆ OCCIDENTALIS Per Antonium de Herrera Regium Indiarum et Castellæ Historiographum" style="width:200px;"></th>
  </tr>
  <tr>
    <td style="border: none">1510 Las Sergas de Esplandián by Garci Rodriguez de Montalvo - Wikipedia Commons</td>
    <td style="border: none">1597 Cornelis Wytfliet, Granata Nova et California</td>
    <td style="border: none">1622 Antonio de Herrera y Tordesillas, DESCRIPTIO INDIÆ OCCIDENTALIS</td>
  </tr>
</table>


<table style="border: none">
  <tr>
    <th style="border: none"><img src="/4 1625 Briggs The North part of America.png" alt="1625 Briggs The North part of America The North part of America conteyning Newfoundland, New England, Virginia, Florida, New Spaine and Nova Francia, with ye riche Iles of Hispaniola, Cuba, Jamaica, and Porto Rieco, on the south, and upon ye west the large and goodly island of California" style="width:200px;"></th>
    <th style="border: none"><img src="/5 1626 John Speed AMERICA.jpg" alt="1626 John Speed, AMERICA" style="width:400px;"></th>
    <th style="border: none"><img src="/6 1669 G. Sanson (State 1), AMERIQUE SEPTENTRIONALE.jpg" alt="1669 G. Sanson AMERIQUE SEPTENTRIONALE" style="width:400px;"></th>
  </tr>
  <tr>
    <td style="border: none">1625 Briggs The North part of America</td>
    <td style="border: none">1626 John Speed, America with those known parts</td>
    <td style="border: none">1669 G. Sanson, Amerique Septentrionale</td>
  </tr>
</table>

<table style="border: none">
  <tr>
    <th style="border: none"><img src="/7 1656 G. Sanson inset view of Sanson map.png" alt="1656 G. Sanson inset view of Sanson map" style="width:400px;"></th>
    <th style="border: none"><img src="/8 1720 De Fer, La Californie ou Nouvelle Caroline.jpg" alt="1720 De Fer, La Californie ou Nouvelle Caroline" style="width:400px;"></th>
    <th style="border: none"><img src="/9 1762 Kino, Passage by land to California.jpg" alt="1762 Kino, Passage by land to California" style="width:200px;"></th>
  </tr>
  <tr>
    <td style="border: none">1656 G. Sanson inset view of Sanson map</td>
    <td style="border: none">1720 De Fer, La Californie ou Nouvelle Caroline</td>
    <td style="border: none">1762 Kino, Passage by land to California</td>
  </tr>
</table>

<table style="border: none">
  <tr>
    <th style="border: none"><img src="/10 1770 Robert de Vaugondy, Carte de la Californie.jpg" alt="1770 Robert de Vaugondy, Carte de la Californie" style="width:400px;"></th>
    <th style="border: none"><img src="/11 1865 Shuzo Sato.jpg" alt="1865 Shuzo Sato" style="width:400px;"></th>
  </tr>
  <tr>
    <td style="border: none">1770 Vaugondy</td>
    <td style="border: none">1865 Shuzo Sato</td>
  </tr>
</table>