# Adam Engelbrecht — RF Engineer III

6+ years designing antennas and RF front-ends for embedded wireless
platforms. Currently focused on multi-radio coexistence, custom antenna
integration, and AI-driven engineering workflows.

[rfpro.dev](https://rfpro.dev/) · open-source engineering tools below.

---

## Engineering MCP toolkit

An open-source toolkit of 18 [Model Context Protocol](https://modelcontextprotocol.io)
servers (14 public), including the flagship Python/Rust transmission-line
calculator `lineforge`, that lets AI agents drive RF, EMC, PCB,
EM-simulation, circuit-simulation, lab-instrument, and requirements
workflows end-to-end. The public servers are AGPL-3.0-or-later.

→ **[eng-mcp-suite](https://github.com/RFingAdam/eng-mcp-suite)** —
catalog + installer + bolt-on for private MCPs. **Start here.**

| Domain | Tool |
|---|---|
| Transmission lines (closed-form + bitmap FD-Laplace) | [lineforge](https://github.com/RFingAdam/lineforge) |
| PCB layout review (EMC + SI, 93 tools) | [mcp-pcb-emcopilot](https://github.com/RFingAdam/mcp-pcb-emcopilot) |
| 3D FDTD electromagnetic simulation | [mcp-openems](https://github.com/RFingAdam/mcp-openems) |
| Wire-antenna method-of-moments | [mcp-nec2-antenna](https://github.com/RFingAdam/mcp-nec2-antenna) |
| RF circuit + system simulation | [mcp-ltspice-qucs](https://github.com/RFingAdam/mcp-ltspice-qucs) |
| EMC regulatory lookup (FCC / CISPR / IEC / ISO) | [mcp-emc-regulations](https://github.com/RFingAdam/mcp-emc-regulations) |
| Engineering diagrams (stack-ups, block diagrams, test setups) | [drawio-engineering-mcp](https://github.com/RFingAdam/drawio-engineering-mcp) |
| 3D modeling | [mcp-blender](https://github.com/RFingAdam/mcp-blender) |
| Remote device access (SSH / serial) | [mcp-remote-access](https://github.com/RFingAdam/mcp-remote-access) |
| VNA control | [copper-mountain-vna-mcp](https://github.com/RFingAdam/copper-mountain-vna-mcp) |
| Spectrum analyzer | [mcp-rs-spectrum-analyzer](https://github.com/RFingAdam/mcp-rs-spectrum-analyzer) |
| Comms tester | [mcp-rs-cmw500](https://github.com/RFingAdam/mcp-rs-cmw500) |
| Signal generators | [mcp-rs-siggen](https://github.com/RFingAdam/mcp-rs-siggen) |
| CST Studio Suite | [mcp-cst-studio](https://github.com/RFingAdam/mcp-cst-studio) |

## Standalone RF tools

| Tool | What it does |
|---|---|
| [RFlect](https://github.com/RFingAdam/RFlect) | Antenna visualization — chamber measurements, VNA S-parameters, 2D/3D gain patterns, TRP, S11 / VSWR. |
| [gnss-toolkit](https://github.com/RFingAdam/gnss-toolkit) | GNSS receiver evaluation — NMEA capture, AT-command control, TTFF and CEP₅₀ / CEP₉₅ / RMS error analytics. |
| [rf-interference-calculator](https://github.com/RFingAdam/rf-interference-calculator) | RF spectrum interference and IMD / harmonics analyzer. |

## Other

| Project | What it does |
|---|---|
| [VPN-AP](https://github.com/RFingAdam/VPN-AP) | Raspberry-Pi travel router with VPN for secure hotel internet. |
| [ESP32-DIV](https://github.com/RFingAdam/ESP32-DIV) | ESP32 multi-purpose wireless testing toolkit. |
| [helium-weather-station](https://github.com/RFingAdam/helium-weather-station) | Battery / solar LoRa weather station on the Helium Network. |
| [claude-skill-homeassistant](https://github.com/RFingAdam/claude-skill-homeassistant) | Claude Code skill for managing Home Assistant workflows. |
| [BMO](https://github.com/RFingAdam/BMO) | Local AI companion. |

## Links

- Portfolio + writing: [**rfpro.dev**](https://rfpro.dev/)
- Toolkit playbook: [eng-mcp-suite/docs/playbook](https://github.com/RFingAdam/eng-mcp-suite/tree/main/docs/playbook)
- Contact: see [rfpro.dev](https://rfpro.dev/)
