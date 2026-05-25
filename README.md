# Cold Air Damming Field Brief

Web slide deck explaining the May 23-25, 2026 cold-air-damming setup from the Southeast into the New York metro area.

The deck uses:

- NWS AFD excerpts from FFC, PHI, and OKX
- AviationWeather METAR screenshots
- WPC surface analysis images
- NOAA/NWS MRMS radar loop over an OpenStreetMap basemap
- 00Z sounding-derived comparison chart
- 925/850 mb layer diagnostics for the elevated warm/moist conveyor
- An OKX parcel-source inset separating the surface wedge from the 925 mb elevated source layer
- Hourly METAR flight-category timelines to show wedge duration without SPECI count bias
- Instrument-pilot decision and briefing-workflow slides focused on low ceilings, embedded convection proof, alternates, terrain, and escape paths
- A worked KCDW/KFRG westbound go/no-go example using observed ceilings, nearby TAFs, route/terrain constraints, and convective-proof gates

## Source Traceability

- NWS AFD screenshots: FFC, OKX, PHI products issued May 24-25, 2026.
- SPC Day 1 0100Z update: remnant lower/mid-tropospheric MCV moving into the southern Appalachians.
- WPC surface analyses: May 24 00Z/12Z/18Z and May 25 00Z.
- Soundings: University of Wyoming archive for OKX, FFC, IAD, and RNK at 00Z May 25, 2026.
- Parcel diagnostics: MetPy calculations from the archived OKX 00Z sounding, comparing surface, 925 mb, and 850 mb parcels.
- METARs: AviationWeather API 48-hour observations for KJFK, KLGA, KTEB, KCDW, KFRG, KABE, KIPT, KATL, and KCLT.
- KFRG operational discussion uses the fetched 0153Z observation: 13/13 C, 040/05, 2 SM BR, OVC003, LIFR.
- TAFs for the worked decision example: KTEB/KJFK/KISP 0245Z, KABE 0131Z, and KIPT 0212Z May 25 products from the AviationWeather API.
- Freezing-level context is derived from 00Z soundings: OKX about 12.7k ft, IAD/RNK about 13.9k ft, FFC about 14.5k ft.
- Radar loop: NOAA/NWS MRMS base reflectivity frames from 01:10Z-03:02Z May 25 over OpenStreetMap basemap tiles.
- Convective validation in the static deck uses proxy evidence from MRMS reflectivity plus METAR TS/CB/lightning wording; live preflight should confirm with dedicated lightning and echo-top products.

Open `index.html` directly, or deploy as a static site.
