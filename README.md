<div align="center">
  <img src="assets/netscope-icon.svg" width="128" alt="NetScope icon">
  <h1>NetScope</h1>
  <p><strong>IP & Networking Workbench</strong></p>
  <p>Lightweight, responsive calculators for IPv4, IPv6, subnet planning, routing, conversions, performance and packet analysis.</p>
  <p><strong>Standalone HTML · No installation · Offline capable · Desktop & mobile</strong></p>
</div>

### Start here

**[Launch NetScope online](https://alihosseiniyash.github.io/NetScope/)** · **[Download the offline HTML](https://alihosseiniyash.github.io/NetScope/download.html)** · **[Browse source code](https://github.com/alihosseiniyash/NetScope)**

The online demo is hosted through GitHub Pages. The downloadable version is one self-contained HTML file that works without an internet connection.

## Features

| Tool | Capabilities |
|---|---|
| **IPv4 calculator** | Linked IP / CIDR / subnet-mask inputs, network and broadcast addresses, host ranges, classification, binary representations |
| **VLSM planner** | Allocate variable-sized subnets from host requirements, avoid overlaps, export CSV, save plans locally |
| **CIDR & ranges** | Split subnets, summarize networks, convert ranges to CIDR blocks |
| **Routing & comparison** | Longest-prefix-match lookup, route metrics, subnet membership and overlap checks |
| **IPv6 calculator** | Compression / expansion, prefix calculations, address classification |
| **Binary & MAC** | Decimal, binary and hexadecimal conversions; MAC/EUI-64 utilities |
| **Network performance** | Bandwidth, throughput, RTT, bandwidth-delay product, packet rates and transfer-time estimates |
| **MTU & fragmentation** | Packet sizes, IPv4 fragmentation, offsets and overhead estimates |
| **Reference** | CIDR subnet table, special address ranges, frequently used ports |

## Getting started

### Use the online app

Open **[NetScope's live calculator](https://alihosseiniyash.github.io/NetScope/)** in a desktop or mobile browser.

### Download and use offline

1. Open the **[Download page](https://alihosseiniyash.github.io/NetScope/download.html)**.
2. Select **Download standalone HTML** to save `NetScope_Networking_Workbench.html`.
3. Open the downloaded file in Chrome, Edge, Firefox, or Safari. All calculations work locally.

**Alternative:** [View the standalone HTML in the repository](NetScope_Networking_Workbench.html). GitHub's repository file view shows source code, so use the Download page above for the easiest file download.

## About the project

NetScope was built to combine frequently used networking calculations into a single, practical tool for learning, lab work and network engineering. AI-assisted development was part of the implementation process.

It runs entirely in the browser; it is **not** a live network scanner or device-management platform. Performance estimates depend on the user-supplied assumptions and should not be treated as measured network results.

## Privacy and local data

- No account, backend, telemetry or external API is required.
- The current app stores theme preferences and optionally saved VLSM plans in the browser's local storage.
- Results are calculated locally in the browser.
- Clearing site data may remove saved local plans.

## Contributing and feedback

Suggestions, bug reports and enhancement ideas are welcome through GitHub Issues.

Please include the tool, input values, expected result, actual result and browser when reporting a calculation issue.

## Licensing

No open-source license has been selected yet. A public GitHub repository allows people to view and download the application, but redistribution and modification permissions should be clarified by adding a license before encouraging derivative projects.
