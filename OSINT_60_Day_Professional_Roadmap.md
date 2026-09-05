# Cyber Crime Investigation & OSINT — 60-Day Professional Roadmap

A practical **60-day roadmap** designed to turn a Cyber Crime Investigation & OSINT course outline into a job-ready learning journey focused on:

- OSINT Investigation
- Cyber Intelligence
- Threat Intelligence
- Fraud Research
- Digital Footprint Analysis
- Social Media Investigation
- Domain & Infrastructure Intelligence
- AML / Financial Crime Research
- AI-assisted Investigation
- Professional Reporting

> Goal: Finish the journey with practical skills, portfolio projects, professional reports, and a clear path toward freelance or junior analyst work.

---

## Course Modules Covered

1. Introduction to Cyber Crime & Forensics  
2. Case Study Analysis: Bangladesh Perspective  
3. Cyber Intelligence, Monitoring & Investigation  
4. Open Source Intelligence (OSINT) Techniques  
5. Data Breaches & Leaks Investigation  
6. Social Media Based Crime & Investigations  
7. Names, Email, Usernames & People Search  
8. Google Dorking & Reverse Image Search  
9. Domain & User IP Investigation  
10. CDR, IPDR, IPTSP & ISP Log Analysis  
11. Web-Based Crime & Investigation  
12. Mobile Financial Crime & Investigation  
13. Tor, VPN, Dark Web & Cryptocurrency  
14. Organised Crime & Investigation  
15. Digital Evidence Collection Process  
16. Anti-Money Laundering & Financing  
17. AI Tools & Deepfake Detection  
18. Recent Crime Based Assignment & Presentation  

---

# 60-Day Roadmap

## Week 1 — Investigation Fundamentals

### Topics
- Cyber Crime & Forensics
- Bangladesh cybercrime case studies
- Cyber Intelligence
- Digital Evidence
- Investigator mindset
- Evidence integrity
- Source validation
- Chain of custody

### Learn

```text
Requirement
    ↓
Collection
    ↓
Processing
    ↓
Analysis
    ↓
Verification
    ↓
Reporting
```

### Skills
- Intelligence lifecycle
- Primary vs secondary sources
- Source reliability
- Confidence levels
- Corroboration
- Timeline creation
- Evidence logging
- Ethical and legal boundaries

### Deliverable
Create a **2-page Intelligence Brief** containing:

- Incident summary
- Timeline
- Key entities
- Infrastructure
- Sources
- Findings
- Confidence assessment
- Unknowns

---

## Week 2 — Core OSINT & People Investigation

### Topics
- OSINT techniques
- Name search
- Email investigation
- Username investigation
- People search
- Google Dorking
- Reverse image search

### Search Operators

```text
site:
filetype:
intitle:
inurl:
"exact phrase"
OR
-
before:
after:
```

### Investigation Pivot Model

```text
Username
   ↓
Other Platforms
   ↓
Profile Image
   ↓
Reverse Image
   ↓
Website
   ↓
Domain
   ↓
Email
   ↓
Organization
```

### Tools

- Google
- Bing
- Brave Search
- Wayback Machine
- WhatsMyName
- Sherlock
- Hunter
- Have I Been Pwned
- Google Lens
- TinEye
- Yandex Images
- ExifTool

### Deliverable
Create a **Digital Footprint Report**.

Suggested structure:

```text
1. Executive Summary
2. Known Identifiers
3. Username Findings
4. Email Findings
5. Social Accounts
6. Image Findings
7. Domains / Websites
8. Timeline
9. Confidence
10. Sources
```

---

## Week 3 — Domain, IP & Infrastructure Intelligence

### Topics
- Domain investigation
- WHOIS / RDAP
- DNS
- ASN
- IP ownership
- Hosting providers
- Subdomains
- TLS certificates
- Certificate Transparency
- Technology fingerprinting
- Archived websites

### Tools

- WHOIS
- RDAP
- crt.sh
- DNSDumpster
- Shodan
- Censys
- VirusTotal
- SecurityTrails
- urlscan.io
- BuiltWith
- Wayback Machine
- Maltego
- SpiderFoot

