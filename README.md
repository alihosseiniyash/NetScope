<div align="center">

<img src="assets/netscope-icon.svg" width="170" alt="NetScope logo">

# NetScope
### IP & Networking Workbench

A lightweight, responsive networking calculator for IPv4, IPv6, subnet planning, routing, address conversions, performance, and packet analysis.

**One HTML file · No installation · Works offline · Desktop & mobile**

[**Try NetScope online**](https://alihosseiniyash.github.io/NetScope/) · [**Download the standalone HTML**](NetScope_Networking_Workbench.html)

</div>

> **Deployment note:** The online demo will be available after GitHub Pages is enabled in the repository settings. The downloadable HTML already works offline.

**Explore the interactive workbench:** [Launch NetScope](https://alihosseiniyash.github.io/NetScope/) · [Download the offline version](NetScope_Networking_Workbench.html)

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

### Use online

Open the [NetScope web app](https://alihosseiniyash.github.io/NetScope/) once GitHub Pages is enabled.

### Run offline (no server required)

1. Download [`NetScope_Networking_Workbench.html`](NetScope_Networking_Workbench.html).
2. Open it in a recent Chrome, Edge, Firefox, or Safari browser.
3. Start calculating; the app doesn't require an internet connection.

The downloadable HTML contains its CSS and JavaScript inline. The website version (`index.html`) is the same app with a separate SVG favicon.

## Publish the web demo

In this repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. Once GitHub reports the site as deployed, the live URL should be:

https://alihosseiniyash.github.io/NetScope/

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
