# 🔍 OSINT Nexus — The Ultimate Open Source Intelligence Toolkit

> **A curated, categorized collection of 410+ OSINT tools for investigators, journalists, researchers, and security professionals.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> **🗓️ Last verified: 10 October 2026.** Every entry links to the tool's own website, extension-store page or repository; catalogues and guides are kept separately in [Directories and Meta-Resources](#directories-and-meta-resources). All GitHub links were checked to confirm the repository exists, and new additions and higher-risk entries were checked individually against the tool's own site; the remaining entries carry over from the July 2026 review. See the [Changelog](#changelog) for what changed. Tool availability changes fast — if you hit a dead link, please open an issue.

---

## Contents

Holding a specific clue — a photo, a username, a ship, a wallet address? Start with [Start From What You Have](#start-from-what-you-have). Looking for a tool by name? Use the [Tool Index A–Z](#tool-index-az).

| Theme | Sections (number of tools) |
|-------|----------------------------|
| **Start here** | [How to Use This Toolkit](#how-to-use-this-toolkit)<br>[Start From What You Have](#start-from-what-you-have)<br>[Tool Index A–Z](#tool-index-az) |
| **Places and imagery** | 🗺️ [Maps and Geolocation](#maps-and-geolocation) (34)<br>🛰️ [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) (25)<br>☀️ [Weather, Time and Shadow Analysis](#weather-time-and-shadow-analysis) (14) |
| **Search, people and platforms** | 🔎 [Search Engines and Advanced Operators](#search-engines-and-advanced-operators) (10)<br>📱 [Social Media Intelligence](#social-media-intelligence) (20)<br>💬 [Messaging and Forums](#messaging-and-forums) (8)<br>👤 [Username and Identity Search](#username-and-identity-search) (10)<br>📧 [Email, Phone and People Lookup](#email-phone-and-people-lookup) (10)<br>🧑 [Facial Recognition](#facial-recognition) (4) |
| **Media verification** | 🖼️ [Reverse Image Search and Image Forensics](#reverse-image-search-and-image-forensics) (14)<br>🤖 [AI-Generated and Synthetic Media Detection](#ai-generated-and-synthetic-media-detection) (5)<br>🎬 [Video Analysis and Verification](#video-analysis-and-verification) (6)<br>🎙️ [Audio Analysis and Acoustic OSINT](#audio-analysis-and-acoustic-osint) (22) |
| **Organisations, money and law** | 🏢 [Corporate and Financial Intelligence](#corporate-and-financial-intelligence) (16)<br>🏛️ [Public Records, Procurement and Lobbying](#public-records-procurement-and-lobbying) (14)<br>🚫 [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons) (8)<br>⚖️ [Legal and Court Records](#legal-and-court-records) (10)<br>⛓️ [Cryptocurrency and Blockchain](#cryptocurrency-and-blockchain) (15) |
| **Transport** | ✈️ [Transport Tracking](#transport-tracking) (21)<br>🚢 [Maritime Intelligence](#maritime-intelligence) (11) |
| **Infrastructure and cyber** | 🌐 [Domains, IPs and Internet Infrastructure](#domains-ips-and-internet-infrastructure) (37)<br>🔓 [Data Leaks and Breach Intelligence](#data-leaks-and-breach-intelligence) (8)<br>💻 [Code and Technical Search](#code-and-technical-search) (6) |
| **Conflict and environment** | 💣 [Conflict, Arms and Munitions](#conflict-arms-and-munitions) (14)<br>🌍 [Environmental and Wildlife Intelligence](#environmental-and-wildlife-intelligence) (16) |
| **Workflow and tooling** | 📦 [Archiving and Preservation](#archiving-and-preservation) (14)<br>🧩 [Browser Extensions and Scrapers](#browser-extensions-and-scrapers) (8)<br>📊 [Data Analysis and Visualization](#data-analysis-and-visualization) (14)<br>📝 [Frameworks, Automation and Case Management](#frameworks-automation-and-case-management) (12)<br>🔤 [Translation and Language](#translation-and-language) (4)<br>📚 [Directories and Meta-Resources](#directories-and-meta-resources) (7) |
| **Reference** | [Deprecated and Defunct Tools](#deprecated-and-defunct-tools)<br>[Tool Count by Pricing](#tool-count-by-pricing)<br>[Changelog](#changelog)<br>[Contributing](#contributing)<br>[Disclaimer](#disclaimer)<br>[License](#license) |

---

## How to Use This Toolkit

There are three ways to find a tool:

1. **By what you have** — [Start From What You Have](#start-from-what-you-have) maps a starting clue (a photo, username, company, ship, wallet address and so on) to the right sections.
2. **By topic** — the [Contents](#contents) groups every section by theme. Sections with sub-categories open with a **Jump to** line.
3. **By name** — open the [Tool Index A–Z](#tool-index-az), or press `Ctrl+F` / `Cmd+F`. On GitHub you can also click the outline button (☰) at the top right of the README to see every heading.

Each tool entry follows this format:

| Field | Meaning |
|-------|---------|
| **Tool** | Tool name, linked to its official website, extension-store page or repository |
| **Description** | What it does and how OSINT professionals use it |
| **Pricing** | 🟢 Free · 🟡 Freemium · 🔴 Paid · 🔵 Open Source |

**Status flags used in this edition:**

- ⚠️ Still available, but with an important caveat (reduced functionality, access restrictions, ownership or pricing changes, or maintenance concerns)
- ⚫ No longer available or effectively defunct — listed in [Deprecated and Defunct Tools](#deprecated-and-defunct-tools)

---

## Start From What You Have

| If you have… | Start with | Then try |
|--------------|------------|----------|
| A photo | [Reverse Image Search](#reverse-image-search) | [Maps and Geolocation](#maps-and-geolocation) · [Weather, Time and Shadow Analysis](#weather-time-and-shadow-analysis) · [AI-Generated and Synthetic Media Detection](#ai-generated-and-synthetic-media-detection) |
| A video | [Video Analysis and Verification](#video-analysis-and-verification) | [Reverse Image Search (keyframes)](#reverse-image-search) · [Maps and Geolocation](#maps-and-geolocation) · [Archiving and Preservation](#archiving-and-preservation) |
| An audio recording | [Audio Analysis and Acoustic OSINT](#audio-analysis-and-acoustic-osint) | [Background Event Cross-Reference](#background-event-cross-reference) · [Historical Weather](#historical-weather) |
| A username or handle | [Username and Identity Search](#username-and-identity-search) | [Social Media Intelligence](#social-media-intelligence) · [Messaging and Forums](#messaging-and-forums) |
| An email address | [Email, Phone and People Lookup](#email-phone-and-people-lookup) | [Data Leaks and Breach Intelligence](#data-leaks-and-breach-intelligence) · [Username and Identity Search](#username-and-identity-search) |
| A phone number | [Email, Phone and People Lookup](#email-phone-and-people-lookup) | [Telegram tools](#telegram) |
| A public figure's name | [Search Engines and Advanced Operators](#search-engines-and-advanced-operators) | [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons) · [Corporate and Financial Intelligence](#corporate-and-financial-intelligence) · [Legal and Court Records](#legal-and-court-records) |
| A company or organisation | [Corporate and Financial Intelligence](#corporate-and-financial-intelligence) | [Public Records, Procurement and Lobbying](#public-records-procurement-and-lobbying) · [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons) · [Legal and Court Records](#legal-and-court-records) |
| A website or domain | [WHOIS, DNS and Certificates](#whois-dns-and-certificates) | [Website Fingerprinting and Connections](#website-fingerprinting-and-connections) · [Archiving and Preservation](#archiving-and-preservation) · [Code and Technical Search](#code-and-technical-search) |
| An IP address | [IP, ASN and Routing](#ip-asn-and-routing) | [Threat Intelligence and Reputation](#threat-intelligence-and-reputation) · [Internet-Wide Device Search](#internet-wide-device-search) |
| A crypto wallet address | [Cryptocurrency and Blockchain](#cryptocurrency-and-blockchain) | [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons) · [Data Leaks and Breach Intelligence](#data-leaks-and-breach-intelligence) |
| A ship name, IMO or MMSI number | [Maritime Intelligence](#maritime-intelligence) | [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons) · [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) |
| An aircraft registration or flight number | [Aviation](#aviation) | [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) |
| A vehicle or number plate | [Road and Vehicles](#road-and-vehicles) | [Maps and Geolocation](#maps-and-geolocation) |
| A Telegram channel or Discord server | [Messaging and Forums](#messaging-and-forums) | [Archiving and Preservation](#archiving-and-preservation) · [Browser Extensions and Scrapers](#browser-extensions-and-scrapers) |
| A place or coordinates | [Maps and Geolocation](#maps-and-geolocation) | [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) · [Weather, Time and Shadow Analysis](#weather-time-and-shadow-analysis) |
| A conflict incident | [Conflict, Arms and Munitions](#conflict-arms-and-munitions) | [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) · [Maps and Geolocation](#maps-and-geolocation) |
| An environmental claim | [Environmental and Wildlife Intelligence](#environmental-and-wildlife-intelligence) | [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) |
| A claim, quote or news story | [Search Engines and Advanced Operators](#search-engines-and-advanced-operators) | [Social Media Intelligence](#social-media-intelligence) · [Archiving and Preservation](#archiving-and-preservation) · [AI-Generated and Synthetic Media Detection](#ai-generated-and-synthetic-media-detection) |
| A page that might disappear | [Archiving and Preservation](#archiving-and-preservation) | — |
| A pile of documents or data | [Documents and Data Wrangling](#documents-and-data-wrangling) | [Link Analysis and Networks](#link-analysis-and-networks) · [Translation and Language](#translation-and-language) |
| Foreign-language material | [Translation and Language](#translation-and-language) | [Regional search engines](#search-engines-and-advanced-operators) |

---

## Tool Index A–Z

Every tool in this list, alphabetically. Each name links to the section where it appears.

<details>
<summary><b>Show all 417 tools</b></summary>

**0–9** · [2GIS](#map-platforms) · [4CAT](#browser-extensions-and-scrapers) · [4plebs](#forums-and-imageboards)

**A** · [AbuseIPDB](#threat-intelligence-and-reputation) · [ACLED](#conflict-monitoring-and-documentation) · [Adobe Audition](#spectrogram-and-frequency-analysis) · [Adobe Podcast Enhance](#background-sound-isolation-and-enhancement) · [ADS-B Exchange](#aviation) · [ADSB.lol](#aviation) · [AHA Music (Extension)](#speech-language-and-music-identification) · [AI or Not](#ai-generated-and-synthetic-media-detection) · [Airframes](#aviation) · [Airwars](#conflict-monitoring-and-documentation) · [AlienVault OTX](#threat-intelligence-and-reputation) · [AllTrails](#geolocation-aids) · [Apollo Mapping](#commercial-imagery) · [Apple Maps](#map-platforms) · [Aqueduct Water Risk Atlas](#land-forests-and-emissions) · [ArchiveBox](#capture-and-monitoring-tools) · [Archive.today](#public-web-archives) · [ArchiveWeb.page](#capture-and-monitoring-tools) · [Arctic Shift](#reddit-youtube-and-linkedin) · [Arkham Intelligence](#tracing-attribution-and-risk) · [Arquivo.pt](#public-web-archives) · [ASF Vertex](#imagery-viewers-and-archives) · [Atlos](#conflict-monitoring-and-documentation) · [Audacity](#spectrogram-and-frequency-analysis) · [Auto Archiver](#capture-and-monitoring-tools) · [Awesome OSINT](#directories-and-meta-resources) · [Azure AI Video Indexer](#video-analysis-and-verification)

**B** · [Baidu](#search-engines-and-advanced-operators) · [Baidu Image Search](#reverse-image-search) · [Baidu Maps](#map-platforms) · [BAILII](#legal-and-court-records) · [BBOT](#recon-and-automation) · [Bellingcat Online Investigation Toolkit](#directories-and-meta-resources) · [Bellingcat OpenStreetMap Search](#geolocation-aids) · [Bellingcat Toolkit: China-related Resources](#directories-and-meta-resources) · [Bing](#search-engines-and-advanced-operators) · [Bing Maps](#map-platforms) · [Bing Visual Search](#reverse-image-search) · [BirdNET Analyzer](#environmental-and-bioacoustic-sound-identification) · [BirdNET Web Demo](#environmental-and-bioacoustic-sound-identification) · [Blackbird](#username-and-identity-search) · [Blender](#charts-maps-and-timelines) · [Blockchair](#block-explorers) · [Blockstream Explorer](#block-explorers) · [Bluesky Social Graph (Jaz)](#bluesky-and-the-fediverse) · [Brave Search](#search-engines-and-advanced-operators) · [Breadcrumbs](#tracing-attribution-and-risk) · [BskyFollowFinder](#bluesky-and-the-fediverse) · [BuiltWith](#website-fingerprinting-and-connections) · [Bulletpicker](#weapons-and-munitions-identification)

**C** · [CanLII](#legal-and-court-records) · [Carbon Mapper](#land-forests-and-emissions) · [Castrick Clues](#email-phone-and-people-lookup) · [CAT-UXO](#weapons-and-munitions-identification) · [CelesTrak](#satellites-in-orbit) · [Censys Platform](#internet-wide-device-search) · [Chainabuse](#tracing-attribution-and-risk) · [Chainalysis](#tracing-attribution-and-risk) · [Charity Commission Register](#charities-and-official-notices) · [Chronotrains](#rail) · [CITES Trade Database](#wildlife-and-biodiversity) · [ClearSky (Bluesky)](#bluesky-and-the-fediverse) · [Climate TRACE](#land-forests-and-emissions) · [Cobalt](#video-analysis-and-verification) · [Companies House (UK)](#company-registers-and-ownership) · [Content Credentials Verify](#ai-generated-and-synthetic-media-detection) · [Convert Geographic Units](#coordinates-and-map-utilities) · [Copernicus Browser](#imagery-viewers-and-archives) · [Copernicus Emergency Management Service](#analysis-and-event-monitoring) · [CourtListener / RECAP](#legal-and-court-records) · [Criminal IP](#internet-wide-device-search) · [crt.sh](#whois-dns-and-certificates) · [Crunchbase](#company-registers-and-ownership) · [CSI Linux](#investigation-environments)

**D** · [Datasette](#documents-and-data-wrangling) · [Datawrapper](#charts-maps-and-timelines) · [DeBank](#tracing-attribution-and-risk) · [DeepFake-o-Meter](#ai-generated-and-synthetic-media-detection) · [DeepL Translator](#translation-and-language) · [DeepStateMap](#conflict-monitoring-and-documentation) · [DeHashed](#data-leaks-and-breach-intelligence) · [Demucs](#background-sound-isolation-and-enhancement) · [Disboard](#discord) · [DiscordChatExporter](#browser-extensions-and-scrapers) · [discord.id](#discord) · [DiscordLeaks](#data-leaks-and-breach-intelligence) · [Distill.io](#capture-and-monitoring-tools) · [DNSDumpster](#whois-dns-and-certificates) · [DNSlytics](#whois-dns-and-certificates) · [DomainTools Whois](#whois-dns-and-certificates) · [draw.io](#link-analysis-and-networks) · [DVLA Vehicle Enquiry](#road-and-vehicles)

**E** · [Earth Explorer (USGS)](#imagery-viewers-and-archives) · [Earth Online (ESA)](#imagery-viewers-and-archives) · [eBird](#wildlife-and-biodiversity) · [EDGAR Full-Text Search](#company-registers-and-ownership) · [EDGAR (SEC)](#company-registers-and-ownership) · [EIA International](#land-forests-and-emissions) · [ELAN](#annotation-and-batch-processing) · [ENF Fingerprinting Tool](#enf-electric-network-frequency-analysis) · [ENS App](#tracing-attribution-and-risk) · [Environmental Justice Atlas](#land-forests-and-emissions) · [EOSDA LandViewer](#imagery-viewers-and-archives) · [Epieos](#email-phone-and-people-lookup) · [Equasis](#maritime-intelligence) · [Esri World Imagery Wayback](#imagery-viewers-and-archives) · [Etherscan](#block-explorers) · [EU Business Registers (e-Justice)](#company-registers-and-ownership) · [EU Financial Transparency System](#procurement-and-public-spending) · [Europe's Most Wanted](#legal-and-court-records) · [EU Sanctions Map](#sanctions-and-politically-exposed-persons) · [EU Transparency Register](#lobbying-and-political-finance) · [ExifTool](#image-forensics-and-metadata)

**F** · [F4Map](#map-platforms) · [FAA Aircraft Registry](#aviation) · [FaceCheck.ID](#facial-recognition) · [Face Comparison by ToolPie](#facial-recognition) · [FARA eFile](#lobbying-and-political-finance) · [FEC Campaign Finance Data](#lobbying-and-political-finance) · [FediDB](#bluesky-and-the-fediverse) · [FFmpeg](#video-analysis-and-verification) · [ffprobe](#audio-metadata-and-file-forensics) · [Find a Tender (UK)](#procurement-and-public-spending) · [Find Case Law (UK)](#legal-and-court-records) · [Flickr Map](#street-level-and-crowdsourced-imagery) · [FlightAware](#aviation) · [Flightradar24](#aviation) · [Flourish](#charts-maps-and-timelines) · [FOFA](#internet-wide-device-search) · [Forensically](#image-forensics-and-metadata) · [FotoForensics](#image-forensics-and-metadata) · [Freesound](#environmental-and-bioacoustic-sound-identification) · [Friture](#spectrogram-and-frequency-analysis)

**G** · [gallery-dl](#browser-extensions-and-scrapers) · [Gaode Maps (Amap)](#map-platforms) · [GeoConfirmed](#conflict-monitoring-and-documentation) · [Geo Data Tool](#ip-asn-and-routing) · [Geograph](#street-level-and-crowdsourced-imagery) · [GeoHints](#geolocation-aids) · [Gephi](#link-analysis-and-networks) · [GH Archive](#code-and-technical-search) · [Ghost Archive](#public-web-archives) · [GHunt](#username-and-identity-search) · [GitHub Code Search](#code-and-technical-search) · [Gitleaks](#code-and-technical-search) · [GLEIF LEI Search](#company-registers-and-ownership) · [Global Energy Monitor](#land-forests-and-emissions) · [Global Fishing Watch](#maritime-intelligence) · [Global Forest Watch](#land-forests-and-emissions) · [GoFullPage](#capture-and-monitoring-tools) · [Google Admin Toolbox Messageheader](#email-phone-and-people-lookup) · [Google Ads Transparency Center](#advertising-transparency) · [Google Advanced Search](#search-engines-and-advanced-operators) · [Google Alerts](#search-engines-and-advanced-operators) · [Google Earth Engine](#analysis-and-event-monitoring) · [Google Earth Pro](#map-platforms) · [Google Earth Timelapse](#imagery-viewers-and-archives) · [Google Earth (web)](#map-platforms) · [Google Flood Hub](#analysis-and-event-monitoring) · [Google Hacking Database](#search-engines-and-advanced-operators) · [Google Lens](#reverse-image-search) · [Google Maps](#map-platforms) · [Google Translate](#translation-and-language) · [Google Trends](#search-engines-and-advanced-operators) · [GovMap](#map-platforms) · [GPSJam](#analysis-and-event-monitoring) · [GrayHatWarfare](#internet-wide-device-search) · [grep.app](#code-and-technical-search) · [GreyNoise](#threat-intelligence-and-reputation)

**H** · [Have I Been Pwned](#data-leaks-and-breach-intelligence) · [Hitta.se](#email-phone-and-people-lookup) · [Hive AI-Generated Content Detection](#ai-generated-and-synthetic-media-detection) · [Holehe](#email-phone-and-people-lookup) · [Host.io](#whois-dns-and-certificates) · [HUDOC](#legal-and-court-records) · [Hudson Rock (Free Tools)](#data-leaks-and-breach-intelligence) · [Hugin](#image-collections-and-panoramas) · [Hunchly](#capture-and-monitoring-tools) · [Hunter.io](#email-phone-and-people-lookup) · [Hurricane Electric BGP Toolkit](#ip-asn-and-routing)

**I** · [ICANN Lookup](#whois-dns-and-certificates) · [ICIJ Offshore Leaks Database](#leaks-and-investigative-databases) · [IDCrawl](#username-and-identity-search) · [IDN Checker (Punycoder)](#whois-dns-and-certificates) · [IMO GISIS](#maritime-intelligence) · [ImportGenius](#trade-and-supply-chains) · [ImportYeti](#trade-and-supply-chains) · [iNaturalist](#environmental-and-bioacoustic-sound-identification) · [Instagram Location Search](#facebook-and-instagram) · [Instaloader](#browser-extensions-and-scrapers) · [Instant Data Scraper](#browser-extensions-and-scrapers) · [Instant Username Search](#username-and-identity-search) · [Intelligence X](#data-leaks-and-breach-intelligence) · [IntelTechniques Tools](#directories-and-meta-resources) · [Interpol Red Notices](#legal-and-court-records) · [InVID / WeVerify Verification Plugin](#video-analysis-and-verification) · [IPinfo](#ip-asn-and-routing) · [iTrace](#weapons-and-munitions-identification)

**J** · [Jeffrey's Image Metadata Viewer](#image-forensics-and-metadata) · [Justia](#legal-and-court-records)

**K** · [Kakao Map](#map-platforms) · [KartaView](#street-level-and-crowdsourced-imagery) · [kepler.gl](#charts-maps-and-timelines) · [Kumu](#link-analysis-and-networks)

**L** · [LeakIX](#internet-wide-device-search) · [Leak-Lookup](#data-leaks-and-breach-intelligence) · [Library of Leaks](#data-leaks-and-breach-intelligence) · [LightningMaps](#historical-weather) · [LinkedIn Post Timestamp Extractor](#reddit-youtube-and-linkedin) · [LittleSis](#company-registers-and-ownership) · [Liveuamap](#conflict-monitoring-and-documentation) · [LobbyFacts](#lobbying-and-political-finance) · [Locust Hub (FAO)](#wildlife-and-biodiversity) · [Logseq](#notes-and-case-management) · [LPR Maps](#road-and-vehicles) · [Lumen Database](#legal-and-court-records)

**M** · [Maigret](#username-and-identity-search) · [Maltego](#link-analysis-and-networks) · [MapBiomas](#land-forests-and-emissions) · [MapChecking](#geolocation-aids) · [Mapillary](#street-level-and-crowdsourced-imagery) · [MapSwitcher](#coordinates-and-map-utilities) · [Mapy.com](#map-platforms) · [MarineTraffic](#maritime-intelligence) · [MediaInfo](#audio-metadata-and-file-forensics) · [mempool.space](#block-explorers) · [Merlin Bird ID](#environmental-and-bioacoustic-sound-identification) · [Meta Ad Library](#advertising-transparency) · [Meta Content Library](#facebook-and-instagram) · [MetaSleuth](#tracing-attribution-and-risk) · [Meteostat](#historical-weather) · [Mitaka](#browser-extensions-and-scrapers) · [Mojeek](#search-engines-and-advanced-operators) · [MoonCalc](#sun-moon-and-shadows) · [MOT History](#road-and-vehicles) · [MW Geofind](#reddit-youtube-and-linkedin) · [MXToolbox](#email-phone-and-people-lookup) · [MyShipTracking](#maritime-intelligence)

**N** · [N2YO](#satellites-in-orbit) · [Namechk](#username-and-identity-search) · [Name Variant Search](#username-and-identity-search) · [NASA Earthdata Search](#imagery-viewers-and-archives) · [NASA FIRMS](#analysis-and-event-monitoring) · [NASA Worldview](#imagery-viewers-and-archives) · [Naver](#search-engines-and-advanced-operators) · [Naver Map](#map-platforms) · [Navtex](#maritime-intelligence) · [Netcraft Site Report](#website-fingerprinting-and-connections) · [Netlas.io](#internet-wide-device-search) · [NHTSA VIN Decoder](#road-and-vehicles) · [NOAA Climate Data Online](#historical-weather) · [North Data](#company-registers-and-ownership)

**O** · [Obsidian](#notes-and-case-management) · [OCCRP Aleph Pro](#leaks-and-investigative-databases) · [OFAC Sanctions List Search](#sanctions-and-politically-exposed-persons) · [Ogimet](#historical-weather) · [OKLink](#block-explorers) · [Onyphe](#internet-wide-device-search) · [OpenAerialMap](#imagery-viewers-and-archives) · [OpenCorporates](#company-registers-and-ownership) · [Open ENF](#enf-electric-network-frequency-analysis) · [Open Measures](#monitoring-and-cross-platform-analysis) · [Open Ownership](#company-registers-and-ownership) · [OpenRailwayMap](#rail) · [OpenRefine](#documents-and-data-wrangling) · [OpenSanctions](#sanctions-and-politically-exposed-persons) · [OpenSecrets](#lobbying-and-political-finance) · [OpenSky Network](#aviation) · [Open Source Munitions Portal](#weapons-and-munitions-identification) · [OpenStreetMap](#map-platforms) · [OpenStreetMap (via Overpass Turbo)](#geolocation-aids) · [Open Supply Hub](#trade-and-supply-chains) · [Opentender](#procurement-and-public-spending) · [OrbTrack](#satellites-in-orbit) · [Oryx](#weapons-and-munitions-identification) · [OSINT Framework](#directories-and-meta-resources) · [OSINT Industries](#email-phone-and-people-lookup) · [OSoMeNet (formerly Hoaxy)](#monitoring-and-cross-platform-analysis) · [Overpass Ultra](#geolocation-aids) · [OWASP Amass](#recon-and-automation)

**P** · [PACER](#legal-and-court-records) · [Papago](#translation-and-language) · [PeakFinder](#geolocation-aids) · [PeakVisor](#geolocation-aids) · [Perma.cc](#public-web-archives) · [PimEyes](#facial-recognition) · [Pinpoint](#documents-and-data-wrangling) · [PixPlot](#image-collections-and-panoramas) · [Planespotters.net](#aviation) · [Planet Labs](#commercial-imagery) · [Plonk It](#geolocation-aids) · [Pray Times](#sun-moon-and-shadows) · [ProPublica Nonprofit Explorer](#charities-and-official-notices) · [PublicWWW](#website-fingerprinting-and-connections)

**Q** · [QGIS](#analysis-and-event-monitoring)

**R** · [RadarBox](#aviation) · [Radar Interference Tracker](#analysis-and-event-monitoring) · [RAMMB SLIDER](#imagery-viewers-and-archives) · [ransomware.live](#data-leaks-and-breach-intelligence) · [RAWGraphs](#charts-maps-and-timelines) · [Realtime Trains](#rail) · [recon-ng](#recon-and-automation) · [ReplayWeb.page](#capture-and-monitoring-tools) · [Resource Watch](#land-forests-and-emissions) · [RIPEstat](#ip-asn-and-routing) · [Robtex](#ip-asn-and-routing) · [RootAbout](#reverse-image-search) · [RuPEP](#sanctions-and-politically-exposed-persons)

**S** · [SanctionsExplorer](#sanctions-and-politically-exposed-persons) · [satellites.pro](#imagery-viewers-and-archives) · [Search4Faces](#facial-recognition) · [Search by Image (Extension)](#reverse-image-search) · [SecurityTrails](#whois-dns-and-certificates) · [Sentinel-2 Cloudless (EOX)](#imagery-viewers-and-archives) · [ShadeMap](#sun-moon-and-shadows) · [Shadow Finder](#sun-moon-and-shadows) · [ShadowMap](#sun-moon-and-shadows) · [Shazam](#speech-language-and-music-identification) · [Sherlock](#username-and-identity-search) · [Sherloq](#image-forensics-and-metadata) · [ShipFinder](#maritime-intelligence) · [ShipSpotting.com](#maritime-intelligence) · [Shodan](#internet-wide-device-search) · [Sightengine AI Image Detection](#ai-generated-and-synthetic-media-detection) · [SingleFile](#capture-and-monitoring-tools) · [SIPRI Arms Transfers Database](#weapons-and-munitions-identification) · [Skopenow](#monitoring-and-cross-platform-analysis) · [SkyFi](#commercial-imagery) · [Skylight](#maritime-intelligence) · [Snap Map](#location-based-platforms) · [Social Analyzer](#username-and-identity-search) · [Software Heritage Archive](#code-and-technical-search) · [Solscan](#block-explorers) · [Sonic Visualiser](#spectrogram-and-frequency-analysis) · [SoX (Sound eXchange)](#annotation-and-batch-processing) · [Species+](#wildlife-and-biodiversity) · [SpiderFoot](#recon-and-automation) · [Spleeter](#background-sound-isolation-and-enhancement) · [Strava Global Heatmap](#location-based-platforms) · [Subfinder](#recon-and-automation) · [SunCalc](#sun-moon-and-shadows) · [SunEarthTools](#sun-moon-and-shadows)

**T** · [Tableau Public](#charts-maps-and-timelines) · [TED – Tenders Electronic Daily](#procurement-and-public-spending) · [Telegago](#telegram) · [Telegram Phone Number Checker](#telegram) · [Telemetr.io](#telegram) · [Telepathy](#telegram) · [Tencent Maps](#map-platforms) · [TGStat](#telegram) · [That'sThem](#email-phone-and-people-lookup) · [The Gazette (UK)](#charities-and-official-notices) · [theHarvester](#recon-and-automation) · [The Information Laundromat](#website-fingerprinting-and-connections) · [Time and Date](#historical-weather) · [TimelineJS](#charts-maps-and-timelines) · [TinEye](#reverse-image-search) · [Trace Labs OSINT VM](#investigation-environments) · [Trase](#land-forests-and-emissions) · [Tronscan](#block-explorers) · [TrueCaller](#email-phone-and-people-lookup) · [TruffleHog](#code-and-technical-search) · [Tsurugi Linux](#investigation-environments) · [twtData X Trends Archive](#x-twitter)

**U** · [UCDP](#conflict-monitoring-and-documentation) · [UK CAA G-INFO](#aviation) · [UK Electoral Commission Political Finance](#lobbying-and-political-finance) · [UK Sanctions List Search](#sanctions-and-politically-exposed-persons) · [Umbra Space](#commercial-imagery) · [UN Comtrade Database](#trade-and-supply-chains) · [UNOSAT](#conflict-monitoring-and-documentation) · [UN Security Council Consolidated List](#sanctions-and-politically-exposed-persons) · [URLhaus](#threat-intelligence-and-reputation) · [urlscan.io](#website-fingerprinting-and-connections) · [USAspending](#procurement-and-public-spending) · [Uwazi](#notes-and-case-management)

**V** · [Validin](#threat-intelligence-and-reputation) · [VesselFinder](#maritime-intelligence) · [ViewDNS.info](#whois-dns-and-certificates) · [VirusTotal](#threat-intelligence-and-reputation) · [VLC Media Player](#video-analysis-and-verification)

**W** · [WalletExplorer](#tracing-attribution-and-risk) · [Wappalyzer](#website-fingerprinting-and-connections) · [War & Sanctions](#sanctions-and-politically-exposed-persons) · [Wayback Machine (Internet Archive)](#public-web-archives) · [Weather Underground History](#historical-weather) · [Web Scraper](#browser-extensions-and-scrapers) · [what3words](#geolocation-aids) · [What CMS](#website-fingerprinting-and-connections) · [WhatsMyName](#username-and-identity-search) · [Whisper (OpenAI)](#speech-language-and-music-identification) · [Who Posted What?](#facebook-and-instagram) · [Whoxy](#whois-dns-and-certificates) · [WiGLE](#geolocation-aids) · [Wikimapia](#map-platforms) · [Wikipedia: List of Company Registers](#directories-and-meta-resources) · [Wikipedia: List of Web Archiving Initiatives](#directories-and-meta-resources) · [Wildlife Trade Portal](#wildlife-and-biodiversity) · [Windy](#historical-weather) · [World Database on Protected Areas](#wildlife-and-biodiversity) · [World License Plates](#road-and-vehicles) · [World Port Index](#maritime-intelligence)

**X** · [xeno-canto](#environmental-and-bioacoustic-sound-identification) · [XTools](#monitoring-and-cross-platform-analysis) · [X (Twitter) Advanced Search](#x-twitter)

**Y** · [Yandex Images](#reverse-image-search) · [Yandex Maps](#map-platforms) · [Yandex Search](#search-engines-and-advanced-operators) · [Yandex Translate](#translation-and-language) · [YouTube Metadata](#reddit-youtube-and-linkedin) · [yt-dlp](#video-analysis-and-verification)

**Z** · [Zeeschuimer](#browser-extensions-and-scrapers) · [Zoom Earth](#imagery-viewers-and-archives) · [ZoomEye](#internet-wide-device-search) · [Zotero](#capture-and-monitoring-tools)

</details>

---

## Maps and Geolocation

Tools for mapping, geolocating imagery, and working with geographic data.

**Jump to:** [Map Platforms](#map-platforms) · [Street-Level and Crowdsourced Imagery](#street-level-and-crowdsourced-imagery) · [Geolocation Aids](#geolocation-aids) · [Coordinates and Map Utilities](#coordinates-and-map-utilities)

### Map Platforms

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Maps](https://maps.google.com) | The most widely used mapping platform. OSINT use: Street View for visual verification, historical imagery, measuring distances, identifying businesses and landmarks. | 🟢 Free |
| [Google Earth Pro](https://www.google.com/earth/versions/#earth-pro) | Desktop application with advanced satellite imagery, historical imagery timeline, 3D terrain, measurement tools, and GIS data import. Essential for geolocation and temporal analysis. | 🟢 Free |
| [Google Earth (web)](https://earth.google.com/web/) | Browser version of Google Earth with 3D buildings, measuring tools and historical imagery — no install needed. | 🟢 Free |
| [Bing Maps](https://www.bing.com/maps) | Microsoft's mapping platform with Bird's Eye View (oblique aerial imagery) not available on Google Maps. Useful for verifying angles and perspectives. | 🟢 Free |
| [Apple Maps](https://maps.apple.com) | Apple's mapping service with Look Around (street-level imagery). Sometimes has newer imagery than Google in certain areas. Web version available. | 🟢 Free |
| [OpenStreetMap](https://www.openstreetmap.org) | The open, community-edited world map. Inspect any feature's tags and edit history to see who mapped it and when. | 🟢 Free / 🔵 Open Source |
| [Yandex Maps](https://yandex.com/maps) | Russia's primary mapping platform. Crucial for investigations in Russia, CIS countries, and Turkey. Street-level panoramas and local business data. | 🟢 Free |
| [Baidu Maps](https://map.baidu.com) | China's dominant mapping platform. Essential for investigations involving Chinese locations. Includes Chinese street-level imagery and local business data. | 🟢 Free |
| [Gaode Maps (Amap)](https://www.amap.com) | China's second major mapping platform (Alibaba-owned). Detailed Chinese mapping data, traffic info, and POI data not on Western platforms. | 🟢 Free |
| [Tencent Maps](https://map.qq.com) | Tencent's mapping service. Useful for cross-referencing Chinese locations. Has its own street-level imagery. | 🟢 Free |
| [Naver Map](https://map.naver.com) | South Korea's leading map, with street-level imagery and local business data. Google's map data is limited in Korea, so use Naver or Kakao for Korean locations. | 🟢 Free |
| [Kakao Map](https://map.kakao.com) | Korean mapping service with Roadview street-level imagery and detailed local listings. | 🟢 Free |
| [2GIS](https://2gis.com) | Detailed city maps with building-level business directories, strongest in Russia, Central Asia and the Gulf. | 🟢 Free |
| [Mapy.com](https://mapy.com) | Czech mapping service (formerly Mapy.cz) with excellent outdoor and hiking maps and its own street-level panoramas across Central Europe. | 🟢 Free |
| [Wikimapia](https://wikimapia.org) | Collaborative mapping project where users annotate locations. Useful for identifying military bases, factories, and other sites described by locals. | 🟢 Free |
| [F4Map](https://demo.f4map.com) | Interactive 3D map rendering OpenStreetMap data. Useful for visualizing building heights, terrain, and urban layouts for geolocation verification. | 🟢 Free |
| [GovMap](https://www.govmap.gov.il) | Israel's official government mapping portal. Detailed cadastral data, aerial imagery, and infrastructure for Israeli territory. | 🟢 Free |

### Street-Level and Crowdsourced Imagery

| Tool | Description | Pricing |
|------|-------------|---------|
| [Mapillary](https://www.mapillary.com) | Crowdsourced street-level imagery (Meta-owned). Covers areas Google Street View doesn't. Images are timestamped and geotagged. | 🟢 Free |
| [KartaView](https://kartaview.org) | Crowdsourced street-level photo platform. Ground-level imagery, especially in Eastern Europe and areas with sparse Google coverage. | 🟢 Free |
| [Geograph](https://www.geograph.org.uk) | Project to photograph every 1 km grid square of Britain and Ireland — millions of geolocated, dated photos to compare against. | 🟢 Free |
| [Flickr Map](https://www.flickr.com/map) | Map of geotagged Flickr photos. Browse an area to find dated photos of a location, often going back many years. | 🟢 Free |

### Geolocation Aids

| Tool | Description | Pricing |
|------|-------------|---------|
| [GeoHints](https://geohints.com) | A reference guide for GeoGuessr-style geolocation. Clues by country: road markings, bollards, utility poles, signage. Invaluable for image geolocation. | 🟢 Free |
| [Plonk It](https://www.plonkit.net) | Country-by-country guides to geolocation clues (road markings, poles, signs, number plates) written for GeoGuessr players. | 🟢 Free |
| [OpenStreetMap (via Overpass Turbo)](https://overpass-turbo.eu) | Query and extract specific features from OpenStreetMap's open database. Search building types, infrastructure, and POIs by attribute. Extremely powerful for targeted geolocation. | 🟢 Free / 🔵 Open Source |
| [Overpass Ultra](https://overpass-ultra.us) | A modern Overpass Turbo alternative with MapLibre rendering, shareable queries, and improved styling. Handy for infrastructure-pattern geolocation. | 🟢 Free / 🔵 Open Source |
| [Bellingcat OpenStreetMap Search](https://osm-search.bellingcat.com) | Bellingcat's tool for searching OpenStreetMap data by object type and location. Simplifies complex Overpass queries into a friendly interface. | 🟢 Free |
| [PeakFinder](https://www.peakfinder.com) | Renders the mountain skyline from any viewpoint and names the peaks. Match a photo's horizon to find where it was taken. | 🟢 Free (web) / 🔴 Paid (app) |
| [PeakVisor](https://peakvisor.com) | Mountain and terrain identification. Match mountain silhouettes to geolocate photos taken in mountainous areas. | 🟡 Freemium |
| [WiGLE](https://wigle.net) | Crowdsourced database of Wi-Fi, cell, and Bluetooth networks mapped worldwide by BSSID/MAC. Geolocate a device or router by its network identifier — powerful for wireless-signal OSINT. | 🟢 Free (account required) |
| [AllTrails](https://www.alltrails.com) | Hiking and trail maps. Identify trails and paths visible in imagery; user-uploaded geotagged photos add ground-level context. | 🟡 Freemium |
| [MapChecking](https://www.mapchecking.com) | Estimate crowd sizes by drawing an area on a map and adjusting crowd density. Used by journalists to verify protest/rally attendance claims. | 🟢 Free |
| [what3words](https://what3words.com) | Divides the world into 3m x 3m squares, each with a unique 3-word address. Used in emergency services and can help pinpoint exact locations. | 🟢 Free (basic) / 🟡 Freemium (API) |

### Coordinates and Map Utilities

| Tool | Description | Pricing |
|------|-------------|---------|
| [Convert Geographic Units](https://applications.pgc.umn.edu/convert/) | Convert between coordinate formats (decimal degrees, DMS, UTM, MGRS). Essential when working with coordinates from different sources. | 🟢 Free |
| [MapSwitcher](https://github.com/david-r-edgar/MapSwitcher) | ⚠️ Browser extension to switch between map services (Google, Bing, Yandex, etc.) for the same location with one click. The original Chrome Web Store release can no longer be installed; load it from source, or use the similar [OpenSwitchMaps](https://github.com/tankaru/OpenSwitchMaps) (Chrome/Firefox). | 🟢 Free / 🔵 Open Source |

> **See also:** [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation) for overhead imagery, [Weather, Time and Shadow Analysis](#weather-time-and-shadow-analysis) for working out *when* a photo was taken, and Instagram Location Search in [Facebook and Instagram](#facebook-and-instagram).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Satellite Imagery and Earth Observation

Access and analyze satellite imagery for change detection, infrastructure monitoring, and environmental analysis.

**Jump to:** [Imagery Viewers and Archives](#imagery-viewers-and-archives) · [Commercial Imagery](#commercial-imagery) · [Analysis and Event Monitoring](#analysis-and-event-monitoring)

### Imagery Viewers and Archives

| Tool | Description | Pricing |
|------|-------------|---------|
| [Copernicus Browser](https://browser.dataspace.copernicus.eu) | ESA/Copernicus Data Space Ecosystem browser — the current front-end for Sentinel-1/2/3/5P data, with time-lapse and analysis tools. Successor to Sentinel Hub Playground and EO Browser, whose web apps were retired on 20 March 2026. | 🟢 Free |
| [Esri World Imagery Wayback](https://livingatlas.arcgis.com/wayback/) | Every archived version of Esri's World Imagery basemap since 2014. Compare high-resolution imagery of the same spot across dozens of dates. | 🟢 Free |
| [Google Earth Timelapse](https://earthengine.google.com/timelapse/) | Annual cloud-free satellite mosaics from 1984 onwards as a zoomable time-lapse. Shows construction, deforestation and coastline change. | 🟢 Free |
| [Sentinel-2 Cloudless (EOX)](https://cloudless.eox.at/preview) | EOX's seamless, cloud-free global Sentinel-2 mosaics at 10 m resolution, released yearly — a clean baseline for spotting change. | 🟢 Free (non-commercial) |
| [NASA Worldview](https://worldview.earthdata.nasa.gov) | Near-real-time satellite imagery from NASA's fleet. Visualize fires, smoke plumes, flooding, and other events. Supports temporal comparison. | 🟢 Free |
| [Zoom Earth](https://zoom.earth) | Near-real-time weather satellite imagery, wildfire detections and storm tracking on a fast map. | 🟢 Free |
| [EOSDA LandViewer](https://eos.com/landviewer/) | Search, view and download free Sentinel and Landsat scenes and buy commercial high-resolution imagery, with on-the-fly index analysis. | 🟡 Freemium |
| [Earth Explorer (USGS)](https://earthexplorer.usgs.gov) | Free access to the USGS archive of Landsat imagery, aerial photos, and elevation data. Decades of historical imagery. | 🟢 Free |
| [NASA Earthdata Search](https://search.earthdata.nasa.gov) | Search and download NASA's Earth observation datasets (MODIS, VIIRS, Landsat and more). Free Earthdata login required for downloads. | 🟢 Free |
| [ASF Vertex](https://search.asf.alaska.edu) | Alaska Satellite Facility's search for radar (SAR) data, including every Sentinel-1 scene. SAR sees through cloud and at night. | 🟢 Free |
| [Earth Online (ESA)](https://earth.esa.int) | European Space Agency's platform for accessing Sentinel mission data and other ESA Earth observation datasets. | 🟢 Free |
| [OpenAerialMap](https://openaerialmap.org) | Open repository of publicly licensed aerial and satellite imagery. Includes drone imagery, post-disaster captures, and humanitarian mapping data. | 🟢 Free / 🔵 Open Source |
| [satellites.pro](https://satellites.pro) | Quick access to satellite imagery from Google, Bing, Yandex, and Esri in one interface. Convenient for rapid comparison. | 🟢 Free |
| [RAMMB SLIDER](https://rammb-slider.cira.colostate.edu) | Real-time weather satellite imagery viewer. Full-disk imagery from GOES, Himawari, and Meteosat. Useful for verifying weather conditions at specific times. | 🟢 Free |

### Commercial Imagery

| Tool | Description | Pricing |
|------|-------------|---------|
| [Planet Labs](https://www.planet.com) | Commercial constellation capturing daily imagery of the entire Earth at 3-5m resolution. Gold standard for monitoring change over time. | 🔴 Paid (journalist/NGO programs available) |
| [Umbra Space](https://umbra.space) | Commercial Synthetic Aperture Radar (SAR) provider. SAR penetrates clouds and captures imagery at night — essential when optical imagery is unavailable. Note: Umbra also releases an open SAR archive worth checking. | 🔴 Paid (open sample archive available) |
| [SkyFi](https://www.skyfi.com) | Marketplace for purchasing satellite imagery from multiple providers (Planet, Airbus, Maxar). Simplifies ordering high-resolution commercial imagery. | 🔴 Paid |
| [Apollo Mapping](https://apollomapping.com) | Satellite and aerial imagery broker offering access to imagery from 30+ providers. Useful for obtaining historical high-res imagery for specific dates. | 🔴 Paid |

### Analysis and Event Monitoring

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Earth Engine](https://earthengine.google.com) | Cloud platform for planetary-scale geospatial analysis. Access decades of satellite data (Landsat, Sentinel, MODIS) and run custom analyses. Used for environmental monitoring and change detection. | 🟢 Free (research/non-commercial) |
| [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov) | Fire Information for Resource Management System. Detect active fires and thermal anomalies worldwide in near-real-time via MODIS and VIIRS. Used to verify conflict/fire events. | 🟢 Free |
| [Copernicus Emergency Management Service](https://emergency.copernicus.eu) | EU rapid-mapping service publishing satellite-based damage and flood-extent maps after disasters such as floods, fires and earthquakes. | 🟢 Free |
| [Google Flood Hub](https://sites.research.google/floods/) | Google's AI-powered flood forecasting platform. Visualize flood predictions and historical flood data for river basins globally. | 🟢 Free |
| [Radar Interference Tracker](https://ollielballinger.users.earthengine.app/view/interference) | Detect GPS/radar jamming and interference by analyzing Sentinel-1 SAR data. Reveals military electronic warfare activity. Built by Ollie Ballinger. | 🟢 Free |
| [GPSJam](https://gpsjam.org) | Visualize GPS interference and jamming zones worldwide using ADS-B aircraft data. Reveals areas of electronic warfare or intentional disruption. | 🟢 Free |
| [QGIS](https://qgis.org) | Professional open-source GIS. Full GIS analysis, custom map creation, spatial data processing. The open-source alternative to ArcGIS. | 🟢 Free / 🔵 Open Source |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Weather, Time and Shadow Analysis

Verify timestamps, analyze lighting, and work out when (and where) photos and videos were taken.

**Jump to:** [Sun, Moon and Shadows](#sun-moon-and-shadows) · [Historical Weather](#historical-weather)

### Sun, Moon and Shadows

| Tool | Description | Pricing |
|------|-------------|---------|
| [SunCalc](https://www.suncalc.org) | Calculate sun position, golden hour, and sunrise/sunset for any location and date. Essential for chronolocation from sun position. | 🟢 Free |
| [SunEarthTools](https://www.sunearthtools.com) | Sun position, shadow length and sun-path diagrams for any place and time — an alternative to SunCalc for chronolocation. | 🟢 Free |
| [MoonCalc](https://www.mooncalc.org) | Moon position, phase, and moonrise and moonset times for any location and date. Useful for night-time photos. | 🟢 Free |
| [Shadow Finder](https://github.com/bellingcat/ShadowFinder) | Bellingcat tool that maps every place on Earth where an object of known height would cast a shadow of a given length at a given time. Run it in the browser via the Colab button in the README, or locally in Python. | 🟢 Free / 🔵 Open Source |
| [ShadowMap](https://app.shadowmap.org/) | 3D shadow simulation for any location and time. Visualize how buildings and terrain cast shadows through the day. Free web app; paid Shadowmap Studio for professional use. | 🟡 Freemium |
| [ShadeMap](https://shademap.app) | Interactive shade/shadow visualization on a 3D globe. Calculate shadow coverage at any moment for geolocation and chronolocation. | 🟢 Free |
| [Pray Times](https://praytimes.org) | Calculate Islamic prayer (azan) times for any location and date. Azan in a recording can pinpoint both time and region with precision. | 🟢 Free |

### Historical Weather

| Tool | Description | Pricing |
|------|-------------|---------|
| [Time and Date](https://www.timeanddate.com) | Historical weather, sun/moon data, and time-zone lookups for any location and date. Useful for corroborating weather claims in media. | 🟢 Free |
| [Weather Underground History](https://www.wunderground.com/history) | Historical observations from airports and personal weather stations, often at hourly or finer resolution. | 🟢 Free |
| [Meteostat](https://meteostat.net) | Open historical weather and climate data from thousands of stations, with charts and downloads. | 🟢 Free |
| [Ogimet](https://www.ogimet.com) | Archive of raw meteorological reports (SYNOP, METAR) from stations worldwide — useful where other sites lack history. | 🟢 Free |
| [NOAA Climate Data Online](https://www.ncei.noaa.gov/cdo-web/) | NOAA's archive of historical weather-station data worldwide, including daily summaries and storm events. | 🟢 Free |
| [LightningMaps](https://www.lightningmaps.org) | Real-time and archived lightning strikes from the Blitzortung community network. Check claims of storms at a given time and place. | 🟢 Free |
| [Windy](https://www.windy.com) | Interactive weather-model maps (wind, rain, cloud, waves) with webcams and station data. | 🟡 Freemium |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Search Engines and Advanced Operators

General and regional search engines, plus operator references. Run important searches on more than one engine — each has its own index and blind spots.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Advanced Search](https://www.google.com/advanced_search) | Form-based builder for Google operators: exact phrases, `site:`, `filetype:`, language, region and last-updated filters. Add `before:` / `after:` to bound results by date. | 🟢 Free |
| [Bing](https://www.bing.com) | A separate index from Google that often surfaces different results. Supports useful operators such as `ip:` (sites hosted on an IP address), `inbody:` and `filetype:`. | 🟢 Free |
| [Yandex Search](https://yandex.com) | Russia's largest search engine, with better coverage of Russian- and Ukrainian-language sites, VK and regional media than Western engines. | 🟢 Free |
| [Baidu](https://www.baidu.com) | China's dominant search engine. Essential for Chinese-language sources, companies and news that Google indexes poorly. | 🟢 Free |
| [Naver](https://www.naver.com) | South Korea's leading search portal, including its blogs, cafés (forums) and news that rank poorly elsewhere. | 🟢 Free |
| [Brave Search](https://search.brave.com) | Privacy-focused search engine with its own independent index — a useful cross-check when Google and Bing return the same results. | 🟢 Free |
| [Mojeek](https://www.mojeek.com) | UK search engine with its own crawler and no tracking. Unpersonalised results show how a claim appears to a neutral searcher. | 🟢 Free |
| [Google Hacking Database](https://www.exploit-db.com/google-hacking-database) | Exploit-DB's catalogue of search queries ('dorks') that find exposed files, login pages and misconfigured servers. Learn operator patterns for your own searches. | 🟢 Free |
| [Google Alerts](https://www.google.com/alerts) | Email notifications when new pages match a query. Monitor names, companies or unique phrases over time. | 🟢 Free |
| [Google Trends](https://trends.google.com) | Shows how search interest in a term changes over time and by region — useful for dating when and where a story or narrative began spreading. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Social Media Intelligence

Tools for searching, monitoring, and analyzing social media platforms.

**Jump to:** [X (Twitter)](#x-twitter) · [Facebook and Instagram](#facebook-and-instagram) · [Bluesky and the Fediverse](#bluesky-and-the-fediverse) · [Reddit, YouTube and LinkedIn](#reddit-youtube-and-linkedin) · [Location-Based Platforms](#location-based-platforms) · [Advertising Transparency](#advertising-transparency) · [Monitoring and Cross-Platform Analysis](#monitoring-and-cross-platform-analysis)

### X (Twitter)

| Tool | Description | Pricing |
|------|-------------|---------|
| [X (Twitter) Advanced Search](https://x.com/search-advanced) | X's built-in advanced search: filter by words, accounts, dates, engagement and language for timeline reconstruction. X also documents location operators (`near:`, `within:`, `geocode:`), but since early 2026 some users report they return no results — test them before relying on them. | 🟢 Free (X account required) |
| [twtData X Trends Archive](https://twtdata.com/twitter-trends/) | Dated archive of what trended on X by country and city, one page per place and day, with each trend's best position and hours on the list where the location is tracked hourly. Useful for dating when a hashtag or narrative took off in a given country. | 🟢 Free (no account; follower and tweet CSV exports are paid) |

### Facebook and Instagram

| Tool | Description | Pricing |
|------|-------------|---------|
| [Who Posted What?](https://whopostedwhat.com) | Facebook keyword-by-date search by Henk van Ess. Surfaces historical public Facebook posts that native search hides. Requires being logged into a Facebook account. | 🟢 Free (donation-supported) |
| [Meta Content Library](https://transparency.meta.com/researchtools/meta-content-library) | Meta's official research API for public content across Facebook and Instagram. The sanctioned successor to CrowdTangle (which Meta shut down in 2024). Available to qualified researchers. | 🟢 Free (approved researchers) |
| [Instagram Location Search](https://github.com/bellingcat/instagram-location-search) | Bellingcat CLI tool to find Instagram location IDs near given coordinates. Still maintained; requires Instagram session cookies. Note: the old follow-on `instagram-scraper` no longer exists, so it's now mainly a location-ID lead generator. | 🟢 Free / 🔵 Open Source |

### Bluesky and the Fediverse

| Tool | Description | Pricing |
|------|-------------|---------|
| [Bluesky Social Graph (Jaz)](https://bsky.jazco.dev) | Engagement-based social graph for Bluesky. Visualize who interacts with whom to map communities and clusters around an account. | 🟢 Free |
| [BskyFollowFinder](https://bsky.thieflord.dev) | Bluesky network analysis. Find mutual connections, discover who your follows follow, and map relationships. | 🟢 Free |
| [ClearSky (Bluesky)](https://clearsky.app) | Bluesky account intelligence: block lists, who blocks whom, handle history, and list membership. Useful for network and moderation analysis. | 🟢 Free |
| [FediDB](https://fedidb.com) | Statistics and directory of Fediverse servers (Mastodon, Misskey, Pixelfed and more): software, size and activity. Useful for profiling an instance. | 🟢 Free |

### Reddit, YouTube and LinkedIn

| Tool | Description | Pricing |
|------|-------------|---------|
| [Arctic Shift](https://arctic-shift.photon-reddit.com) | Archive and search of Reddit posts and comments, including many later deleted. Fills much of the gap left by Pushshift. | 🟢 Free |
| [YouTube Metadata](https://mattw.io/youtube-metadata/) | Shows hidden details for any YouTube video, channel or playlist: exact upload time (UTC), tags, recording location where set, and every thumbnail size for reverse image search. | 🟢 Free |
| [MW Geofind](https://mattw.io/youtube-geofind/) | Search YouTube for videos uploaded near given coordinates, or scan channels for geotagged uploads — useful for finding footage of an event. Location search still works; channel and topic results are thinner since YouTube cut back location metadata. | 🟢 Free |
| [LinkedIn Post Timestamp Extractor](https://ollie-boyd.github.io/Linkedin-post-timestamp-extractor/) | Decodes a LinkedIn post or comment URL into its exact publication time (LinkedIn itself only shows '2w' or '3mo'). | 🟢 Free / 🔵 Open Source |

### Location-Based Platforms

| Tool | Description | Pricing |
|------|-------------|---------|
| [Snap Map](https://map.snapchat.com) | Snapchat's public map of geotagged Snaps worldwide. Real-time crowd-sourced video and photo from events, protests, and breaking news. | 🟢 Free |
| [Strava Global Heatmap](https://www.strava.com/heatmap) | Fitness platform with a global heatmap of exercise routes. Has revealed military bases, secret facilities, and personnel movement patterns. | 🟡 Freemium |

### Advertising Transparency

| Tool | Description | Pricing |
|------|-------------|---------|
| [Meta Ad Library](https://www.facebook.com/ads/library/) | Every active ad on Facebook, Instagram and Messenger, plus a seven-year archive of political and issue ads with spend and reach. Reveals who is paying to push a message. | 🟢 Free |
| [Google Ads Transparency Center](https://adstransparency.google.com) | Search ads run by any verified advertiser across Google Search, YouTube and display networks, including political ads. | 🟢 Free |

### Monitoring and Cross-Platform Analysis

| Tool | Description | Pricing |
|------|-------------|---------|
| [OSoMeNet (formerly Hoaxy)](https://osome.iu.edu/tools/osomenet/) | ⚠️ Indiana University OSoMe's tool for visualizing how information spreads across multiple social platforms. Hoaxy's functionality now lives here, and the old Hoaxy address redirects to it. | 🟢 Free |
| [Open Measures](https://openmeasures.io) | Search and analyze content from fringe and alt-tech platforms (Telegram, 4chan, Gab and more). The free public app and API cover data at least 6 months old with a daily request limit; Pro and Enterprise plans are paid. Formerly the Social Media Analysis Toolkit (SMAT). | 🟡 Freemium |
| [Skopenow](https://www.skopenow.com) | Professional social media and web investigation platform. Automated collection and analysis across platforms with reporting. | 🔴 Paid |
| [XTools](https://xtools.wmcloud.org) | Wikimedia's analytics for Wikipedia pages and editors: who wrote a page, its edit history and top editors. Helps spot paid or reputation-management editing. | 🟢 Free / 🔵 Open Source |

> **See also:** [Messaging and Forums](#messaging-and-forums) for Telegram and Discord, and [Browser Extensions and Scrapers](#browser-extensions-and-scrapers) for Zeeschuimer, 4CAT and Instaloader.

<sub>[⬆ Back to contents](#contents)</sub>

---

## Messaging and Forums

Investigate Telegram, Discord, forums, and other communication channels.

**Jump to:** [Telegram](#telegram) · [Discord](#discord) · [Forums and Imageboards](#forums-and-imageboards)

### Telegram

| Tool | Description | Pricing |
|------|-------------|---------|
| [Telegago](https://cse.google.com/cse?cx=006368593537057042503:efxu7xprihg) | Google Custom Search Engine focused on Telegram content. Search channels and groups via indexed web content. | 🟢 Free |
| [TGStat](https://tgstat.com) | Telegram analytics. Search channels/groups; view subscriber growth, engagement, and cross-posting patterns. | 🟡 Freemium |
| [Telemetr.io](https://telemetr.io) | Telegram channel analytics. Track subscriber dynamics, post reach, engagement, and content patterns. | 🟡 Freemium |
| [Telepathy](https://github.com/prose-intelligence-ltd/Telepathy-Community) | ⚠️ OSINT toolkit for Telegram investigations: extract members, messages and media from groups and channels. Limited maintenance — the last release (2.3.4) dates from July 2024 and the README warns that installing from source is broken, so use a published release. | 🟢 Free / 🔵 Open Source |
| [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker) | Bellingcat tool to check whether phone numbers are associated with Telegram accounts and retrieve usernames. | 🟢 Free / 🔵 Open Source |

> **Tip:** Public Telegram channels can be read in a browser without an account at `https://t.me/s/<channel_name>`.

### Discord

| Tool | Description | Pricing |
|------|-------------|---------|
| [discord.id](https://discord.id/) | Decodes a Discord user ID into its account creation date and shows the public avatar, banner and badges. Discord IDs are 'snowflakes', so you can also do it by hand: (ID ÷ 4194304) + 1420070400000 = creation time in Unix milliseconds. | 🟢 Free |
| [Disboard](https://disboard.org) | Public directory of Discord servers searchable by tag and language — find communities around a topic. | 🟢 Free |

### Forums and Imageboards

| Tool | Description | Pricing |
|------|-------------|---------|
| [4plebs](https://4plebs.org) | Archive of several 4chan boards (/pol/, /x/, /sp/, etc.), searchable by keyword, date, and image hash. Useful for tracking extremist content and disinformation origins. | 🟢 Free |

> **See also:** DiscordChatExporter in [Browser Extensions and Scrapers](#browser-extensions-and-scrapers) and DiscordLeaks in [Data Leaks and Breach Intelligence](#data-leaks-and-breach-intelligence).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Username and Identity Search

Find accounts and digital footprints across platforms.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Search for usernames across 400+ social networks simultaneously. The most popular OSINT username enumeration tool. | 🟢 Free / 🔵 Open Source |
| [Maigret](https://github.com/soxoj/maigret) | Advanced username search across 3,000+ sites. A powerful Sherlock evolution with profile page parsing and identifier extraction. | 🟢 Free / 🔵 Open Source |
| [WhatsMyName](https://whatsmyname.app) | Username enumeration checking 600+ websites, maintained with a focus on reducing false positives. Also powers many other tools' site lists. | 🟢 Free / 🔵 Open Source |
| [Blackbird](https://github.com/p1ngul1n0/blackbird) | Fast username (and email) search across hundreds of sites, with metadata extraction and reporting. | 🟢 Free / 🔵 Open Source |
| [Social Analyzer](https://github.com/qeeqbox/social-analyzer) | Finds a profile across 1,000+ sites and rates its confidence in each match. CLI or web interface. | 🟢 Free / 🔵 Open Source |
| [Instant Username Search](https://instantusername.com) | Checks a handle across 100+ platforms as you type — a quick first pass before running Sherlock or Maigret. | 🟢 Free |
| [Namechk](https://namechk.com) | Check username and domain availability across dozens of platforms at once. Quick way to map a person's online presence. | 🟢 Free |
| [Name Variant Search](https://bellingcat.github.io/name-variant-search/) | Bellingcat tool that generates common variations of a person's name (spellings, initials, ordering) and builds search queries from them. Essential when searching across languages and alphabets. | 🟢 Free / 🔵 Open Source |
| [GHunt](https://github.com/mxrch/GHunt) | Google account investigation tool. Extracts data from a Google account/email (profile, Maps reviews, calendar, etc.). Requires authenticated cookies. Actively maintained. | 🟢 Free / 🔵 Open Source |
| [IDCrawl](https://www.idcrawl.com) | Aggregated people/username search pulling social profiles, phone, email, and public records into one view. Good quick pivot from a username or real name. No sign-up required. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Email, Phone and People Lookup

Investigate email addresses and phone numbers, trace where emails came from, and find people.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Epieos](https://epieos.com) | Reverse email and phone lookup. Reveals connected Google account data, linked services, and profiles from a single address. One of the most-used email OSINT tools today. | 🟡 Freemium |
| [Holehe](https://github.com/megadose/holehe) | CLI tool that checks whether an email is registered on 120+ sites via password-reset/registration flows, usually without alerting the target. | 🟢 Free / 🔵 Open Source |
| [Hunter.io](https://hunter.io) | Find and verify professional email addresses associated with a domain. Useful for mapping an organization's staff. | 🟡 Freemium |
| [OSINT Industries](https://osint.industries) | Commercial email/phone/username enrichment returning linked accounts across hundreds of services. Popular with professional investigators. | 🔴 Paid (limited free trial) |
| [Castrick Clues](https://castrickclues.com) | Email, username and phone lookups with a clean web interface; free searches plus paid credits and an API. | 🟡 Freemium |
| [MXToolbox](https://mxtoolbox.com) | Email and DNS diagnostics: MX, SPF and DMARC records, blacklist checks, and an email header analyzer that traces which servers handled a message. | 🟡 Freemium |
| [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/) | Paste raw email headers to see each relay hop, delays and authentication results — useful for checking whether an email was spoofed. | 🟢 Free |
| [TrueCaller](https://www.truecaller.com) | Identify unknown phone numbers via a crowdsourced caller-ID database of hundreds of millions of users. Reverse phone lookup. | 🟡 Freemium |
| [Hitta.se](https://www.hitta.se) | Swedish person and business search. Find individuals, phone numbers, and addresses in Sweden's public records. | 🟢 Free |
| [That'sThem](https://thatsthem.com) | US reverse lookup by name, email, phone, address, or IP. A free starting point for US-based people search; paid plans add more daily queries. | 🟡 Freemium |

> **See also:** Telegram Phone Number Checker in [Messaging and Forums](#messaging-and-forums), and breach-exposure checks in [Data Leaks and Breach Intelligence](#data-leaks-and-breach-intelligence).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Facial Recognition

Tools for face matching and comparison.

| Tool | Description | Pricing |
|------|-------------|---------|
| [PimEyes](https://pimeyes.com) | Reverse face search engine. Upload a face photo to find where that face appears online. Extremely powerful and controversial. | 🟡 Freemium (limited free) / 🔴 Paid |
| [FaceCheck.ID](https://facecheck.id) | Reverse face search across social media, mugshots, and news. Alternative to PimEyes with different source databases. | 🟡 Freemium |
| [Search4Faces](https://search4faces.com) | Facial recognition focused on Russian/CIS networks (VK, OK.ru) plus older TikTok and ClubHouse avatars. Over a billion indexed faces, though databases aren't updated in real time. | 🟢 Free (limited) / 🟡 Freemium |
| [Face Comparison by ToolPie](https://facecomparison.toolpie.com) | Compare two face photos and get a similarity score. Free, browser-based, no account needed — a quick first pass, never proof of identity. | 🟢 Free |

> ⚠️ Face search is error-prone and can expose private people. Treat any match as a lead to verify independently, and check the legal limits where you work.

<sub>[⬆ Back to contents](#contents)</sub>

---

## Reverse Image Search and Image Forensics

Trace the origin of images, detect manipulation, and read hidden metadata.

**Jump to:** [Reverse Image Search](#reverse-image-search) · [Image Forensics and Metadata](#image-forensics-and-metadata) · [Image Collections and Panoramas](#image-collections-and-panoramas)

### Reverse Image Search

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Lens](https://lens.google.com) | Google's visual search. Identify objects, landmarks, text, and find visually similar images. Also extracts text (OCR). | 🟢 Free |
| [Yandex Images](https://yandex.com/images/) | Widely regarded as the strongest reverse image engine for faces and locations, especially in Eastern Europe. A staple first stop for geolocation. | 🟢 Free |
| [Bing Visual Search](https://www.bing.com/visualsearch) | Microsoft's reverse image search. Its index differs from Google's and Yandex's, so it is worth running every time. | 🟢 Free |
| [TinEye](https://tineye.com) | Dedicated reverse image search. Finds exact and modified matches. Its "oldest" sort shows the first known appearance of an image online. | 🟢 Free (basic) / 🔴 Paid (API) |
| [Baidu Image Search](https://image.baidu.com) | Reverse image search with strong coverage of Chinese websites and platforms. | 🟢 Free |
| [Search by Image (Extension)](https://github.com/dessant/search-by-image) | Browser extension to right-click any image and reverse-search it across Google, Yandex, TinEye, Bing, and more at once. | 🟢 Free / 🔵 Open Source |
| [RootAbout](https://rootabout.com) | Reverse image search against Internet Archive collections (plus an Open Library book-cover search). Finds near-identical copies only, and searches can be slow or fail intermittently. | 🟢 Free |

### Image Forensics and Metadata

| Tool | Description | Pricing |
|------|-------------|---------|
| [Forensically](https://29a.ch/photo-forensics/) | Browser-based image forensics: Error Level Analysis (ELA), clone detection, metadata extraction, noise analysis. Helps detect manipulation. | 🟢 Free |
| [FotoForensics](https://fotoforensics.com) | Long-running online ELA and metadata forensics service. A second opinion alongside Forensically for tampering analysis. | 🟢 Free |
| [Sherloq](https://github.com/GuidoBartoli/sherloq) | Open-source desktop toolkit that bundles many image-forensics methods (ELA, noise analysis, clone detection, JPEG analysis) in one interface. | 🟢 Free / 🔵 Open Source |
| [ExifTool](https://exiftool.org) | The gold standard for reading, writing, and editing metadata in image, video, and document files. Extract GPS coords, camera model, timestamps, and more. | 🟢 Free / 🔵 Open Source |
| [Jeffrey's Image Metadata Viewer](https://exif.regex.info/exif.cgi) | Long-running web tool that shows full EXIF, IPTC and XMP metadata for an uploaded image or image URL, with a map for GPS data. | 🟢 Free |

### Image Collections and Panoramas

| Tool | Description | Pricing |
|------|-------------|---------|
| [Hugin](https://hugin.sourceforge.io) | Open-source panoramic photo stitcher. Advanced control over alignment and projection — useful for reconstructing scenes from multiple photos. | 🟢 Free / 🔵 Open Source |
| [PixPlot](https://github.com/YaleDHLab/pix-plot) | Yale DHLab machine-learning tool for visualizing and clustering large image collections by visual similarity. (The old project page now redirects; use the GitHub repo.) | 🟢 Free / 🔵 Open Source |

> **See also:** the InVID / WeVerify plugin in [Video Analysis and Verification](#video-analysis-and-verification) (it handles images too) and [AI-Generated and Synthetic Media Detection](#ai-generated-and-synthetic-media-detection).

<sub>[⬆ Back to contents](#contents)</sub>

---

## AI-Generated and Synthetic Media Detection

Check whether images, video or audio were generated or altered by AI, and read provenance data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Content Credentials Verify](https://verify.contentauthenticity.org/) | Checks an image or video for C2PA Content Credentials — signed provenance data recording the capture device, editing software or AI generator. Missing credentials prove nothing; valid ones are strong evidence. | 🟢 Free |
| [Hive AI-Generated Content Detection](https://hivemoderation.com/ai-generated-content-detection) | Classifier that estimates whether an image, video, text or audio file was AI-generated. Free web demo and Chrome extension; paid API. | 🟡 Freemium |
| [AI or Not](https://www.aiornot.com) | AI-content checker for images, audio, video, text and deepfakes — a quick second opinion alongside Hive. | 🟡 Freemium |
| [Sightengine AI Image Detection](https://sightengine.com/detect-ai-generated-images) | Detects AI-generated and deepfake images with a probability score. Free account with limited checks; paid API. | 🟡 Freemium |
| [DeepFake-o-Meter](https://zinc.cse.buffalo.edu/ubmdfl/deep-o-meter/) | University at Buffalo's open platform that runs several academic deepfake-detection models on the same image, video or audio file so you can compare their verdicts. | 🟢 Free (account required) |

> ⚠️ AI detectors give probabilities, not proof, and are easily fooled by compression, cropping or newer models. Use them as one signal alongside reverse image search, metadata and source checks.

<sub>[⬆ Back to contents](#contents)</sub>

---

## Video Analysis and Verification

Analyze, verify, download, and extract data from video content.

| Tool | Description | Pricing |
|------|-------------|---------|
| [InVID / WeVerify Verification Plugin](https://weverify.eu/verification-plugin/) | The standard verification extension for journalists, now developed under the vera.ai project. Extracts keyframes from YouTube, Facebook and X videos, runs reverse image searches, and offers a magnifier, metadata reader and forensic filters. Some advanced tools (such as synthetic-image detection) need a verified-professional account. Install from the [Chrome Web Store](https://chromewebstore.google.com/detail/fake-news-debunker-invid/mhccpoafgdgbhnjfhkcmgknndkeenfhe). | 🟢 Free |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | The de-facto standard CLI downloader for YouTube and 1,000+ sites. Archive source video and metadata for offline analysis. Replaces the old youtube-dl/single-site downloaders. | 🟢 Free / 🔵 Open Source |
| [Cobalt](https://cobalt.tools) | Clean, no-ads web/CLI media downloader supporting X, TikTok, Instagram, YouTube and more. Useful for quickly preserving a specific clip. | 🟢 Free / 🔵 Open Source |
| [FFmpeg](https://ffmpeg.org) | Command-line toolkit to extract frames (`ffmpeg -i in.mp4 -vf fps=1 frame_%04d.png`), trim clips, convert formats and read stream metadata. | 🟢 Free / 🔵 Open Source |
| [VLC Media Player](https://www.videolan.org/vlc/) | Plays almost any format, with frame-by-frame stepping (E key), speed control, and Tools → Codec Information for stream metadata. | 🟢 Free / 🔵 Open Source |
| [Azure AI Video Indexer](https://vi.microsoft.com) | Microsoft's AI video analysis. Extracts faces, on-screen text (OCR), objects, scenes, transcription, and sentiment. Free account covers up to 40 indexing hours. | 🟡 Freemium / 🔴 Paid |

> **See also:** YouTube Metadata and MW Geofind in [Reddit, YouTube and LinkedIn](#reddit-youtube-and-linkedin), and Ghost Archive for saving videos in [Archiving and Preservation](#archiving-and-preservation).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Audio Analysis and Acoustic OSINT

Tools for analyzing audio recordings to extract geolocation, environmental, and metadata intelligence. Acoustic OSINT is a rapidly evolving discipline used in Bellingcat-style challenges, conflict verification, and journalistic investigations.

> **Workflow overview:**
> `Metadata Extraction → ENF Grid Analysis → Spectrogram Visualization → Background Sound Isolation → Environmental Sound ID → Cross-reference & Geolocation`

**Jump to:** [Audio Metadata and File Forensics](#audio-metadata-and-file-forensics) · [Spectrogram and Frequency Analysis](#spectrogram-and-frequency-analysis) · [ENF (Electric Network Frequency) Analysis](#enf-electric-network-frequency-analysis) · [Environmental and Bioacoustic Sound Identification](#environmental-and-bioacoustic-sound-identification) · [Background Sound Isolation and Enhancement](#background-sound-isolation-and-enhancement) · [Speech, Language and Music Identification](#speech-language-and-music-identification) · [Background Event Cross-Reference](#background-event-cross-reference) · [Annotation and Batch Processing](#annotation-and-batch-processing)

### Audio Metadata and File Forensics

| Tool | Description | Pricing |
|------|-------------|---------|
| [MediaInfo](https://mediaarea.net/en/MediaInfo) | Detailed technical and tag information for audio/video files: codec, bitrate, channel layout, encoder version, container metadata. GUI and CLI. Useful for detecting re-encoded or tampered files. | 🟢 Free / 🔵 Open Source |
| [ffprobe](https://ffmpeg.org/ffprobe.html) | Part of FFmpeg. CLI tool for detailed stream/container metadata from any audio/video file. `ffprobe -v quiet -print_format json -show_format -show_streams file.mp3` | 🟢 Free / 🔵 Open Source |

> **ExifTool** (see [Image Forensics and Metadata](#image-forensics-and-metadata)) also reads tags from MP3, WAV, M4A, FLAC and OGG files — run `exiftool "file.mp3"`, wrapping paths that contain spaces in quotes.

### Spectrogram and Frequency Analysis

| Tool | Description | Pricing |
|------|-------------|---------|
| [Audacity](https://www.audacityteam.org) | The essential starting point. Use **Spectrogram view** for frequency-over-time, and **Plot Spectrum** (Analyze menu) for FFT. Set FFT size to 16384+ for high-resolution plots. Identify ENF hum, mechanical noise, and environmental signatures. Linux: `sudo apt install audacity`. | 🟢 Free / 🔵 Open Source |
| [Sonic Visualiser](https://www.sonicvisualiser.org) | Professional audio analysis with synchronized views (waveform, spectrogram, spectrum), a Vamp plugin system, and annotation layers. More powerful than Audacity for forensic-grade analysis. | 🟢 Free / 🔵 Open Source |
| [Adobe Audition](https://www.adobe.com/products/audition.html) | Professional DAW with advanced spectral frequency display and spectral repair tools. Useful for isolating specific sounds within a dense recording. | 🔴 Paid |
| [Friture](https://friture.org) | Real-time audio analyzer with spectrogram, spectrum, and octave-band views. Good for quick frequency profiling. Cross-platform, lightweight. | 🟢 Free / 🔵 Open Source |

### ENF (Electric Network Frequency) Analysis

ENF analysis compares the subtle fluctuation of the electrical hum in a recording (50 Hz or 60 Hz and harmonics) against historical grid-frequency data to estimate **when and where** a recording was made. 50 Hz = Europe, most of Asia, Africa and Australia. 60 Hz = North America, parts of South America, South Korea, Taiwan, Saudi Arabia and western Japan.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Open ENF](https://github.com/openenf/openenf) | ⚠️ Open-source CLI that extracts the ENF signal from a `.wav` file and matches it against downloaded grid-frequency data to estimate when it was recorded. Beta software; currently covers the Central European and GB grids only, and works best on recordings of ~3 minutes or more. | 🟢 Free / 🔵 Open Source |
| [ENF Fingerprinting Tool](https://github.com/GalenReich/enf_fingerprinting_tool) | ⚠️ Browser-based ENF prototype built as part of Bellingcat community work (see also [ENFormant](https://github.com/CargoCultScientist/ENFormant)). Good for learning the technique; its author says it should not yet be used for real investigations. | 🟢 Free / 🔵 Open Source |

> **Manual check in Audacity:** Analyze → Plot Spectrum, set the FFT size to 16384 and use a linear frequency axis. A sharp peak at exactly 50 Hz or 60 Hz (plus harmonics at 100/150 Hz or 120/180 Hz) confirms a grid-connected recording and indicates the continent.

### Environmental and Bioacoustic Sound Identification

| Tool | Description | Pricing |
|------|-------------|---------|
| [BirdNET Analyzer](https://github.com/birdnet-team/BirdNET-Analyzer) | Cornell Lab / Chemnitz University's open-source bird-sound recognition engine. Batch-analyze long recordings from the CLI for timestamped species detections. Species ranges can narrow location. The third-party `birdnetlib` package is a handy Python wrapper. | 🟢 Free / 🔵 Open Source |
| [BirdNET Web Demo](https://birdnet.cornell.edu/demo/) | Cornell Lab's in-browser BirdNET: identify bird species from a short clip, with the audio processed locally (nothing is uploaded) — handy when evidence must stay private. A mobile app with live detections is at [birdnet.cornell.edu/app](https://birdnet.cornell.edu/app/). | 🟢 Free |
| [Merlin Bird ID](https://merlin.allaboutbirds.org) | Mobile app with Sound ID. Identifies bird species in real time; cross-reference with range maps to constrain location. | 🟢 Free |
| [xeno-canto](https://xeno-canto.org) | Crowdsourced database of 800,000+ bird recordings mapped by species and location. Compare unknown calls against confirmed recordings filtered by region. | 🟢 Free |
| [iNaturalist](https://www.inaturalist.org) | AI species identification from audio and images, covering insects, amphibians, and more. Constrain location to a species' known range. | 🟢 Free |
| [Freesound](https://freesound.org) | Community audio database with 500,000+ sounds tagged by type and location. Find reference recordings of specific environments (stations, markets, squares) to compare against your sample. | 🟢 Free |

### Background Sound Isolation and Enhancement

| Tool | Description | Pricing |
|------|-------------|---------|
| [Demucs](https://github.com/adefossez/demucs) | ⚠️ Open-source source-separation model (originally Meta's). Split a recording into stems, or isolate speech from ambient background. Runs locally via Python. The Meta repo was archived in January 2025; the author's fork receives only critical fixes. | 🟢 Free / 🔵 Open Source |
| [Spleeter](https://github.com/deezer/spleeter) | Deezer's open-source separation library (2/4/5 stems) for isolating ambient sound from foreground speech. Legacy: the latest release (v2.3.0) is several years old, so prefer Demucs for new work. | 🟢 Free / 🔵 Open Source |
| [Adobe Podcast Enhance](https://podcast.adobe.com/enhance) | AI speech enhancement that removes background noise. Web-based, no install. Useful for cleaning a recording before analysis. | 🟢 Free (web) |

> **Audacity:** Effect → Noise Reduction removes steady background noise so intermittent sounds stand out. Combine it with high- and low-pass filters to separate speech (300–3400 Hz), traffic and machinery (low frequencies) and birds or insects (high frequencies).

### Speech, Language and Music Identification

| Tool | Description | Pricing |
|------|-------------|---------|
| [Whisper (OpenAI)](https://github.com/openai/whisper) | State-of-the-art open-source speech recognition and language detection. Transcribes and auto-detects language even in noisy recordings. `pip install openai-whisper`. A crucial first step when voices are present. | 🟢 Free / 🔵 Open Source |
| [Shazam](https://www.shazam.com) | Identify music in the background of a recording. Background music can reveal broadcast source, country, or venue. | 🟢 Free |
| [AHA Music (Extension)](https://www.aha-music.com) | Browser extension that identifies music playing on your computer in real time. Play the file and let it detect recognizable music. | 🟢 Free |

### Background Event Cross-Reference

Heard something identifiable in the background? Check it against the recording's claimed time and place:

- **Aircraft** → flight history in [Aviation](#aviation) (ADS-B Exchange, Flightradar24, FlightAware)
- **Ship horns or engines** → vessel positions in [Maritime Intelligence](#maritime-intelligence)
- **Call to prayer (azan)** → Pray Times in [Sun, Moon and Shadows](#sun-moon-and-shadows)
- **Thunder, rain or wind** → archives in [Historical Weather](#historical-weather)

### Annotation and Batch Processing

| Tool | Description | Pricing |
|------|-------------|---------|
| [ELAN](https://archive.mpi.nl/tla/elan) | Linguistic annotation tool from the Max Planck Institute. Create time-coded annotations on audio/video — useful for systematically documenting every sound event. | 🟢 Free |
| [SoX (Sound eXchange)](http://sox.sourceforge.net) | The "Swiss Army knife" of terminal audio processing. Convert formats, apply filters, measure statistics, and batch-process. `sox file.mp3 -n stat` gives a statistical summary. | 🟢 Free / 🔵 Open Source |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Corporate and Financial Intelligence

Investigate companies, beneficial ownership, trade relationships, and financial data.

**Jump to:** [Company Registers and Ownership](#company-registers-and-ownership) · [Leaks and Investigative Databases](#leaks-and-investigative-databases) · [Trade and Supply Chains](#trade-and-supply-chains)

### Company Registers and Ownership

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenCorporates](https://opencorporates.com) | The world's largest open database of companies — 200M+ records from 140+ jurisdictions. Free basic search; bulk/API requires subscription. | 🟡 Freemium |
| [Companies House (UK)](https://find-and-update.company-information.service.gov.uk) | UK's official company register. Free filings, directors, ownership (PSC), and financial statements for all UK companies. Free public API. | 🟢 Free |
| [GLEIF LEI Search](https://search.gleif.org) | Global Legal Entity Identifier database: a company's LEI record, registered address and — where reported — its direct and ultimate parent companies. | 🟢 Free |
| [North Data](https://www.northdata.com) | European company information: beneficial ownership, financials, network graphs, and corporate hierarchies for EU companies. | 🟡 Freemium / 🔴 Paid |
| [EU Business Registers (e-Justice)](https://e-justice.europa.eu/489/EN/business_registers__search_for_a_company_in_the_eu) | Access point for company registers across EU member states, with direct links to each country's official register. | 🟢 Free |
| [EDGAR (SEC)](https://www.sec.gov/edgar) | US SEC database. All public company filings including annual reports, insider trading, and ownership disclosures. | 🟢 Free |
| [EDGAR Full-Text Search](https://www.sec.gov/edgar/search/) | Full-text search across SEC EDGAR filings since 2001. Search names, companies, or terms across millions of documents. | 🟢 Free |
| [Open Ownership](https://www.openownership.org) | Beneficial-ownership transparency organisation. Its global Open Ownership Register closed on 29 November 2024; use the site for guidance and links to national beneficial-ownership registers, and its [bulk data](https://bods-data.openownership.org) for research. | 🟢 Free |
| [Crunchbase](https://www.crunchbase.com) | Company profiles with funding rounds, investors, acquisitions and key people — strongest for start-ups and private tech firms. | 🟡 Freemium |
| [LittleSis](https://littlesis.org) | Free database mapping relationships between powerful people and organizations. Visualize corporate boards, political connections, and influence networks. | 🟢 Free |

### Leaks and Investigative Databases

| Tool | Description | Pricing |
|------|-------------|---------|
| [ICIJ Offshore Leaks Database](https://offshoreleaks.icij.org) | Searchable database from Panama, Paradise, and Pandora Papers and other leaks. Explore offshore entities, intermediaries, and beneficial owners. | 🟢 Free |
| [OCCRP Aleph Pro](https://aleph.occrp.org) | OCCRP's investigative data platform, relaunched as Aleph Pro in December 2025 at the same address. Search leaked databases, company registries, court records and other sources. Public datasets are open to everyone; an account with wider access requires an application (free for nonprofit journalists). | 🟢 Free (public data) / 🟡 Account by application |

### Trade and Supply Chains

| Tool | Description | Pricing |
|------|-------------|---------|
| [ImportYeti](https://www.importyeti.com) | Free US import/export customs record search. Find suppliers and buyers. A good free alternative to paid trade-data tools. | 🟢 Free |
| [ImportGenius](https://www.importgenius.com) | Search US and international import/export shipping records. Track supply chains, trading partners, and smuggling. | 🔴 Paid |
| [UN Comtrade Database](https://comtradeplus.un.org) | UN international trade statistics. Bilateral trade flows between countries for specific commodities. Detect sanctions-evasion patterns. | 🟢 Free |
| [Open Supply Hub](https://opensupplyhub.org) | Open map of production facilities worldwide (factories, farms, processing sites) contributed by brands and suppliers. Link products and brands to specific sites. | 🟢 Free |

> **See also:** [Public Records, Procurement and Lobbying](#public-records-procurement-and-lobbying), [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons), and the list of company registers in [Directories and Meta-Resources](#directories-and-meta-resources).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Public Records, Procurement and Lobbying

Follow public money and influence: procurement notices, government spending, lobbying and political-finance registers, charities, and official notices.

**Jump to:** [Procurement and Public Spending](#procurement-and-public-spending) · [Lobbying and Political Finance](#lobbying-and-political-finance) · [Charities and Official Notices](#charities-and-official-notices)

### Procurement and Public Spending

| Tool | Description | Pricing |
|------|-------------|---------|
| [TED – Tenders Electronic Daily](https://ted.europa.eu/en/) | The EU's official public-procurement journal. Search contract notices and award decisions across member states to see who wins public contracts and for how much. | 🟢 Free |
| [Opentender](https://opentender.eu) | Procurement-data portal from the DIGIWHIST project covering EU member states and several other countries, with integrity indicators (such as single bidding) for spotting risky tenders. | 🟢 Free |
| [EU Financial Transparency System](https://ec.europa.eu/budget/financial-transparency-system/) | European Commission database of who received money from the EU budget, how much, and for what — trace EU grants and contracts to companies and NGOs. | 🟢 Free |
| [USAspending](https://www.usaspending.gov) | Official source for US federal spending: contracts, grants and loans searchable by recipient, agency and location. | 🟢 Free |
| [Find a Tender (UK)](https://www.find-tender.service.gov.uk) | UK government service where public-sector buyers publish procurement notices and contract awards. | 🟢 Free |

### Lobbying and Political Finance

| Tool | Description | Pricing |
|------|-------------|---------|
| [EU Transparency Register](https://transparency-register.europa.eu/index_en) | Official register of organisations lobbying EU institutions, with declared budgets, staff and interests. | 🟢 Free |
| [LobbyFacts](https://www.lobbyfacts.eu) | Tracks the EU Transparency Register over time, including historical entries and meetings with Commission officials. Run by Corporate Europe Observatory and LobbyControl. | 🟢 Free |
| [OpenSecrets](https://www.opensecrets.org) | US political spending and lobbying data. Track campaign donations, lobbying expenditures, and financial influence on US politics. | 🟢 Free |
| [FEC Campaign Finance Data](https://www.fec.gov/data/) | US Federal Election Commission data on money raised and spent by federal candidates, parties and PACs, including itemised contributions. | 🟢 Free |
| [UK Electoral Commission Political Finance](https://search.electoralcommission.org.uk) | Search donations, loans and spending reported by UK political parties, candidates and campaigners. | 🟢 Free |
| [FARA eFile](https://efile.fara.gov/ords/fara/f?p=1381:1) | US Department of Justice filings under the Foreign Agents Registration Act: who lobbies or does PR in the US for foreign governments and parties, and what they are paid. | 🟢 Free |

### Charities and Official Notices

| Tool | Description | Pricing |
|------|-------------|---------|
| [ProPublica Nonprofit Explorer](https://projects.propublica.org/nonprofits/) | Search US tax-exempt organisations and their IRS Form 990 filings: revenue, executive pay and grants. | 🟢 Free |
| [Charity Commission Register](https://register-of-charities.charitycommission.gov.uk) | Official register of charities in England and Wales, with trustees, accounts and linked charities. | 🟢 Free |
| [The Gazette (UK)](https://www.thegazette.co.uk) | The UK's official public record: insolvency notices, company strike-offs, deceased estates and other statutory notices. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Sanctions and Politically Exposed Persons

Check sanctions lists, PEP databases, and politically exposed individuals.

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenSanctions](https://www.opensanctions.org) | Unified database of international sanctions, PEPs, and persons of interest, aggregating 30+ official sources. Free and open source. | 🟢 Free / 🔵 Open Source |
| [OFAC Sanctions List Search](https://sanctionssearch.ofac.treas.gov) | US Treasury's official search of the SDN and other OFAC lists, with fuzzy name matching. Entries can include aliases, vessel IMO numbers and crypto addresses. | 🟢 Free |
| [UK Sanctions List Search](https://search-uk-sanctions-list.service.gov.uk) | Official search of the UK Sanctions List, the single source for UK designations since the OFSI Consolidated List closed on 28 January 2026. | 🟢 Free |
| [EU Sanctions Map](https://www.sanctionsmap.eu) | Official EU sanctions visualization. See all EU restrictive measures by country, regime, and type. | 🟢 Free |
| [UN Security Council Consolidated List](https://main.un.org/securitycouncil/en/content/un-sc-consolidated-list) | All individuals and entities subject to UN Security Council sanctions, downloadable in several formats. | 🟢 Free |
| [SanctionsExplorer](https://sanctionsexplorer.org) | C4ADS search of current and historical sanctions across major sanctioning authorities (US, EU, UK, UN and more). | 🟢 Free |
| [War & Sanctions](https://war-sanctions.gur.gov.ua) | Ukraine's Defence Intelligence (GUR) portal on Russia's war economy: foreign components found in weapons, shadow-fleet vessels, defence companies and the sanctions status of linked people and entities. | 🟢 Free |
| [RuPEP](https://rupep.org) | Russian and Belarusian PEP database. Track officials, oligarchs, and their connections. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Legal and Court Records

Access court filings, judgments, wanted notices, and legal takedown records.

| Tool | Description | Pricing |
|------|-------------|---------|
| [CourtListener / RECAP](https://www.courtlistener.com) | Access US federal court records. CourtListener (free) and PACER (paid). Search millions of filings, opinions, and dockets. | 🟢 Free (CourtListener) / 🔴 Paid (PACER) |
| [PACER](https://pacer.uscourts.gov) | Official access to US federal court dockets and filings, charged per page (fees are waived if you spend $30 or less a quarter). Check CourtListener's free RECAP archive first. | 🔴 Paid |
| [Justia](https://law.justia.com) | Free US case law, codes and regulations, with federal dockets on Justia Dockets. | 🟢 Free |
| [Find Case Law (UK)](https://caselaw.nationalarchives.gov.uk) | The National Archives' official service publishing judgments and tribunal decisions from courts in England and Wales. | 🟢 Free |
| [BAILII](https://www.bailii.org) | British and Irish Legal Information Institute: free case law and legislation from the UK and Ireland, including older judgments. | 🟢 Free |
| [CanLII](https://www.canlii.org) | Canadian Legal Information Institute: free Canadian court decisions and legislation. | 🟢 Free |
| [HUDOC](https://hudoc.echr.coe.int) | European Court of Human Rights case-law database, searchable by country, article and keyword. | 🟢 Free |
| [Interpol Red Notices](https://www.interpol.int/How-we-work/Notices/Red-Notices/View-Red-Notices) | Public extracts of Interpol Red Notices (requests to locate and provisionally arrest a person). Most notices are not public, so absence proves nothing. | 🟢 Free |
| [Europe's Most Wanted](https://eumostwanted.eu) | Europol-hosted list of the most-wanted fugitives sought by EU member states. | 🟢 Free |
| [Lumen Database](https://lumendatabase.org) | Database of legal takedown requests (DMCA, copyright, defamation). Reveals removed content and why — useful for uncovering suppressed information. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Cryptocurrency and Blockchain

Investigate blockchain transactions, wallets, and crypto-related activity.

**Jump to:** [Block Explorers](#block-explorers) · [Tracing, Attribution and Risk](#tracing-attribution-and-risk)

### Block Explorers

| Tool | Description | Pricing |
|------|-------------|---------|
| [Etherscan](https://etherscan.io) | Ethereum block explorer. Track ETH transactions, balances, smart contracts, and token transfers. The standard for Ethereum investigation. | 🟢 Free |
| [Blockchair](https://blockchair.com) | Multi-chain explorer and search (Bitcoin, Ethereum, and many others) with advanced filtering. A strong single entry point for cross-chain lookups. | 🟢 Free / 🟡 Freemium (API) |
| [mempool.space](https://mempool.space) | Open-source Bitcoin explorer and mempool visualizer. Inspect transactions, fees, and address activity in detail. | 🟢 Free / 🔵 Open Source |
| [Blockstream Explorer](https://blockstream.info) | Clean Bitcoin and Liquid explorer, also available as a Tor onion service. | 🟢 Free |
| [Tronscan](https://tronscan.org) | Official TRON block explorer. Essential for tracing USDT on TRON (TRC-20), the stablecoin most used in scams and sanctions evasion. | 🟢 Free |
| [Solscan](https://solscan.io) | Leading Solana explorer: transactions, token transfers, accounts and program activity. | 🟢 Free |
| [OKLink](https://www.oklink.com) | Multi-chain explorer covering Bitcoin, Ethereum, TRON and dozens of other networks, with address labels. | 🟡 Freemium |

### Tracing, Attribution and Risk

| Tool | Description | Pricing |
|------|-------------|---------|
| [Arkham Intelligence](https://intel.arkm.com) | Entity-labeled blockchain analytics. Maps wallet clusters to real-world people and organizations, with visual flow tracing. | 🟡 Freemium |
| [Breadcrumbs](https://www.breadcrumbs.app) | Visual wallet and transaction flow-tracing tool aimed at investigators, with free tiers for basic tracing. | 🟡 Freemium |
| [MetaSleuth](https://metasleuth.io) | BlockSec's visual fund-flow tracer for Ethereum and other major chains, with address labels. Free tier for basic graphs. | 🟡 Freemium |
| [WalletExplorer](https://www.walletexplorer.com) | Bitcoin explorer that groups addresses into wallets using common-input heuristics and labels known exchanges and services. | 🟢 Free |
| [DeBank](https://debank.com) | Portfolio and activity view of an EVM address across chains: tokens, DeFi positions, NFTs and transaction history. | 🟢 Free |
| [ENS App](https://app.ens.domains) | Resolve Ethereum Name Service names (such as name.eth) to addresses and see the records an owner has published. | 🟢 Free |
| [Chainabuse](https://www.chainabuse.com) | Community reports of scam, ransomware and fraud addresses across chains, run by TRM Labs. Check an address before you trace it. | 🟢 Free |
| [Chainalysis](https://www.chainalysis.com) | Industry-standard commercial blockchain investigation and compliance platform used by agencies and exchanges. | 🔴 Paid |

> **See also:** OFAC's sanctions list includes designated crypto addresses — search it in [Sanctions and Politically Exposed Persons](#sanctions-and-politically-exposed-persons).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Transport Tracking

Track aircraft, satellites, trains, and road vehicles.

**Jump to:** [Aviation](#aviation) · [Satellites in Orbit](#satellites-in-orbit) · [Rail](#rail) · [Road and Vehicles](#road-and-vehicles)

### Aviation

| Tool | Description | Pricing |
|------|-------------|---------|
| [Flightradar24](https://www.flightradar24.com) | Real-time global flight tracker using ADS-B. Track military/government flights, aircraft over conflict zones, and flight history. | 🟡 Freemium / 🔴 Paid (premium history) |
| [FlightAware](https://flightaware.com) | Flight tracking with extensive US coverage. Detailed history, route analysis, and airport activity. Preferred by US-focused investigators. | 🟡 Freemium / 🔴 Paid |
| [ADS-B Exchange](https://globe.adsbexchange.com) | ⚠️ Global ADS-B flight tracker known for not filtering military, government and private aircraft, with historical playback. Acquired by JetNet in 2023: the free web globe remains public, but bulk data and API access are more restricted. | 🟢 Free (viewer) |
| [ADSB.lol](https://adsb.lol) | Community-run, unfiltered ADS-B tracker with a free API. A good open alternative for tracking aircraft, including those hidden on commercial trackers. | 🟢 Free / 🔵 Open Source |
| [OpenSky Network](https://opensky-network.org) | Non-profit ADS-B network with a live map and a large historical flight-data archive available to researchers. | 🟢 Free |
| [RadarBox](https://www.radarbox.com) | Flight tracker with its own receiver network, flight history and airport data. | 🟡 Freemium |
| [Airframes](https://app.airframes.io) | Community-collected ACARS, VDL2, HFDL and satellite messages sent by aircraft — reveals flight details that ADS-B alone doesn't show. | 🟢 Free |
| [Planespotters.net](https://www.planespotters.net) | Airframe histories (registrations, operators, delivery dates) and photos for commercial and many private aircraft. | 🟢 Free |
| [FAA Aircraft Registry](https://registry.faa.gov/aircraftinquiry/) | Official US aircraft register: look up an N-number, serial number or registered owner. | 🟢 Free |
| [UK CAA G-INFO](https://siteapps.caa.co.uk/g-info/) | Official UK aircraft register: G-registered aircraft, their owners and registration history. | 🟢 Free |

### Satellites in Orbit

| Tool | Description | Pricing |
|------|-------------|---------|
| [OrbTrack](https://www.orbtrack.org) | Real-time satellite tracking. Visualize the position and orbit of satellites, the ISS, and debris. Verify satellite pass times. | 🟢 Free |
| [CelesTrak](https://celestrak.org) | Authoritative public source of satellite orbital data (TLEs), launch catalogues and visualisations. | 🟢 Free |
| [N2YO](https://www.n2yo.com) | Live satellite tracking and pass predictions for any location. | 🟢 Free |

### Rail

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenRailwayMap](https://www.openrailwaymap.org) | OpenStreetMap-based map of the world's railways: tracks, stations, signalling, electrification and speed limits. | 🟢 Free / 🔵 Open Source |
| [Realtime Trains](https://www.realtimetrains.co.uk) | Live and historical running data for trains in Great Britain, including platforms and actual arrival and departure times. | 🟢 Free |
| [Chronotrains](https://www.chronotrains.com) | Visualize how far you can travel by train from any European station in a given time. Useful for understanding transit possibilities and alibis. | 🟢 Free |

### Road and Vehicles

| Tool | Description | Pricing |
|------|-------------|---------|
| [World License Plates](https://www.worldlicenseplates.com) | Enthusiast-run reference of number-plate designs and formats for every country and region — narrow down where a vehicle is registered. Not an official source. | 🟢 Free |
| [NHTSA VIN Decoder](https://vpic.nhtsa.dot.gov/decoder/) | Official US decoder that turns a 17-character VIN into make, model, year, plant and specifications. | 🟢 Free |
| [DVLA Vehicle Enquiry](https://vehicleenquiry.service.gov.uk) | UK government check of a registration number: make, colour, tax and MOT status, and month of first registration. | 🟢 Free |
| [MOT History](https://www.check-mot.service.gov.uk) | UK MOT test history for a registration: test dates, recorded mileage and failures — check that a vehicle matches what a photo shows. | 🟢 Free |
| [LPR Maps](https://www.lprmaps.com) | Community map of automatic number-plate recognition (ALPR) cameras — research the surveillance infrastructure in an area. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Maritime Intelligence

Track ships, monitor maritime activity, and investigate vessel movements and ownership.

| Tool | Description | Pricing |
|------|-------------|---------|
| [MarineTraffic](https://www.marinetraffic.com) | Global ship tracking via AIS. Vessel positions, port calls, voyage history, and ownership details. The standard for maritime OSINT. | 🟡 Freemium / 🔴 Paid (full history) |
| [VesselFinder](https://www.vesselfinder.com) | Real-time vessel tracking with AIS. Free tier offers good coverage. Port arrival/departure data and vessel details. | 🟡 Freemium |
| [MyShipTracking](https://www.myshiptracking.com) | Free AIS vessel tracking with port calls and vessel details. | 🟢 Free |
| [ShipFinder](https://shipfinder.co) | Simplified vessel tracking. Good for quick lookups of positions and basic voyage info. | 🟡 Freemium |
| [Global Fishing Watch](https://globalfishingwatch.org/map/) | Visualize global fishing vessel activity. Detect illegal fishing, transshipment events, and fleet movements via AIS and VMS. | 🟢 Free |
| [Skylight](https://www.skylight.global) | Ai2's maritime-awareness platform, using AIS and satellite imagery to flag dark vessels and suspected illegal fishing. Free for eligible government and NGO partners. | 🟢 Free (eligible partners) |
| [Equasis](https://www.equasis.org) | Free maritime safety database. Ship inspection records, flag history, classification, and ownership data. Run by the European Maritime Safety Agency. | 🟢 Free (registration required) |
| [IMO GISIS](https://gisis.imo.org) | International Maritime Organization database: ship particulars by IMO number, registered owners and company IMO numbers. Free registration. | 🟢 Free |
| [ShipSpotting.com](https://www.shipspotting.com) | Millions of user photos of ships, searchable by name or IMO number — confirm a vessel's appearance and former names. | 🟢 Free |
| [World Port Index](https://msi.nga.mil/Publications/WPI) | US National Geospatial-Intelligence Agency database of ports worldwide, with location, facilities and characteristics. | 🟢 Free |
| [Navtex](https://www.navtex.net) | Maritime navigational warning system. Monitor safety information, coastal warnings, and navigational hazards. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Domains, IPs and Internet Infrastructure

Investigate websites, domains, hosting, certificates, routing, and internet-connected devices.

**Jump to:** [WHOIS, DNS and Certificates](#whois-dns-and-certificates) · [Website Fingerprinting and Connections](#website-fingerprinting-and-connections) · [IP, ASN and Routing](#ip-asn-and-routing) · [Internet-Wide Device Search](#internet-wide-device-search) · [Threat Intelligence and Reputation](#threat-intelligence-and-reputation)

### WHOIS, DNS and Certificates

| Tool | Description | Pricing |
|------|-------------|---------|
| [ICANN Lookup](https://lookup.icann.org) | Official ICANN WHOIS lookup — the authoritative source for domain registration data. | 🟢 Free |
| [DomainTools Whois](https://whois.domaintools.com) | Industry-leading WHOIS with historical records. Track ownership changes, DNS history, and connected domains. | 🟡 Freemium / 🔴 Paid |
| [Whoxy](https://www.whoxy.com) | WHOIS search with reverse lookup. Find all domains registered by a person/email/company. Affordable API. | 🟡 Freemium / 🔴 Paid |
| [crt.sh](https://crt.sh) | Certificate Transparency log search. Enumerate a domain's subdomains and infrastructure from issued TLS certificates. A free, essential recon staple. | 🟢 Free |
| [DNSDumpster](https://dnsdumpster.com) | Free DNS reconnaissance and mapping. Discover subdomains, hosts, MX/NS records, and visualize a domain's footprint. | 🟢 Free |
| [SecurityTrails](https://securitytrails.com) | Historical DNS, WHOIS, and subdomain data. Track how a domain's infrastructure changed over time. | 🟡 Freemium / 🔴 Paid |
| [ViewDNS.info](https://viewdns.info) | A one-stop set of free DNS/IP utilities: reverse IP, reverse WHOIS, DNS records, IP history, and more. | 🟢 Free |
| [DNSlytics](https://dnslytics.com) | Reverse IP, reverse analytics and AdSense ID, and DNS history lookups for connecting websites run by the same owner. | 🟡 Freemium |
| [Host.io](https://host.io) | Domain data including backlinks, redirects, co-hosted domains on the same IP and shared analytics IDs. | 🟡 Freemium |
| [IDN Checker (Punycoder)](https://www.punycoder.com) | Detect internationalized domain name (IDN) homograph attacks. Identifies visually similar characters used in phishing domains. | 🟢 Free |

### Website Fingerprinting and Connections

| Tool | Description | Pricing |
|------|-------------|---------|
| [urlscan.io](https://urlscan.io) | Scan and analyze websites. See what a URL loads (DOM, cookies, requests, screenshots) without visiting it yourself. Searchable historical scans. | 🟡 Freemium |
| [PublicWWW](https://publicwww.com) | Search the source code of websites. Find sites sharing an analytics ID, ad code, or snippet — connect sites to the same operator. | 🟡 Freemium / 🔴 Paid |
| [BuiltWith](https://builtwith.com) | Profile a site's full technology stack (analytics, frameworks, trackers, hosting). Useful for fingerprinting and connecting related sites. | 🟡 Freemium |
| [Wappalyzer](https://www.wappalyzer.com) | Browser extension and website that detect a site's technologies (CMS, analytics, frameworks) — quick fingerprinting while you browse. | 🟡 Freemium |
| [What CMS](https://whatcms.org) | Detect the CMS a website uses, plus hosting providers, themes, and plugins. | 🟢 Free |
| [Netcraft Site Report](https://sitereport.netcraft.com) | Hosting history, netblock owner, nameservers and technologies for any website. | 🟢 Free |
| [The Information Laundromat](https://www.informationlaundromat.com) | Alliance for Securing Democracy / ISD tool for spotting laundered content and linked websites. Content similarity finds reposted or rewritten articles; metadata similarity compares analytics IDs, IPs and other indicators across domains. | 🟢 Free |

### IP, ASN and Routing

| Tool | Description | Pricing |
|------|-------------|---------|
| [IPinfo](https://ipinfo.io) | IP address lookups: geolocation, ASN, hosting and VPN detection, and the company behind the address. | 🟡 Freemium |
| [Geo Data Tool](https://www.geodatatool.com) | IP geolocation lookup and geographic data conversion utility. Map IP addresses to approximate physical locations. | 🟢 Free |
| [Hurricane Electric BGP Toolkit](https://bgp.he.net) | Look up autonomous systems, IP prefixes and peering — who actually owns and announces an IP range. | 🟢 Free |
| [RIPEstat](https://stat.ripe.net) | RIPE NCC's dashboard for any IP, prefix or ASN: registration, routing history, geolocation and abuse contacts. | 🟢 Free |
| [Robtex](https://www.robtex.com) | Graphs the relationships between domains, IPs, nameservers and mail servers. | 🟡 Freemium |

### Internet-Wide Device Search

| Tool | Description | Pricing |
|------|-------------|---------|
| [Shodan](https://www.shodan.io) | The search engine for internet-connected devices. Find servers, webcams, ICS/SCADA, databases, and open ports by banner, product, port, or geography. A cornerstone of technical OSINT. | 🟡 Freemium (one-time paid tiers) |
| [Censys Platform](https://platform.censys.io) | Internet-wide host and certificate search. Rich structured data on services, TLS certs, and software — a strong complement to Shodan. Replaced Censys Legacy Search (search.censys.io), deprecated in September 2026; the free account is limited to 100 results per search. | 🟡 Freemium |
| [ZoomEye](https://www.zoomeye.org) | Chinese cyberspace search engine indexing hosts, devices, and services worldwide. Useful for cross-checking Shodan/Censys results. | 🟡 Freemium |
| [FOFA](https://en.fofa.info) | Chinese internet asset search engine with powerful fingerprint queries. Strong coverage of assets under-represented on Western engines. | 🟡 Freemium |
| [Netlas.io](https://netlas.io) | Internet-wide scan data: hosts, domains, certificates, and responses, with a generous free query allowance. | 🟡 Freemium |
| [Onyphe](https://www.onyphe.io) | Cyber-defense search engine aggregating scan data, threat intel, and exposed-asset information. | 🟡 Freemium |
| [LeakIX](https://leakix.net) | Search engine for exposed services and leaks found by internet-wide scanning, such as open databases and exposed .git or .env files. | 🟡 Freemium |
| [Criminal IP](https://www.criminalip.io) | Internet asset search with risk scoring for IPs and domains, exposed services and vulnerabilities. | 🟡 Freemium |
| [GrayHatWarfare](https://buckets.grayhatwarfare.com) | Search engine for publicly exposed cloud storage — open S3/Azure/GCP buckets and their files. Frequently surfaces accidentally public sensitive data. | 🟡 Freemium |

### Threat Intelligence and Reputation

| Tool | Description | Pricing |
|------|-------------|---------|
| [VirusTotal](https://www.virustotal.com) | Scan files, URLs, domains and IPs against dozens of security engines. The Relations tab and passive DNS link infrastructure together. | 🟡 Freemium |
| [AbuseIPDB](https://www.abuseipdb.com) | Community reports of abusive IP addresses (scanning, spam, brute-force attacks). | 🟡 Freemium |
| [AlienVault OTX](https://otx.alienvault.com) | Open Threat Exchange: community threat-intelligence 'pulses' linking IPs, domains and file hashes to campaigns. Now part of LevelBlue. | 🟢 Free |
| [URLhaus](https://urlhaus.abuse.ch) | abuse.ch database of URLs used to distribute malware, searchable by URL, host or file hash. | 🟢 Free |
| [GreyNoise](https://viz.greynoise.io) | Identifies IPs that are mass-scanning the internet, helping separate targeted activity from background noise. | 🟡 Freemium |
| [Validin](https://www.validin.com) | Historical DNS, certificate and HTTP response data for pivoting across infrastructure. Free community accounts available. | 🟡 Freemium |

> **See also:** command-line recon tools (Subfinder, Amass, BBOT, SpiderFoot) in [Recon and Automation](#recon-and-automation).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Data Leaks and Breach Intelligence

Search leaked databases, breach notifications, and leak-site monitoring for investigative purposes.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if an email or phone appears in known breaches. Created by Troy Hunt. The most trusted breach notification service. | 🟢 Free |
| [Hudson Rock (Free Tools)](https://www.hudsonrock.com/free-tools) | Free lookups that check whether an email, domain, or username appears in infostealer malware logs. Excellent for assessing infostealer exposure. | 🟢 Free (free tools) / 🔴 Paid |
| [DeHashed](https://dehashed.com) | Search engine for leaked databases by email, username, name, IP, phone, address, or password hash. | 🔴 Paid |
| [Leak-Lookup](https://leak-lookup.com) | Breach search engine. Query leaked data by email, username, keyword, domain, or password. | 🟡 Freemium / 🔴 Paid |
| [Intelligence X](https://intelx.io) | Search engine for leaked data, darknet content, and OSINT selectors. Archives Tor sites, paste sites, and breach data. Powerful but the useful tiers are paid. | 🟡 Freemium / 🔴 Paid |
| [Library of Leaks](https://search.libraryofleaks.org) | Distributed Denial of Secrets' searchable archive of leaked documents and datasets released in the public interest. | 🟢 Free |
| [DiscordLeaks](https://discordleaks.unicornriot.ninja) | Searchable archive of leaked Discord messages from extremist groups, published by Unicorn Riot. | 🟢 Free |
| [ransomware.live](https://www.ransomware.live) | Tracks victims posted on ransomware groups' leak sites, with group profiles and timelines. | 🟡 Freemium |

> ⚠️ Use breach data only to assess exposure or corroborate facts in lawful investigations. Never log in with leaked credentials.

<sub>[⬆ Back to contents](#contents)</sub>

---

## Code and Technical Search

Search source code and repositories for attribution, deleted history, and exposed secrets.

| Tool | Description | Pricing |
|------|-------------|---------|
| [grep.app](https://grep.app) | Search across 500K+ public Git repositories. Find API keys, config files, code snippets, and developer attributions. | 🟢 Free |
| [GitHub Code Search](https://github.com/search) | GitHub's native code search covers millions of public repos with regex and qualifiers. Find leaked secrets, usernames, and unique strings tied to a target. | 🟢 Free (GitHub account) |
| [GH Archive](https://www.gharchive.org) | Archive of public GitHub events since 2011 (pushes, issues, stars), queryable in Google BigQuery. Recover activity from deleted repositories or accounts. | 🟢 Free |
| [Software Heritage Archive](https://archive.softwareheritage.org) | Universal archive of public source code from GitHub, GitLab and other forges, including repositories that have since been deleted. | 🟢 Free |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scan Git repos, S3 buckets, Docker images, and CI/CD systems for exposed secrets, API keys, and credentials. | 🟢 Free / 🔵 Open Source |
| [Gitleaks](https://github.com/gitleaks/gitleaks) | Fast scanner for secrets (API keys, tokens, passwords) in Git history and files — a lighter alternative to TruffleHog. | 🟢 Free / 🔵 Open Source |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Conflict, Arms and Munitions

Track conflict events, identify weapons and munitions, and document civilian harm.

**Jump to:** [Conflict Monitoring and Documentation](#conflict-monitoring-and-documentation) · [Weapons and Munitions Identification](#weapons-and-munitions-identification)

### Conflict Monitoring and Documentation

| Tool | Description | Pricing |
|------|-------------|---------|
| [ACLED](https://acleddata.com) | Real-time data on political violence and protest events worldwide, with precise geolocations. The standard for conflict tracking. | 🟢 Free (registration required) |
| [UCDP](https://ucdp.uu.se) | Uppsala Conflict Data Program: the longest-running dataset on organised violence, with geocoded event-level data. | 🟢 Free |
| [Liveuamap](https://liveuamap.com) | Real-time interactive map of conflict events, protests, and security incidents. Covers Ukraine, the Middle East, Africa, and other zones. | 🟢 Free |
| [DeepStateMap](https://deepstatemap.live) | Daily-updated map of the front line and territorial control in Russia's war against Ukraine. | 🟢 Free |
| [GeoConfirmed](https://geoconfirmed.org) | Volunteer-run maps of geolocated photos and videos from conflict zones, each linked to the source footage. | 🟢 Free |
| [Airwars](https://airwars.org) | Monitors civilian harm from explosive weapons in conflicts, with incident-level casualty records. | 🟢 Free |
| [UNOSAT](https://unosat.org/products/) | UN satellite-based damage assessments and situational analyses for conflict zones and natural disasters. | 🟢 Free |
| [Atlos](https://www.atlos.org) | Collaborative platform for visual investigation and geolocation. Open-source tooling for verifying conflict incidents from media. | 🟢 Free / 🔵 Open Source |

### Weapons and Munitions Identification

| Tool | Description | Pricing |
|------|-------------|---------|
| [CAT-UXO](https://cat-uxo.com) | UXO identification reference. Identify unexploded ordnance and munitions found in conflict zones from photos. | 🟢 Free |
| [Bulletpicker](https://bulletpicker.com) | US military ordnance identification database. Detailed technical data on bombs, rockets, mines, and other ordnance. | 🟢 Free |
| [Open Source Munitions Portal](https://osmp.ngo) | Open database for identifying munitions from images, run by Airwars, Conflict Armament Research and King's College London. Work in progress — coverage is strongest for the Middle East and Ukraine. | 🟢 Free |
| [Oryx](https://www.oryxspioenkop.com) | Lists of military equipment losses, each documented with photo or video evidence. | 🟢 Free |
| [iTrace](https://itrace.conflictarm.com) | Conflict Armament Research's global map of weapons and ammunition documented in conflict zones and traced back to manufacturers and supply chains. | 🟢 Free |
| [SIPRI Arms Transfers Database](https://www.sipri.org/databases/armstransfers) | All international transfers of major conventional weapons since 1950, by supplier and recipient. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Environmental and Wildlife Intelligence

Investigate deforestation, pollution, emissions, wildlife trafficking, and ecological data.

**Jump to:** [Land, Forests and Emissions](#land-forests-and-emissions) · [Wildlife and Biodiversity](#wildlife-and-biodiversity)

### Land, Forests and Emissions

| Tool | Description | Pricing |
|------|-------------|---------|
| [Global Forest Watch](https://www.globalforestwatch.org) | Monitor deforestation in near-real-time. Tree-cover-loss alerts, fire data, and land-use analysis. Used to track illegal logging. | 🟢 Free |
| [MapBiomas](https://mapbiomas.org) | Annual land-cover and land-use maps back to 1985 for Brazil and several other countries, with deforestation alerts. | 🟢 Free |
| [Trase](https://trase.earth) | Traces commodity supply chains (soy, beef, palm oil, cocoa) from production regions to traders and importing countries, linked to deforestation. | 🟢 Free |
| [Global Energy Monitor](https://globalenergymonitor.org) | Trackers of coal plants, oil and gas pipelines, LNG terminals, steel plants and more, with owners and locations. | 🟢 Free |
| [Climate TRACE](https://climatetrace.org) | Independent, facility-level greenhouse-gas emissions estimates (from satellites and AI) for power plants, oil fields, ships and more. | 🟢 Free |
| [Carbon Mapper](https://carbonmapper.org) | Satellite and aircraft detections of methane and CO₂ plumes from individual facilities, with a public data portal. | 🟢 Free |
| [Resource Watch](https://resourcewatch.org) | Hundreds of datasets visualized on maps: air quality, deforestation, water stress, food production. A World Resources Institute platform. | 🟢 Free |
| [Aqueduct Water Risk Atlas](https://www.wri.org/aqueduct) | Map global water stress, flood risk, and drought severity. Useful for environmental investigations and climate-impact analysis. | 🟢 Free |
| [Environmental Justice Atlas](https://ejatlas.org) | Global map of environmental conflicts, documenting ecological disputes, pollution, and land-grabbing with detailed case studies. | 🟢 Free |
| [EIA International](https://eia-international.org) | Environmental Investigation Agency's reporting on environmental crimes: illegal logging, wildlife trafficking, and climate crimes. | 🟢 Free |

### Wildlife and Biodiversity

| Tool | Description | Pricing |
|------|-------------|---------|
| [CITES Trade Database](https://trade.cites.org) | International trade in endangered species. Search permits and shipments regulated under CITES. Track wildlife-trafficking patterns. | 🟢 Free |
| [Species+](https://speciesplus.net) | CITES species database with trade data, distribution maps, and legal status. Identify protected species encountered in investigations. | 🟢 Free |
| [Wildlife Trade Portal](https://www.wildlifetradeportal.org) | Monitor global wildlife trade with species-level data. Analyze legal and illegal trade flows. | 🟢 Free |
| [World Database on Protected Areas](https://www.protectedplanet.net) | Global database of terrestrial and marine protected areas. Verify whether activities occur in protected zones. | 🟢 Free |
| [eBird](https://ebird.org) | Cornell Lab's database of bird sightings and range maps. Check whether a species seen or heard in media occurs in the claimed place and season. | 🟢 Free |
| [Locust Hub (FAO)](https://locust-hub-hqfao.hub.arcgis.com) | Track desert locust swarms globally. FAO platform monitoring outbreaks and their impact on food security. | 🟢 Free |

> **See also:** iNaturalist, xeno-canto and BirdNET in [Environmental and Bioacoustic Sound Identification](#environmental-and-bioacoustic-sound-identification), and fishing-vessel tracking in [Maritime Intelligence](#maritime-intelligence).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Archiving and Preservation

Capture and preserve web content before it disappears.

**Jump to:** [Public Web Archives](#public-web-archives) · [Capture and Monitoring Tools](#capture-and-monitoring-tools)

### Public Web Archives

| Tool | Description | Pricing |
|------|-------------|---------|
| [Wayback Machine (Internet Archive)](https://web.archive.org) | The most comprehensive web archive. Billions of saved pages back to 1996. View how sites looked at specific dates. | 🟢 Free |
| [Archive.today](https://archive.today) | On-demand webpage snapshot service. Creates permanent frozen copies of pages and often bypasses paywalls on archived content. | 🟢 Free |
| [Ghost Archive](https://ghostarchive.org) | On-demand archiving that can also save YouTube videos and pages that archive.today and the Wayback Machine struggle with. | 🟢 Free |
| [Arquivo.pt](https://arquivo.pt) | Portugal's national web archive, with full-text search across archived pages back to the 1990s — including many non-Portuguese sites. | 🟢 Free |
| [Perma.cc](https://perma.cc) | Harvard Law School Library's permanent-link service, used by courts and journals to create stable, citable archives. | 🟡 Freemium |

### Capture and Monitoring Tools

| Tool | Description | Pricing |
|------|-------------|---------|
| [ArchiveWeb.page](https://archiveweb.page) | Webrecorder's browser extension that records everything you browse — including logged-in and dynamic pages — into a WACZ web-archive file. | 🟢 Free / 🔵 Open Source |
| [ReplayWeb.page](https://replayweb.page) | Opens and replays WARC and WACZ web archives in the browser. Pairs with ArchiveWeb.page and Auto Archiver. | 🟢 Free / 🔵 Open Source |
| [Auto Archiver](https://github.com/bellingcat/auto-archiver) | Bellingcat's automated archiving tool. Bulk-archive URLs from spreadsheets to the Wayback Machine, archive.today, or local storage. | 🟢 Free / 🔵 Open Source |
| [ArchiveBox](https://archivebox.io) | Self-hosted web archiving. Save pages to WARC, HTML, PDF, and screenshots in your own repository — good for building a private evidence archive. | 🟢 Free / 🔵 Open Source |
| [SingleFile](https://github.com/gildas-lormeau/SingleFile) | Browser extension that saves a complete web page (images, styles and all) as a single HTML file. | 🟢 Free / 🔵 Open Source |
| [GoFullPage](https://gofullpage.com) | Chrome extension for one-click, full-length page screenshots, exportable to PNG or PDF. | 🟡 Freemium |
| [Hunchly](https://www.hunchly.com) | Automated web-capture tool for investigators. Runs in the background while browsing, saving every page with timestamps and hashes for legal evidence. | 🔴 Paid (~$130/year) |
| [Zotero](https://www.zotero.org) | Reference manager and page archiver. Save full snapshots with metadata; organize research with tags and collections. | 🟢 Free / 🔵 Open Source |
| [Distill.io](https://distill.io) | Web page change monitoring. Get notified when specific parts of pages change — track profile updates, price changes, or content edits. | 🟡 Freemium |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Browser Extensions and Scrapers

Extensions and tools for data extraction, bulk downloading, and browser-based investigation.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Instant Data Scraper](https://webrobots.io/instantdata/) | AI-powered browser extension that auto-detects tables and lists on pages and exports them to CSV/Excel. No coding required. | 🟢 Free |
| [Web Scraper](https://webscraper.io) | Point-and-click scraper extension for multi-page sites (pagination, nested pages) that exports to CSV or XLSX. | 🟡 Freemium |
| [Zeeschuimer](https://github.com/digitalmethodsinitiative/zeeschuimer) | Browser extension that intercepts social-media API traffic and saves it as structured data. Captures from TikTok, Instagram, X, LinkedIn, and more. Pairs with 4CAT for analysis. | 🟢 Free / 🔵 Open Source |
| [4CAT](https://github.com/digitalmethodsinitiative/4cat) | The Digital Methods Initiative's capture and analysis toolkit. Import data from Zeeschuimer or other sources and run analyses such as word trees, hashtag networks and image walls. | 🟢 Free / 🔵 Open Source |
| [Instaloader](https://instaloader.github.io) | Download Instagram profiles, posts, stories, reels, and metadata. Python CLI for bulk Instagram data collection. | 🟢 Free / 🔵 Open Source |
| [gallery-dl](https://github.com/mikf/gallery-dl) | Command-line downloader for image galleries and collections from hundreds of sites, preserving metadata. | 🟢 Free / 🔵 Open Source |
| [DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter) | Export Discord chat history to HTML, JSON, CSV, or plain text. Preserve Discord evidence for investigations. | 🟢 Free / 🔵 Open Source |
| [Mitaka](https://github.com/ninoseki/mitaka) | Browser extension: select an IP, domain, URL, hash or other indicator on any page and search it across Shodan, VirusTotal, urlscan.io and many more. | 🟢 Free / 🔵 Open Source |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Data Analysis and Visualization

Clean, explore, and present investigative data: link charts, documents, maps, and timelines.

**Jump to:** [Link Analysis and Networks](#link-analysis-and-networks) · [Documents and Data Wrangling](#documents-and-data-wrangling) · [Charts, Maps and Timelines](#charts-maps-and-timelines)

### Link Analysis and Networks

| Tool | Description | Pricing |
|------|-------------|---------|
| [Maltego](https://www.maltego.com) | The industry-standard OSINT link-analysis and visualization platform. Map relationships between people, companies, domains, IPs, and more via transforms. | 🟡 Freemium (Community Edition) / 🔴 Paid |
| [Gephi](https://gephi.org) | Open-source network analysis and visualization. Create complex graphs from large datasets; supports social network analysis. | 🟢 Free / 🔵 Open Source |
| [Kumu](https://kumu.io) | Web platform for mapping relationships and systems, good for publishing interactive network maps. | 🟡 Freemium |
| [draw.io](https://www.drawio.com) | Diagramming app (web and desktop) for quick link charts and flow diagrams; files can stay on your own device. | 🟢 Free / 🔵 Open Source |

### Documents and Data Wrangling

| Tool | Description | Pricing |
|------|-------------|---------|
| [Pinpoint](https://journaliststudio.google.com/pinpoint/) | Google's AI-powered document and image analysis for journalists. OCR, entity extraction, and search across large document collections. | 🟢 Free |
| [OpenRefine](https://openrefine.org) | Clean and reconcile messy data (inconsistent names, duplicates, formats) before analysis — a staple for working with leaks and registries. | 🟢 Free / 🔵 Open Source |
| [Datasette](https://datasette.io) | Explore and publish datasets (SQLite) through a browsable web interface with SQL queries. | 🟢 Free / 🔵 Open Source |

### Charts, Maps and Timelines

| Tool | Description | Pricing |
|------|-------------|---------|
| [Datawrapper](https://www.datawrapper.de) | Create publication-ready charts, maps, and tables. Used by major newsrooms. Clean output, no coding. | 🟡 Freemium |
| [Flourish](https://flourish.studio) | Newsroom-favourite tool for interactive charts, maps, and scrollytelling stories. A strong Datawrapper alternative for narrative visuals. | 🟡 Freemium |
| [RAWGraphs](https://rawgraphs.io) | Open-source visualization framework for unconventional chart types from spreadsheet data. Bridges data and vector graphics. | 🟢 Free / 🔵 Open Source |
| [Tableau Public](https://public.tableau.com) | Free version of Tableau for interactive charts and dashboards. Everything you save is published publicly. | 🟢 Free |
| [kepler.gl](https://kepler.gl) | Browser-based geospatial visualisation for large location datasets (points, arcs, heatmaps, time playback). Data stays in your browser. | 🟢 Free / 🔵 Open Source |
| [TimelineJS](https://timeline.knightlab.com) | Knight Lab tool that turns a Google Sheet into an interactive, embeddable timeline. | 🟢 Free / 🔵 Open Source |
| [Blender](https://www.blender.org) | Professional 3D modeling and rendering. Used in OSINT for crime-scene reconstruction, terrain modeling, and event recreation. | 🟢 Free / 🔵 Open Source |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Frameworks, Automation and Case Management

Automate collection, organize investigations, and set up a safe working environment.

**Jump to:** [Recon and Automation](#recon-and-automation) · [Notes and Case Management](#notes-and-case-management) · [Investigation Environments](#investigation-environments)

### Recon and Automation

| Tool | Description | Pricing |
|------|-------------|---------|
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | Powerful open-source OSINT automation. Point it at a domain, IP, email, name, or username and it queries 200+ modules to build an entity graph. Also offered as a hosted service (SpiderFoot HX). | 🟢 Free / 🔵 Open Source / 🔴 Paid (HX) |
| [recon-ng](https://github.com/lanmaster53/recon-ng) | Modular recon framework with a Metasploit-style workflow. Automates domain, host, and contact discovery into a local database. | 🟢 Free / 🔵 Open Source |
| [theHarvester](https://github.com/laramies/theHarvester) | Classic CLI tool for gathering emails, subdomains, hosts, and names from public search engines and data sources. A recon staple. | 🟢 Free / 🔵 Open Source |
| [Subfinder](https://github.com/projectdiscovery/subfinder) | ProjectDiscovery's fast passive subdomain-enumeration tool, querying dozens of sources at once. | 🟢 Free / 🔵 Open Source |
| [OWASP Amass](https://github.com/owasp-amass/amass) | In-depth attack-surface mapping and subdomain discovery using passive sources and active techniques. | 🟢 Free / 🔵 Open Source |
| [BBOT](https://github.com/blacklanternsecurity/bbot) | Black Lantern Security's recursive recon framework, where each module feeds its results to the others. | 🟢 Free / 🔵 Open Source |

### Notes and Case Management

| Tool | Description | Pricing |
|------|-------------|---------|
| [Obsidian](https://obsidian.md) | Markdown knowledge management with graph-based note linking. Build interconnected investigation notebooks; a plugin ecosystem extends it for OSINT. | 🟢 Free (personal) / 🔴 Paid (sync/commercial) |
| [Logseq](https://logseq.com) | Open-source, privacy-first outliner (local storage) with bidirectional linking and daily journals for investigation logging. | 🟢 Free / 🔵 Open Source |
| [Uwazi](https://www.uwazi.io) | Open-source document management for human-rights organizations. Organize, analyze, and publish collections of legal and investigative documents. | 🟢 Free / 🔵 Open Source |

### Investigation Environments

| Tool | Description | Pricing |
|------|-------------|---------|
| [Trace Labs OSINT VM](https://github.com/tracelabs/tlosint-vm) | Kali-based virtual machine pre-loaded with OSINT tools, maintained by Trace Labs for its missing-persons CTFs. | 🟢 Free / 🔵 Open Source |
| [Tsurugi Linux](https://tsurugi-linux.org) | Digital-forensics and OSINT Linux distribution with image, video and audio tools pre-installed, for evidence-safe work in an isolated environment. | 🟢 Free |
| [CSI Linux](https://csilinux.com) | Investigation-focused Linux distribution with a broad suite of pre-configured OSINT and forensics tools. An alternative to Tsurugi. | 🟢 Free |

> **See also:** Hunchly in [Capture and Monitoring Tools](#capture-and-monitoring-tools) and Maltego in [Link Analysis and Networks](#link-analysis-and-networks).

<sub>[⬆ Back to contents](#contents)</sub>

---

## Translation and Language

Read foreign-language sources, documents, and screenshots.

| Tool | Description | Pricing |
|------|-------------|---------|
| [DeepL Translator](https://www.deepl.com/translator) | High-quality machine translation for European and major Asian languages; translates whole documents. | 🟡 Freemium |
| [Google Translate](https://translate.google.com) | Covers 200+ languages, with document and website translation; the mobile app translates signs and screenshots through the camera. | 🟢 Free |
| [Yandex Translate](https://translate.yandex.com) | Often stronger than others for Russian, Ukrainian and Turkic languages; translates text in images. | 🟢 Free |
| [Papago](https://papago.naver.com) | Naver's translator, strong for Korean, Japanese and Chinese. | 🟢 Free |

> **See also:** Name Variant Search in [Username and Identity Search](#username-and-identity-search) for spelling variants and transliterations of names.

<sub>[⬆ Back to contents](#contents)</sub>

---

## Directories and Meta-Resources

Other curated directories and reference lists. Unlike the rest of this toolkit, these link to catalogues and guides rather than to individual tools.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Bellingcat Online Investigation Toolkit](https://bellingcat.gitbook.io/toolkit) | Bellingcat's volunteer-maintained catalogue of investigation tools, with detailed how-to pages, limitations and cost notes. | 🟢 Free |
| [OSINT Framework](https://osintframework.com) | A browsable directory that maps OSINT needs to tools by category. The go-to starting map for finding the right tool for a task. | 🟢 Free |
| [IntelTechniques Tools](https://inteltechniques.com/tools/) | Michael Bazzell's search-tool collection for streamlined queries across many platforms and data types. | 🟢 Free |
| [Awesome OSINT](https://github.com/jivoi/awesome-osint) | Large community-maintained list of OSINT tools and resources on GitHub. | 🟢 Free / 🔵 Open Source |
| [Bellingcat Toolkit: China-related Resources](https://bellingcat.gitbook.io/toolkit/more/all-tools/china-related-resources) | Bellingcat's guide to Chinese registries and platforms, such as court judgments, company credit records and corporate data sites. | 🟢 Free |
| [Wikipedia: List of Company Registers](https://en.wikipedia.org/wiki/List_of_company_registers) | Comprehensive list of company registers worldwide. A useful starting point when investigating companies in unfamiliar jurisdictions. | 🟢 Free |
| [Wikipedia: List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives) | Directory of web-archiving initiatives worldwide. Find regional and specialized archives beyond the Internet Archive. | 🟢 Free |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Deprecated and Defunct Tools

These tools were listed in earlier editions but are now defunct, unreliable, restricted, or replaced. They're kept here so investigators don't waste time chasing dead links.

| Tool | Status | Notes |
|------|--------|-------|
| LinkdTime (freegeoip.live/linkedtime) | ⚫ Defunct / unreliable | Relied on decoding numeric LinkedIn profile IDs to estimate account creation date. LinkedIn moved to public vanity IDs and changed profile structure, breaking this method. For a rough "joined" date, use the profile's own *About → Joined* field or a current LinkedIn post-date extractor instead. |
| Spot (spotthe.bot) | ⚫ Likely defunct | X/Twitter bot-behavior analyzer. Dependent on Twitter API access, which changed drastically in 2023; the tool has not shown reliable signs of life since. Use Bot Sentinel-style services or manual heuristics for automation analysis. |
| CrowdTangle | ⚫ Shut down (2024) | Meta discontinued CrowdTangle. Its sanctioned replacement is the **Meta Content Library** (see [Facebook and Instagram](#facebook-and-instagram)). |
| instagram-scraper (bellingcat follow-on) | ⚫ No longer exists | The scraper that Instagram Location Search fed into is gone. Instagram Location Search still returns location IDs, but you'll need another method to pull media from them. |
| NeutrOSINT | ⚫ Unmaintained | Multi-purpose repo went stale and its underlying lookups broke. Prefer maintained tools: Maigret/Blackbird (usernames), Holehe/Epieos (email), and dedicated phone/IP tools. |
| GeoSpy (geospy.ai) | ⚫ No public access (Apr 2026) | Graylark rebranded GeoSpy as **Raven** and now sells it only to qualified law-enforcement, government and enterprise customers; geospy.ai redirects to that announcement. There is no free tier. |
| Sentinel Hub Playground / EO Browser | ⚫ Retired (20 Mar 2026) | Planet retired the Sentinel Hub web apps. Use **Copernicus Browser** (see [Satellite Imagery and Earth Observation](#satellite-imagery-and-earth-observation)) for free Sentinel data, or Planet Insights for commercial work. |
| Social Bearing (socialbearing.com) | ⚫ Defunct | The domain now redirects to its creator's blog and the search tool is no longer available. Free X/Twitter analytics tools have largely disappeared since X's 2023 API changes. |
| Index Database (indexdb.org) | ⚫ Unstable / gone | Breach-dump directory that has been intermittently offline and is not a dependable source. Use Have I Been Pwned and Hudson Rock's free tools instead. |
| DiscordLookup (discordlookup.com) | ⚫ Archived (Nov 2025) | The original open-source project was archived; its domain now hosts the EasyPoll bot, and discordlookup.org is an unofficial clone. Use **discord.id** (see [Discord](#discord)). |
| Open Ownership Register | ⚫ Closed (29 Nov 2024) | The global beneficial-ownership register closed. Open Ownership still publishes guidance and bulk data; search national registers such as Companies House (PSC data) instead. |
| License Plate Maps (licenseplatemaps.com) | ⚫ Not found | No reference site exists at this address — the name came from a Bellingcat Toolkit page. Use **World License Plates** (see [Road and Vehicles](#road-and-vehicles)). |

<sub>[⬆ Back to contents](#contents)</sub>

---

## Tool Count by Pricing

**418 tools** in total. The counts below overlap, because many tools carry more than one pricing label (for example, free and open source).

| Type | Tools |
|------|-------|
| 🟢 Free | 336 — free to use, including free tiers |
| 🔵 Open Source | 78 — source code is public |
| 🟡 Freemium | 74 — free tier with paid features, or access by application |
| 🔴 Paid | 31 — subscription or per-use payment |

---

## Changelog

### 10 October 2026

**Easier to navigate**

- Fixed 7 contents links that didn't work on GitHub: emoji in those section headings changed their link anchors. Headings are now plain text, so every contents link resolves.
- Grouped the sections by theme and added [Start From What You Have](#start-from-what-you-have), a collapsible [Tool Index A–Z](#tool-index-az), **Jump to** lines and back-to-contents links.
- Split large sections into sub-categories — for example, Social Media by platform and Domains, IPs and Internet Infrastructure by task.

**More tools**

- Added 180 tools, bringing the list to 417.
- New sections: Search Engines and Advanced Operators; AI-Generated and Synthetic Media Detection; Public Records, Procurement and Lobbying; Translation and Language; Directories and Meta-Resources.

**Original links**

- Every entry now links to the tool's own site, extension-store page or repository. Directories and Wikipedia lists moved to Directories and Meta-Resources, and the anonymous "China-related Resources" spreadsheet was replaced with Bellingcat's maintained page.
- Discord Lookup → discord.id. The original DiscordLookup was archived in November 2025, and the `.org` site was an unofficial clone.
- License Plate Maps removed (no reference site exists at that address) → World License Plates.
- X location operators merged into X (Twitter) Advanced Search, with a warning that they may return no results since early 2026.
- Updated links for Castrick Clues, BirdNET Web Demo, ShadowMap, InVID / WeVerify, Telepathy and Convert Geographic Units.
- Fixed five GitHub links to repositories that don't exist: Twitter Location Search, ENF Whale and GridFisherman (replaced with Open ENF and the ENF Fingerprinting Tool), MapSwitcher, and Search by Image.
- Updated moved URLs: Censys (→ Censys Platform), Hoaxy (→ OSoMeNet), Name Variant Search, EDGAR Full-Text Search, Open Source Munitions Portal, Shadow Finder, PixPlot, BirdNET Analyzer, Demucs, Face Comparison by ToolPie, and x.com.

**Status changes**

- Moved to Deprecated: GeoSpy (law-enforcement only as Raven), Sentinel Hub Playground / EO Browser (retired March 2026), Social Bearing, DiscordLookup, Open Ownership Register (closed November 2024), and License Plate Maps.
- Updated: OCCRP Aleph → Aleph Pro (wider access by application), Open Measures (free tier limited to older data), Telepathy (limited maintenance), Spleeter (legacy), RootAbout, The Information Laundromat, SanctionsExplorer, IDCrawl, That'sThem, and Azure AI Video Indexer.

**Tidied**

- Merged duplicate entries (ExifTool, FlightAware, MarineTraffic, TruffleHog, Hunchly, ShadeMap, InVID, Telegram Phone Number Checker, Hitta.se) and turned the Audacity technique rows into tips.
- Moved misplaced tools — for example ADS-B Exchange to Aviation, Pray Times to Sun, Moon and Shadows, and Tsurugi and CSI Linux to Investigation Environments.

---

## Contributing

Found a tool that should be listed here? Want to update a description, pricing, or status?

1. Fork this repository.
2. Add or update the tool in the most relevant section and sub-category.
3. Follow the existing format: `| [Tool Name](https://official-link) | What it does and how investigators use it | Pricing |`
4. Link to the tool's **official** website, extension-store page or source repository — not a directory, mirror, or article about it.
5. Add the tool to the [Tool Index A–Z](#tool-index-az).
6. For status changes, add ⚠️ with a note, or move dead tools to [Deprecated and Defunct Tools](#deprecated-and-defunct-tools) with a note.
7. Keep section headings plain text (no emoji or symbols such as `&` or `/`) so the contents links keep working.
8. Submit a pull request.

### Guidelines

- Tools must be relevant to OSINT investigations
- Include accurate pricing and, where relevant, a last-checked note
- Write clear, actionable descriptions explaining the OSINT use case
- Place tools in the most relevant category

---

## Disclaimer

This toolkit is intended for **lawful research, journalism, and security purposes only**. Always ensure your use of these tools complies with local laws, platform terms of service, and ethical guidelines. Many tools here can access personal data — including facial recognition and breach data — so handle all information responsibly and consider the human impact of misidentification.

---

## License

This toolkit reference is released under the [MIT License](LICENSE). Individual tools listed here have their own licenses and terms of service.
