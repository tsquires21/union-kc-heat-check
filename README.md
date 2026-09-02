# Union KC Heat Check

**Live: https://tsquires21.github.io/union-kc-heat-check/**

Will the game be shortened or cancelled? This answers it before you drive to the field.

Pick a field complex and see the forecast **WBGT** (Wet Bulb Globe Temperature) hour by hour,
colour-coded by which of the [Heartland Soccer Association's extreme-heat
guidelines](https://www.heartlandsoccer.net/weather/extreme-heat-guidelines/) each hour lands in:

| WBGT | Outcome |
|---|---|
| ≤ 86.9 °F | Games on as scheduled |
| 87.0 – 91.9 °F | Heat Schedule — shortened games + water breaks |
| ≥ 92.0 °F | Games suspended or cancelled |

## WBGT is not wet-bulb temperature

Worth being clear about, because the two get confused constantly. Plain wet-bulb temperature
uses only heat and humidity. **WBGT also folds in sunshine and wind**, and on a clear afternoon
it runs 10–15° hotter. On 1 Sep 2026 at Olathe, air temperature was 99.1 °F, plain wet bulb was
75.9 °F — and WBGT was 87.0 °F. Those last two land in *different categories*.

The numbers here are the National Weather Service's hourly WBGT forecast for that exact field,
so they are the same quantity Heartland measures.

## This is a forecast, not the official call

Heartland reads a real WBGT device on-site at game time and posts updates to their weather line.
Use this to decide what to pack and what to expect — not whether a game is on.

## How it works

One HTML file. No server, no build step, no account, no API key, no tracking, no cookies.
It reads [api.weather.gov](https://api.weather.gov) directly from your browser — the NWS
publishes `wetBulbGlobeTemperature` in its raw gridpoint forecast, about seven days out, and
every field below sits in the Kansas City (EAX) grid.

Add it to your phone's home screen and it opens like an app.

### Fields

| | |
|---|---|
| **Union KC home** | Paragon Star (Lee's Summit) · Garmin Olathe |
| **Other Heartland complexes** | Scheels Overland Park · Swope Soccer Village · Compass Minerals |

There is also a "use my location" button for anywhere else in the NWS WBGT coverage area.

## Unofficial

A parent-built tool. Not affiliated with or endorsed by Union KC Soccer Club or the Heartland
Soccer Association. The crest belongs to the club.
