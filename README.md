<div align="center">

# OSINT Techniques

> **Open Source Intelligence — Tools, Techniques & Resources**

![Version](https://img.shields.io/badge/version-2.0-blue?style=flat-square)
![Language](https://img.shields.io/badge/language-DE%20%2F%20EN-orange?style=flat-square)
![License](https://img.shields.io/badge/license-open--source-green?style=flat-square)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)

*A curated reference guide for OSINT practitioners — from fundamentals to advanced tooling.*

</div>

---

## Table of Contents

| # | Section |
|---|---------|
| 01 | [Gap Analysis Methodology](#-gap-analysis-methodology) |
| 02 | [Password Reset Reconnaissance](#-password-reset-reconnaissance) |
| 03 | [Reverse Image Searching](#-reverse-image-searching) |
| 04 | [Satellite Imagery](#-satellite-imagery) |
| 05 | [Photo Time of Day](#-calculate-photo-time-of-day) |
| 06 | [Fictional Account Creation](#-fictional-account-creation) |
| 07 | [Antivirus Scanners](#-antivirus-scanners) |
| 08 | [Anonymous File Sharing](#-anonymous-file-sharing) |
| 09 | [OSINT Tools by Category](#-osint-tools-by-category) |
| 10 | [Books & Reading Material](#-books--essential-reading) |
| 11 | [Search Engines](#-search-engines) |

---

## Gap Analysis Methodology

> The foundation of structured OSINT research — bringing order to complexity.

Gap Analysis is a method for taking stock of what you already know, then systematically identifying what you still need to find. It brings structure to any investigation.

### The Four Core Questions

```
1. What do I know?
2. What does it mean?
3. What do I need to know?
4. How can I find it?
```

Work through these iteratively as your investigation evolves — each answered question often reveals new gaps.

---

## Password Reset Reconnaissance

> Platform password reset flows can leak partial contact information without triggering alerts.

> **Note:** Only use against accounts you are authorized to investigate. Never trigger automatic resets (marked below).

| Platform | Information Revealed |
|----------|---------------------|
| **Facebook** | Shows alternative contact methods; number of asterisks matches email length |
| **Google** | Prompts for last known password; shows redacted recovery phone (last 2 digits) |
| **Twitter / X** | Shows redacted email — first 2 chars of username + first letter of domain; asterisk count matches length |
| **Yahoo** | Shows redacted alternate email — first char, last 2 chars, full domain |
| **Microsoft** | Shows redacted phone number with last 2 digits |
| **Instagram** | ⛔ Auto-sends reset email — **do not use** |
| **LinkedIn** | ⛔ Auto-sends reset email — **do not use** |
| **Foursquare** | ⛔ Auto-sends reset email — **do not use** |

---

## Reverse Image Searching

| Tool | Link |
|------|------|
| Yandex Images | https://images.yandex.com |
| Bing Visual Search | https://bing.com/visualsearch |
| Google Images | https://images.google.com |
| TinEye | https://tineye.com |

---

## Satellite Imagery

### Live & Recent Imagery
| Service | Link |
|---------|------|
| Google Earth (New Imagery Tool) | https://earth.google.com |
| Mapbox Live | https://mapbox.com |

### Historical & Comparative
| Service | Link |
|---------|------|
| Bing Maps | https://bing.com/maps |
| Descartes Labs | https://map.descarteslabs.com |
| Dual Maps | https://data.mashedworld.com/dualmaps/map.htm |
| Google Maps | https://maps.google.com |
| Wikimapia | https://wikimapia.com |
| World Imagery WayBack | https://livingatlas.arcgis.com/wayback |
| Yandex Maps | https://yandex.com/maps |
| Zoom Earth | https://zoomearth.com |

---

## ⏱️ Calculate Photo Time of Day

Estimate when a photo was taken based on sun angle and shadow direction.

| Tool | Link |
|------|------|
| SunCalc.net | https://suncalc.net |
| SunCalc.org | https://suncalc.org |

---

## Fictional Account Creation

Generate synthetic personas for undercover OSINT operations.

| Tool | Purpose |
|------|---------|
| [This Person Does Not Exist](https://thispersondoesnotexist.com/) | AI-generated face photos |
| [This Resume Does Not Exist](https://thisresumedoesnotexist.com/) | Fake CV / résumé |
| [This Rental Does Not Exist](https://thisrentaldoesnotexist.com) | Fake property listing |
| [Fake Name Generator](https://www.fakenamegenerator.com/) | Full identity details |
| [Random User Generator](https://randomuser.me/) | Random user profiles |
| [Dating Profile Generator](https://www.dating-profile-generator.org.uk/) | Dating-style bios |
| [Fake Persona Generator](https://businer.com/fakeid.php) | Fake ID details |
| [International Name Generator](https://www.behindthename.com/random/) | Culturally accurate names |

---

## Antivirus Scanners

Online scanners for checking files and URLs without local installation.

| Scanner | Link |
|---------|------|
| VirusTotal | https://virustotal.com |
| Jotti | https://virusscan.jotti.org |
| AnonScanner | https://anonscanner.com |
| File2Scan | http://www.file2scan.net |
| NodeDistribute | http://nodistribute.com |
| Majyx Scanner | http://v2.scan.majyx.net |

---

## Anonymous File Sharing

Using **OnionShare** for anonymous, temporary file distribution via Tor:

```
1. Download and install OnionShare → https://onionshare.org
2. Click "Connect to Tor"
3. Drag & drop files into the upload area
4. Wait for initialization
5. Copy the .onion URL and private key
6. Share both the link + key + Tor Browser download link with recipients
```

> **Tip:** You can stop sharing at any time from within the app — useful if you only want a single download, or if your link was shared with unauthorized parties.

---

## OSINT Tools by Category

---

### Anonymous Search

| Tool | Link |
|------|------|
| DuckDuckGo | https://duckduckgo.com |
| StartPage | https://startpage.com |
| Qwant | https://qwant.com |
| Yacy (decentralized) | https://yacy.net |

---

### Bot & Troll Detection

| Tool | Link |
|------|------|
| Bot Sentinel | https://botsentinel.com |
| Botometer | https://botometer.iuni.iu.edu |
| Emergent | https://emergent.info |
| Faker Fact | https://fakerfact.org |
| Hoaxy | https://hoaxy.osome.iu.edu |
| Information Operations Archive | https://io-archive.org |
| Twitter Trails | http://twittertrails.com |

---

### Digital Forensics

| Tool | Description |
|------|-------------|
| [Autopsy](https://www.autopsy.com) | Open source forensics platform |
| [EnCase](https://www.opentext.com) | Commercial forensics suite |
| [Volatility](https://www.volatilityfoundation.org) | Memory forensics framework |
| [Wireshark](https://www.wireshark.org) | Network protocol analyzer |
| [Cellebrite UFED](https://www.cellebrite.com) | Mobile device forensics |
| [Magnet AXIOM](https://www.magnetforensics.com) | Digital investigations platform |
| [Kali Linux](https://www.kali.org) | Pentesting & forensics distro |
| [CAINE](https://www.caine-live.net) | GNU/Linux forensics live distro |
| [SIFT (SANS)](https://digital-forensics.sans.org) | Ubuntu forensics workstation |
| [Yara](https://github.com/VirusTotal/yara) | Pattern matching / malware ID |
| [NetworkMiner](http://www.netresec.com) | Network forensic analyzer |
| [TestDisk](https://www.cgsecurity.org/wiki/TestDisk) | Data recovery |
| [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec) | Photo / file recovery |
| [Plaso (log2timeline)](https://plaso.readthedocs.io) | Timeline aggregation |
| [Nmap](https://nmap.org) | Network scanning |
| [Snort](https://www.snort.org) | Intrusion detection |

---

### Domain Intelligence

| Tool | Link |
|------|------|
| BuiltWith | https://builtwith.com |
| Analyze ID | https://analyzeid.com |
| DNS Trails | https://dnstrails.com |
| Domain Big Data | https://domainbigdata.com |
| DomainIQ | https://domainiq.com |
| Spyse | https://spyse.com |
| ViewDNS Whois | https://viewdns.info |
| Whoisology | https://whoisology.com |
| Whoxy | https://whoxy.com/reverse-whois |

---

### Email Investigation

| Tool | Link |
|------|------|
| [Holehe](https://github.com/megadose/holehe) | Check email across platforms |
| [Mosint](https://github.com/alpkeskin/mosint) | Email OSINT tool |
| [HaveIBeenPwned](https://haveibeenpwned.com) | Breach lookup |
| [Dehashed](https://dehashed.com) | Leaked credential search |
| [Hunter.io](https://hunter.io) | Find corporate emails |
| [IntelligenceX](https://intelx.io) | Data & email search |
| [Email Rep](https://emailrep.io) | Email reputation check |
| [Ghost Project](https://ghostproject.fr) | Leaked data lookup |
| [Spycloud](https://spycloud.com) | Breach intelligence |
| [TruMail](https://trumail.io) | Email verification |
| [PasteBin Dump](https://psbdmp.ws) | Pastebin leak search |

---

### Forensics & Metadata

| Tool | Link |
|------|------|
| ExifData | https://exifdata.com |
| FotoForensics | https://fotoforensics.com |
| Forensically | https://29a.ch/photo-forensics |
| Extract Metadata | https://extractmetadata.com |
| Image Verification | https://reveal-mklab.iti.gr |
| WayBack Machine | https://archive.org |

---

### Infrastructure Analysis

| Tool | Link |
|------|------|
| Shodan | https://shodan.io |
| Censys | https://censys.io |
| URLscan | https://urlscan.io |
| DNS Dumpster | https://dnsdumpster.com |
| MX Toolbox | https://mxtoolbox.com |
| Certificate Transparency | https://crt.sh |
| VirusTotal | https://virustotal.com |
| PublicWWW | https://publicwww.com |
| Similar Web | https://similarweb.com |
| Wigle (WiFi/BSSID) | https://wigle.net |
| Zoom Eye | https://zoomeye.org |
| Thingful (IoT) | https://thingful.net |

---

### IP Address Investigation

| Tool | Link |
|------|------|
| Shodan | https://shodan.io |
| Censys | https://censys.io |
| IPLocation | https://iplocation.net |
| ViewDNS | https://viewdns.info |
| Exonerator (Tor) | https://exonerator.torproject.org |
| VirusTotal | https://virustotal.com |

---

### Image Tools

| Tool | Description |
|------|-------------|
| [ImgOps](https://imgops.com) | Image operations hub |
| [Depix](https://github.com/spipm/Depixelization_poc) | Depixelate redacted text |
| [Unredacted (Bishop Fox)](https://github.com/BishopFox/unredacter) | Defeat pixelation redaction |

---

### Live Cameras

| Service | Link |
|---------|------|
| EarthCam | https://earthcam.com |
| Opentopia | http://opentopia.com |
| WorldCam | https://worldcam.eu |
| Airport Webcams | https://airportwebcams.net |

---

### Tor Network

| Tool | Link |
|------|------|
| Ahmia (clearnet) | https://ahmia.fi |
| Dark Search | https://darksearch.io |
| Tor2Web | https://tor2web.org |
| Not Evil (Tor only) | `hss3uro2hsxfogfq.onion` |

---

### Telephone Investigation

| Tool | Link |
|------|------|
| TrueCaller | https://truecaller.com |
| Spy Dialer | https://spydialer.com |
| Carrier Lookup | https://carrierlookup.com |
| That's Them | https://thatsthem.com |
| Open CNAM | https://opencnam.com |
| Twilio Lookup | https://twilio.com/lookup |
| Nuwber | https://nuwber.com |

---

### Vehicle Investigation

| Tool | Description |
|------|-------------|
| [Nomerogram](https://nomerogram.ru) | Russian license plates |
| [Vin-Info](https://vin-info.com) | VIN lookups |
| [World License Plates](https://worldlicenseplates.com) | International plate database |

---

### Username Investigation

| Tool | Link |
|------|------|
| [Sherlock](https://github.com/sherlock-project/sherlock) | Hunt usernames across 300+ sites |
| [Maigret](https://github.com/soxoj/maigret) | Collect dossier by username |
| [Nexfil](https://github.com/thewhiteh4t/nexfil) | Username finder |
| [KnowEm](https://knowem.com) | Social media username checker |
| [User Search](https://usersearch.org) | Cross-platform search |
| [Webmii](https://webmii.com) | People search |
| [PimEyes](https://pimeyes.com) | Facial recognition search |
| [FaceCheck](https://facecheck.id) | Face-based search |
| [GHunt](https://github.com/mxrch/GHunt) | Google account OSINT |

---

### GitHub Investigation

| Tool | Description |
|------|-------------|
| [Shhgit](https://github.com/eth0izzle/shhgit) | Find secrets in GitHub repos |
| [GitFive](https://github.com/mxrch/GitFive) | Track GitHub users |
| [Gitleaks](https://github.com/gitleaks/gitleaks) | Secret scanning |
| [Octosuite](https://github.com/bellingcat/octosuite) | GitHub OSINT framework |
| [Zen](https://github.com/s0md3v/Zen) | Find emails of GitHub users |

---

### Comprehensive OSINT Tools (CLI / Automated)

| Tool | Description |
|------|-------------|
| [Amass](https://github.com/owasp-amass/amass) | Attack surface mapping |
| [SpiderFoot](https://github.com/smicallef/spiderfoot) | OSINT automation |
| [Recon-ng](https://github.com/lanmaster53/recon-ng) | Modular recon framework |
| [Maltego](https://maltego.com) | Graphical link analysis |
| [TheHarvester](https://github.com/laramies/theHarvester) | Emails & subdomain harvester |
| [Metagoofil](https://github.com/laramies/metagoofil) | Metadata extraction |
| [H8mail](https://github.com/khast3x/h8mail) | Email breach hunting |
| [PhoneInfoga](https://github.com/sundowndev/phoneinfoga) | Phone number recon |
| [Instaloader](https://github.com/instaloader/instaloader) | Instagram data downloader |
| [Blackbird](https://github.com/p1ngul1n0/blackbird) | Username search across social media |
| [Telepathy](https://github.com/proseltd/Telepathy-Community) | Telegram OSINT toolkit |
| [Twint](https://github.com/twintproject/twint-zero) | Twitter scraping |
| [Harpoon](https://github.com/Te-k/harpoon) | CLI OSINT tool |
| [Social Analyzer](https://github.com/qeeqbox/social-analyzer) | Find profiles across 1000+ sites |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Video downloader (evidence collection) |

---

### Online Malware Analysis Sandboxes

| Tool | Link |
|------|------|
| Hybrid Analysis | https://hybrid-analysis.com |
| Any.run | https://any.run |
| Joe Sandbox | https://document-analyzer.net |
| Deepviz | https://sandbox.deepviz.com |
| ThreatExpert | https://threatexpert.com |

---

### Threat Intelligence

| Tool | Link |
|------|------|
| AlienVault OTX | https://otx.alienvault.com |
| IBM X-Force Exchange | https://exchange.xforce.ibmcloud.com |
| ThreatConnect | https://threatconnect.com |
| Recorded Future | https://recordedfuture.com |
| Threatminer | https://threatminer.org |
| OSINT Framework | https://osintframework.com |
| The Exploit DB | https://exploit-db.com |

---

## Books & Essential Reading

### Top Recommendation

> **[OSINT Techniques: Resources for Uncovering Online Information — Michael Bazzell (10th Ed., 2023)](https://inteltechniques.com/book1.html)**
> The single most important book for any OSINT practitioner.

---

### Key Handbooks & Manuals

| Title | Source |
|-------|--------|
| [US Army ATP 2-22.9 — OSINT (2017)](https://irp.fas.org/doddir/army/atp2-22-9-2017.pdf) | US Army |
| [NATO OSINT Handbook (2001)](http://www.oss.net/dynamaster/file_archive/030201/ca5fb66734f540fbb4f8f6ef759b258c/NATO%20OSINT%20Handbook%20v1.2%20-%20Jan%202002.pdf) | NATO |
| [Berkeley Protocol on Digital Open Source Investigations](https://www.ohchr.org/Documents/Publications/OHCHR_BerkeleyProtocol.pdf) | UN / OHCHR |
| [I-Intelligence OSINT Handbook 2020](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf) | i-intelligence.eu |
| [Psychology of Intelligence Analysis — Heuer (2006)](https://www.ialeia.org/docs/Psychology_of_Intelligence_Analysis.pdf) | IALEIA |
| [DoJ — Legal Considerations for Online Cyber Threat Intelligence](https://www.justice.gov/criminal-ccips/page/file/1252341/download) | US DOJ |
| [The OSINT Treasure Trove](https://bib.opensourceintelligence.biz) | Open Source |
| [Blockint — The OSINT Library](https://www.blockint.nl/the-osint-library/) | Blockint |

---

### 📝 Selected Academic Papers

| Author | Title |
|--------|-------|
| Mercado, S. (2004) | [Sailing the Sea of OSINT in the Information Age](https://www.cia.gov/library/center-for-the-study-of-intelligence/csi-publications/csi-studies/studies/vol48no3/article05.html) |
| Glassman & Kang (2011) | Intelligence in the internet age: emergence of OSINT |
| Omand, Bartlett & Miller (2012) | Introducing Social Media Intelligence (SOCMINT) |
| Williams & Blum (2018) | [Defining Second Generation OSINT for the Defense Enterprise](https://www.rand.org/pubs/research_reports/RR1964.html) |
| Block, L. (2023) | The Long History of OSINT — *Journal of Intelligence History* |
| VanPuyvelde & Tabárez Rienzi (2025) | [The Rise of Open-Source Intelligence](https://www.cambridge.org/core/journals/european-journal-of-international-security/article/rise-of-opensource-intelligence/21122432399ECB8078BF0D89A76D0586) |

---

## Search Engines

| Engine | Link |
|--------|------|
| SearXNG (meta-search) | https://searx.space |
| Google Custom Search | https://cse.google.com/cse?cx=90a35b59cee2a42e1 |
| DuckDuckGo | https://duckduckgo.com |
| Qwant | https://qwant.com |
| search.hbubli.cc | https://search.hbubli.cc |

---

## OSINT Resource Hubs

| Resource | Link |
|----------|------|
| OSINT Framework | https://osintframework.com |
| Bellingcat Online Toolkit | https://bit.ly/bcattools |
| MetaOSINT (4000+ resources) | https://metaosint.github.io/table |
| Awesome OSINT (GitHub) | https://github.com/jivoi/awesome-osint |
| Ph055a OSINT Collection | https://github.com/Ph055a/OSINT_Collection |
| OSINTCurio.us 10-Minute Tips | https://osintcurio.us/10-minute-tips |
| Rae Baker Deep Dive List | https://start.me/p/7kYgk2/rae-baker-deep-dive-osint |
| OSINT4ALL | https://start.me/p/L1rEYQ/osint4all |
| Anonymousplanet Guide | https://anonymousplanet.org |

---

<div align="center">

---

*If this guide helped you, consider starring or forking the repo.*
*Suggestions and improvements are always welcome.*

**Happy hunting. Stay ethical. Stay legal.**

</div>
