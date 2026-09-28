# Swisshelm Park History Map

An interactive history map of **Swisshelm Park**, Pittsburgh, Pennsylvania, with Duck Hollow, the Nine Mile Run valley, and the edges of Frick Park and Swissvale.

**Open the map:** https://0xguy07.github.io/swisshelm-park-history/

Next door: the [Frick Park History Map](https://0xguy07.github.io/frick-park-history/).

## What's on it

- **Historical photographs** (1907–2004), each placed at its estimated camera position with a direction arrow and a link to Street View today.
- **Dated events** (1808–2027) with sources and a location-confidence rating.
- **Street histories**: former names (Pitt → Pocono, West → Whipple, Black Oak → Onondago, North → Nevada, Leland → Lippert → Le Blanc), when streets were laid out, and what happened on them.
- **Lost roads** and the **1923 Pittsburgh–Swissvale city line**.
- **Census residents, 1900–1950**: households from the U.S. censuses of 1900, 1910, 1920, 1930, 1940, and 1950, placed at their house numbers (or along their street when no number was recorded). Names were transcribed from handwriting; uncertain readings are marked "?".
- **Old map overlays**, georeferenced to today's streets: 1904, 1951, 1960, and 1993 USGS topographic maps; 1911, 1923, and 1939 G. M. Hopkins plat maps; and a 1938 aerial photograph.
- A **timeline slider** to view the neighborhood as of any year.

## Accuracy notes

- Photo and some event locations are **estimates** based on catalog descriptions; each item shows its confidence.
- Plat overlays were georeferenced by matching street corners (typical error 5–15 m; the 1911 plat about 15 m). The 1938 aerial is a single tilted photograph (20–50 m error at the edges).
- Census transcriptions were read from microfilm images and contain errors. Check the original page (enumeration district and sheet are given for every household) before relying on a name or age.

## Sources and credits

| Material | Source | Rights |
|---|---|---|
| Photographs (1907–1963) | Pittsburgh City Photographer Collection and Allegheny Conference on Community Development Photographs, Archives & Special Collections, University of Pittsburgh Library System, via [Historic Pittsburgh](https://historicpittsburgh.org/) | Marked "No Copyright – United States" (City Photographer); see each item's rights statement |
| 2004 slag dump photos | Squirrel Hill Historical Society collection, via Historic Pittsburgh | See item rights statements |
| Plat maps (1911, 1923, 1939) | G. M. Hopkins Co., *Real Estate Plat-Books of the City of Pittsburgh*, via Historic Pittsburgh | Historic Pittsburgh |
| Topographic maps | U.S. Geological Survey, Historical Topographic Map Collection | Public domain |
| 1938 aerial | PennPilot, Pennsylvania Geological Survey / PASDA | Public domain |
| Census images | U.S. National Archives (1940 and 1950); Internet Archive microfilm (1900–1930) | Public domain |
| Street geometry, addresses | © OpenStreetMap contributors (ODbL); Allegheny County parcel data via WPRDC | ODbL / open data |
| Neighborhood boundary | City of Pittsburgh, via WPRDC | Open data |
| Base maps | Esri World Street Map and World Imagery | Esri terms |

Key published sources for the events and street histories include the *Pittsburgh Press* (31 Dec 1939, p. 43), *Pittsburgh Sun-Telegraph* (15 Dec 1939, p. 32; 11 Apr 1950, p. 6), Andrew S. McElwaine's "Slag in the Park," the City of Pittsburgh's Frick Park Historic Landmark nomination (2023), Michelle Fanzo's *Cultural Survey of Swissvale* (1992), the Historical Marker Database, and Wikipedia.

## Corrections and contributions

Found an error, have a photo, or remember something about the neighborhood? Please [open an issue](https://github.com/0xguy07/swisshelm-park-history/issues).

## Files

- `index.html`: the map (a single page using [Leaflet](https://leafletjs.com/))
- `swisshelm-park.geojson`: all map data (photos, events, streets, lost roads, boundary, census households)
- `assets/`: photographs and georeferenced overlay images