### Deliverable
Create an **Infrastructure Intelligence Report**.

```text
Domain
 ├── Registrar
 ├── DNS
 ├── Subdomains
 ├── Certificates
 ├── IPs
 ├── ASN
 ├── Hosting
 ├── Technologies
 ├── Historical Records
 └── Related Infrastructure
```

---

## Week 4 — Social Media, Image & Geolocation OSINT

### Topics
- Social media investigations
- Account verification
- Username reuse
- Timeline analysis
- Reverse image search
- Geolocation
- Image provenance
- Content verification

### Image Verification Workflow

```text
Image
 ↓
Reverse Search
 ↓
Earliest Appearance
 ↓
Source Comparison
 ↓
Landmarks
 ↓
Signs / Language
 ↓
Map Comparison
 ↓
Geolocation Assessment
```

### Tools

- Google Lens
- TinEye
- Google Maps
- Google Earth
- OpenStreetMap
- Mapillary
- SunCalc
- ExifTool
- InVID / WeVerify

### Deliverable
Complete:

- 2 reverse-image investigations
- 2 geolocation challenges
- 1 social-media verification case

---

## Week 5 — Data Breaches, Dark Web & Cryptocurrency

### Topics
- Breach intelligence
- Credential exposure concepts
- Breach validation
- Threat actor claims
- Dark web fundamentals
- Tor
- Onion services
- Cryptocurrency OSINT
- Blockchain analysis

### Dark Web Concepts

```text
Surface Web
Deep Web
Dark Web
Tor
.onion
Forums
Marketplaces
Threat Actors
Leak Sites
```

### Cryptocurrency Skills

- Wallet addresses
- Transaction IDs
- Block explorers
- Transaction graphs
- Attribution concepts
- Wallet clustering concepts
- Confidence assessment

### Tools

- Etherscan
- Blockchain explorers
- Maltego
- Graph visualization tools

### Deliverable
Create a **Synthetic Crypto Investigation Report**.

```text
Wallet A
 ↓
Transactions
 ↓
Wallet B / C
 ↓
Known Service
 ↓
Timeline
 ↓
Analyst Assessment
```

---

## Week 6 — Financial Crime, CDR/IPDR & Organized Crime

### Topics
- CDR analysis
- IPDR analysis
- Mobile financial crime
- AML
- KYC
- UBO
- PEP
- Sanctions
- Organized crime link analysis

> Use only synthetic, training, or properly authorized datasets for CDR, IPDR, ISP, telecom, financial, or subscriber data.

### CDR Fields

```text
Caller
Receiver
Timestamp
Duration
Cell / Site
IMEI
IMSI
```

### IPDR Fields

```text
Source IP
Destination IP
Port
Timestamp
Protocol
Session Duration
Data Volume
```

### Tools

- Excel
- Google Sheets
- Python
- pandas
- SQLite
- Maltego
- Gephi
- yEd

### Deliverable

Build a synthetic network containing:

- 8 people
- 4 companies
- 5 phone numbers
- Transactions
- Relationships

Then create:

- Link chart
- Timeline
- Evidence table
- Intelligence assessment

---

## Week 7 — AI, Deepfake Detection & Automation

### Topics
- AI-assisted investigation
- Deepfake verification
- Entity extraction
- Timeline extraction
- Translation
- Report assistance
- Automation

### Verification Principle

```text
Source Provenance
+
Reverse Search
+
Metadata
+
Frame Inspection
+
Context Verification
+
Independent Sources
```

> AI-generated leads are not evidence. Always verify findings independently.

### Python Skills

```text
requests
BeautifulSoup
pandas
regex
JSON
CSV
APIs
```

### Automation Ideas

```text
Domain → DNS → IP → ASN
Username → Platform Checks
URLs → Archive Checks
CSV → Timeline
Evidence → Structured Table
```

### Deliverable

Build one small GitHub project:

## OSINT Case Organizer

Input:

```text
URLs
Notes
Dates
Entities
```

Output:

```text
Evidence CSV
Timeline
Source List
Confidence Tags
```

---

## Week 8 — Capstone Investigation

No new theory.

Run a complete public-source investigation using a fictional, CTF, lab, owned, or properly authorized target.

