# Awesome-Mapping-Navigation

# Awesome-Mapping-Navigation

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Turn-by-Turn Navigation, Geocoding, Map Rendering & Location Services*
**Last updated: October 2026**

This repository tracks notable **commercial platforms** and **open-source projects** for **Mapping & Navigation**. These tools help developers and consumers navigate the world, render maps, geocode addresses, and build location-aware applications.

**Examples** include Google Maps, Apple Maps, Waze, HERE WeGo, MapQuest, OpenStreetMap, TomTom GO, OsmAnd, Citymapper, and Windows Maps (the category leaders).

**Open-source emphasis**: The open-source mapping ecosystem is **exceptionally mature and production-proven**. **OpenStreetMap** is the world's largest open geographic database, licensed under the **Open Database License (ODbL)**, with data contributed by millions of volunteers and national mapping agencies . **OsmAnd** provides a full-featured offline navigation app built on OSM data, and **GraphHopper** delivers open-source routing with a commercial API option. This section documents these production-grade solutions.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global mapping and navigation market is estimated at **~$15B in 2026**, growing toward **~$35B by 2032**. The sector is **highly concentrated** — **Google Maps** dominates consumer navigation and the developer API market, while **Apple Maps**, **Waze**, and **HERE WeGo** compete for consumer mindshare. **Pricing varies dramatically**: **Google Maps Platform** offers a **$200 monthly credit** and three subscription plans — **Starter at $100/month for 50,000 calls**, **Essentials at $275/month for 100,000 calls**, and **Pro at $1,200/month for 250,000 calls** . **HERE WeGo** and **Waze** are **100% free** to consumers . **MapQuest** offers a free tier with **ad-free options at $1.99–$4.99/month** . **TomTom GO** charges **£19.99/year** for car navigation . **Windows Maps** is **freeware** bundled with Windows .

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Google Maps](https://maps.google.com/)** | **The dominant mapping and navigation platform.** Consumer app plus developer APIs for maps, routes, places, and environment. | **Subscription plans**: **Starter $100/month** (50,000 calls), **Essentials $275/month** (100,000 calls), **Pro $1,200/month** (250,000 calls) . | **$200 monthly credit** for Google Maps Platform. **Free usage caps per SKU** (e.g., Dynamic Maps: 10,000 free loads/month) . | **~$350B revenue (Alphabet FY2025)** |
| **[Apple Maps](https://www.apple.com/maps/)** | **Apple's native mapping app.** Privacy-focused navigation with Look Around, detailed city experiences, and EV routing. | **Free** — bundled with Apple devices . | **Unlimited** — free for all Apple device users. | **~$400B revenue (Apple FY2025 est.)** |
| **[Waze](https://www.waze.com/)** | **Community-driven navigation.** Real-time traffic, police alerts, and crowd-sourced road reports. | **Free** — 100% free . | **Unlimited** — free for all users. | **Part of Google (~$350B revenue)** |
| **[HERE WeGo](https://www.here.com/)** | **Free navigation app from HERE Technologies.** Offline maps, public transit in 1,900+ cities, and turn-by-turn voice guidance. | **Free** — no cost to consumers . | **Unlimited** — free for all users. | **Private (HERE Technologies)** |
| **[MapQuest](https://www.mapquest.com/)** | **Long-standing mapping and navigation service.** Turn-by-turn directions and route planning. | **Free with ads**. **Ad-Free**: **$1.99–$4.99/month** . | **Free tier**: Core navigation with ads. | **Private (System1)** |
| **[TomTom GO](https://www.tomtom.com/)** | **Premium navigation app.** Real-time traffic, speed camera alerts, and offline maps. | **£19.99/year** for car navigation . | **No free tier** for full navigation. **Free trial** available. | **Private (~$500M+ revenue est.)** |
| **[Windows Maps](https://www.microsoft.com/en-us/p/windows-maps/9wzdncrfj3tj)** | **Microsoft's native Windows mapping app.** Voice navigation, turn-by-turn directions, and Ink support. | **Freeware** — bundled with Windows . | **Unlimited** — free with Windows. | **~$281B revenue (Microsoft FY2025)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[OpenStreetMap](https://github.com/openstreetmap/openstreetmap-website)** — **The world's largest open geographic database.** **ODbL licensed** — free to copy, distribute, and adapt with attribution . Maintained by millions of volunteers plus national mapping agencies (Austria, Australia, Canada, Czech Republic, Finland, France, Croatia, Netherlands, New Zealand, Serbia, Slovenia, Spain, South Africa, UK) . Powers thousands of websites, mobile apps, and hardware devices . | [![Stars](https://img.shields.io/github/stars/openstreetmap/openstreetmap-website?style=social&color=white)](https://github.com/openstreetmap/openstreetmap-website/stargazers) | ~3,500 |
| **[OsmAnd](https://github.com/osmandapp/OsmAnd)** — **Full-featured offline navigation app built on OpenStreetMap.** Turn-by-turn voice guidance, offline maps, and extensive customization. Available for Android and iOS. **GPL-3.0**. | [![Stars](https://img.shields.io/github/stars/osmandapp/OsmAnd?style=social&color=white)](https://github.com/osmandapp/OsmAnd/stargazers) | ~5,000 |
| **[GraphHopper](https://github.com/graphhopper/graphhopper)** — **Open-source routing engine with commercial API option.** Fast routing for cars, bikes, and pedestrians. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/graphhopper/graphhopper?style=social&color=white)](https://github.com/graphhopper/graphhopper/stargazers) | ~5,500 |
| **[Leaflet](https://github.com/Leaflet/Leaflet)** — **The leading open-source JavaScript library for interactive maps.** Lightweight, mobile-friendly, and extensible. **BSD-2-Clause**. | [![Stars](https://img.shields.io/github/stars/Leaflet/Leaflet?style=social&color=white)](https://github.com/Leaflet/Leaflet/stargazers) | ~43,000 |
| **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)** — **Open-source fork of Mapbox GL JS.** Vector tile rendering with no API key required. **BSD-3-Clause**. | [![Stars](https://img.shields.io/github/stars/maplibre/maplibre-gl-js?style=social&color=white)](https://github.com/maplibre/maplibre-gl-js/stargazers) | ~10,000 |
| **[Nominatim](https://github.com/osm-search/Nominatim)** — **Open-source geocoding from OpenStreetMap data.** Search by name and address, reverse geocoding. **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/osm-search/Nominatim?style=social&color=white)](https://github.com/osm-search/Nominatim/stargazers) | ~3,500 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Valhalla](https://github.com/valhalla/valhalla)** — Open-source routing engine with multi-modal support. **MIT** . |
| **[Photon](https://github.com/komoot/photon)** — Free geocoding service using OpenStreetMap data. No API key required . |
| **[OpenMapTiles](https://github.com/openmaptiles/openmaptiles)** — Open-source map tile schema for vector tiles. **MIT** . |
| **[MapLibre Native](https://github.com/maplibre/maplibre-native)** — Open-source native SDK for iOS, Android, and desktop. **BSD-2-Clause** . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mapping and navigation platforms handle location data; ensure compliance with privacy regulations and applicable location data laws.
- **OpenStreetMap attribution**: If you use OSM data, you **must credit OpenStreetMap** and make clear the data is under ODbL. For interactive maps, place attribution in a corner or splash screen .

---

**Made for developers, GIS professionals, urban planners, and navigation enthusiasts.**
Let's make mapping and navigation more open, transparent, and accessible.
