# markusvankempen.github.io

Personal site for **Markus van Kempen** — open-source MCP servers and IDE tools, devices, the Englishtown ferry, STEM teaching, and talks.

**Live site:** [https://markusvankempen.github.io](https://markusvankempen.github.io)

## What's Here

A single-page site built with IBM Carbon Design System styling that highlights:

| Tool | Platform | Description | Links |
|------|----------|-------------|-------|
| **Maximo API Explorer** | VS Code | Discover, browse, and test IBM Maximo REST APIs directly from VS Code | [Marketplace](https://marketplace.visualstudio.com/items?itemName=MarkusvanKempen.maximo-api-explorer) • [Open VSX](https://open-vsx.org/extension/markusvankempen/maximo-api-explorer) • [Source](https://github.com/markusvankempen/maximo-mcp-ai-integration-options) |
| **MCP Ticket Demo** | MCP server · MIT | Full-stack reference server: 10 tools, auth, rate limiting, observability | [GitHub](https://github.com/markusvankempen/mcp-ticket-demo) • [npm](https://www.npmjs.com/package/mcp-ticket-demo) |
| **LF MCP Demo** | VS Code · MIT | Control-plane extension for the ticket demo | [Marketplace](https://marketplace.visualstudio.com/items?itemName=MarkusvanKempen.lf-mcp-summit-demo) • [Open VSX](https://open-vsx.org/extension/markusvankempen/lf-mcp-summit-demo) • [Extension source](https://github.com/markusvankempen/mcp-ticket-demo/tree/main/extension) |
| **Maximo MCP Server** | Claude / ChatGPT / Copilot | Model Context Protocol server for AI-assisted Maximo development | [Marketplace](https://marketplace.visualstudio.com/items?itemName=MarkusvanKempen.maximo-mcp) • [Open VSX](https://open-vsx.org/extension/markusvankempen/maximo-mcp) • [npm](https://www.npmjs.com/package/maximo-mcp-server) • [Source](https://github.com/markusvankempen/maximo-mcp-ai-integration-options) |
| **Watson Orchestrate Builder** | VS Code | Visual tool builder and agent manager for Watson Orchestrate | [Marketplace](https://marketplace.visualstudio.com/items?itemName=MarkusvanKempen.wxo-builder) • [Open VSX](https://open-vsx.org/extension/markusvankempen/wxo-builder) • [Source](https://github.com/markusvankempen/wxo-builder-vscode-extension) |
| **Maximo VS Code Extension** | VS Code | Lightweight Maximo API connectivity and testing | [Source](https://github.com/markusvankempen/maximo-mcp-ai-integration-options/tree/main/vscode-extension) |
| **WxO CLI Utilities Toolkit** | CLI / Bash | Exporter, Importer, Comparer, and Validator for IBM Watson Orchestrate deployments. | [Source](https://github.com/markusvankempen/WxO-Importer-Export-Comparer-Validator) |
| **Stanza Clock** | Chrome | Word clock new tab, companion to ESP-WordClock8x8 | [GitHub](https://github.com/markusvankempen/chrome-stanzaclock) • [Release](https://github.com/markusvankempen/chrome-stanzaclock/releases/latest) |
| **ESP Word Clock 8×8** | ESP32 | WS2812 word clock with web dashboard, MQTT, and OTA | [GitHub](https://github.com/markusvankempen/ESP-WordClock8x8) |
| **Ink O'Clock** | Alexa | Tells the time with a line from a book | [GitHub](https://github.com/markusvankempen/ink-oclock) |
| **ESP TFT Plane Radar** | ESP32-C3 | Live ADS-B radar on a round TFT | [GitHub](https://github.com/markusvankempen/ESP-TFT-PlaneRadar) |
| **ESP32 Traffic Paxcounter** | ESP32 | Dual-LiDAR traffic and ferry queue counter | [GitHub](https://github.com/markusvankempen/ESP32-Traffic-Paxcounter) |
| **FerryLight** | Community | Englishtown ↔ Jersey Cove ferry tracker — blog, slides, and live app | [Blog](https://markusvankempen.github.io/FerryLight-Blog/) • [App](https://ferrylight.online) • [GitHub](https://github.com/markusvankempen/FerryLight-Blog) |
| **Slack ↔ WxO Gateway** | MCP · Apache 2.0 | Route Slack channels to Watsonx Orchestrate agents | [npm](https://www.npmjs.com/package/@markusvankempen/slack-wxo-mcp-gateway) • [GitHub](https://github.com/markusvankempen/slack-wxo-mcp-gateway) |
| **TTGO T-Beam Sensor Node** | ESP32 · Apache 2.0 | LoRaWAN node with BME280, GPS, and a web map | [GitHub](https://github.com/markusvankempen/TTGO-T-Beam-Sensor-Node-with-Web-Dashboard) |
| **RAM-TEST** | Amiga · 1988 | Recovered GIGATRON memory diagnostic | [GitHub](https://github.com/markusvankempen/amiga-ram-test) |

Maximo tools live in [maximo-mcp-ai-integration-options](https://github.com/markusvankempen/maximo-mcp-ai-integration-options). The ticket demo and its extension live in [mcp-ticket-demo](https://github.com/markusvankempen/mcp-ticket-demo).

The About section also covers [HackMIT 2023](https://markusvankempen.wordpress.com/2024/01/11/mit-hackaton-2023/), [STEM classes at Six Nations Polytechnic](https://markusvankempen.wordpress.com/2018/05/16/techwednesday-2018-sixnationpolytechnic-with-watson-ibm-cloud-and-pis/), and field demos: [sonification](https://markusvankempen.wordpress.com/2018/02/27/127/), [LoRaWAN rhino tracking](https://www.youtube.com/watch?v=Xh_DIKPzCWk), and [Watson Visual Recognition at CeBIT](https://www.youtube.com/watch?v=P9rdW2wjIgg). Topic tags, `robots.txt`, and `sitemap.xml` point search engines at [github.com/markusvankempen](https://github.com/markusvankempen).

## Tech Stack

- Pure HTML + CSS (no build tools)
- IBM Plex Sans font (Google Fonts)
- Carbon Design System color tokens & spacing
- Responsive (mobile-friendly)

## Deployment

Hosted via GitHub Pages. Push to `main` and the site updates automatically.

```bash
git add -A
git commit -m "Update site"
git push origin main
```

## License

Apache 2.0
