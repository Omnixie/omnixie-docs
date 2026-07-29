# Omnixie Docs

Documentation and product catalog site for [Omnixie](https://www.omnixie.com) - a Silicon Valley electronics company crafting Nixie tube clocks, VFD displays, and precision electronic components.

Served at **https://docs.omnixie.com** via GitHub Pages.

## Products

### Clocks
- **Omnixie Clock** - WiFi-enabled Nixie tube clock supporting 6 tube types (IN-14, IN-8-2, Z570M, ZM1080, NL-5441, NL-841)
- **Omnixie Plus Clock** - Premium WiFi Nixie tube clock for large-format tubes (IN-18, ZM1040)
- **VIVID** - WiFi-enabled VFD tube clock with IPS display
- **Chrono-Wood Clock** - WiFi-enabled LED clock with wooden enclosure
- **NeoGoggles** - Programmable RGB LED party glasses

### Components
- **NCH6300HV** - High-voltage DC-DC booster (100-230V adjustable output)
- **NCH8200HV** - Fixed 170V DC-DC booster for Nixie tube projects
- **NTDB4** - Nixie Tube Driver Board for 4 tubes with SPI interface

### Resources
- Nixie tube overview and specifications
- VFD tube overview
- IN-12 Nixie tube technical reference
- How to test a Nixie tube

## Tech Stack

- Static HTML/CSS site, no build step
- Custom CSS design system (`styles/omnixie-brand.css`) - dark-first theme with Nixie amber glow aesthetic
- Inter typeface

## Deployment

Hosted on **GitHub Pages** (deploy from `main` branch). Any push to `main` publishes automatically.

Custom domain `docs.omnixie.com` is configured via the `CNAME` file plus a DNS CNAME record pointing `docs.omnixie.com` -> `omnixie.github.io`. The `.nojekyll` file disables Jekyll so files are served as-is.

## License

Copyright 2009-2026 Omnixie. All rights reserved.
