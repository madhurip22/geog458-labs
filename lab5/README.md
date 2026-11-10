# Bainbridge Island–Seattle Vessel Traffic

## Study area and dates

I mapped the water between Bainbridge Island and downtown Seattle on March 1, 2023 (a Wednesday). I picked it because the Bainbridge ferry is a well-known Seattle route, and a normal weekday shows regular traffic.

Data is from [AccessAIS](https://marinecadastre.gov/accessais/). Times are in UTC, so in Seattle time (PST) my data runs from Feb 28 at 4pm to Mar 1 at 4pm. I kept the file small by using just one day and one area.

## Interpretation

- **Mornings are busiest.** The most boats are moving around 7–9am PST. The quietest time is midnight–3am. This might be because of the morning commute into Seattle.
- **Ferries repeat the same routes.** With the Passenger filter on, the paths stack up between Bainbridge and downtown Seattle.
- **Most boats are parked.** Most vessels are "Other" (mostly pleasure boats and sailboats), and most of them never move. Tour boats also stay docked, maybe because it's the off-season.
- **There are very few cargo ships and tankers.** Only a few showed up, and most stayed docked.

## Feature proposal

**User:** a Bainbridge ferry commuter.

**Feature:** clicking a trail would show the boat's name and type, so you can tell which line is your ferry.

**Inspired by:** the [deck.gl interactivity guide](https://deck.gl/docs/developer-guide/interactivity), which shows how clicking or hovering on map objects can bring up info about them.