# Screensaver Collection

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

### Engineering and technology

| Screensaver | What it shows | Link |
|---|---|---|
| **Simple Machines** | Animations of the three classes of levers, the wheel and axle, a block and tackle, a ramp, a wedge, a screw jack and a gear train. Each one shows the mechanical advantage formula with a worked example and where students see it in everyday life. | [Open](https://eric15774.github.io/screensavers/simple-machines/) |
| **How a Diesel Engine Works** | One cylinder of a turbocharged truck diesel running through intake, compression, power and exhaust, with live crank angle, approximate gas temperature and pressure. Cards cover compression ignition, the turbocharger, engine brakes, air brakes, efficiency and DPF/DEF, with CDL tips. | [Open](https://eric15774.github.io/screensavers/diesel-engine/) |
| **Where Our Units Came From** | 24 everyday and odd units, from the inch and the furlong to horsepower, psi, the BTU and the decibel. Each one gives its origin, its exact modern definition and where you will run into it. Pairs well with the SI Units screensaver. | [Open](https://eric15774.github.io/screensavers/units-history/) |

### Math and patterns

| Screensaver | What it shows | Link |
|---|---|---|
| **Equations That Changed the World** | 18 famous equations "written" on a chalkboard, from the Pythagorean theorem and Newton's laws to E = mc² and Shannon's information theory. Each card gives who and when, what it means in plain words, what it changed, and a quick example to try. | [Open](https://eric15774.github.io/screensavers/famous-equations/) |
| **Laws, Rules and Paradoxes** | 52 laws of nature, rules of thumb and paradoxes in alphabetical order, so Archimedes' principle sits next to the Abilene paradox and Murphy's law sits next to Mendel. Color tags show which kind each one is. | [Open](https://eric15774.github.io/screensavers/laws-and-paradoxes/) |
| **Fractals and Chaos** | Eight live animations: a Mandelbrot zoom to 100,000×, the chaos game building a Sierpinski triangle, the Barnsley fern, the Koch snowflake, three double pendulums drifting apart, the Lorenz butterfly, the logistic map's road to chaos, and a growing fractal tree. | [Open](https://eric15774.github.io/screensavers/fractals-and-chaos/) |

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
- **Older computers:** The Mandelbrot zoom on the Fractals and Chaos page does heavy math in real time. On a slow classroom PC it may look choppy, but it still works.
- **No setup:** Each screensaver is a single self-contained `index.html` file. There is nothing to install, and they work in any modern browser.
- **Scale:** The solar system orbits are drawn closer together than they really are so all eight planets fit. The page says so on screen.
- **Diesel numbers:** Temperatures and pressures on the diesel page are approximate values from a simple model of a turbocharged truck engine.
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
simple-machines/    Simple Machines
diesel-engine/      How a Diesel Engine Works
units-history/      Where Our Units Came From
famous-equations/   Equations That Changed the World
laws-and-paradoxes/ Laws, Rules and Paradoxes
fractals-and-chaos/ Fractals and Chaos
periodic-table/     Periodic Table
nuclides/           Chart of the Nuclides
si-units/           SI Units and Prefixes
```

To add a new screensaver, make a new folder with an `index.html` in it, then add a card for it on the home page and a row in the tables above.

---

Made by Eric Longwell for classrooms at Lenape Technical School.
