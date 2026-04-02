# 🔍 OSINT Nexus — The Ultimate Open Source Intelligence Toolkit

> **A curated, categorized, and comprehensive collection of 200+ OSINT tools for investigators, journalists, researchers, and security professionals.**
>
> Inspired by [Bellingcat's Online Investigation Toolkit](https://www.bellingcat.com/category/resources/how-to/) — improved, expanded, and maintained for the modern OSINT workflow.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📖 Table of Contents

- [How to Use This Toolkit](#how-to-use-this-toolkit)
- [Maps & Geolocation](#-maps--geolocation)
- [Satellite Imagery & Earth Observation](#-satellite-imagery--earth-observation)
- [Social Media Intelligence](#-social-media-intelligence)
- [Username & Identity Search](#-username--identity-search)
- [Facial Recognition & Image Analysis](#-facial-recognition--image-analysis)
- [Reverse Image Search & Verification](#-reverse-image-search--verification)
- [Video Analysis & Verification](#-video-analysis--verification)
- [Transportation Tracking](#-transportation-tracking)
- [Maritime Intelligence](#-maritime-intelligence)
- [Corporate & Financial Intelligence](#-corporate--financial-intelligence)
- [Data Leaks & Breach Intelligence](#-data-leaks--breach-intelligence)
- [Domain, IP & Website Analysis](#-domain-ip--website-analysis)
- [Archiving & Preservation](#-archiving--preservation)
- [Environmental & Wildlife Intelligence](#-environmental--wildlife-intelligence)
- [Conflict, Arms & Munitions](#-conflict-arms--munitions)
- [Sanctions & Politically Exposed Persons](#-sanctions--politically-exposed-persons)
- [Legal & Court Records](#-legal--court-records)
- [Data Visualization & Analysis](#-data-visualization--analysis)
- [Workflow, Note-Taking & Case Management](#-workflow-note-taking--case-management)
- [Browser Extensions & Scrapers](#-browser-extensions--scrapers)
- [Code & Technical Search](#-code--technical-search)
- [Communication & Messaging Intelligence](#-communication--messaging-intelligence)
- [Cryptocurrency & Blockchain](#-cryptocurrency--blockchain)
- [Phone & People Lookup](#-phone--people-lookup)
- [Weather, Time & Shadow Analysis](#-weather-time--shadow-analysis)
- [Miscellaneous & Specialty Tools](#-miscellaneous--specialty-tools)

---

## How to Use This Toolkit

Each tool entry follows this format:

| Field | Meaning |
|-------|---------|
| **Name** | Tool name with link |
| **Description** | What it does and how OSINT professionals use it |
| **Pricing** | 🟢 Free · 🟡 Freemium · 🔴 Paid · 🔵 Open Source |

> **Tip:** Use `Ctrl+F` / `Cmd+F` to quickly find a specific tool.

---

## 🗺️ Maps & Geolocation

Tools for mapping, geolocating imagery, and working with geographic data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Maps](https://maps.google.com) | The most widely used mapping platform. OSINT use: Street View for visual verification, historical imagery, measuring distances, identifying businesses and landmarks. | 🟢 Free |
| [Google Earth Pro](https://www.google.com/earth/versions/#earth-pro) | Desktop application with advanced satellite imagery, historical imagery timeline, 3D terrain, measurement tools, and GIS data import. Essential for geolocation and temporal analysis. | 🟢 Free |
| [Google Earth Engine](https://earthengine.google.com) | Cloud-based platform for planetary-scale geospatial analysis. Access decades of satellite data (Landsat, Sentinel, MODIS) and run custom analyses. Used for environmental monitoring and change detection. | 🟢 Free (for research/non-commercial) |
| [Bing Maps](https://www.bing.com/maps) | Microsoft's mapping platform with Bird's Eye View (oblique aerial imagery) not available on Google Maps. Useful for verifying angles and perspectives. | 🟢 Free |
| [Apple Maps](https://maps.apple.com) | Apple's mapping service with Look Around (street-level imagery). Sometimes has newer imagery than Google in certain areas. Web version available. | 🟢 Free |
| [Baidu Maps](https://map.baidu.com) | China's dominant mapping platform. Essential for investigations involving Chinese locations. Includes Chinese street-level imagery and local business data. | 🟢 Free |
| [Gaode Maps (Amap)](https://www.amap.com) | China's second major mapping platform (Alibaba-owned). Provides detailed Chinese mapping data, traffic info, and POI data not available on Western platforms. | 🟢 Free |
| [Tencent Maps](https://map.qq.com) | Tencent's mapping service. Useful for cross-referencing Chinese locations. Has its own street-level imagery. | 🟢 Free |
| [Yandex Maps](https://yandex.com/maps) | Russia's primary mapping platform. Crucial for investigations in Russia, CIS countries, and Turkey. Offers street-level panoramas and local business data. | 🟢 Free |
| [Wikimapia](https://wikimapia.org) | Collaborative mapping project where users annotate locations. Useful for identifying military bases, factories, and other sites described by locals. | 🟢 Free |
| [OpenStreetMap (via Overpass Turbo)](https://overpass-turbo.eu) | Query and extract specific features from OpenStreetMap's massive open database. Search for specific building types, infrastructure, POIs by attribute. Extremely powerful for targeted geolocation. | 🟢 Free / 🔵 Open Source |
| [Bellingcat OpenStreetMap Search](https://osm-search.bellingcat.com) | Bellingcat's dedicated tool for searching OpenStreetMap data by object type and location. Simplifies complex Overpass queries into a user-friendly interface. | 🟢 Free |
| [Mapillary](https://www.mapillary.com) | Crowdsourced street-level imagery platform (Meta-owned). Covers areas Google Street View doesn't. Images are timestamped and geotagged. | 🟢 Free |
| [KartaView](https://kartaview.org) | Crowdsourced street-level photo platform. Another source of ground-level imagery, especially in Eastern Europe and areas with sparse Google coverage. | 🟢 Free |
| [F4Map](https://demo.f4map.com) | Interactive 3D map rendering OpenStreetMap data. Useful for visualizing building heights, terrain, and urban layouts for geolocation verification. | 🟢 Free |
| [what3words](https://what3words.com) | Divides the world into 3m x 3m squares, each with a unique 3-word address. Used in emergency services and can help pinpoint exact locations. | 🟢 Free (basic) / 🟡 Freemium (API) |
| [GeoHints](https://geohints.com) | A reference guide for GeoGuessr-style geolocation. Contains clues by country including road markings, bollards, utility poles, and signage patterns. Invaluable for image geolocation. | 🟢 Free |
| [MapChecking](https://www.mapchecking.com) | Estimate crowd sizes by drawing an area on a map and adjusting crowd density. Used by journalists to verify protest/rally attendance claims. | 🟢 Free |
| [MapSwitcher](https://github.com/nicbou/MapSwitcher) | Browser extension to switch between map services (Google, Bing, Yandex, etc.) for the same location with one click. Huge time saver. | 🟢 Free / 🔵 Open Source |
| [GovMap](https://www.govmap.gov.il) | Israel's official government mapping portal. Detailed cadastral data, aerial imagery, and infrastructure for Israeli territory. | 🟢 Free |
| [About Maps and Satellites](https://aboutmapsandsatellites.com) | Educational resource explaining how to use maps and satellite imagery for OSINT investigations. Guides on imagery interpretation and geolocation techniques. | 🟢 Free |
| [Convert Geographic Units](https://www.pgc.umn.edu/apps/convert/) | Convert between coordinate formats (decimal degrees, DMS, UTM, MGRS). Essential when working with coordinates from different sources. | 🟢 Free |
| [Geo Data Tool](https://www.geodatatool.com) | IP geolocation lookup and geographic data conversion utility. Map IP addresses to approximate physical locations. | 🟢 Free |
| [Quick Geolocation Search](https://github.com/Quorafind/Quick-Geolocation-Search) | Rapid coordinate-based search tool that queries multiple mapping platforms simultaneously. Speeds up the geolocation workflow. | 🟢 Free / 🔵 Open Source |
| [MW Geofind](https://mattw.io/youtube-geofind/) | Search YouTube videos by geographic location. Find videos uploaded from specific coordinates or within a radius — useful for verifying events. | 🟢 Free |
| [Chronotrains](https://www.chronotrains.com) | Visualize how far you can travel by train from any European station in a given time. Useful for understanding transit possibilities and alibis. | 🟢 Free |
| [License Plate Maps](https://www.licenseplatemaps.com) | Reference for license plate formats by country/state. Helps identify vehicle origin from partial plate visibility in images and video. | 🟢 Free |
| [Instagram Location Search](https://github.com/bellingcat/instagram-location-search) | Search Instagram posts by geographic coordinates. Find user-generated content from specific locations for event verification. | 🟢 Free / 🔵 Open Source |

---

## 🛰️ Satellite Imagery & Earth Observation

Access and analyze satellite imagery for change detection, infrastructure monitoring, and environmental analysis.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Sentinel Hub Playground](https://apps.sentinel-hub.com/sentinel-playground/) | Access and visualize Sentinel-2 satellite imagery with various band combinations (true color, NDVI, false color). 10m resolution, global coverage, updated every 5 days. | 🟢 Free (basic) / 🟡 Freemium (advanced) |
| [NASA Worldview](https://worldview.earthdata.nasa.gov) | Near-real-time satellite imagery from NASA's fleet. Visualize fires, smoke plumes, flooding, and other events. Supports temporal comparison. | 🟢 Free |
| [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov) | Fire Information for Resource Management System. Detect active fires and thermal anomalies worldwide in near-real-time via MODIS and VIIRS. Used to verify conflict/fire events. | 🟢 Free |
| [Planet Labs](https://www.planet.com) | Commercial satellite constellation capturing daily imagery of the entire Earth at 3-5m resolution. Gold standard for monitoring change over time. | 🔴 Paid (journalist/NGO programs available) |
| [Umbra Space](https://umbra.space) | Commercial Synthetic Aperture Radar (SAR) satellite provider. SAR penetrates clouds and captures imagery at night — essential when optical imagery is unavailable. | 🔴 Paid |
| [SkyFi](https://www.skyfi.com) | Marketplace for purchasing satellite imagery from multiple providers (Planet, Airbus, Maxar). Simplifies ordering high-resolution commercial imagery. | 🔴 Paid |
| [Apollo Mapping](https://apollomapping.com) | Satellite and aerial imagery broker offering access to imagery from 30+ providers. Useful for obtaining historical high-res imagery for specific dates. | 🔴 Paid |
| [Earth Explorer (USGS)](https://earthexplorer.usgs.gov) | Free access to the USGS archive of Landsat imagery, aerial photos, and elevation data. Decades of historical imagery. | 🟢 Free |
| [Earth Online (ESA)](https://earth.esa.int) | European Space Agency's platform for accessing Sentinel mission data and other ESA Earth observation datasets. | 🟢 Free |
| [OpenAerialMap](https://openaerialmap.org) | Open repository of publicly licensed aerial and satellite imagery. Includes drone imagery, post-disaster captures, and humanitarian mapping data. | 🟢 Free / 🔵 Open Source |
| [satellites.pro](https://satellites.pro) | Quick access to satellite imagery from Google, Bing, Yandex, and Esri in a single interface. Convenient for rapid comparison. | 🟢 Free |
| [RAMMB SLIDER](https://rammb-slider.cira.colostate.edu) | Real-time weather satellite imagery viewer. Full-disk imagery from GOES, Himawari, and Meteosat. Useful for verifying weather conditions at specific times. | 🟢 Free |
| [Google Flood Hub](https://sites.research.google/floods/) | Google's AI-powered flood forecasting platform. Visualize flood predictions and historical flood data for river basins globally. | 🟢 Free |
| [Radar Interference Tracker](https://ollielballinger.users.earthengine.app/view/interference) | Detect GPS/radar jamming and interference by analyzing Sentinel-1 SAR data. Reveals military electronic warfare activity. Built by Ollie Ballinger. | 🟢 Free |
| [GPSJam](https://gpsjam.org) | Visualize GPS interference and jamming zones worldwide using ADS-B aircraft data. Reveals areas of electronic warfare or intentional disruption. | 🟢 Free |
| [QGIS](https://qgis.org) | Professional open-source Geographic Information System. Full GIS analysis, custom map creation, spatial data processing. The open-source alternative to ArcGIS. | 🟢 Free / 🔵 Open Source |
| [PeakVisor](https://peakvisor.com) | Mountain and terrain identification app. Match mountain silhouettes to geolocate photos taken in mountainous areas. | 🟡 Freemium |
| [ShadeMap](https://shademap.app) | Visualize sun shadows on a 3D map at any date and time. Helps verify when a photo was taken based on shadow direction and length. | 🟢 Free |

---

## 📱 Social Media Intelligence

Tools for searching, monitoring, and analyzing social media platforms.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Twitter Advanced Search](https://twitter.com/search-advanced) | Twitter/X's built-in advanced search. Filter by date range, user, location, engagement, language. Indispensable for timeline reconstruction. | 🟢 Free |
| [Twitter Location Search](https://github.com/bellingcat/twitter-location-search) | Search tweets by geographic coordinates and radius. Find eyewitness content from specific locations. | 🟢 Free / 🔵 Open Source |
| [Who Posted What?](https://whopostedwhat.com) | Facebook search tool by Henk van Ess. Search public Facebook posts by keyword and date without needing a Facebook account. | 🟢 Free |
| [Meta Content Library](https://transparency.meta.com/researchtools/meta-content-library) | Meta's official research API for accessing public content across Facebook and Instagram. Available to qualified researchers. | 🟢 Free (for approved researchers) |
| [Bluesky Insights](https://bsky.jazco.dev) | Analytics and search tool for the Bluesky social network. Explore posts, user networks, and trending content. | 🟢 Free |
| [BskyFollowFinder](https://bsky.thieflord.dev) | Bluesky network analysis tool. Find mutual connections, discover who your follows follow, and map network relationships. | 🟢 Free |
| [BskyThreadReader](https://bskythreadreader.glitch.me) | Read and archive Bluesky threads in a clean format. Useful for preserving threaded discussions. | 🟢 Free |
| [Strava](https://www.strava.com/heatmap) | Fitness tracking platform with a global heatmap showing exercise routes. Has revealed the locations of military bases, secret facilities, and intelligence personnel movements. | 🟡 Freemium |
| [Snap Map](https://map.snapchat.com) | Snapchat's public map showing geotagged Snaps worldwide. Real-time crowd-sourced video and photo content from events, protests, and breaking news. | 🟢 Free |
| [Hoaxy](https://hoaxy.osome.iu.edu) | Visualize the spread of misinformation and fact-checks on Twitter/X. Network analysis of how claims propagate. | 🟢 Free |
| [Skopenow](https://www.skopenow.com) | Professional social media and web investigation platform. Automated collection and analysis across multiple platforms with reporting. | 🔴 Paid |
| [Spot](https://spotthe.bot) | Bot detection tool. Analyze social media accounts for automated behavior patterns and bot-like activity. | 🟢 Free |
| [LinkdTime](https://freegeoip.live/linkedtime/) | Determine when a LinkedIn profile was created based on profile URL ID analysis. | 🟢 Free |
| [Open Measures](https://openmeasures.io) | Search and analyze content from fringe and extremist platforms (Telegram, 4chan, Gab, etc.). Previously known as the Social Media Analysis Toolkit. | 🟡 Freemium |

---

## 👤 Username & Identity Search

Find accounts and digital footprints across platforms.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Search for usernames across 400+ social networks simultaneously. The most popular OSINT username enumeration tool. | 🟢 Free / 🔵 Open Source |
| [Maigret](https://github.com/soxoj/maigret) | Advanced username search across 2500+ sites. Fork of Sherlock with additional features including profile page parsing and data extraction. | 🟢 Free / 🔵 Open Source |
| [WhatsMyName](https://whatsmyname.app) | Username enumeration tool checking 600+ websites. Maintained with a focus on reducing false positives. | 🟢 Free / 🔵 Open Source |
| [Namechk](https://namechk.com) | Check username and domain availability across dozens of platforms simultaneously. Quick way to map a person's online presence. | 🟢 Free |
| [Blackbird](https://github.com/p1ngul1n0/blackbird) | OSINT tool for fast username searching across 500+ sites. Supports Tor routing for anonymous searches. | 🟢 Free / 🔵 Open Source |
| [NeutrOSINT](https://github.com/JEROMEBSN/NeutrOSINT) | Multi-purpose OSINT tool combining username search, email lookup, phone lookup, and IP analysis in one interface. | 🟢 Free / 🔵 Open Source |
| [Name Variant Search](https://namevariants.com) | Generate name variations, transliterations, and alternative spellings. Essential when searching for individuals across different languages and alphabets. | 🟢 Free |
| [Ghunt](https://github.com/mxrch/GHunt) | Google account investigation tool. Extract information from Google accounts including profile photos, Maps reviews, and Google Calendar data. | 🟢 Free / 🔵 Open Source |
| [IDN Checker](https://www.punycoder.com) | Detect internationalized domain name (IDN) homograph attacks. Identifies visually similar characters used in phishing domains. | 🟢 Free |

---

## 🧑‍🦰 Facial Recognition & Image Analysis

Tools for face matching, comparison, and recognition.

| Tool | Description | Pricing |
|------|-------------|---------|
| [PimEyes](https://pimeyes.com) | Reverse face search engine. Upload a face photo to find where that face appears online. Extremely powerful and controversial. | 🟡 Freemium (limited free) / 🔴 Paid |
| [FaceCheck.ID](https://facecheck.id) | Reverse face search across social media, mugshots, and news. Alternative to PimEyes with different source databases. | 🟡 Freemium |
| [Search4Faces](https://search4faces.com) | Facial recognition search engine focused on Russian social networks (VK, OK.ru). Covers ~500M+ profile photos. | 🟢 Free (limited) / 🟡 Freemium |
| [Face Comparison by ToolPie](https://www.toolpie.com/face-comparison) | Compare two face images for similarity. Free client-side face comparison without uploading to servers. | 🟢 Free |

---

## 🔎 Reverse Image Search & Verification

Trace the origin of images, detect manipulation, and verify visual content.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Lens](https://lens.google.com) | Google's visual search tool. Identify objects, landmarks, text, and find visually similar images. Also extracts text from images (OCR). | 🟢 Free |
| [TinEye](https://tineye.com) | Dedicated reverse image search engine. Finds exact and modified matches. Unique "oldest" sort feature shows the first known appearance of an image online. | 🟢 Free (basic) / 🔴 Paid (API) |
| [Search by Image (Browser Extension)](https://github.com/nicbou/reverse-image-search) | Browser extension that lets you right-click any image and reverse-search it on Google, Yandex, TinEye, Bing, and more simultaneously. | 🟢 Free / 🔵 Open Source |
| [Forensically](https://29a.ch/photo-forensics/) | Browser-based image forensics tool. Error Level Analysis (ELA), clone detection, metadata extraction, noise analysis. Helps detect image manipulation. | 🟢 Free |
| [ExifTool](https://exiftool.org) | The gold standard for reading, writing, and editing metadata in image, video, and document files. Extract GPS coords, camera model, timestamps, and more. | 🟢 Free / 🔵 Open Source |
| [xIFr](https://github.com/nicbou/xIFr) | Firefox extension for viewing EXIF and metadata directly in the browser. Quick metadata inspection without downloading files. | 🟢 Free / 🔵 Open Source |
| [InVID](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Verification plugin for journalists. Video/image keyframe extraction, reverse image search, metadata analysis, and magnification tools in one package. | 🟢 Free |
| [Pinpoint](https://journaliststudio.google.com/pinpoint/) | Google's AI-powered document and image analysis tool for journalists. OCR, entity extraction, and search across large document collections. | 🟢 Free |
| [AutoStitch](http://matthewalunbrown.com/autostitch/autostitch.html) | Automatic panorama stitching software. Combine multiple overlapping images into a single panorama for spatial context. | 🟢 Free |
| [Hugin](https://hugin.sourceforge.io) | Open-source panoramic photo stitcher. Advanced control over image alignment and projection — useful for reconstructing scenes from multiple photos. | 🟢 Free / 🔵 Open Source |
| [PixPlot](https://dhlab.yale.edu/projects/pixplot/) | Machine learning-based tool for visualizing and clustering large image collections. Plot thousands of images by visual similarity. | 🟢 Free / 🔵 Open Source |
| [RootAbout](https://rootabout.com) | Reverse image search for book covers and artwork. Search by ISBN, DOI, or image to identify publications. | 🟢 Free |

---

## 🎬 Video Analysis & Verification

Analyze, verify, and extract data from video content.

| Tool | Description | Pricing |
|------|-------------|---------|
| [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Chrome/Firefox plugin for video verification. Extract keyframes from YouTube/Facebook/Twitter videos, perform reverse image search on frames, and analyze metadata. | 🟢 Free |
| [Azure AI Video Indexer](https://vi.microsoft.com) | Microsoft's AI-powered video analysis. Extracts faces, text (OCR), objects, scenes, spoken words (transcription), and sentiments from video. | 🟡 Freemium (10 hours free) / 🔴 Paid |
| [Twitter Video Downloader](https://twittervideodownloader.com) | Download videos from Twitter/X for offline analysis and archiving. Preserves original quality. | 🟢 Free |

---

## ✈️ Transportation Tracking

Track aircraft, vehicles, and land transportation.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Flightradar24](https://www.flightradar24.com) | Real-time global flight tracker using ADS-B data. Track military/government flights, identify aircraft over conflict zones, and access flight history. | 🟡 Freemium / 🔴 Paid (premium history) |
| [FlightAware](https://flightaware.com) | Flight tracking with extensive US coverage. Detailed flight history, route analysis, and airport activity. Preferred by US-focused investigators. | 🟡 Freemium / 🔴 Paid |
| [OrbTrack](https://www.orbtrack.org) | Real-time satellite tracking. Visualize the position and orbit of satellites, the ISS, and space debris. Verify satellite pass times. | 🟢 Free |
| [AllTrails](https://www.alltrails.com) | Hiking and trail map platform. Identify trails and paths visible in imagery. User-uploaded photos geotagged along routes can provide ground-level context. | 🟡 Freemium |

---

## 🚢 Maritime Intelligence

Track ships, monitor maritime activity, and investigate vessel movements.

| Tool | Description | Pricing |
|------|-------------|---------|
| [MarineTraffic](https://www.marinetraffic.com) | Global ship tracking using AIS data. Vessel positions, port calls, voyage history, and ownership details. The standard for maritime OSINT. | 🟡 Freemium / 🔴 Paid (full history) |
| [VesselFinder](https://www.vesselfinder.com) | Real-time vessel tracking with AIS data. Free tier offers good coverage. Port arrival/departure data and vessel details. | 🟡 Freemium |
| [ShipFinder](https://shipfinder.co) | Simplified vessel tracking platform. Good for quick lookups of vessel positions and basic voyage information. | 🟡 Freemium |
| [Equasis](https://www.equasis.org) | Free maritime safety database. Ship inspection records, flag history, classification, and ownership data. Run by the European Maritime Safety Agency. | 🟢 Free (registration required) |
| [Global Fishing Watch](https://globalfishingwatch.org/map/) | Visualize global fishing vessel activity. Detect illegal fishing, transshipment events, and track fishing fleet movements via AIS and VMS data. | 🟢 Free |
| [Navtex](https://www.navtex.net) | Maritime navigational warning system. Monitor maritime safety information, coastal warnings, and navigational hazards. | 🟢 Free |

---

## 🏢 Corporate & Financial Intelligence

Investigate companies, beneficial ownership, trade relationships, and financial data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenCorporates](https://opencorporates.com) | World's largest open database of companies. 200M+ company records from 140+ jurisdictions. Free basic search; bulk data requires subscription. | 🟡 Freemium |
| [Companies House (UK)](https://www.gov.uk/government/organisations/companies-house) | UK's official company register. Free access to filings, directors, ownership, and financial statements for all UK companies. | 🟢 Free |
| [ICIJ Offshore Leaks Database](https://offshoreleaks.icij.org) | Searchable database from Panama Papers, Paradise Papers, Pandora Papers, and other major leaks. Explore offshore entities, intermediaries, and beneficial owners. | 🟢 Free |
| [OpenSecrets](https://www.opensecrets.org) | US political spending and lobbying data. Track campaign donations, lobbying expenditures, and the financial influence of organizations on US politics. | 🟢 Free |
| [LittleSis](https://littlesis.org) | Free database mapping relationships between powerful people and organizations. Visualize corporate boards, political connections, and influence networks. | 🟢 Free |
| [North Data](https://www.northdata.com) | European company information platform. Beneficial ownership, financial data, network graphs, and corporate hierarchies for EU companies. | 🟡 Freemium / 🔴 Paid |
| [Open Ownership](https://www.openownership.org) | Global beneficial ownership data. Track the real humans behind corporate structures across multiple jurisdictions. | 🟢 Free |
| [EU Consolidated Corporate Registers](https://e-justice.europa.eu/489/EN/business_registers__search_for_a_company_in_the_eu) | Access point for company registers across all EU member states. Direct links to each country's official business register. | 🟢 Free |
| [Wikipedia List of Company Registers](https://en.wikipedia.org/wiki/List_of_company_registers) | Comprehensive list of company registers worldwide. Useful starting point when investigating companies in unfamiliar jurisdictions. | 🟢 Free |
| [EDGAR (SEC)](https://www.sec.gov/edgar) | US Securities and Exchange Commission's database. All public company filings including annual reports, insider trading, and ownership disclosures. | 🟢 Free |
| [EDGAR Suite (Full-Text Search)](https://efts.sec.gov/LATEST/search-index?q=) | Full-text search across all SEC EDGAR filings. Search for names, companies, or terms across millions of documents. | 🟢 Free |
| [ImportGenius](https://www.importgenius.com) | Search US and international import/export shipping records. Track supply chains, identify trading partners, and investigate smuggling. | 🔴 Paid |
| [ImportYeti](https://www.importyeti.com) | Free US import/export record search. Find suppliers and buyers based on customs data. Good free alternative to ImportGenius. | 🟢 Free |
| [Global Suppliers Online](https://www.globalsuppliersonline.com) | Database of global manufacturers and suppliers. Investigate supply chain relationships and find company connections. | 🟢 Free |
| [UN Comtrade Database](https://comtradeplus.un.org) | United Nations international trade statistics. Bilateral trade flows between countries for specific commodities. Detect sanctions evasion patterns. | 🟢 Free |
| [OCCRP Aleph](https://aleph.occrp.org) | OCCRP's investigative data platform. Search across leaked databases, corporate registries, court records, and other data sources. | 🟢 Free |
| [The Information Laundromat](https://www.informationlaundromat.com) | Track laundered narratives and coordinated information operations. Analyze how disinformation is packaged and distributed. | 🟢 Free |

---

## 🔓 Data Leaks & Breach Intelligence

Search leaked databases and credential breaches for investigative purposes.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if an email or phone number appears in known data breaches. Created by Troy Hunt. The most trusted breach notification service. | 🟢 Free |
| [DeHashed](https://dehashed.com) | Search engine for leaked databases. Search by email, username, name, IP, phone, address, or password hash. | 🔴 Paid |
| [Leak-Lookup](https://leak-lookup.com) | Database breach search engine. Query leaked data by email, username, keyword, domain, or password. | 🟡 Freemium / 🔴 Paid |
| [Intelx.io (Intelligence X)](https://intelx.io) | Search engine for leaked data, darknet content, and OSINT data. Archives Tor sites, paste sites, and breach data. Powerful but expensive. | 🟡 Freemium / 🔴 Paid |
| [Index Database](https://indexdb.org) | Directory of publicly available database dumps and data breach information. | 🟢 Free |
| [DiscordLeaks](https://discordleaks.unicornriot.ninja) | Searchable archive of leaked Discord server messages from extremist groups, published by Unicorn Riot. | 🟢 Free |

---

## 🌐 Domain, IP & Website Analysis

Investigate websites, domains, infrastructure, and technology stacks.

| Tool | Description | Pricing |
|------|-------------|---------|
| [DomainTools Whois Lookup](https://whois.domaintools.com) | Industry-leading WHOIS lookup with historical records. Track domain ownership changes over time, DNS history, and connected domains. | 🟡 Freemium / 🔴 Paid |
| [ICANN Lookup](https://lookup.icann.org) | Official ICANN WHOIS lookup. The authoritative source for domain registration data. | 🟢 Free |
| [Whoxy](https://www.whoxy.com) | WHOIS search with reverse lookup capabilities. Find all domains registered by a person/email/company. Affordable API. | 🟡 Freemium / 🔴 Paid |
| [Urlscan.io](https://urlscan.io) | Scan and analyze websites. See what a URL loads, including DOM, cookies, requests, and screenshots — without visiting it yourself. | 🟡 Freemium |
| [PublicWWW](https://publicwww.com) | Search the source code of websites. Find sites using specific analytics IDs, ad codes, or code snippets. Connect websites to the same operator. | 🟡 Freemium / 🔴 Paid |
| [What CMS](https://whatcms.org) | Detect the Content Management System a website uses. Also identifies hosting providers, themes, and plugins. | 🟢 Free |
| [Lumen](https://lumendatabase.org) | Database of legal takedown requests (DMCA, copyright, defamation). Reveals what content was removed and why — useful for uncovering suppressed information. | 🟢 Free |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scan Git repositories, S3 buckets, and other sources for exposed API keys, passwords, and secrets. | 🟢 Free / 🔵 Open Source |

---

## 📦 Archiving & Preservation

Capture and preserve web content before it disappears.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Wayback Machine (Internet Archive)](https://web.archive.org) | The most comprehensive web archive. Billions of saved web pages going back to 1996. View how websites looked at specific dates. | 🟢 Free |
| [Archive.today](https://archive.today) | On-demand webpage snapshot service. Creates permanent, frozen copies of web pages. Bypasses paywalls on archived content. | 🟢 Free |
| [Web Archives (aggregator)](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives) | Directory of web archiving initiatives worldwide. Find regional and specialized web archives beyond the Internet Archive. | 🟢 Free |
| [Hunchly](https://www.hunchly.com) | Automated web capture tool for investigators. Runs in the background during browsing, saving every page visited with timestamps and hashes for legal evidence. | 🔴 Paid (~$130/year) |
| [Auto Archiver](https://github.com/bellingcat/auto-archiver) | Bellingcat's automated archiving tool. Bulk archive URLs from spreadsheets to the Wayback Machine, archive.today, or local storage. | 🟢 Free / 🔵 Open Source |
| [Zotero](https://www.zotero.org) | Reference manager and web page archiver. Save full snapshots of web pages with metadata. Organize research with tags and collections. | 🟢 Free / 🔵 Open Source |
| [Distill.io](https://distill.io) | Web page change monitoring. Get notified when specific parts of web pages change — useful for tracking profile updates, price changes, or content edits. | 🟡 Freemium |

---

## 🌍 Environmental & Wildlife Intelligence

Tools for investigating environmental crime, deforestation, wildlife trafficking, and ecological data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Global Forest Watch](https://www.globalforestwatch.org) | Monitor deforestation in near-real-time. Tree cover loss alerts, fire data, and land use analysis. Used by investigators tracking illegal logging. | 🟢 Free |
| [Resource Watch](https://resourcewatch.org) | Hundreds of datasets visualized on maps: air quality, deforestation, water stress, food production. World Resources Institute platform. | 🟢 Free |
| [Aqueduct Water Risk Atlas](https://www.wri.org/aqueduct) | Map global water stress, flood risk, and drought severity. Useful for environmental investigations and climate impact analysis. | 🟢 Free |
| [Environmental Justice Atlas](https://ejatlas.org) | Global map of environmental conflicts. Documents ecological disputes, pollution incidents, and land-grabbing with detailed case studies. | 🟢 Free |
| [Global Monitoring System (ECOSOLVE)](https://ecosolve.org) | Environmental monitoring platform tracking pollution, emissions, and ecological health indicators. | 🟢 Free |
| [CITES Trade Database](https://trade.cites.org) | International trade in endangered species. Search permits and shipments regulated under CITES. Track wildlife trafficking patterns. | 🟢 Free |
| [Species+](https://speciesplus.net) | CITES species database with trade data, distribution maps, and legal status. Identify protected species encountered in investigations. | 🟢 Free |
| [WildEye](https://wildlifejustice.org/wildeye/) | Wildlife crime monitoring tool by Wildlife Justice Commission. Track seizures, arrests, and prosecutions related to wildlife trafficking. | 🟢 Free |
| [Wildlife Trade Portal](https://www.wildlifetradeportal.org) | Monitor global wildlife trade with species-level data. Analyze legal and illegal trade flows. | 🟢 Free |
| [World Database on Protected Areas](https://www.protectedplanet.net) | Global database of terrestrial and marine protected areas. Verify whether activities are occurring in protected zones. | 🟢 Free |
| [Merlin (Cornell Lab)](https://merlin.allaboutbirds.org) | Bird identification app using AI. Identify birds by photo or sound. Relevant for verifying location claims using bird species present in media. | 🟢 Free |
| [Locust Hub (FAO)](https://locust-hub-hqfao.hub.arcgis.com) | Track desert locust swarms globally. FAO platform monitoring locust outbreaks and their impact on food security. | 🟢 Free |
| [EIA Global Environmental Crime Tracker](https://eia-international.org) | Environmental Investigation Agency's tracker of environmental crimes including illegal logging, wildlife trafficking, and climate crimes. | 🟢 Free |

---

## 💣 Conflict, Arms & Munitions

Identify weapons, munitions, and track conflict events.

| Tool | Description | Pricing |
|------|-------------|---------|
| [ACLED (Armed Conflict Location & Event Data)](https://acleddata.com) | Real-time data on political violence and protest events worldwide. Detailed event-level data with precise geolocations. The standard for conflict tracking. | 🟢 Free (registration required) |
| [Liveuamap](https://liveuamap.com) | Real-time interactive map of conflict events, protests, and security incidents. Covers Ukraine, Middle East, Africa, and other conflict zones. | 🟢 Free |
| [CAT UXO](https://cat-uxo.com) | Collaborative Arms Transparency — UXO identification tool. Identify unexploded ordnance and munitions found in conflict zones from photos. | 🟢 Free |
| [Bulletpicker.com](https://bulletpicker.com) | US military ordnance identification database. Detailed technical data on bombs, rockets, mines, and other military ordnance. | 🟢 Free |
| [Open Source Munitions Portal](https://www.omsportal.org) | Open database for identifying munitions from images. Collaborative platform for weapons identification in conflict documentation. | 🟢 Free |
| [UNOSAT Analyses](https://unosat.org/products/) | United Nations satellite-based damage assessments and situational analyses for conflict zones and natural disasters. | 🟢 Free |
| [Atlos](https://www.atlos.org) | Collaborative platform for visual investigation and geolocation. Open-source tool for verifying conflict incidents from media. | 🟢 Free / 🔵 Open Source |

---

## 🚫 Sanctions & Politically Exposed Persons

Check sanctions lists, PEP databases, and politically exposed individuals.

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenSanctions](https://www.opensanctions.org) | Unified database of international sanctions, PEPs, and persons of interest. Aggregates data from 30+ official sources. Free and open source. | 🟢 Free / 🔵 Open Source |
| [SanctionsExplorer](https://sanctionsexplorer.org) | Visual search and exploration of OFAC sanctions data. Explore networks and connections between sanctioned entities. | 🟢 Free |
| [EU Sanctions Map](https://sanctionsmap.eu) | Official EU sanctions visualization. See all EU restrictive measures by country, regime, and sanction type. | 🟢 Free |
| [RuPEP](https://rupep.org) | Russian and Belarusian politically exposed persons database. Track Russian oligarchs, officials, and their connections. | 🟢 Free |

---

## ⚖️ Legal & Court Records

Access court filings, legal documents, and law enforcement data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [US Court Case Databases (PACER/RECAP)](https://www.courtlistener.com) | Access US federal court records. CourtListener (free) and PACER (paid). Search millions of court filings, opinions, and dockets. | 🟢 Free (CourtListener) / 🔴 Paid (PACER) |
| [Police Records Access Project](https://www.policerec.com) | Platform for accessing US police records including use-of-force incidents, misconduct complaints, and department policies. | 🟢 Free |
| [Uwazi](https://www.uwazi.io) | Open-source document management for human rights organizations. Organize, analyze, and publish collections of legal and investigative documents. | 🟢 Free / 🔵 Open Source |

---

## 📊 Data Visualization & Analysis

Create charts, graphs, network diagrams, and visual presentations of investigative data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Maltego](https://www.maltego.com) | The industry-standard OSINT link analysis and visualization platform. Map relationships between people, companies, domains, IPs, and more. Transform-based data gathering. | 🟡 Freemium (Community Edition) / 🔴 Paid |
| [Gephi](https://gephi.org) | Open-source network analysis and visualization software. Create complex network graphs from large datasets. Supports social network analysis. | 🟢 Free / 🔵 Open Source |
| [Datawrapper](https://www.datawrapper.de) | Create publication-ready charts, maps, and tables. Used by major newsrooms. Clean output, no coding required. | 🟡 Freemium |
| [RAWGraphs](https://rawgraphs.io) | Open-source data visualization framework. Create unconventional chart types from spreadsheet data. Bridge between data and vector graphics. | 🟢 Free / 🔵 Open Source |
| [Blender](https://www.blender.org) | Professional 3D modeling and rendering software. Used in OSINT for 3D crime scene reconstruction, terrain modeling, and visual recreations of events. | 🟢 Free / 🔵 Open Source |

---

## 📝 Workflow, Note-Taking & Case Management

Organize investigations, manage evidence, and maintain operational workflows.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Obsidian](https://obsidian.md) | Markdown-based knowledge management with graph-based note linking. Build interconnected investigation notebooks. Plugin ecosystem extends functionality for OSINT. | 🟢 Free (personal) / 🔴 Paid (sync/commercial) |
| [Logseq](https://logseq.com) | Open-source outliner and knowledge management tool. Privacy-first (local storage), bidirectional linking, and daily journals for investigation logging. | 🟢 Free / 🔵 Open Source |
| [Osint Tools Map](https://osinttools.io) | Visual map of OSINT tools organized by category. Useful for discovering new tools and understanding the OSINT landscape. | 🟢 Free |
| [Hunchly](https://www.hunchly.com) | Web capture and case management tool for investigations. Automatically saves and hashes every page visited. Court-admissible evidence chain. | 🔴 Paid |

---

## 🧩 Browser Extensions & Scrapers

Extensions and tools for data extraction, monitoring, and browser-based investigation.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Instant Data Scraper](https://chrome.google.com/webstore/detail/instant-data-scraper/ofaokhiedipichpaobibbnahnkdoiiah) | AI-powered browser extension that automatically detects tables and lists on web pages and exports them to CSV/Excel. No coding required. | 🟢 Free |
| [Zeeschuimer](https://github.com/digitalmethodsinitiative/zeeschuimer) | Browser extension that intercepts social media API traffic and saves it as structured data. Captures data from TikTok, Instagram, Twitter, LinkedIn, and more. | 🟢 Free / 🔵 Open Source |
| [InstaLoader](https://instaloader.github.io) | Download Instagram profiles, posts, stories, reels, IGTV, and metadata. Python-based command-line tool for bulk Instagram data collection. | 🟢 Free / 🔵 Open Source |
| [Discord Chat Exporter](https://github.com/Tyrrrz/DiscordChatExporter) | Export Discord chat history in HTML, JSON, CSV, or plain text. Preserve Discord evidence for investigations. | 🟢 Free / 🔵 Open Source |

---

## 💻 Code & Technical Search

Search code repositories, technical infrastructure, and source code.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Grep.app](https://grep.app) | Search across 500K+ public Git repositories. Find API keys, configuration files, code snippets, and developer attributions. | 🟢 Free |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scan Git repos, S3 buckets, Docker images, and CI/CD systems for exposed secrets, API keys, and credentials. | 🟢 Free / 🔵 Open Source |

---

## 💬 Communication & Messaging Intelligence

Investigate Telegram, messaging platforms, and communication channels.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Telegago](https://cse.google.com/cse?cx=006368593537057042503:efxu7xprihg) | Google Custom Search Engine focused on Telegram content. Search Telegram channels and groups via indexed web content. | 🟢 Free |
| [TGStat](https://tgstat.com) | Telegram analytics platform. Search channels/groups, view subscriber growth, engagement metrics, and cross-posting patterns. | 🟡 Freemium |
| [TelegramDB](https://www.telegramdb.org) | Search and explore Telegram groups and channels. Discover public Telegram communities by keyword. | 🟢 Free |
| [Telemetrio](https://telemetr.io) | Telegram channel analytics. Track subscriber dynamics, post reach, engagement, and content patterns. | 🟡 Freemium |
| [Telemetry (Telegram)](https://telemetry.so) | Another Telegram analytics platform offering channel statistics, audience overlap analysis, and growth tracking. | 🟡 Freemium |
| [Telepathy](https://github.com/jordanwildon/Telepathy) | OSINT toolkit for Telegram investigations. Extract members, messages, and media from Telegram groups and channels. | 🟢 Free / 🔵 Open Source |
| [Telegram Group Joiner](https://github.com/th3unkn0n/TeleGram-Scraper) | Tool for discovering and joining Telegram groups related to specific topics. Used for infiltration research and monitoring. | 🟢 Free / 🔵 Open Source |
| [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker) | Check if phone numbers are associated with Telegram accounts. Bellingcat tool for linking phone numbers to Telegram identities. | 🟢 Free / 🔵 Open Source |
| [4plebs](https://4plebs.org) | Archive of 4chan boards (/pol/, /x/, /sp/, etc.). Searchable by keyword, date, and image hash. Essential for tracking extremist content and disinformation origins. | 🟢 Free |

---

## ⛓️ Cryptocurrency & Blockchain

Investigate blockchain transactions, wallets, and crypto-related activity.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Etherscan](https://etherscan.io) | Ethereum blockchain explorer. Track ETH transactions, wallet balances, smart contracts, and token transfers. The standard for Ethereum investigation. | 🟢 Free |
| [527 Explorer](https://527explorer.com) | Explore 527 political organizations and their blockchain/financial activities. Track dark money in US politics. | 🟢 Free |

---

## 📞 Phone & People Lookup

Investigate phone numbers, find people, and verify identities.

| Tool | Description | Pricing |
|------|-------------|---------|
| [TrueCaller](https://www.truecaller.com) | Identify unknown phone numbers using crowdsourced caller ID database of 300M+ users. Reverse phone lookup. | 🟡 Freemium |
| [Hitta.se](https://www.hitta.se) | Swedish person and business search. Find individuals, phone numbers, and addresses in Sweden's public records. | 🟢 Free |
| [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker) | Check whether phone numbers are linked to Telegram accounts and retrieve associated usernames. | 🟢 Free / 🔵 Open Source |

---

## ☀️ Weather, Time & Shadow Analysis

Verify timestamps, analyze lighting conditions, and determine when photos/videos were taken.

| Tool | Description | Pricing |
|------|-------------|---------|
| [SunCalc](https://www.suncalc.org) | Calculate sun position, golden hour, sunrise/sunset for any location and date. Essential for chronolocation — determining when a photo was taken based on sun position. | 🟢 Free |
| [Shadow Finder](https://shadowfinder.com) | Estimate the time a photo was taken by analyzing shadow length and direction combined with location data. | 🟢 Free |
| [ShadowMap](https://shadowmap.org) | 3D shadow simulation for any location and time. Visualize how buildings and terrain cast shadows throughout the day. | 🟢 Free |
| [ShadeMap](https://shademap.app) | Interactive shade and shadow visualization on a 3D globe. Calculate shadow coverage at any point in time for geolocation and chronolocation. | 🟢 Free |

---

## 🧰 Miscellaneous & Specialty Tools

Specialized tools that don't fit neatly into other categories.

| Tool | Description | Pricing |
|------|-------------|---------|
| [China-related Resources](https://docs.google.com/spreadsheets/d/1Ekwz82FJnKbVp3IcDJ8N4NdRmxfgOImM8pNqaLaHM3c) | Curated collection of OSINT resources specifically for investigating Chinese entities, including social media platforms, corporate registries, and mapping tools. | 🟢 Free |
| [Hitta.se](https://www.hitta.se) | Swedish public records search including person lookup, address verification, and business data. | 🟢 Free |
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if personal data has been compromised in known data breaches. Useful as a starting point for identity verification. | 🟢 Free |

---

## 📋 Tool Count by Pricing

| Type | Count | Description |
|------|-------|-------------|
| 🟢 Free | ~120 | Completely free to use |
| 🔵 Open Source | ~40 | Free and open source (many overlap with Free) |
| 🟡 Freemium | ~30 | Free tier with paid premium features |
| 🔴 Paid | ~15 | Requires subscription or payment |

---

## 🤝 Contributing

Found a tool that should be listed here? Want to update a description or pricing?

1. Fork this repository
2. Add the tool in the appropriate category
3. Follow the existing format: `| [Tool Name](URL) | Description | Pricing |`
4. Submit a Pull Request

### Guidelines

- Tools must be relevant to OSINT investigations
- Include accurate pricing information
- Write clear, actionable descriptions explaining the OSINT use case
- Place tools in the most relevant category

---

## ⚠️ Disclaimer

This toolkit is intended for **lawful research, journalism, and security purposes only**. Always ensure your use of these tools complies with local laws, terms of service, and ethical guidelines. Many tools in this list can access personal data — handle all information responsibly.

---

## 📜 License

This toolkit reference is released under [MIT License](LICENSE). Individual tools listed here have their own licenses and terms of service.

---

> **Built for [OSINT Nexus](https://github.com/your-repo) — Professional OSINT Case & Evidence Management**
