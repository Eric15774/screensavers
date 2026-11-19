# Science Screensavers

This is a collection of web pages to put on a classroom screen when you don't want something else up there.

Each page is a full-screen science display that runs on its own. Every few seconds it moves to something new, like a planet, an element, an earthquake or a star, and shows a short card of real facts about it. Students who glance up learn something, and students who stop to read learn more.

**Home page:** https://eric15774.github.io/screensavers/

## The screensavers

### Earth and sky

| Screensaver | What it shows | Link |
|---|---|---|
| **The Solar System Today** | Where every planet is right now, worked out from NASA JPL orbital data. Each planet's card gives its current distance from the Sun and from Earth and how long a radio signal takes to get there. | [Open](https://eric15774.github.io/screensavers/solar-system/) |
| **Earthquakes: The Last 24 Hours** | Every earthquake the U.S. Geological Survey recorded in the past day, drawn on a world map with the tectonic plate boundaries. It zooms in on the biggest quakes and shows the magnitude, depth, energy released and distance to the nearest plate boundary. | [Open](https://eric15774.github.io/screensavers/earthquakes/) |
| **Earth's History in One Day** | All 4.54 billion years of Earth's history squeezed into a 24-hour clock. The hand sweeps to 27 events, from Earth forming at midnight to the Industrial Revolution in the last 200th of a second. Includes Pennsylvania's coal and the rise of the Appalachians. | [Open](https://eric15774.github.io/screensavers/geologic-time/) |
| **When This Light Left** | How long light takes to reach us from the Moon, the Sun, 18 stars and the Andromeda Galaxy, and what was happening on Earth when that light set out. The years are worked out from today's date. | [Open](https://eric15774.github.io/screensavers/starlight/) |
| **Constellations** | A star map that tours the 88 constellations. | [Open](https://eric15774.github.io/screensavers/constellations/) |

### Physics and chemistry

| Screensaver | What it shows | Link |
|---|---|---|
| **Periodic Table** | Zooms in on a random element and shows its mass, state, melting and boiling points, density, electron configuration, discovery and uses. | [Open](https://eric15774.github.io/screensavers/periodic-table/) |
| **Chart of the Nuclides** | Isotopes, half-lives and decay modes across the chart of the nuclides. | [Open](https://eric15774.github.io/screensavers/nuclides/) |
| **SI Units and Prefixes** | The SI base units, derived units and metric prefixes. | [Open](https://eric15774.github.io/screensavers/si-units/) |

## Using them in a classroom

1. Open the link on the computer connected to the classroom screen.
2. Press **F** (or F11) for full screen.
3. Leave it running. The mouse pointer hides itself after a few seconds.

| Control | What it does |
|---|---|
| Click or **Space** | Skip to the next item |
| **F** | Toggle full screen |

The pages are built to run all day. The Solar System and Earthquake pages reload themselves every few hours so their data stays fresh.

## Good to know

- **Internet:** Every page needs a connection to load. The earthquake page also checks the USGS feed every 5 minutes. If the connection drops, it keeps showing the last data it got.
- **No setup:** Each screensaver is a single self-contained `index.html` file. There is nothing to install, and they work in any modern browser.
- **Scale:** The solar system orbits are drawn closer together than they really are so all eight planets fit. The page says so on screen.
- **Star distances:** Distances to far-off stars like Betelgeuse, Polaris and Deneb are uncertain, and the cards give the range astronomers report.

## Data sources

- Earthquakes: [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/) live GeoJSON feed
- Plate boundaries: Peter Bird (2003), *An updated digital model of plate boundaries*, via [fraxen/tectonicplates](https://github.com/fraxen/tectonicplates)
- World map: [Natural Earth](https://www.naturalearthdata.com/) 1:110m land
- Planet positions: NASA JPL approximate Keplerian orbital elements (E. M. Standish)
- Geologic time spans: International Commission on Stratigraphy chart
- Element and nuclide data: Eric Longwell's data workbooks, also in the [spreadsheets](https://github.com/eric15774/spreadsheets) repo

## Folder layout

```
index.html          Home page linking to every screensaver
solar-system/       The Solar System Today
earthquakes/        Earthquakes: The Last 24 Hours
geologic-time/      Earth's History in One Day
starlight/          When This Light Left
constellations/     Constellations
periodic-table/     Periodic Table
nuclides/           Chart of the Nuclides
si-units/           SI Units and Prefixes
```

To add a new screensaver, make a new folder with an `index.html` in it, then add a card for it on the home page and a row in the tables above.

---

Made by Eric Longwell for classrooms at Lenape Technical School.