### Investigation Flow

```text
Domain
  ↓
IP
  ↓
Infrastructure
  ↓
Social Accounts
  ↓
Username
  ↓
Email
  ↓
Images
  ↓
Archived Pages
  ↓
Companies
  ↓
Relationships
  ↓
Timeline
  ↓
Assessment
```

### Final Deliverables

1. Executive Intelligence Report — 8–15 pages
2. Evidence spreadsheet
3. Maltego / link-analysis graph
4. Investigation timeline
5. 5-slide executive briefing
6. Redacted portfolio version

---

# Professional OSINT Toolkit

| Area | Tools |
|---|---|
| Search | Google, Bing, Brave Search |
| Archives | Wayback Machine |
| Username | WhatsMyName, Sherlock |
| Email | Hunter, HIBP |
| Image | Google Lens, TinEye, ExifTool |
| Domain | WHOIS, RDAP, crt.sh |
| DNS / IP | DNSDumpster, Censys, Shodan |
| Cyber Intelligence | VirusTotal, urlscan.io |
| Link Analysis | Maltego, Gephi, yEd |
| Automation | Python, pandas |
| Mapping | Google Earth, OSM, Mapillary |
| Notes | Obsidian, Notion |
| Reporting | Word, Google Docs, PDF |

---

# Recommended Certifications

## 1. TCM Practical OSINT Research Professional — PORP

**Recommended as the first serious practical OSINT certification.**

Focuses on:

- Search engines
- People OSINT
- Email
- Username
- Image intelligence
- Social media
- Websites
- Automation
- Reporting

**Priority:** ★★★★★

---

## 2. Maltego Academy

Good for:

- Link analysis
- Entity relationships
- Cybercrime investigations
- People investigations
- Domain investigations

**Priority:** ★★★★☆

---

## 3. Trace Labs OSINT Search Party / CTF

Useful for hands-on practice and portfolio evidence.

**Priority:** ★★★★★ for practical experience

---

## 4. IntelTechniques OSIP

Recommended after gaining practical investigation experience.

Good for:

- Advanced OSINT
- Full case workflow
- Professional reporting
- Investigation methodology

**Priority:** ★★★★☆

---

## 5. GIAC Open Source Intelligence — GOSI

Premium certification for professional OSINT analysts.

Best when employer-funded.

**Priority:** ★★★★★ reputation  
**Beginner affordability:** ★☆☆☆☆

---

# Recommended Certification Order

```text
Maltego Academy
      ↓
Trace Labs / OSINT CTF Practice
      ↓
TCM PORP
      ↓
Real Investigation Experience
      ↓
IntelTechniques OSIP
      ↓
GIAC GOSI
```

---

# Portfolio Targets by Day 60

| Asset | Target |
|---|---:|
| Mini OSINT Investigations | 15+ |
| Full Professional Reports | 4 |
| Link Analysis Graphs | 3+ |
| Geolocation Cases | 5+ |
| Domain Investigations | 5+ |
| Automation Project | 1 |
| Major Capstone | 1 |
| Public Portfolio Pieces | 3–5 |
| OSINT CTF Participation | 1+ |
| Serious Certification Target | PORP |
| Freelance Profiles | 2–3 |

---

# Earning Paths

## 1. Public Digital Footprint Audit

Deliver:

```text
Public Accounts
Domain Exposure
Email Exposure
Image Exposure
Publicly Visible Information
Recommendations
```

---

## 2. Company Due-Diligence Research

Deliver:

```text
Company
Founders
Public Business Records
Websites
Domains
News
Adverse Media
Relationships
Risk Indicators
Sources
```

---

## 3. Domain Intelligence Report

Deliver:

```text
Domain
IP
ASN
DNS
Certificates
Subdomains
Technologies
Historical Infrastructure
Public Exposure
```

---

## 4. Social Media Verification

Deliver:

- Account authenticity analysis
- Content origin
- Image reuse findings
- Timeline
- Related public identities
- Confidence assessment

---

## 5. Brand Impersonation Monitoring

Monitor publicly available information for:

- Fake domains
- Fake profiles
- Typosquatting
- Impersonation
- Phishing infrastructure
- Fake advertisements

