# OSINT Research Resources

A comprehensive collection of Open Source Intelligence (OSINT) tools, websites, and resources for digital investigations, geolocation analysis, and metadata extraction.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-December%202025-brightgreen.svg)](https://github.com)

---

## Quick Start Guide

### New to OSINT? Start Here!

#### Your First Investigation (30 minutes)

1. **Basic Image Search**
   - Upload any image to [Google Reverse Image Search](https://images.google.com/)
   - Try [TinEye](https://tineye.com/) for comparison
   
2. **Extract Metadata**
   - Upload the same image to [Metadata2go](https://www.metadata2go.com/)
   - Look for GPS coordinates, creation date, camera model
   
3. **Verify Location**
   - If GPS coordinates exist, check them on [Google Earth Pro](https://www.google.com/earth/versions/)
   - Use [SunCalc](https://www.suncalc.org/) to verify time from shadows

4. **Practice More**
   - Try challenges at [KASE Scenarios](https://kasescenarios.com/)
   - Join [Trace Labs](https://tracelabs.org/) for real investigations

#### Essential Setup

**Browser Extensions:**
- Wayback Machine
- Archive.today button  
- EXIF Viewer
- User-Agent Switcher

**Command Line (Optional):**
```bash
# Install ExifTool for advanced metadata extraction
# macOS: brew install exiftool
# Ubuntu: sudo apt install libimage-exiftool-perl

# Basic usage
exiftool image.jpg
exiftool -gps:all image.jpg
```

---

## Table of Contents

- [Learning & Training Platforms](#learning--training-platforms)
- [Metadata Analysis Tools](#metadata-analysis-tools)
- [Data Comparison & Analysis](#data-comparison--analysis)
- [Geolocation & Mapping](#geolocation--mapping)
- [Additional OSINT Resources](#additional-osint-resources)
- [Contributing](#contributing)
- [Legal & Ethical Considerations](#legal--ethical-considerations)

---

## Learning & Training Platforms

Professional training resources and scenario-based learning for OSINT practitioners.

| Resource | Description | Status | Type |
|----------|-------------|--------|------|
| [KASE Scenarios](https://kasescenarios.com/) | Interactive OSINT training scenarios and challenges | Active | Training |
| [Trace Labs](https://tracelabs.org/) | OSINT competitions for missing persons investigations | Active | CTF/Training |
| [Click Safe Intelligence](https://clicksafeintelligence.com/) | OSINT training and cybersecurity education | Active | Training |
| [NCPTF](https://ncptf.org/) | National Child Protection Task Force resources | Active | Training/Resources |
| [GeoHints](https://geohints.com/) | Geolocation learning resources and tips | Active | Education |

---

## Metadata Analysis Tools

Tools for extracting, viewing, and analyzing metadata from various file types.

### Online Tools

| Tool | Description | Status | Best For |
|------|-------------|--------|----------|
| [Metadata2go](https://www.metadata2go.com/) | Upload files to view metadata from 50+ file types | Active | Multi-format support |
| [EXIF.tools](https://exif.tools/) | Web wrapper for ExifTool with comprehensive extraction | Active | Technical users |
| [ExifView.net](https://exifview.net/) | Client-side metadata viewer (no upload required) | Active | Privacy-focused |
| [Jimpl EXIF Viewer](https://jimpl.com/) | Privacy-focused online EXIF viewer | Active | Privacy & Security |

### Desktop/Command-Line Tools

| Tool | Description | Platform | Status |
|------|-------------|----------|--------|
| [ExifTool](https://exiftool.org/) | Industry-standard CLI tool for metadata extraction | Win/Mac/Linux | Actively Maintained |
| [FOCA](https://github.com/ElevenPaths/FOCA) | Metadata extraction from public documents | Windows | Active |
| [Metagoofil](https://github.com/laramies/metagoofil) | Metadata extraction from public documents | Python | Active |

### Notes on Metadata Tools

**Important Update (December 2025):**
- **Jeffrey's Image Metadata Viewer** was permanently discontinued in December 2025 due to bandwidth costs
- **Recommended Alternatives:**
  - **Metadata2go** - Best for multi-format support
  - **EXIF.tools** - Best for technical users needing raw ExifTool output
  - **ExifView.net** - Best for privacy (client-side processing)

**ExifTool Usage:**
```bash
# Install ExifTool
# macOS
brew install exiftool

# Ubuntu/Debian
sudo apt install libimage-exiftool-perl

# Basic usage
exiftool image.jpg
exiftool -all image.jpg
exiftool -gps:all image.jpg

# Extract metadata to text file
exiftool -a -G1 -s image.jpg > metadata.txt

# Remove all metadata
exiftool -all= image.jpg
```

---

## Data Comparison & Analysis

| Tool | Description | Use Case |
|------|-------------|----------|
| [Diffchecker](https://www.diffchecker.com/) | Compare text, images, PDFs, and files | Document comparison, change detection |
| [Beyond Compare](https://www.scootersoftware.com/) | Professional file/folder comparison tool | Advanced file analysis |
| [WinMerge](https://winmerge.org/) | Open-source file/folder comparison | Free alternative |

---

## Geolocation & Mapping

Essential tools for geospatial intelligence and location verification.

### Geolocation Resources

| Resource | Description | Status |
|----------|-------------|--------|
| [GeoHints](https://geohints.com/) | Tips and tricks for geolocation OSINT | Active |
| [GeoGuessr Wiki](https://geoguessr.fandom.com/wiki/GeoGuessr_Wiki) | Comprehensive geolocation knowledge base | Active |
| [OpenStreetMap Tagging](https://wiki.openstreetmap.org/wiki/Map_features) | Infrastructure and regional mapping features | Active |
| [Google Street View Changelogs](https://www.google.com/streetview/explore/) | Historical Street View coverage updates | Active |
| [Google Earth Pro](https://www.google.com/earth/versions/) | Advanced satellite imagery and historical views | Active |
| [SunCalc](https://www.suncalc.org/) | Sun position calculator for image verification | Active |
| [PeakFinder](https://www.peakfinder.org/) | Mountain peak identification tool | Active |

### Geolocation Techniques

- **Shadow Analysis:** Use SunCalc to determine time/location from shadows
- **Architectural Style:** Buildings and infrastructure patterns
- **Flora/Fauna:** Regional vegetation and wildlife
- **Street Furniture:** Traffic signs, utility poles, road markings
- **Language/Script:** Signs and text in images
- **Vehicle Types:** Regional vehicle models and license plates
- **Transport Authorities:** Local sign manuals and infrastructure standards
  - [Manual on Uniform Traffic Control Devices (MUTCD)](https://mutcd.fhwa.dot.gov/) - US traffic signs
  - [UK Traffic Signs Manual](https://www.gov.uk/government/collections/traffic-signs-manual) - UK standards
  - [European Transport Standards](https://transport.ec.europa.eu/) - EU regulations
  - Search: "[Country] transport authority sign manual PDF" for regional guides

---

## Additional OSINT Resources

### Comprehensive OSINT Frameworks

| Framework | Description |
|-----------|-------------|
| [OSINT Framework](https://osintframework.com/) | Categorized collection of OSINT tools |
| [IntelTechniques Tools](https://inteltechniques.com/tools/) | Custom search tools by Michael Bazzell |
| [Bellingcat's Online Investigation Toolkit](https://bit.ly/bcattools) | Curated tools from Bellingcat |

### Social Media Intelligence (SOCMINT)

### Social Media Intelligence (SOCMINT)

SOCMINT (Social Media Intelligence) is a branch of OSINT that focuses on collecting, analyzing, and interpreting information from social media platforms.

#### What is SOCMINT?

Social media platforms have become one of the richest sources of intelligence for investigations. SOCMINT covers platforms including:

**Major Platforms:**
- Twitter / X
- Facebook
- Instagram
- LinkedIn
- TikTok
- YouTube
- Reddit

**Specialized Platforms:**
- GitHub (developer activity)
- Behance (creative work)
- Strava (fitness/routes)
- Soundcloud (music/audio)
- Discord (communities)
- Telegram (messaging/channels)

#### Why SOCMINT Matters

People often leave digital traces through:
- **Reused Usernames:** Same handle across multiple platforms
- **Photo Metadata:** GPS coordinates in uploaded images
- **Cross-Linking:** URLs and usernames in bios
- **Location Clues:** Check-ins, geotagged posts, background landmarks
- **Social Connections:** Friends, followers, tagged photos
- **Behavioral Patterns:** Posting times, habits, schedules

Most investigations today—whether cybercrime, missing persons, threat intelligence, or fraud—have some trace on social media. The key principle: **the internet never forgets.**

#### SOCMINT Use Cases

With collected information, investigators can:
- Assist in locating missing persons based on photos and online posts
- Verify if a job applicant's claims match their online presence
- Investigate criminal networks via social media connections
- Map digital trails to connect sockpuppet accounts
- Trace scammers by linking their bios across platforms
- Establish timelines through post histories
- Identify associates through tagged content and comments

#### Core SOCMINT Principles

**1. Everything Must Be Public**
- Never engage, log in, friend-request, or scrape private data
- OSINT is ethical intelligence, not intrusion
- Respect platform terms of service
- No social engineering or deception

**2. Cross-Platform Analysis is Essential**
- A Twitter handle leads to GitHub
- GitHub reveals a LinkedIn profile
- LinkedIn mentions a university
- University website has team photos
- Now you have a verified identity

**3. Reused Usernames Are Valuable**
- People often reuse the same handle across multiple sites
- Find patterns and validate connections
- Document all discovered accounts
- Verify each account belongs to the target

**4. Context Over Raw Data**
- Location + Time + Activity = Intelligence
- Example: Someone posts vacation photos while claiming to be elsewhere
- Cross-reference timestamps across platforms
- Build a comprehensive timeline

**5. Ethical Boundaries**
- **Do NOT:** Dox, leak, manipulate, or intimidate
- **Do NOT:** Harass or contact subjects
- **Do NOT:** Access private information without authorization
- **Remember:** We are protectors of truth, not stalkers or threat actors

#### SOCMINT Tools

| Tool | Purpose | Status |
|------|---------|--------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Username search across social platforms | Active |
| [WhatsMyName](https://whatsmyname.app/) | Find where a username exists across hundreds of platforms | Active |
| [Namechk](https://namechk.com/) | Verify username availability/usage across platforms | Active |
| [Namecheckup](https://namecheckup.com/) | Alternative username checker with extensive coverage | Active |
| [Social-Analyzer](https://github.com/qeeqbox/social-analyzer) | Profile analysis across platforms | Active |
| [Lullar](https://lullar.com/) | Social media profile discovery | Active |
| [Blackbird](https://github.com/p1ngul1n0/blackbird) | Username OSINT across 500+ sites | Active |
| [Maigret](https://github.com/soxoj/maigret) | Collect information about username from sites | Active |

#### SOCMINT Techniques

**Username Enumeration:**
```bash
# Using Sherlock
python3 sherlock username123

# Using WhatsMyName
# Visit https://whatsmyname.app/ and enter username
```

**Google Dorking for Social Media:**
```
site:twitter.com "username"
site:linkedin.com "company name" "job title"
site:instagram.com "location"
site:github.com "email address"
```

**Reverse Image Search for Profiles:**
- Upload profile pictures to Google Images, TinEye, Yandex
- Find where else the same image appears
- Discover alternate accounts or identity theft

**Archive Social Media Content:**
- Use Archive.today for posts before they're deleted
- Screenshot everything with timestamps
- Document URLs and metadata
- Maintain chain of custody

**Timeline Analysis:**
- Extract post timestamps across all platforms
- Convert to UTC for consistency
- Look for gaps or patterns
- Cross-reference with known events

#### SOCMINT Investigation Workflow

```
1. Identify Starting Point (username, email, phone, image)
   ↓
2. Username Enumeration (Sherlock, WhatsMyName)
   ↓
3. Profile Discovery & Documentation
   ↓
4. Content Collection & Archiving
   ↓
5. Metadata Extraction from Posts/Images
   ↓
6. Social Graph Mapping (connections, followers)
   ↓
7. Timeline Construction
   ↓
8. Cross-Platform Verification
   ↓
9. Report Generation
```

#### SOCMINT Best Practices

- **Archive First, Analyze Later:** Content disappears quickly
- **Use Multiple Tools:** Each tool has different coverage
- **Document Everything:** Screenshots, URLs, timestamps
- **Verify Connections:** Don't assume same username = same person
- **Respect Privacy:** Public doesn't mean free-for-all
- **Stay Updated:** Platforms change features constantly
- **Use Separate Accounts:** Never investigate from personal accounts
- **Consider OPSEC:** Use VMs for sensitive investigations

| Tool | Purpose |
|------|---------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Username search across social platforms |
| [WhatsMyName](https://whatsmyname.app/) | Find where a username exists across hundreds of platforms |
| [Namechk](https://namechk.com/) | Verify username usage across platforms |
| [Namecheckup](https://namecheckup.com/) | Alternative username verification service |
| [Social-Analyzer](https://github.com/qeeqbox/social-analyzer) | Profile analysis across platforms |
| [Lullar](https://lullar.com/) | Social media profile discovery |

### Domain & Infrastructure Analysis

| Tool | Purpose |
|------|---------|
| [DNSDumpster](https://dnsdumpster.com/) | DNS reconnaissance and research |
| [Censys](https://search.censys.io/) | Internet-wide scanning and analysis |
| [Shodan](https://www.shodan.io/) | IoT and exposed device search |
| [SecurityTrails](https://securitytrails.com/) | DNS and domain history |

### Image & Video Analysis

| Tool | Purpose |
|------|---------|
| [Google Reverse Image Search](https://images.google.com/) | Find similar/source images |
| [TinEye](https://tineye.com/) | Reverse image search |
| [FotoForensics](https://fotoforensics.com/) | Image authenticity analysis |
| [InVID](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Video verification browser extension |

### Archiving & Preservation

| Tool | Purpose |
|------|---------|
| [Archive.today](https://archive.ph/) | Webpage archiving and preservation |
| [Wayback Machine](https://web.archive.org/) | Historical webpage snapshots |
| [Hunchly](https://www.hunch.ly/) | Professional web capture for investigations |

---

## Learning Resources

### Books
- **"Open Source Intelligence Techniques"** by Michael Bazzell
- **"OSINT Techniques"** by Nihad Hassan
- **"We Are Bellingcat"** by Eliot Higgins

### Online Courses
- [Trace Labs OSINT Training](https://www.tracelabs.org/training)
- [SANS SEC487: Open-Source Intelligence Gathering](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- [Udemy OSINT Courses](https://www.udemy.com/topic/osint/)

### Communities & Forums
- [r/OSINT](https://www.reddit.com/r/OSINT/) - Reddit community
- [OSINT Curious](https://osintcurio.us/) - Project and podcast
- [Bellingcat Discord](https://discord.gg/bellingcat)

---

## Setting Up Your OSINT Toolkit

### Essential Browser Extensions

```
✓ Wayback Machine
✓ Archive.today button
✓ Exif Viewer
✓ User-Agent Switcher
✓ Screenshot tools (FireShot, Nimbus)
✓ Video DownloadHelper
```

### Python OSINT Libraries

```bash
# Install popular OSINT Python packages
pip install exifread           # EXIF data extraction
pip install pillow             # Image processing
pip install googlesearch-python # Google searching
pip install tweepy             # Twitter API
pip install beautifulsoup4     # Web scraping
pip install requests           # HTTP requests
```

### Virtual Machine Setup

Consider using a dedicated VM for OSINT work:
- **Operating System:** Ubuntu/Kali Linux
- **Tools Pre-installed:** Many OSINT distributions available
- **Privacy:** Separate from personal system
- **Sandboxing:** Safe environment for testing tools

---

## Learning Path

### Week 1: Fundamentals
- Understand what OSINT is and its legal boundaries
- Learn basic Google dorking techniques
- Practice reverse image search
- Try simple metadata extraction

### Week 2: Metadata & Documents
- Master ExifTool usage
- Extract metadata from PDFs, images, and documents
- Understand GPS coordinates and timestamps
- Practice with real files

### Week 3: Geolocation
- Study [GeoHints](https://geohints.com/) and [GeoGuessr Wiki](https://geoguessr.fandom.com/wiki/GeoGuessr_Wiki)
- Practice geolocation challenges at [KASE Scenarios](https://kasescenarios.com/)
- Learn shadow analysis techniques
- Use Google Earth Pro for verification

### Week 4: Social Media & Advanced
- Username searches across platforms
- Profile analysis and network mapping
- Archive social media content properly
- Join your first OSINT CTF competition

---

## Practice Exercises

### Exercise 1: Image Metadata Analysis
1. Download any image from a public source
2. Extract metadata using [Metadata2go](https://www.metadata2go.com/)
3. Check for GPS coordinates
4. Verify location on Google Maps
5. Document your findings

### Exercise 2: Website Reconnaissance
1. Choose a website (use your own or public example)
2. Use Google dorking: `site:example.com filetype:pdf`
3. Extract metadata from found documents
4. Map the organization structure
5. Create a report

### Exercise 3: Geolocation Challenge
1. Visit [KASE Scenarios](https://kasescenarios.com/)
2. Choose a beginner challenge
3. Use multiple tools from this repository
4. Document your methodology
5. Compare with the solution

---

## Common OSINT Workflows

### Workflow 1: Image Verification
```
1. Reverse Image Search (Google, TinEye, Yandex)
   ↓
2. Metadata Extraction (ExifTool, Metadata2go)
   ↓
3. GPS Verification (Google Earth, OpenStreetMap)
   ↓
4. Timestamp Analysis (SunCalc for shadow matching)
   ↓
5. Authenticity Check (FotoForensics)
   ↓
6. Cross-Reference Sources
   ↓
7. Document Findings
```

### Workflow 2: Document Analysis
```
1. Document Acquisition (Google Dorking, Public Sources)
   ↓
2. Metadata Extraction (ExifTool, FOCA, Metagoofil)
   ↓
3. Author/Creator Identification
   ↓
4. Software Version Analysis
   ↓
5. Internal Path Discovery
   ↓
6. Timeline Creation
   ↓
7. Report Generation
```

### Workflow 3: Geolocation Investigation
```
1. Initial Clues (Signs, Architecture, Flora)
   ↓
2. Region Identification (GeoGuessr Wiki, GeoHints)
   ↓
3. Infrastructure Analysis (OpenStreetMap, Transport Manuals)
   ↓
4. Narrowing Down (Street View, Satellite Imagery)
   ↓
5. Shadow/Sun Analysis (SunCalc)
   ↓
6. Final Verification (Multiple Sources)
   ↓
7. Coordinate Confirmation
```

---

## Pro Tips

### General OSINT Tips
- **Document Everything:** Keep detailed notes of your methodology
- **Verify from Multiple Sources:** Never rely on a single source
- **Use Archive Tools:** Websites change - archive important findings
- **Stay Legal:** Always respect privacy laws and ToS
- **Time Zones Matter:** Convert all timestamps to UTC for consistency
- **OPSEC:** Use VMs and separate browsers for sensitive investigations

### Metadata Extraction Tips
- **Check Multiple Tools:** Different tools extract different metadata
- **Original Files Only:** Metadata is often stripped from social media
- **Look for Hidden Data:** Check for embedded thumbnails and alternate data streams
- **Compare Timestamps:** Creation date vs. modification date tells a story

### Geolocation Tips
- **Start Broad, Then Narrow:** Continent → Country → Region → City → Location
- **Learn Sign Systems:** Different countries have distinct traffic signs
- **Flora Identification:** Plants can narrow down climate zones
- **Power Line Styles:** Electrical infrastructure varies by country
- **Language Clues:** Alphabet, script, and language on signs
- **Use Multiple Angles:** Cross-reference Google Street View with satellite imagery

---

## Common Mistakes to Avoid

### Don't:
- Access non-public information without authorization
- Violate terms of service of platforms
- Harass, stalk, or harm individuals
- Share private information publicly
- Ignore legal restrictions in your jurisdiction
- Make assumptions without verification
- Forget to archive evidence before it disappears

### Do:
- Stay within legal boundaries always
- Document your complete methodology
- Verify information from multiple sources
- Respect privacy rights and ethical boundaries
- Get proper authorization for professional investigations
- Use archived versions to avoid alerting targets
- Join OSINT communities for learning and support

---

## Investigation Template

Use this template for structured investigations:

```markdown
# OSINT Investigation Report

## Case Information
- **Case ID:** [Unique identifier]
- **Date Started:** [YYYY-MM-DD]
- **Investigator:** [Your name/handle]
- **Objective:** [What are you trying to find?]

## Scope & Authorization
- **Legal Authorization:** [Yes/No - Details]
- **Scope Limitations:** [What won't you investigate?]
- **Jurisdictional Considerations:** [Applicable laws]

## Sources Used
- [ ] Search Engines (Google, Bing, Yandex)
- [ ] Social Media Platforms
- [ ] Public Records & Databases
- [ ] Metadata Analysis Tools
- [ ] Geolocation Resources
- [ ] Archive Services
- [ ] Other: ___________

## Timeline of Activities
| Date/Time (UTC) | Action Taken | Tool Used | Result |
|-----------------|--------------|-----------|--------|
| 2025-12-19 10:30 | Initial image search | Google Images | Found 3 matches |
| 2025-12-19 10:45 | Metadata extraction | ExifTool | GPS: 51.5074° N, 0.1278° W |

## Findings

### Source 1: [Platform/Website Name]
- **URL:** https://example.com/...
- **Date Accessed:** 2025-12-19
- **Archived:** [Archive.today link]
- **Key Information:** 
  - Finding 1
  - Finding 2
- **Verification Status:** Verified / Partial / Unverified

### Source 2: [Platform/Website Name]
- **URL:** https://example.com/...
- **Date Accessed:** 2025-12-19
- **Archived:** [Archive.today link]
- **Key Information:**
  - Finding 1
  - Finding 2
- **Verification Status:** Verified / Partial / Unverified

## Analysis
[Synthesize findings - what patterns emerge?]

## Verification Methods
- Cross-referenced X with Y
- Confirmed via independent source Z
- Metadata timestamp matches reported date
- Geolocation verified through multiple angles

## Confidence Level
- **High (90-100%):** [Which findings?]
- **Medium (50-89%):** [Which findings?]
- **Low (<50%):** [Which findings?]

## Limitations
- Could not access [specific resource]
- Conflicting information from [sources X and Y]
- Unable to verify [specific claim]

## Conclusion
[Summary of investigation results]

## Recommendations
[Next steps or additional investigations needed]

## Evidence Preservation
- All screenshots saved to: [location]
- Web archives created: [list Archive.today links]
- Metadata files exported: [location]
- Chain of custody maintained: [Yes/No]
```

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Contribution Guidelines

1. **Tool Verification:** Ensure tools are actively maintained (updated within last 12 months)
2. **Legal Tools Only:** No tools designed for illegal activities
3. **Documentation:** Provide clear descriptions and use cases
4. **Testing:** Verify tools work before submitting
5. **Organization:** Place tools in appropriate categories

---

## Legal & Ethical Considerations

### Important Disclaimer

This repository is for **educational and legitimate investigative purposes only**. Users must:

- Comply with all applicable laws and regulations
- Respect privacy and data protection laws (GDPR, CCPA, etc.)
- Obtain proper authorization before conducting investigations
- Follow terms of service for all platforms and tools
- Use tools ethically and responsibly

### Ethical OSINT Principles

1. **Legal Compliance:** Only access publicly available information
2. **Authorization:** Obtain permission for organizational investigations
3. **Privacy Respect:** Minimize collection of personal data
4. **Responsible Disclosure:** Report vulnerabilities appropriately
5. **Do No Harm:** Never use OSINT for stalking, harassment, or illegal activities

### Country-Specific Considerations

Different jurisdictions have varying laws regarding:
- Data collection and processing
- Privacy rights and expectations
- Surveillance and monitoring
- Cross-border data transfer

**Always consult with legal counsel when conducting OSINT operations.**

---

## Tool Status Key

| Symbol | Meaning |
|--------|---------|
| Active | Tool is maintained and functional |
| Limited | Tool has limitations or partial functionality |
| Discontinued | Tool is no longer maintained |
| Paid | Requires payment or subscription |
| Free | Completely free to use |

---

## Contact & Support

- **Issues:** Open an issue in this repository
- **Suggestions:** Submit a pull request with new tools
- **Questions:** Start a discussion in the Discussions tab

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- OSINT Community contributors worldwide
- Tool developers maintaining these resources
- Security researchers and investigators
- Trace Labs and other OSINT training organizations

---

<div align="center">

**Star this repository if you find it helpful!**

Made with care by the OSINT Community

*Last Updated: December 2025*

</div>
