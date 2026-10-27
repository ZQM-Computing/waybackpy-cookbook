# waybackpy Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **waybackpy cookbook** — Wayback Machine queries and archiving from Python. Second-tier OSINT tool in the wave-8 set. Patterns are planned from the design, not yet from fleet runs. It is intended for Researchers who query archived pages and save new snapshots programmatically. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** waybackpy patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (satellite imagery, weather, routing, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Researchers who query archived pages and save new snapshots programmatically.

## Prerequisites

- waybackpy in the fleet Python environment
- Python 3.11+
- A URL to query or archive

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-query` | Querying the closest snapshot for a URL |
| 02 | `02-save` | Saving a page to the archive |
| 03 | `03-cdx` | CDX search across a domain's history |

## Repository layout

```text
waybackpy-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [scrapy-cookbook](https://github.com/ZQM-Computing/scrapy-cookbook) — Polite web scraping spiders, pipelines, and exports
- [exiftool-cookbook](https://github.com/ZQM-Computing/exiftool-cookbook) — Metadata reading and writing from the command line
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