---

## 6. Cyber Threat Intelligence Briefs

Deliver:

```text
Threat
Actor
Infrastructure
Indicators
Campaign
Timeline
Impact
Sources
Recommendations
```

---

# First-Earning Strategy

## Days 1–20
Focus on:

- Fundamentals
- Core OSINT
- Practice labs
- Evidence collection
- Reporting

## Days 21–30
Create:

- Digital Footprint Report
- Domain Intelligence Report
- Image / Geolocation Report

## Day 30+
Build professional profiles on:

- LinkedIn
- Upwork
- Fiverr
- GitHub
- Notion Portfolio

## Days 31–60
Start applying for:

- OSINT Researcher gigs
- Due diligence research
- Digital footprint audits
- Threat intelligence research
- Brand monitoring
- Public-source verification
- Junior analyst opportunities

---

# Professional Positioning

Avoid advertising yourself as:

> "I can investigate anyone."

Prefer:

> **I provide evidence-backed open-source research, digital-footprint analysis, domain intelligence, verification, and professional reports using lawful publicly available information.**

---

# Investigator Skill Stack

```text
                OSINT INVESTIGATOR
                       │
          ┌────────────┼────────────┐
          ↓            ↓            ↓
      Collection    Analysis     Reporting
          │            │            │
    Search Engines   Timeline    Executive Summary
    People OSINT     Correlation Evidence Table
    Social Media     Link Graph  Sources
    Image / Geo      Confidence  Recommendations
    Domain / IP      Validation  Presentation
    Threat Intel
```

Underneath everything:

```text
OPSEC
+
Ethics
+
Legal Authorization
+
Evidence Integrity
```

---

# Suggested Learning Resources

- Bellingcat Online Investigation Toolkit
- Maltego Academy
- Trace Labs
- TCM Security OSINT Training
- IntelTechniques
- SANS SEC497 materials and OSINT references
- GIAC GOSI certification resources

---

# Final 60-Day Target

```text
MONTH 1
│
├─ Week 1 → Investigation + Evidence + OPSEC
├─ Week 2 → Search + People + Username + Email
├─ Week 3 → Domain + IP + Infrastructure
└─ Week 4 → Social + Image + Geolocation
             ↓
       3 Portfolio Reports

MONTH 2
│
├─ Week 5 → Breach + Dark Web + Crypto
├─ Week 6 → Financial Crime + CDR/IPDR + AML
├─ Week 7 → AI + Deepfake + Automation
└─ Week 8 → Full Capstone
             ↓
       Professional Portfolio
             ↓
       Trace Labs / CTF
             ↓
          PORP Prep
             ↓
      LinkedIn + Upwork + Fiverr
             ↓
       First Paid OSINT Work
             ↓
      Junior OSINT / CTI Role
```

---

# Legal & Ethical Notice

This roadmap is intended for:

- Public-source research
- CTFs
- Training environments
- Owned assets
- Properly authorized investigations
- Defensive cybersecurity
- Academic and professional learning

Do not access private telecom, financial, ISP, subscriber, breached, or restricted records without lawful authorization.

---

📚 Best Learning Resources
FREE / LOW COST

1. Bellingcat Toolkit 

Probably one of your most useful resources.

[Bellingcat OSINT resources 
](https://www.bellingcat.com/?utm_source=chatgpt.com)
2. Trace Labs

Hands-on practice.

[Trace Labs OSINT training
](https://docs.tracelabs.org/?utm_source=chatgpt.com)
3. Maltego Academy

Link analysis + cyber investigations.

Maltego platform and Academy

4. TCM OSINT Fundamentals / PORP

Good structured beginner → practical path.
https://certifications.tcm-sec.com/porp/?utm_source=chatgpt.com

5. IntelTechniques

Excellent advanced reference; its current program contains more than 100 hours of training and is updated as OSINT methods change.
https://inteltechniques.com/training?utm_source=chatgpt.com

## Goal

By the end of 60 days, you should not simply know OSINT tools.

You should be able to:

> **Collect → Verify → Correlate → Analyze → Document → Report**

That is the skill set clients and employers can evaluate.
