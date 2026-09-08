# Awesome-Smart-Grid-Management

## Top Smart Grid Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Grid Operations, ADMS/DERMS, Energy Management, Distributed Energy Resources, SCADA & Flexibility Platforms*  
**Last updated: September 2026**

This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Smart Grid Management**. These systems help utilities and energy operators monitor, control, optimize, and orchestrate transmission and distribution grids, including distributed energy resources (DERs), demand response, outage management, and real-time grid intelligence.

**Examples** include OSI Monarch (AspenTech), Siemens Grid Software / Gridscale X, GE GridOS, Schneider EcoStruxure Grid / ADMS, Hitachi Energy Lumada APM, AutoGrid, Uplight, Smarter Grid Solutions, Camus Energy, and EnergyHub (the category leaders).

**Open-source emphasis**: Full utility-grade ADMS/DERMS/SCADA platforms remain predominantly commercial due to safety, reliability, and regulatory requirements. However, strong open-source building blocks exist for energy management systems (EMS), microgrids, DER scheduling, home/building energy optimization, and research/prototyping. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[OSI Monarch (AspenTech)](https://www.aspentech.com/)**  
  High-performance OT-native platform for real-time grid telemetry, SCADA, and mission-critical utility operations.

- **[Siemens Grid Software / Gridscale X](https://www.siemens.com/)**  
  Comprehensive grid software suite covering planning, operations, ADMS/DERMS capabilities, digital twins, and AI-assisted flexibility management.

- **[GE Vernova GridOS](https://www.gevernova.com/)**  
  Grid orchestration platform designed for transmission and distribution, supporting real-time coordination, renewables integration, and resilient operations.

- **[Schneider Electric EcoStruxure Grid / ADMS](https://www.se.com/)**  
  Industry-recognized Advanced Distribution Management System with strong DER management, outage response, Volt/VAR optimization, and grid-edge capabilities.

- **[Hitachi Energy Lumada APM](https://www.hitachienergy.com/)**  
  Asset performance and grid management solutions focused on reliability, predictive maintenance, and operational intelligence for power systems.

- **[AutoGrid](https://www.auto-grid.com/)**  
  Flexibility management and DERMS platform enabling real-time optimization of distributed energy resources at scale for utilities and aggregators.

- **[Uplight](https://www.uplight.com/)**  
  Customer engagement and energy management platform that helps utilities activate demand-side flexibility and optimize energy use.

- **[Smarter Grid Solutions, Camus Energy, EnergyHub](https://www.smartergridsolutions.com/)**  
  Specialized DERMS, flexibility, and virtual power plant (VPP) platforms focused on distributed resources, grid-edge control, and market participation.

- **[Other grid & utility platforms](https://www.siemens.com/)**  
  Solutions from major vendors and specialists covering EMS, DMS, OMS, planning tools, and integrated digital grid stacks.

## Open-Source GitHub Projects

- **[MyEMS](https://github.com/MyEMS/myems)**  
  Leading open-source Energy Management System aligned with ISO 50001. Supports monitoring, analysis, and reporting of energy and carbon data, with extensions for PV, storage, microgrids, and related use cases.

- **[Alliander DER Scheduling](https://github.com/alliander-opensource/der-scheduling)**  
  Open-source scheduling stack for Distributed Energy Resources (DER) control according to IEC 61850 standards, aimed at production-grade DER coordination.

- **[EnergyLink Open-Source DERMS](https://github.com/vpdeva/Energylink-Open-Source-DERMS)**  
  Open-source platform exploring energy data exchange, DERMS concepts, connectors, analytics, and dashboarding for distributed energy systems.

- **[Mini-DERMS / Feeder Controllers](https://github.com/ceh6514/Mini-DERMS-Feeder-Controller)**  
  Educational and prototyping systems for feeder-level DER coordination, telemetry ingestion, control loops, and operator dashboards.

- **[FTW – Home Energy Management](https://ftw.sourceful.energy/)**  
  Open-source, local-first home energy management system for solar, batteries, grid interaction, and EV charging with price-aware planning.

- **[Open EMS and microgrid EMS projects](https://github.com/search?q=open+EMS+OR+microgrid+energy+management+OR+DERMS)**  
  Community and research projects for site-level or microgrid energy management, battery/grid regulation, and optimized power flow.

- **[SCADA & control prototypes](https://github.com/search?q=smart+grid+SCADA+OR+PLC+energy+management)**  
  Academic and open projects demonstrating real-time monitoring, fault detection, and renewable prioritization using PLC/SCADA concepts.

- **[IEC 61850 and protocol stacks](https://github.com/search?q=IEC+61850+OR+OpenSCADA+OR+libiec61850)**  
  Open-source libraries and tools supporting power-system communication standards used in smart grid and substation automation.

### Additional Strong Open-Source Options

- **Time-series & analytics stacks**: InfluxDB, TimescaleDB, Grafana, and Prometheus commonly used for grid and DER telemetry.
- **MQTT / IoT brokers**: Mosquitto and related messaging layers for grid-edge device communication.
- **Optimization & forecasting libraries**: Open-source tools for load forecasting, unit commitment, optimal power flow, and flexibility scheduling.
- **GIS & network modeling**: Tools that support grid topology, feeder models, and spatial analysis.
- **Home/building energy systems**: Broader open-source HEMS and BEMS projects that can interface with utility programs.
- Research platforms for virtual power plants, demand response, and transactive energy.

**Frameworks for building custom systems**:  
Utility-scale smart grid management (ADMS, EMS, full DERMS, SCADA) is dominated by commercial platforms because of stringent reliability, cybersecurity, regulatory, and real-time performance requirements.  
Open-source components excel at energy data management (**MyEMS**), DER scheduling (Alliander and related projects), microgrid/site EMS, home energy optimization (**FTW** and similar), and research/prototyping.  
Many modern architectures combine commercial core grid systems with open-source analytics, edge control, and flexibility layers. Full replacement of production ADMS/SCADA with open-source remains rare and requires extensive domain expertise and validation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Smart grid and utility control systems are safety- and mission-critical. They affect power system reliability, public safety, and critical infrastructure. Any software used in live grid operations must meet applicable regulatory, cybersecurity, and operational standards.
- Open-source projects listed here are primarily suitable for energy management, research, microgrids, DER coordination prototypes, or non-critical layers. They are not drop-in replacements for certified utility ADMS/SCADA/DERMS platforms.

---

**Made for utility operators, grid engineers, DER aggregators, energy technologists, and researchers.**  
Let's encourage greater openness, interoperability, and innovation in smart grid software where safety and reliability allow.
