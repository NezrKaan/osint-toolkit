# 🔍 OSINT Nexus — The Ultimate Open Source Intelligence Toolkit

> **A curated, categorized, and comprehensive collection of 230+ OSINT tools for investigators, journalists, researchers, and security professionals.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> **🗓️ Last verified: 14 July 2026.** This edition was reviewed to remove dead links, flag tools whose status changed, and add current staples that were missing (Shodan, Censys, crt.sh, GrayHatWarfare, SpiderFoot, Epieos, Holehe, WiGLE, GeoSpy and more). The highest-risk entries (Twitter/X-API-dependent tools, small indie projects, and tools with pricing changes) were checked individually; the remainder were reviewed against established OSINT community sources. Tool availability changes fast — if you hit a dead link, please open an issue.

---

## 📖 Table of Contents

- [How to Use This Toolkit](#how-to-use-this-toolkit)
- [Maps & Geolocation](#-maps--geolocation)
- [Satellite Imagery & Earth Observation](#-satellite-imagery--earth-observation)
- [Social Media Intelligence](#-social-media-intelligence)
- [Username & Identity Search](#-username--identity-search)
- [Email, Phone & People Lookup](#-email-phone--people-lookup)
- [Facial Recognition & Image Analysis](#-facial-recognition--image-analysis)
- [Reverse Image Search & Verification](#-reverse-image-search--verification)
- [Video Analysis & Verification](#-video-analysis--verification)
- [Audio Analysis & Acoustic OSINT](#-audio-analysis--acoustic-osint)
- [Transportation Tracking](#-transportation-tracking)
- [Maritime Intelligence](#-maritime-intelligence)
- [Corporate & Financial Intelligence](#-corporate--financial-intelligence)
- [Data Leaks & Breach Intelligence](#-data-leaks--breach-intelligence)
- [Domain, IP, Infrastructure & Device Search](#-domain-ip-infrastructure--device-search)
- [Archiving & Preservation](#-archiving--preservation)
- [Environmental & Wildlife Intelligence](#-environmental--wildlife-intelligence)
- [Conflict, Arms & Munitions](#-conflict-arms--munitions)
- [Sanctions & Politically Exposed Persons](#-sanctions--politically-exposed-persons)
- [Legal & Court Records](#-legal--court-records)
- [Data Visualization & Analysis](#-data-visualization--analysis)
- [Frameworks, Automation & Case Management](#-frameworks-automation--case-management)
- [Browser Extensions & Scrapers](#-browser-extensions--scrapers)
- [Code & Technical Search](#-code--technical-search)
- [Communication & Messaging Intelligence](#-communication--messaging-intelligence)
- [Cryptocurrency & Blockchain](#-cryptocurrency--blockchain)
- [Weather, Time & Shadow Analysis](#-weather-time--shadow-analysis)
- [Miscellaneous & Specialty Tools](#-miscellaneous--specialty-tools)
- [Deprecated / No Longer Available](#-deprecated--no-longer-available)

---

## How to Use This Toolkit

Each tool entry follows this format:

| Field | Meaning |
|-------|---------|
| **Name** | Tool name with link |
| **Description** | What it does and how OSINT professionals use it |
| **Pricing** | 🟢 Free · 🟡 Freemium · 🔴 Paid · 🔵 Open Source |

**Status flags used in this edition:**

- ✅ Verified live at time of review (unmarked entries are assumed live)
- ⚠️ Still up but with an important caveat (functionality reduced, ownership/pricing changed, reliability degraded)
- ⚫ No longer available / effectively defunct — moved to the [Deprecated](#-deprecated--no-longer-available) section

> **Tip:** Use `Ctrl+F` / `Cmd+F` to quickly find a specific tool.

---

## 🗺️ Maps & Geolocation

Tools for mapping, geolocating imagery, and working with geographic data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Maps](https://maps.google.com) | The most widely used mapping platform. OSINT use: Street View for visual verification, historical imagery, measuring distances, identifying businesses and landmarks. | 🟢 Free |
| [Google Earth Pro](https://www.google.com/earth/versions/#earth-pro) | Desktop application with advanced satellite imagery, historical imagery timeline, 3D terrain, measurement tools, and GIS data import. Essential for geolocation and temporal analysis. | 🟢 Free |
| [Google Earth Engine](https://earthengine.google.com) | Cloud platform for planetary-scale geospatial analysis. Access decades of satellite data (Landsat, Sentinel, MODIS) and run custom analyses. Used for environmental monitoring and change detection. | 🟢 Free (research/non-commercial) |
| [Bing Maps](https://www.bing.com/maps) | Microsoft's mapping platform with Bird's Eye View (oblique aerial imagery) not available on Google Maps. Useful for verifying angles and perspectives. | 🟢 Free |
| [Apple Maps](https://maps.apple.com) | Apple's mapping service with Look Around (street-level imagery). Sometimes has newer imagery than Google in certain areas. Web version available. | 🟢 Free |
| [Baidu Maps](https://map.baidu.com) | China's dominant mapping platform. Essential for investigations involving Chinese locations. Includes Chinese street-level imagery and local business data. | 🟢 Free |
| [Gaode Maps (Amap)](https://www.amap.com) | China's second major mapping platform (Alibaba-owned). Detailed Chinese mapping data, traffic info, and POI data not on Western platforms. | 🟢 Free |
| [Tencent Maps](https://map.qq.com) | Tencent's mapping service. Useful for cross-referencing Chinese locations. Has its own street-level imagery. | 🟢 Free |
| [Yandex Maps](https://yandex.com/maps) | Russia's primary mapping platform. Crucial for investigations in Russia, CIS countries, and Turkey. Street-level panoramas and local business data. | 🟢 Free |
| [Wikimapia](https://wikimapia.org) | Collaborative mapping project where users annotate locations. Useful for identifying military bases, factories, and other sites described by locals. | 🟢 Free |
| [OpenStreetMap (via Overpass Turbo)](https://overpass-turbo.eu) | Query and extract specific features from OpenStreetMap's open database. Search building types, infrastructure, and POIs by attribute. Extremely powerful for targeted geolocation. | 🟢 Free / 🔵 Open Source |
| [Overpass Ultra](https://overpass-ultra.us) | A modern Overpass Turbo alternative with MapLibre rendering, shareable queries, and improved styling. Handy for infrastructure-pattern geolocation. | 🟢 Free / 🔵 Open Source |
| [Bellingcat OpenStreetMap Search](https://osm-search.bellingcat.com) | Bellingcat's tool for searching OpenStreetMap data by object type and location. Simplifies complex Overpass queries into a friendly interface. | 🟢 Free |
| [Mapillary](https://www.mapillary.com) | Crowdsourced street-level imagery (Meta-owned). Covers areas Google Street View doesn't. Images are timestamped and geotagged. | 🟢 Free |
| [KartaView](https://kartaview.org) | Crowdsourced street-level photo platform. Ground-level imagery, especially in Eastern Europe and areas with sparse Google coverage. | 🟢 Free |
| [F4Map](https://demo.f4map.com) | Interactive 3D map rendering OpenStreetMap data. Useful for visualizing building heights, terrain, and urban layouts for geolocation verification. | 🟢 Free |
| [what3words](https://what3words.com) | Divides the world into 3m x 3m squares, each with a unique 3-word address. Used in emergency services and can help pinpoint exact locations. | 🟢 Free (basic) / 🟡 Freemium (API) |
| [GeoHints](https://geohints.com) | A reference guide for GeoGuessr-style geolocation. Clues by country: road markings, bollards, utility poles, signage. Invaluable for image geolocation. | 🟢 Free |
| [GeoSpy](https://geospy.ai) | ✅ AI photo geolocation from Graylark Technologies. Estimates where a photo was taken from architecture, terrain, and signage — no EXIF/GPS needed. Free tier ~20 lookups; paid plans for volume/API. Treat as a first-pass lead, always verify manually. | 🟡 Freemium (paid from ~$499/mo) |
| [MapChecking](https://www.mapchecking.com) | Estimate crowd sizes by drawing an area on a map and adjusting crowd density. Used by journalists to verify protest/rally attendance claims. | 🟢 Free |
| [MapSwitcher](https://github.com/nicbou/MapSwitcher) | Browser extension to switch between map services (Google, Bing, Yandex, etc.) for the same location with one click. Huge time saver. | 🟢 Free / 🔵 Open Source |
| [GovMap](https://www.govmap.gov.il) | Israel's official government mapping portal. Detailed cadastral data, aerial imagery, and infrastructure for Israeli territory. | 🟢 Free |
| [Convert Geographic Units](https://www.pgc.umn.edu/apps/convert/) | Convert between coordinate formats (decimal degrees, DMS, UTM, MGRS). Essential when working with coordinates from different sources. | 🟢 Free |
| [Geo Data Tool](https://www.geodatatool.com) | IP geolocation lookup and geographic data conversion utility. Map IP addresses to approximate physical locations. | 🟢 Free |
| [MW Geofind](https://mattw.io/youtube-geofind/) | Search YouTube videos by geographic location. Find videos uploaded from specific coordinates or within a radius — useful for verifying events. | 🟢 Free |
| [Chronotrains](https://www.chronotrains.com) | Visualize how far you can travel by train from any European station in a given time. Useful for understanding transit possibilities and alibis. | 🟢 Free |
| [WiGLE](https://wigle.net) | Crowdsourced database of Wi-Fi, cell, and Bluetooth networks mapped worldwide by BSSID/MAC. Geolocate a device or router by its network identifier — powerful for wireless-signal OSINT. | 🟢 Free (account required) |
| [License Plate Maps](https://www.licenseplatemaps.com) | Reference for license plate formats by country/state. Helps identify vehicle origin from partial plate visibility in images and video. | 🟢 Free |
| [Instagram Location Search](https://github.com/bellingcat/instagram-location-search) | ✅ Bellingcat CLI tool to find Instagram location IDs near given coordinates. Still maintained; requires Instagram session cookies. Note: the old follow-on `instagram-scraper` no longer exists, so it's now mainly a location-ID lead generator. | 🟢 Free / 🔵 Open Source |

---

## 🛰️ Satellite Imagery & Earth Observation

Access and analyze satellite imagery for change detection, infrastructure monitoring, and environmental analysis.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Sentinel Hub Playground](https://apps.sentinel-hub.com/sentinel-playground/) | Access and visualize Sentinel-2 imagery with band combinations (true color, NDVI, false color). 10m resolution, global, ~5-day revisit. | 🟢 Free (basic) / 🟡 Freemium |
| [Copernicus Browser](https://browser.dataspace.copernicus.eu) | ESA/Copernicus Data Space Ecosystem browser — the current front-end for Sentinel-1/2/3/5P data, with time-lapse and analysis tools. Successor to the classic Sentinel Hub EO Browser workflow. | 🟢 Free |
| [NASA Worldview](https://worldview.earthdata.nasa.gov) | Near-real-time satellite imagery from NASA's fleet. Visualize fires, smoke plumes, flooding, and other events. Supports temporal comparison. | 🟢 Free |
| [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov) | Fire Information for Resource Management System. Detect active fires and thermal anomalies worldwide in near-real-time via MODIS and VIIRS. Used to verify conflict/fire events. | 🟢 Free |
| [Planet Labs](https://www.planet.com) | Commercial constellation capturing daily imagery of the entire Earth at 3-5m resolution. Gold standard for monitoring change over time. | 🔴 Paid (journalist/NGO programs available) |
| [Umbra Space](https://umbra.space) | Commercial Synthetic Aperture Radar (SAR) provider. SAR penetrates clouds and captures imagery at night — essential when optical imagery is unavailable. Note: Umbra also releases an open SAR archive worth checking. | 🔴 Paid (open sample archive available) |
| [SkyFi](https://www.skyfi.com) | Marketplace for purchasing satellite imagery from multiple providers (Planet, Airbus, Maxar). Simplifies ordering high-resolution commercial imagery. | 🔴 Paid |
| [Apollo Mapping](https://apollomapping.com) | Satellite and aerial imagery broker offering access to imagery from 30+ providers. Useful for obtaining historical high-res imagery for specific dates. | 🔴 Paid |
| [Earth Explorer (USGS)](https://earthexplorer.usgs.gov) | Free access to the USGS archive of Landsat imagery, aerial photos, and elevation data. Decades of historical imagery. | 🟢 Free |
| [Earth Online (ESA)](https://earth.esa.int) | European Space Agency's platform for accessing Sentinel mission data and other ESA Earth observation datasets. | 🟢 Free |
| [OpenAerialMap](https://openaerialmap.org) | Open repository of publicly licensed aerial and satellite imagery. Includes drone imagery, post-disaster captures, and humanitarian mapping data. | 🟢 Free / 🔵 Open Source |
| [satellites.pro](https://satellites.pro) | Quick access to satellite imagery from Google, Bing, Yandex, and Esri in one interface. Convenient for rapid comparison. | 🟢 Free |
| [RAMMB SLIDER](https://rammb-slider.cira.colostate.edu) | Real-time weather satellite imagery viewer. Full-disk imagery from GOES, Himawari, and Meteosat. Useful for verifying weather conditions at specific times. | 🟢 Free |
| [Google Flood Hub](https://sites.research.google/floods/) | Google's AI-powered flood forecasting platform. Visualize flood predictions and historical flood data for river basins globally. | 🟢 Free |
| [Radar Interference Tracker](https://ollielballinger.users.earthengine.app/view/interference) | Detect GPS/radar jamming and interference by analyzing Sentinel-1 SAR data. Reveals military electronic warfare activity. Built by Ollie Ballinger. | 🟢 Free |
| [GPSJam](https://gpsjam.org) | Visualize GPS interference and jamming zones worldwide using ADS-B aircraft data. Reveals areas of electronic warfare or intentional disruption. | 🟢 Free |
| [QGIS](https://qgis.org) | Professional open-source GIS. Full GIS analysis, custom map creation, spatial data processing. The open-source alternative to ArcGIS. | 🟢 Free / 🔵 Open Source |
| [PeakVisor](https://peakvisor.com) | Mountain and terrain identification. Match mountain silhouettes to geolocate photos taken in mountainous areas. | 🟡 Freemium |
| [ShadeMap](https://shademap.app) | Visualize sun shadows on a 3D map at any date and time. Helps verify when a photo was taken based on shadow direction and length. | 🟢 Free |

---

## 📱 Social Media Intelligence

Tools for searching, monitoring, and analyzing social media platforms.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Twitter/X Advanced Search](https://twitter.com/search-advanced) | X's built-in advanced search. Filter by date range, user, location, engagement, language. Still indispensable for timeline reconstruction, though logged-in access is increasingly required. | 🟢 Free (X account often required) |
| [Twitter Location Search](https://github.com/bellingcat/twitter-location-search) | ✅ Search tweets by geographic coordinates and radius. Still listed by Bellingcat, but note X's geo-referencing mainly covers roughly the last week of posts, so historical coverage is limited. | 🟢 Free / 🔵 Open Source |
| [Who Posted What?](https://whopostedwhat.com) | ✅ Facebook keyword-by-date search by Henk van Ess. Surfaces historical public Facebook posts that native search hides. Requires being logged into a Facebook account. | 🟢 Free (donation-supported) |
| [Meta Content Library](https://transparency.meta.com/researchtools/meta-content-library) | Meta's official research API for public content across Facebook and Instagram. The sanctioned successor to CrowdTangle (which Meta shut down in 2024). Available to qualified researchers. | 🟢 Free (approved researchers) |
| [Bluesky Insights](https://bsky.jazco.dev) | Analytics and search for the Bluesky network. Explore posts, user networks, and trending content. | 🟢 Free |
| [BskyFollowFinder](https://bsky.thieflord.dev) | Bluesky network analysis. Find mutual connections, discover who your follows follow, and map relationships. | 🟢 Free |
| [ClearSky (Bluesky)](https://clearsky.app) | Bluesky account intelligence: block lists, who blocks whom, handle history, and list membership. Useful for network and moderation analysis. | 🟢 Free |
| [Hoaxy](https://hoaxy.osome.iu.edu) | ⚠️ Visualize the spread of claims and fact-checks. Now covers both X (Twitter) and Bluesky. Network analysis of how information propagates. | 🟢 Free |
| [Strava Global Heatmap](https://www.strava.com/heatmap) | Fitness platform with a global heatmap of exercise routes. Has revealed military bases, secret facilities, and personnel movement patterns. | 🟡 Freemium |
| [Snap Map](https://map.snapchat.com) | Snapchat's public map of geotagged Snaps worldwide. Real-time crowd-sourced video and photo from events, protests, and breaking news. | 🟢 Free |
| [Skopenow](https://www.skopenow.com) | Professional social media and web investigation platform. Automated collection and analysis across platforms with reporting. | 🔴 Paid |
| [Open Measures](https://openmeasures.io) | Search and analyze content from fringe and alt-tech platforms (Telegram, 4chan, Gab, etc.). Formerly the Social Media Analysis Toolkit. | 🟡 Freemium |
| [Social Bearing](https://socialbearing.com) | X/Twitter analytics and search for tweets, timelines, and account metrics. Coverage depends on API access, so verify results. | 🟡 Freemium |

---

## 👤 Username & Identity Search

Find accounts and digital footprints across platforms.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Search for usernames across 400+ social networks simultaneously. The most popular OSINT username enumeration tool. | 🟢 Free / 🔵 Open Source |
| [Maigret](https://github.com/soxoj/maigret) | Advanced username search across 3,000+ sites. A powerful Sherlock evolution with profile page parsing and identifier extraction. | 🟢 Free / 🔵 Open Source |
| [WhatsMyName](https://whatsmyname.app) | Username enumeration checking 600+ websites, maintained with a focus on reducing false positives. Also powers many other tools' site lists. | 🟢 Free / 🔵 Open Source |
| [Namechk](https://namechk.com) | Check username and domain availability across dozens of platforms at once. Quick way to map a person's online presence. | 🟢 Free |
| [Blackbird](https://github.com/p1ngul1n0/blackbird) | Fast username (and email) search across hundreds of sites, with metadata extraction and reporting. | 🟢 Free / 🔵 Open Source |
| [Name Variant Search](https://namevariants.com) | Generate name variations, transliterations, and alternative spellings. Essential when searching across languages and alphabets. | 🟢 Free |
| [GHunt](https://github.com/mxrch/GHunt) | ✅ Google account investigation tool. Extracts data from a Google account/email (profile, Maps reviews, calendar, etc.). Requires authenticated cookies. Actively maintained. | 🟢 Free / 🔵 Open Source |
| [IDCrawl](https://www.idcrawl.com) | Aggregated people/username search pulling social profiles, and public records into one view. Good quick pivot from a username or real name. | 🟡 Freemium |
| [IDN Checker (Punycoder)](https://www.punycoder.com) | Detect internationalized domain name (IDN) homograph attacks. Identifies visually similar characters used in phishing domains. | 🟢 Free |

---

## 📧 Email, Phone & People Lookup

Investigate email addresses, phone numbers, and find people.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Epieos](https://epieos.com) | Reverse email and phone lookup. Reveals connected Google account data, linked services, and profiles from a single address. One of the most-used email OSINT tools today. | 🟡 Freemium |
| [Holehe](https://github.com/megadose/holehe) | CLI tool that checks whether an email is registered on 120+ sites via password-reset/registration flows, usually without alerting the target. | 🟢 Free / 🔵 Open Source |
| [Hunter.io](https://hunter.io) | Find and verify professional email addresses associated with a domain. Useful for mapping an organization's staff. | 🟡 Freemium |
| [OSINT Industries](https://osint.industries) | Commercial email/phone/username enrichment returning linked accounts across hundreds of services. Popular with professional investigators. | 🔴 Paid (limited free trial) |
| [Castrick Clues](https://tools.castrickclues.com) | Free suite of email, username, and phone OSINT lookups with a clean web UI. | 🟢 Free |
| [TrueCaller](https://www.truecaller.com) | Identify unknown phone numbers via a crowdsourced caller-ID database of hundreds of millions of users. Reverse phone lookup. | 🟡 Freemium |
| [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker) | Bellingcat tool to check whether phone numbers are linked to Telegram accounts and retrieve associated usernames. | 🟢 Free / 🔵 Open Source |
| [Hitta.se](https://www.hitta.se) | Swedish person and business search. Find individuals, phone numbers, and addresses in Sweden's public records. | 🟢 Free |
| [That'sThem](https://thatsthem.com) | US reverse lookup by name, email, phone, address, or IP. A free starting point for US-based people search. | 🟢 Free |

---

## 🧑‍🦰 Facial Recognition & Image Analysis

Tools for face matching, comparison, and recognition.

| Tool | Description | Pricing |
|------|-------------|---------|
| [PimEyes](https://pimeyes.com) | Reverse face search engine. Upload a face photo to find where that face appears online. Extremely powerful and controversial. | 🟡 Freemium (limited free) / 🔴 Paid |
| [FaceCheck.ID](https://facecheck.id) | Reverse face search across social media, mugshots, and news. Alternative to PimEyes with different source databases. | 🟡 Freemium |
| [Search4Faces](https://search4faces.com) | ✅ Facial recognition focused on Russian/CIS networks (VK, OK.ru) plus older TikTok and ClubHouse avatars. Over a billion indexed faces, though databases aren't updated in real time. | 🟢 Free (limited) / 🟡 Freemium |
| [Face Comparison by ToolPie](https://www.toolpie.com/face-comparison) | Compare two face images for similarity. Free client-side face comparison. | 🟢 Free |

---

## 🔎 Reverse Image Search & Verification

Trace the origin of images, detect manipulation, and verify visual content.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Lens](https://lens.google.com) | Google's visual search. Identify objects, landmarks, text, and find visually similar images. Also extracts text (OCR). | 🟢 Free |
| [Yandex Images](https://yandex.com/images/) | Widely regarded as the strongest reverse image engine for faces and locations, especially in Eastern Europe. A staple first stop for geolocation. | 🟢 Free |
| [TinEye](https://tineye.com) | Dedicated reverse image search. Finds exact and modified matches. Its "oldest" sort shows the first known appearance of an image online. | 🟢 Free (basic) / 🔴 Paid (API) |
| [Search by Image (Extension)](https://github.com/ndaniel/searchbyimage) | Browser extension to right-click any image and reverse-search it across Google, Yandex, TinEye, Bing, and more at once. | 🟢 Free / 🔵 Open Source |
| [Forensically](https://29a.ch/photo-forensics/) | Browser-based image forensics: Error Level Analysis (ELA), clone detection, metadata extraction, noise analysis. Helps detect manipulation. | 🟢 Free |
| [FotoForensics](https://fotoforensics.com) | Long-running online ELA and metadata forensics service. A second opinion alongside Forensically for tampering analysis. | 🟢 Free |
| [ExifTool](https://exiftool.org) | The gold standard for reading, writing, and editing metadata in image, video, and document files. Extract GPS coords, camera model, timestamps, and more. | 🟢 Free / 🔵 Open Source |
| [InVID / WeVerify](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Verification plugin for journalists. Video/image keyframe extraction, reverse image search, metadata analysis, and magnification. Now developed under the WeVerify/vera.ai umbrella. | 🟢 Free |
| [Pinpoint](https://journaliststudio.google.com/pinpoint/) | Google's AI-powered document and image analysis for journalists. OCR, entity extraction, and search across large document collections. | 🟢 Free |
| [Hugin](https://hugin.sourceforge.io) | Open-source panoramic photo stitcher. Advanced control over alignment and projection — useful for reconstructing scenes from multiple photos. | 🟢 Free / 🔵 Open Source |
| [PixPlot](https://dhlab.yale.edu/projects/pixplot/) | Machine-learning tool for visualizing and clustering large image collections by visual similarity. | 🟢 Free / 🔵 Open Source |
| [RootAbout](https://rootabout.com) | Reverse image search for book covers and artwork. Search by ISBN, DOI, or image to identify publications. | 🟢 Free |

---

## 🎬 Video Analysis & Verification

Analyze, verify, and extract data from video content.

| Tool | Description | Pricing |
|------|-------------|---------|
| [InVID Verification Plugin](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Chrome/Firefox plugin for video verification. Extract keyframes from YouTube/Facebook/X videos, reverse-search frames, and analyze metadata. | 🟢 Free |
| [Azure AI Video Indexer](https://vi.microsoft.com) | Microsoft's AI video analysis. Extracts faces, on-screen text (OCR), objects, scenes, transcription, and sentiment. | 🟡 Freemium / 🔴 Paid |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | The de-facto standard CLI downloader for YouTube and 1,000+ sites. Archive source video and metadata for offline analysis. Replaces the old youtube-dl/single-site downloaders. | 🟢 Free / 🔵 Open Source |
| [Cobalt](https://cobalt.tools) | Clean, no-ads web/CLI media downloader supporting X, TikTok, Instagram, YouTube and more. Useful for quickly preserving a specific clip. | 🟢 Free / 🔵 Open Source |

---

## 🎙️ Audio Analysis & Acoustic OSINT

Tools for analyzing audio recordings to extract geolocation, environmental, and metadata intelligence. Acoustic OSINT is a rapidly evolving discipline used in Bellingcat-style challenges, conflict verification, and journalistic investigations.

> **Workflow Overview:**
> `Metadata Extraction → ENF Grid Analysis → Spectrogram Visualization → Background Sound Isolation → Environmental Sound ID → Cross-reference & Geolocation`

### 🗂️ Metadata & File Forensics

| Tool | Description | Pricing |
|------|-------------|---------|
| [ExifTool](https://exiftool.org) | Read hidden metadata from MP3, WAV, M4A, FLAC, and OGG files. Extracts encoder info, timestamps, recording device, and occasionally GPS data from field recorders. `exiftool file.mp3`. Wrap paths with spaces in quotes. | 🟢 Free / 🔵 Open Source |
| [MediaInfo](https://mediaarea.net/en/MediaInfo) | Detailed technical and tag information for audio/video files: codec, bitrate, channel layout, encoder version, container metadata. GUI and CLI. Useful for detecting re-encoded or tampered files. | 🟢 Free / 🔵 Open Source |
| [ffprobe](https://ffmpeg.org/ffprobe.html) | Part of FFmpeg. CLI tool for detailed stream/container metadata from any audio/video file. `ffprobe -v quiet -print_format json -show_format -show_streams file.mp3` | 🟢 Free / 🔵 Open Source |

### 📊 Spectrogram & Frequency Analysis

| Tool | Description | Pricing |
|------|-------------|---------|
| [Audacity](https://www.audacityteam.org) | The essential starting point. Use **Spectrogram view** for frequency-over-time, and **Plot Spectrum** (Analyze menu) for FFT. Set FFT size to 16384+ for high-resolution plots. Identify ENF hum, mechanical noise, and environmental signatures. Linux: `sudo apt install audacity`. | 🟢 Free / 🔵 Open Source |
| [Sonic Visualiser](https://www.sonicvisualiser.org) | Professional audio analysis with synchronized views (waveform, spectrogram, spectrum), a Vamp plugin system, and annotation layers. More powerful than Audacity for forensic-grade analysis. | 🟢 Free / 🔵 Open Source |
| [Adobe Audition](https://www.adobe.com/products/audition.html) | Professional DAW with advanced spectral frequency display and spectral repair tools. Useful for isolating specific sounds within a dense recording. | 🔴 Paid |
| [Friture](https://friture.org) | Real-time audio analyzer with spectrogram, spectrum, and octave-band views. Good for quick frequency profiling. Cross-platform, lightweight. | 🟢 Free / 🔵 Open Source |

### ⚡ ENF (Electric Network Frequency) Analysis

ENF analysis compares the subtle fluctuation of the electrical hum in a recording (50 Hz or 60 Hz and harmonics) against historical grid frequency databases to determine **when and where** a recording was made. 50 Hz = Europe/Asia/Africa/Australia. 60 Hz = North America, parts of South America, western Japan.

| Tool | Description | Pricing |
|------|-------------|---------|
| [ENF Whale](https://github.com/bellingcat/ENF-WHAle) | Bellingcat's open-source ENF tool. Extracts the ENF signal and cross-correlates it against historical grid-frequency databases to narrow recording date and region. The most accessible ENF tool for OSINT. | 🟢 Free / 🔵 Open Source |
| [GridFisherman](https://github.com/Nagasaki45/gridfisherman) | Python ENF extraction toolkit. Extracts the 50/60 Hz signal and harmonics, generates ENF contour plots, and supports comparison against reference databases. | 🟢 Free / 🔵 Open Source |
| [Audacity — Plot Spectrum (ENF method)](https://www.audacityteam.org) | Manual ENF detection: set FFT Size to 16384, use a linear frequency axis, and look for sharp peaks at exactly 50/60 Hz (and harmonics 100/150 or 120/180 Hz). A distinct spike confirms grid-connected recording and establishes the continent. | 🟢 Free / 🔵 Open Source |

### 🦜 Environmental & Bioacoustic Sound Identification

| Tool | Description | Pricing |
|------|-------------|---------|
| [BirdNET Analyzer](https://github.com/kahst/BirdNET-Analyzer) | Cornell Lab's open-source bird-sound recognition engine. Batch-analyze long recordings from the CLI for timestamped species detections. Species ranges can narrow location. Install via `pip install birdnetlib`. | 🟢 Free / 🔵 Open Source |
| [BirdNET Web](https://birdnet.cornell.edu/api) | Web version of BirdNET. Upload short clips to identify bird species without installing Python. | 🟢 Free |
| [Merlin Bird ID](https://merlin.allaboutbirds.org) | Mobile app with Sound ID. Identifies bird species in real time; cross-reference with range maps to constrain location. | 🟢 Free |
| [xeno-canto](https://xeno-canto.org) | Crowdsourced database of 800,000+ bird recordings mapped by species and location. Compare unknown calls against confirmed recordings filtered by region. | 🟢 Free |
| [iNaturalist](https://www.inaturalist.org) | AI species identification from audio and images, covering insects, amphibians, and more. Constrain location to a species' known range. | 🟢 Free |
| [Freesound](https://freesound.org) | Community audio database with 500,000+ sounds tagged by type and location. Find reference recordings of specific environments (stations, markets, squares) to compare against your sample. | 🟢 Free |

### 🔊 Background Sound Isolation & Enhancement

| Tool | Description | Pricing |
|------|-------------|---------|
| [Audacity — Noise Reduction](https://www.audacityteam.org) | Effect → Noise Reduction removes consistent background noise to isolate intermittent sounds. Combine with high/low-pass filters to separate bands: speech (300–3400 Hz), traffic/machinery (low), birds/insects (high). | 🟢 Free / 🔵 Open Source |
| [Adobe Podcast Enhance](https://podcast.adobe.com/enhance) | AI speech enhancement that removes background noise. Web-based, no install. Useful for cleaning a recording before analysis. | 🟢 Free (web) |
| [Demucs](https://github.com/facebookresearch/demucs) | Meta's open-source source-separation model. Split a recording into stems, or adapt to isolate speech from ambient background. Runs locally on Linux via Python. | 🟢 Free / 🔵 Open Source |
| [Spleeter](https://github.com/deezer/spleeter) | Deezer's open-source separation library (2/4/5 stems). Useful for isolating ambient environment from foreground speech. Python/Linux compatible. | 🟢 Free / 🔵 Open Source |

### 🗣️ Speech, Language & Accent Analysis

| Tool | Description | Pricing |
|------|-------------|---------|
| [Whisper (OpenAI)](https://github.com/openai/whisper) | State-of-the-art open-source speech recognition and language detection. Transcribes and auto-detects language even in noisy recordings. `pip install openai-whisper`. A crucial first step when voices are present. | 🟢 Free / 🔵 Open Source |
| [Shazam](https://www.shazam.com) | Identify music in the background of a recording. Background music can reveal broadcast source, country, or venue. | 🟢 Free |
| [AHA Music (Extension)](https://www.aha-music.com) | Browser extension that identifies music playing on your computer in real time. Play the file and let it detect recognizable music. | 🟢 Free |

### ✈️ Background Event Cross-Reference

| Tool | Description | Pricing |
|------|-------------|---------|
| [ADSBexchange](https://globe.adsbexchange.com) | ⚠️ Unfiltered global ADS-B flight tracker with historical data. If an aircraft is heard in a recording, cross-reference timestamp/location against flight history. (Acquired by JetNet in 2023; the free web globe remains publicly viewable, but bulk data/API access is now more restricted.) | 🟢 Free (viewer) |
| [FlightAware](https://flightaware.com) | Flight history and airport activity. Cross-reference known timestamps against departures/arrivals to triangulate a location near specific airports. | 🟡 Freemium |
| [MarineTraffic](https://www.marinetraffic.com) | If maritime sounds (foghorns, ship engines) are present, cross-reference against vessel AIS data for the suspected time and location. | 🟡 Freemium |
| [Pray Times](https://praytimes.org) | Calculate Islamic prayer (azan) times for any location and date. Azan in a recording can pinpoint both time and region with precision. | 🟢 Free |

### 🧰 Forensic Audio Suites

| Tool | Description | Pricing |
|------|-------------|---------|
| [Tsurugi Linux](https://tsurugi-linux.org) | Specialized digital-forensics distro with audio, video, and image tools pre-installed. Ideal for evidence-safe acoustic OSINT in an isolated environment. | 🟢 Free |
| [CSI Linux](https://csilinux.com) | OSINT-focused distro with a broad suite of pre-configured investigation tools including audio analysis. Good alternative to Tsurugi. | 🟢 Free |
| [ELAN](https://archive.mpi.nl/tla/elan) | Linguistic annotation tool from the Max Planck Institute. Create time-coded annotations on audio/video — useful for systematically documenting every sound event. | 🟢 Free |
| [SoX (Sound eXchange)](http://sox.sourceforge.net) | The "Swiss Army knife" of terminal audio processing. Convert formats, apply filters, measure statistics, and batch-process. `sox file.mp3 -n stat` gives a statistical summary. | 🟢 Free / 🔵 Open Source |

---

## ✈️ Transportation Tracking

Track aircraft, vehicles, and land transportation.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Flightradar24](https://www.flightradar24.com) | Real-time global flight tracker using ADS-B. Track military/government flights, aircraft over conflict zones, and flight history. | 🟡 Freemium / 🔴 Paid (premium history) |
| [FlightAware](https://flightaware.com) | Flight tracking with extensive US coverage. Detailed history, route analysis, and airport activity. Preferred by US-focused investigators. | 🟡 Freemium / 🔴 Paid |
| [ADSB.lol](https://adsb.lol) | Community-run, unfiltered ADS-B tracker with a free API. A good open alternative for tracking aircraft, including those hidden on commercial trackers. | 🟢 Free / 🔵 Open Source |
| [OrbTrack](https://www.orbtrack.org) | Real-time satellite tracking. Visualize the position and orbit of satellites, the ISS, and debris. Verify satellite pass times. | 🟢 Free |
| [AllTrails](https://www.alltrails.com) | Hiking and trail maps. Identify trails and paths visible in imagery; user-uploaded geotagged photos add ground-level context. | 🟡 Freemium |

---

## 🚢 Maritime Intelligence

Track ships, monitor maritime activity, and investigate vessel movements.

| Tool | Description | Pricing |
|------|-------------|---------|
| [MarineTraffic](https://www.marinetraffic.com) | Global ship tracking via AIS. Vessel positions, port calls, voyage history, and ownership details. The standard for maritime OSINT. | 🟡 Freemium / 🔴 Paid (full history) |
| [VesselFinder](https://www.vesselfinder.com) | Real-time vessel tracking with AIS. Free tier offers good coverage. Port arrival/departure data and vessel details. | 🟡 Freemium |
| [ShipFinder](https://shipfinder.co) | Simplified vessel tracking. Good for quick lookups of positions and basic voyage info. | 🟡 Freemium |
| [Equasis](https://www.equasis.org) | Free maritime safety database. Ship inspection records, flag history, classification, and ownership data. Run by the European Maritime Safety Agency. | 🟢 Free (registration required) |
| [Global Fishing Watch](https://globalfishingwatch.org/map/) | Visualize global fishing vessel activity. Detect illegal fishing, transshipment events, and fleet movements via AIS and VMS. | 🟢 Free |
| [Navtex](https://www.navtex.net) | Maritime navigational warning system. Monitor safety information, coastal warnings, and navigational hazards. | 🟢 Free |

---

## 🏢 Corporate & Financial Intelligence

Investigate companies, beneficial ownership, trade relationships, and financial data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenCorporates](https://opencorporates.com) | The world's largest open database of companies — 200M+ records from 140+ jurisdictions. Free basic search; bulk/API requires subscription. | 🟡 Freemium |
| [Companies House (UK)](https://find-and-update.company-information.service.gov.uk) | UK's official company register. Free filings, directors, ownership (PSC), and financial statements for all UK companies. Free public API. | 🟢 Free |
| [ICIJ Offshore Leaks Database](https://offshoreleaks.icij.org) | Searchable database from Panama, Paradise, and Pandora Papers and other leaks. Explore offshore entities, intermediaries, and beneficial owners. | 🟢 Free |
| [OpenSecrets](https://www.opensecrets.org) | US political spending and lobbying data. Track campaign donations, lobbying expenditures, and financial influence on US politics. | 🟢 Free |
| [LittleSis](https://littlesis.org) | Free database mapping relationships between powerful people and organizations. Visualize corporate boards, political connections, and influence networks. | 🟢 Free |
| [North Data](https://www.northdata.com) | European company information: beneficial ownership, financials, network graphs, and corporate hierarchies for EU companies. | 🟡 Freemium / 🔴 Paid |
| [Open Ownership](https://www.openownership.org) | Global beneficial ownership data. Track the real humans behind corporate structures across jurisdictions. | 🟢 Free |
| [EU Business Registers (e-Justice)](https://e-justice.europa.eu/489/EN/business_registers__search_for_a_company_in_the_eu) | Access point for company registers across EU member states, with direct links to each country's official register. | 🟢 Free |
| [EDGAR (SEC)](https://www.sec.gov/edgar) | US SEC database. All public company filings including annual reports, insider trading, and ownership disclosures. | 🟢 Free |
| [EDGAR Full-Text Search](https://efts.sec.gov/LATEST/search-index?q=) | Full-text search across SEC EDGAR filings. Search names, companies, or terms across millions of documents. | 🟢 Free |
| [ImportYeti](https://www.importyeti.com) | Free US import/export customs record search. Find suppliers and buyers. A good free alternative to paid trade-data tools. | 🟢 Free |
| [ImportGenius](https://www.importgenius.com) | Search US and international import/export shipping records. Track supply chains, trading partners, and smuggling. | 🔴 Paid |
| [UN Comtrade Database](https://comtradeplus.un.org) | UN international trade statistics. Bilateral trade flows between countries for specific commodities. Detect sanctions-evasion patterns. | 🟢 Free |
| [OCCRP Aleph](https://aleph.occrp.org) | OCCRP's investigative data platform. Search across leaked databases, corporate registries, court records, and other sources. | 🟢 Free |
| [The Information Laundromat](https://www.informationlaundromat.com) | Track laundered narratives and coordinated information operations. Analyze how disinformation is packaged and distributed. | 🟢 Free |
| [Sayari / Wikipedia List of Company Registers](https://en.wikipedia.org/wiki/List_of_company_registers) | Comprehensive list of company registers worldwide. A useful starting point when investigating companies in unfamiliar jurisdictions. | 🟢 Free |

---

## 🔓 Data Leaks & Breach Intelligence

Search leaked databases and credential breaches for investigative purposes.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Have I Been Pwned](https://haveibeenpwned.com) | Check if an email or phone appears in known breaches. Created by Troy Hunt. The most trusted breach notification service. | 🟢 Free |
| [DeHashed](https://dehashed.com) | Search engine for leaked databases by email, username, name, IP, phone, address, or password hash. | 🔴 Paid |
| [Leak-Lookup](https://leak-lookup.com) | Breach search engine. Query leaked data by email, username, keyword, domain, or password. | 🟡 Freemium / 🔴 Paid |
| [Intelligence X](https://intelx.io) | Search engine for leaked data, darknet content, and OSINT selectors. Archives Tor sites, paste sites, and breach data. Powerful but the useful tiers are paid. | 🟡 Freemium / 🔴 Paid |
| [Hudson Rock (Free Tools)](https://www.hudsonrock.com/free-tools) | Free lookups that check whether an email, domain, or username appears in infostealer malware logs. Excellent for assessing infostealer exposure. | 🟢 Free (free tools) / 🔴 Paid |
| [DiscordLeaks](https://discordleaks.unicornriot.ninja) | Searchable archive of leaked Discord messages from extremist groups, published by Unicorn Riot. | 🟢 Free |

---

## 🌐 Domain, IP, Infrastructure & Device Search

Investigate websites, domains, hosting infrastructure, certificates, and internet-connected devices. *(This section merges and expands the former "Domain, IP & Website Analysis" category with the internet-wide device search engines that every modern OSINT workflow relies on.)*

### 🔧 Domain, DNS & WHOIS

| Tool | Description | Pricing |
|------|-------------|---------|
| [ICANN Lookup](https://lookup.icann.org) | Official ICANN WHOIS lookup — the authoritative source for domain registration data. | 🟢 Free |
| [DomainTools Whois](https://whois.domaintools.com) | Industry-leading WHOIS with historical records. Track ownership changes, DNS history, and connected domains. | 🟡 Freemium / 🔴 Paid |
| [Whoxy](https://www.whoxy.com) | WHOIS search with reverse lookup. Find all domains registered by a person/email/company. Affordable API. | 🟡 Freemium / 🔴 Paid |
| [crt.sh](https://crt.sh) | Certificate Transparency log search. Enumerate a domain's subdomains and infrastructure from issued TLS certificates. A free, essential recon staple. | 🟢 Free |
| [DNSDumpster](https://dnsdumpster.com) | Free DNS reconnaissance and mapping. Discover subdomains, hosts, MX/NS records, and visualize a domain's footprint. | 🟢 Free |
| [SecurityTrails](https://securitytrails.com) | Historical DNS, WHOIS, and subdomain data. Track how a domain's infrastructure changed over time. | 🟡 Freemium / 🔴 Paid |
| [ViewDNS.info](https://viewdns.info) | A one-stop set of free DNS/IP utilities: reverse IP, reverse WHOIS, DNS records, IP history, and more. | 🟢 Free |
| [Urlscan.io](https://urlscan.io) | Scan and analyze websites. See what a URL loads (DOM, cookies, requests, screenshots) without visiting it yourself. Searchable historical scans. | 🟡 Freemium |
| [PublicWWW](https://publicwww.com) | Search the source code of websites. Find sites sharing an analytics ID, ad code, or snippet — connect sites to the same operator. | 🟡 Freemium / 🔴 Paid |
| [What CMS](https://whatcms.org) | Detect the CMS a website uses, plus hosting providers, themes, and plugins. | 🟢 Free |
| [BuiltWith](https://builtwith.com) | Profile a site's full technology stack (analytics, frameworks, trackers, hosting). Useful for fingerprinting and connecting related sites. | 🟡 Freemium |
| [Lumen Database](https://lumendatabase.org) | Database of legal takedown requests (DMCA, copyright, defamation). Reveals removed content and why — useful for uncovering suppressed information. | 🟢 Free |

### 🖥️ Internet-Wide Device & Attack-Surface Search

| Tool | Description | Pricing |
|------|-------------|---------|
| [Shodan](https://www.shodan.io) | The search engine for internet-connected devices. Find servers, webcams, ICS/SCADA, databases, and open ports by banner, product, port, or geography. A cornerstone of technical OSINT. | 🟡 Freemium (one-time paid tiers) |
| [Censys Search](https://search.censys.io) | Internet-wide host and certificate search. Rich structured data on services, TLS certs, and software — a strong complement to Shodan. | 🟡 Freemium |
| [ZoomEye](https://www.zoomeye.org) | Chinese cyberspace search engine indexing hosts, devices, and services worldwide. Useful for cross-checking Shodan/Censys results. | 🟡 Freemium |
| [FOFA](https://en.fofa.info) | Chinese internet asset search engine with powerful fingerprint queries. Strong coverage of assets under-represented on Western engines. | 🟡 Freemium |
| [Netlas.io](https://netlas.io) | Internet-wide scan data: hosts, domains, certificates, and responses, with a generous free query allowance. | 🟡 Freemium |
| [Onyphe](https://www.onyphe.io) | Cyber-defense search engine aggregating scan data, threat intel, and exposed-asset information. | 🟡 Freemium |
| [GreyNoise](https://viz.greynoise.io) | Identifies IPs that are mass-scanning the internet, helping separate targeted activity from background noise. | 🟡 Freemium |
| [GrayHatWarfare](https://buckets.grayhatwarfare.com) | Search engine for publicly exposed cloud storage — open S3/Azure/GCP buckets and their files. Frequently surfaces accidentally public sensitive data. | 🟡 Freemium |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scan Git repos, S3 buckets, Docker images, and CI/CD systems for exposed secrets, API keys, and credentials. | 🟢 Free / 🔵 Open Source |

---

## 📦 Archiving & Preservation

Capture and preserve web content before it disappears.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Wayback Machine (Internet Archive)](https://web.archive.org) | The most comprehensive web archive. Billions of saved pages back to 1996. View how sites looked at specific dates. | 🟢 Free |
| [Archive.today](https://archive.today) | On-demand webpage snapshot service. Creates permanent frozen copies of pages and often bypasses paywalls on archived content. | 🟢 Free |
| [Hunchly](https://www.hunchly.com) | Automated web-capture tool for investigators. Runs in the background while browsing, saving every page with timestamps and hashes for legal evidence. | 🔴 Paid (~$130/year) |
| [Auto Archiver](https://github.com/bellingcat/auto-archiver) | Bellingcat's automated archiving tool. Bulk-archive URLs from spreadsheets to the Wayback Machine, archive.today, or local storage. | 🟢 Free / 🔵 Open Source |
| [Zotero](https://www.zotero.org) | Reference manager and page archiver. Save full snapshots with metadata; organize research with tags and collections. | 🟢 Free / 🔵 Open Source |
| [ArchiveBox](https://archivebox.io) | Self-hosted web archiving. Save pages to WARC, HTML, PDF, and screenshots in your own repository — good for building a private evidence archive. | 🟢 Free / 🔵 Open Source |
| [Distill.io](https://distill.io) | Web page change monitoring. Get notified when specific parts of pages change — track profile updates, price changes, or content edits. | 🟡 Freemium |

---

## 🌍 Environmental & Wildlife Intelligence

Tools for investigating environmental crime, deforestation, wildlife trafficking, and ecological data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Global Forest Watch](https://www.globalforestwatch.org) | Monitor deforestation in near-real-time. Tree-cover-loss alerts, fire data, and land-use analysis. Used to track illegal logging. | 🟢 Free |
| [Resource Watch](https://resourcewatch.org) | Hundreds of datasets visualized on maps: air quality, deforestation, water stress, food production. A World Resources Institute platform. | 🟢 Free |
| [Aqueduct Water Risk Atlas](https://www.wri.org/aqueduct) | Map global water stress, flood risk, and drought severity. Useful for environmental investigations and climate-impact analysis. | 🟢 Free |
| [Environmental Justice Atlas](https://ejatlas.org) | Global map of environmental conflicts, documenting ecological disputes, pollution, and land-grabbing with detailed case studies. | 🟢 Free |
| [CITES Trade Database](https://trade.cites.org) | International trade in endangered species. Search permits and shipments regulated under CITES. Track wildlife-trafficking patterns. | 🟢 Free |
| [Species+](https://speciesplus.net) | CITES species database with trade data, distribution maps, and legal status. Identify protected species encountered in investigations. | 🟢 Free |
| [Wildlife Trade Portal](https://www.wildlifetradeportal.org) | Monitor global wildlife trade with species-level data. Analyze legal and illegal trade flows. | 🟢 Free |
| [World Database on Protected Areas](https://www.protectedplanet.net) | Global database of terrestrial and marine protected areas. Verify whether activities occur in protected zones. | 🟢 Free |
| [Locust Hub (FAO)](https://locust-hub-hqfao.hub.arcgis.com) | Track desert locust swarms globally. FAO platform monitoring outbreaks and their impact on food security. | 🟢 Free |
| [EIA International](https://eia-international.org) | Environmental Investigation Agency's reporting on environmental crimes: illegal logging, wildlife trafficking, and climate crimes. | 🟢 Free |

---

## 💣 Conflict, Arms & Munitions

Identify weapons, munitions, and track conflict events.

| Tool | Description | Pricing |
|------|-------------|---------|
| [ACLED](https://acleddata.com) | Real-time data on political violence and protest events worldwide, with precise geolocations. The standard for conflict tracking. | 🟢 Free (registration required) |
| [Liveuamap](https://liveuamap.com) | Real-time interactive map of conflict events, protests, and security incidents. Covers Ukraine, the Middle East, Africa, and other zones. | 🟢 Free |
| [CAT-UXO](https://cat-uxo.com) | UXO identification reference. Identify unexploded ordnance and munitions found in conflict zones from photos. | 🟢 Free |
| [Bulletpicker](https://bulletpicker.com) | US military ordnance identification database. Detailed technical data on bombs, rockets, mines, and other ordnance. | 🟢 Free |
| [Open Source Munitions Portal](https://www.omsportal.org) | Open database for identifying munitions from images. Collaborative weapons-ID platform for conflict documentation. | 🟢 Free |
| [UNOSAT](https://unosat.org/products/) | UN satellite-based damage assessments and situational analyses for conflict zones and natural disasters. | 🟢 Free |
| [Atlos](https://www.atlos.org) | Collaborative platform for visual investigation and geolocation. Open-source tooling for verifying conflict incidents from media. | 🟢 Free / 🔵 Open Source |

---

## 🚫 Sanctions & Politically Exposed Persons

Check sanctions lists, PEP databases, and politically exposed individuals.

| Tool | Description | Pricing |
|------|-------------|---------|
| [OpenSanctions](https://www.opensanctions.org) | Unified database of international sanctions, PEPs, and persons of interest, aggregating 30+ official sources. Free and open source. | 🟢 Free / 🔵 Open Source |
| [SanctionsExplorer](https://sanctionsexplorer.org) | Visual search of OFAC sanctions data. Explore networks and connections between sanctioned entities. | 🟢 Free |
| [EU Sanctions Map](https://www.sanctionsmap.eu) | Official EU sanctions visualization. See all EU restrictive measures by country, regime, and type. | 🟢 Free |
| [RuPEP](https://rupep.org) | Russian and Belarusian PEP database. Track officials, oligarchs, and their connections. | 🟢 Free |

---

## ⚖️ Legal & Court Records

Access court filings, legal documents, and law-enforcement data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [CourtListener / RECAP](https://www.courtlistener.com) | Access US federal court records. CourtListener (free) and PACER (paid). Search millions of filings, opinions, and dockets. | 🟢 Free (CourtListener) / 🔴 Paid (PACER) |
| [Uwazi](https://www.uwazi.io) | Open-source document management for human-rights organizations. Organize, analyze, and publish collections of legal and investigative documents. | 🟢 Free / 🔵 Open Source |

---

## 📊 Data Visualization & Analysis

Create charts, graphs, network diagrams, and visual presentations of investigative data.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Maltego](https://www.maltego.com) | The industry-standard OSINT link-analysis and visualization platform. Map relationships between people, companies, domains, IPs, and more via transforms. | 🟡 Freemium (Community Edition) / 🔴 Paid |
| [Gephi](https://gephi.org) | Open-source network analysis and visualization. Create complex graphs from large datasets; supports social network analysis. | 🟢 Free / 🔵 Open Source |
| [Datawrapper](https://www.datawrapper.de) | Create publication-ready charts, maps, and tables. Used by major newsrooms. Clean output, no coding. | 🟡 Freemium |
| [Flourish](https://flourish.studio) | Newsroom-favourite tool for interactive charts, maps, and scrollytelling stories. A strong Datawrapper alternative for narrative visuals. | 🟡 Freemium |
| [RAWGraphs](https://rawgraphs.io) | Open-source visualization framework for unconventional chart types from spreadsheet data. Bridges data and vector graphics. | 🟢 Free / 🔵 Open Source |
| [Blender](https://www.blender.org) | Professional 3D modeling and rendering. Used in OSINT for crime-scene reconstruction, terrain modeling, and event recreation. | 🟢 Free / 🔵 Open Source |

---

## 📝 Frameworks, Automation & Case Management

Organize investigations, automate collection, manage evidence, and maintain operational workflows.

| Tool | Description | Pricing |
|------|-------------|---------|
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | Powerful open-source OSINT automation. Point it at a domain, IP, email, name, or username and it queries 200+ modules to build an entity graph. Also offered as a hosted service (SpiderFoot HX). | 🟢 Free / 🔵 Open Source / 🔴 Paid (HX) |
| [recon-ng](https://github.com/lanmaster53/recon-ng) | Modular recon framework with a Metasploit-style workflow. Automates domain, host, and contact discovery into a local database. | 🟢 Free / 🔵 Open Source |
| [theHarvester](https://github.com/laramies/theHarvester) | Classic CLI tool for gathering emails, subdomains, hosts, and names from public search engines and data sources. A recon staple. | 🟢 Free / 🔵 Open Source |
| [OSINT Framework](https://osintframework.com) | A browsable directory that maps OSINT needs to tools by category. The go-to starting map for finding the right tool for a task. | 🟢 Free |
| [IntelTechniques Tools](https://inteltechniques.com/tools/) | Michael Bazzell's search-tool collection for streamlined queries across many platforms and data types. | 🟢 Free |
| [Obsidian](https://obsidian.md) | Markdown knowledge management with graph-based note linking. Build interconnected investigation notebooks; a plugin ecosystem extends it for OSINT. | 🟢 Free (personal) / 🔴 Paid (sync/commercial) |
| [Logseq](https://logseq.com) | Open-source, privacy-first outliner (local storage) with bidirectional linking and daily journals for investigation logging. | 🟢 Free / 🔵 Open Source |
| [Hunchly](https://www.hunchly.com) | Web-capture and case-management tool. Automatically saves and hashes every page visited for a court-admissible evidence chain. | 🔴 Paid |

---

## 🧩 Browser Extensions & Scrapers

Extensions and tools for data extraction, monitoring, and browser-based investigation.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Instant Data Scraper](https://webrobots.io/instantdata/) | AI-powered browser extension that auto-detects tables and lists on pages and exports them to CSV/Excel. No coding required. | 🟢 Free |
| [Zeeschuimer](https://github.com/digitalmethodsinitiative/zeeschuimer) | Browser extension that intercepts social-media API traffic and saves it as structured data. Captures from TikTok, Instagram, X, LinkedIn, and more. Pairs with 4CAT for analysis. | 🟢 Free / 🔵 Open Source |
| [Instaloader](https://instaloader.github.io) | Download Instagram profiles, posts, stories, reels, and metadata. Python CLI for bulk Instagram data collection. | 🟢 Free / 🔵 Open Source |
| [DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter) | Export Discord chat history to HTML, JSON, CSV, or plain text. Preserve Discord evidence for investigations. | 🟢 Free / 🔵 Open Source |

---

## 💻 Code & Technical Search

Search code repositories and source code for attributions and leaks.

| Tool | Description | Pricing |
|------|-------------|---------|
| [grep.app](https://grep.app) | Search across 500K+ public Git repositories. Find API keys, config files, code snippets, and developer attributions. | 🟢 Free |
| [GitHub Code Search](https://github.com/search) | GitHub's native code search covers millions of public repos with regex and qualifiers. Find leaked secrets, usernames, and unique strings tied to a target. | 🟢 Free (GitHub account) |
| [TruffleHog](https://github.com/trufflesecurity/trufflehog) | Scan Git repos, S3 buckets, Docker images, and CI/CD systems for exposed secrets, API keys, and credentials. | 🟢 Free / 🔵 Open Source |

---

## 💬 Communication & Messaging Intelligence

Investigate Telegram, messaging platforms, and communication channels.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Telegago](https://cse.google.com/cse?cx=006368593537057042503:efxu7xprihg) | Google Custom Search Engine focused on Telegram content. Search channels and groups via indexed web content. | 🟢 Free |
| [TGStat](https://tgstat.com) | Telegram analytics. Search channels/groups; view subscriber growth, engagement, and cross-posting patterns. | 🟡 Freemium |
| [Telemetr.io](https://telemetr.io) | Telegram channel analytics. Track subscriber dynamics, post reach, engagement, and content patterns. | 🟡 Freemium |
| [Telepathy](https://github.com/proseltd/Telepathy-Community) | OSINT toolkit for Telegram investigations. Extract members, messages, and media from groups and channels (community edition open source). | 🟢 Free / 🔵 Open Source |
| [Telegram Phone Number Checker](https://github.com/bellingcat/telegram-phone-number-checker) | Bellingcat tool to check whether phone numbers are associated with Telegram accounts and retrieve usernames. | 🟢 Free / 🔵 Open Source |
| [4plebs](https://4plebs.org) | Archive of several 4chan boards (/pol/, /x/, /sp/, etc.), searchable by keyword, date, and image hash. Useful for tracking extremist content and disinformation origins. | 🟢 Free |
| [Discord Lookup](https://discordlookup.com) | Look up Discord user IDs, account creation dates, and public info from a user ID or invite. Handy for Discord attribution. | 🟢 Free |

---

## ⛓️ Cryptocurrency & Blockchain

Investigate blockchain transactions, wallets, and crypto-related activity.

| Tool | Description | Pricing |
|------|-------------|---------|
| [Etherscan](https://etherscan.io) | Ethereum block explorer. Track ETH transactions, balances, smart contracts, and token transfers. The standard for Ethereum investigation. | 🟢 Free |
| [Blockchair](https://blockchair.com) | Multi-chain explorer and search (Bitcoin, Ethereum, and many others) with advanced filtering. A strong single entry point for cross-chain lookups. | 🟢 Free / 🟡 Freemium (API) |
| [Arkham Intelligence](https://intel.arkm.com) | Entity-labeled blockchain analytics. Maps wallet clusters to real-world people and organizations, with visual flow tracing. | 🟡 Freemium |
| [Breadcrumbs](https://www.breadcrumbs.app) | Visual wallet and transaction flow-tracing tool aimed at investigators, with free tiers for basic tracing. | 🟡 Freemium |
| [mempool.space](https://mempool.space) | Open-source Bitcoin explorer and mempool visualizer. Inspect transactions, fees, and address activity in detail. | 🟢 Free / 🔵 Open Source |
| [Chainalysis](https://www.chainalysis.com) | Industry-standard commercial blockchain investigation and compliance platform used by agencies and exchanges. | 🔴 Paid |

---

## ☀️ Weather, Time & Shadow Analysis

Verify timestamps, analyze lighting, and determine when photos/videos were taken.

| Tool | Description | Pricing |
|------|-------------|---------|
| [SunCalc](https://www.suncalc.org) | Calculate sun position, golden hour, and sunrise/sunset for any location and date. Essential for chronolocation from sun position. | 🟢 Free |
| [Shadow Finder](https://shadowfinder.app) | Estimate when (or where) a photo was taken by combining shadow length and direction with location or time. Bellingcat-associated tool. | 🟢 Free / 🔵 Open Source |
| [ShadowMap](https://shadowmap.org) | 3D shadow simulation for any location and time. Visualize how buildings and terrain cast shadows through the day. | 🟢 Free |
| [ShadeMap](https://shademap.app) | Interactive shade/shadow visualization on a 3D globe. Calculate shadow coverage at any moment for geolocation and chronolocation. | 🟢 Free |
| [Time and Date](https://www.timeanddate.com) | Historical weather, sun/moon data, and time-zone lookups for any location and date. Useful for corroborating weather claims in media. | 🟢 Free |

---

## 🧰 Miscellaneous & Specialty Tools

Specialized tools that don't fit neatly into other categories.

| Tool | Description | Pricing |
|------|-------------|---------|
| [China-related Resources](https://docs.google.com/spreadsheets/d/1Ekwz82FJnKbVp3IcDJ8N4NdRmxfgOImM8pNqaLaHM3c) | Curated collection of OSINT resources for investigating Chinese entities: social platforms, corporate registries, and mapping tools. | 🟢 Free |
| [Hitta.se](https://www.hitta.se) | Swedish public-records search including person lookup, address verification, and business data. | 🟢 Free |
| [Wikipedia List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives) | Directory of web-archiving initiatives worldwide. Find regional and specialized archives beyond the Internet Archive. | 🟢 Free |

---

## 🪦 Deprecated / No Longer Available

These tools were listed in earlier editions but are now defunct, unreliable, or replaced. They're kept here for reference so investigators don't waste time chasing dead links.

| Tool | Status | Notes |
|------|--------|-------|
| LinkdTime (freegeoip.live/linkedtime) | ⚫ Defunct / unreliable | Relied on decoding numeric LinkedIn profile IDs to estimate account creation date. LinkedIn moved to public vanity IDs and changed profile structure, breaking this method. For a rough "joined" date, use the profile's own *About → Joined* field or a current LinkedIn post-date extractor instead. |
| Spot (spotthe.bot) | ⚫ Likely defunct | X/Twitter bot-behavior analyzer. Dependent on Twitter API access, which changed drastically in 2023; the tool has not shown reliable signs of life since. Use Bot Sentinel-style services or manual heuristics for automation analysis. |
| CrowdTangle | ⚫ Shut down (2024) | Meta discontinued CrowdTangle. Its sanctioned replacement is the **Meta Content Library** (see Social Media Intelligence). |
| instagram-scraper (bellingcat follow-on) | ⚫ No longer exists | The scraper that Instagram Location Search fed into is gone. Instagram Location Search still returns location IDs, but you'll need another method to pull media from them. |
| NeutrOSINT | ⚫ Unmaintained | Multi-purpose repo went stale and its underlying lookups broke. Prefer maintained tools: Maigret/Blackbird (usernames), Holehe/Epieos (email), and dedicated phone/IP tools. |
| Index Database (indexdb.org) | ⚫ Unstable / gone | Breach-dump directory that has been intermittently offline and is not a dependable source. Use Have I Been Pwned and Hudson Rock's free tools instead. |

---

## 📋 Tool Count by Pricing (approximate)

| Type | Description |
|------|-------------|
| 🟢 Free | ~150 — completely free to use |
| 🔵 Open Source | ~55 — free and open source (many overlap with Free) |
| 🟡 Freemium | ~45 — free tier with paid premium features |
| 🔴 Paid | ~20 — requires subscription or payment |

---

## 🤝 Contributing

Found a tool that should be listed here? Want to update a description, pricing, or status?

1. Fork this repository
2. Add or update the tool in the appropriate category
3. Follow the existing format: `| [Tool Name](URL) | Description | Pricing |`
4. For status changes, use ⚠️ (caveat) or move dead tools to the Deprecated section with a note
5. Submit a Pull Request

### Guidelines

- Tools must be relevant to OSINT investigations
- Include accurate pricing and, where relevant, a last-checked note
- Write clear, actionable descriptions explaining the OSINT use case
- Place tools in the most relevant category

---

## ⚠️ Disclaimer

This toolkit is intended for **lawful research, journalism, and security purposes only**. Always ensure your use of these tools complies with local laws, platform terms of service, and ethical guidelines. Many tools here can access personal data — including facial recognition and breach data — so handle all information responsibly and consider the human impact of misidentification.

---

## 📜 License

This toolkit reference is released under the [MIT License](LICENSE). Individual tools listed here have their own licenses and terms of service.
