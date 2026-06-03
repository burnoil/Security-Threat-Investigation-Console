# Technology Vulnerability & Patch Intelligence (TVPI)

Technology Vulnerability & Patch Intelligence (TVPI) is a lightweight browser-based vulnerability intelligence platform that correlates enterprise technology inventories against multiple public security intelligence sources.

Rather than scanning endpoints, TVPI helps security, vulnerability management, endpoint engineering, infrastructure, and patch management teams answer a critical question:

> Which technologies in our environment currently have active vulnerability, exploit, disclosure, or patch signals that require investigation?

---

## Screenshot

![TVPI Screenshot](docs/images/tvpi-dashboard.png)

---

## Features

### Asset-Centric Analysis

Analyze:

- Applications
- Operating Systems
- Firmware
- Hardware Appliances
- Network Devices
- Drivers
- SaaS Platforms
- Vendor Products

Examples:

```text
app: Google Chrome
app: Microsoft Office
os: Windows 11
firmware: Dell BIOS
hardware: Fortinet FortiGate
hardware: Cisco ASA
driver: Intel Graphics Driver
saas: Okta
```

## Threat Intelligence Sources

### CISA Known Exploited Vulnerabilities (KEV)

Correlates assets against known exploited vulnerabilities and active exploitation activity.

### Patch Intelligence

Tracks vendor patch and update signals through RSS sources including Patch My PC.

### Zero Day Initiative (ZDI)

Provides visibility into newly disclosed vulnerabilities and emerging threats.

## NVD Enrichment

Optional enrichment provides:

- CVSS Score
- Severity Rating
- Attack Vector
- CVSS Metadata

## FIRST EPSS Integration

Provides:

- Exploit probability score
- EPSS percentile ranking
- Real-world exploit likelihood context

## Vendor Resource Mapping

Links directly to official vendor security advisories and update resources for major vendors including Microsoft, Cisco, Fortinet, Palo Alto, VMware, Dell, HP, Lenovo, QNAP, Synology, Adobe, Okta, and Zoom.

## Feed Freshness Monitoring

TVPI tracks:

- Browser retrieval time
- Repository mirror time
- Feed age warnings

## Built-In Asset Profiles

Includes:

- Endpoint Baseline
- Network Security
- Server Infrastructure
- Identity & SaaS
- Firmware / Hardware Risk Set
- Management Plane / Remote Admin Tools

Custom profiles can also be created and stored locally.

## Export Capabilities

- Asset CSV Export
- Results CSV Export
- Executive Report Export
- Critical / High Priority Copy Workflow

## Priority Scoring

Findings are categorized as:

- Critical / Immediate Review
- High Priority
- Medium Priority
- Low / No Current Signal

Based on:

- KEV Matches
- ZDI Disclosures
- Patch Signals
- NVD Severity
- EPSS Probability

## Intended Audience

- Security Engineers
- Endpoint Engineers
- Vulnerability Management Teams
- Infrastructure Architects
- Patch Management Teams
- Security Operations
- Enterprise IT Operations

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages
- GitHub Actions

No backend infrastructure required.

## Live Demo

https://burnoil.github.io/technology-vulnerability-patch-intelligence/

## Current Version

**Version 0.8.0**

### Recent Enhancements

- Official vendor resource mapping
- NVD CVSS enrichment
- FIRST EPSS integration
- Feed freshness monitoring
- Asset profile system
- CSV import/export
- ZDI correlation
- Patch intelligence correlation
- KEV correlation engine

## Roadmap

- Asset criticality tagging
- Internet-facing asset scoring
- EPSS-weighted prioritization
- Vendor version intelligence
- SBOM ingestion
- CPE matching
- Executive reporting views
- BigFix integration
- MECM integration
- Action1 integration

---

### Why TVPI?

Traditional vulnerability scanners answer:

> What vulnerabilities exist?

TVPI helps answer:

> Which technologies should I investigate first?

That distinction makes it useful for enterprise vulnerability prioritization and patch governance workflows.

## License

MIT