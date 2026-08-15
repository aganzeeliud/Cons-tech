---
Title: OWR Conservation Technology Strategy
Subtitle: Okapi Wildlife Reserve — Ituri Region, Democratic Republic of the Congo
Author: Wildlife Conservation Society (WCS) — Conservation Technology Unit
Prepared-by: WCS Conservation Tech & OWR CCOPS
Contact: conservationtech@wcs.org
Date: 2026-08-15
Version: 1.0
Keywords: conservation technology, law enforcement monitoring, ecological monitoring, data management
---

# OWR CONS TEC STRATEGY (2026–2030)

***

OWR Conservation Technology Strategy

Okapi Wildlife Reserve, Ituri Region — Democratic Republic of the Congo

Prepared by: Wildlife Conservation Society (WCS) — Conservation Technology Unit
Date: 2026-08-15 | Version: V1

***

Executive Summary

This concise strategy outlines a focused, five-year plan (2026–2030) to modernize OWR field operations, close data gaps, and strengthen biodiversity protection using appropriate conservation technologies. Priorities are: (1) digitize patrol reporting and incident response; (2) integrate camera traps, telemetry, acoustic sensors, eDNA, and satellite alerts into a unified ingestion and alerting pipeline; (3) apply AI and remote-sensing automation to reduce data-processing delays; and (4) build local capacity through targeted training and a certified trainer program. Expected outcomes: faster operational response, higher-quality monitoring data, measurable reductions in processing lag, and sustainable local ownership.

Key Strategic Outcomes (short)
- 100% digital patrol logging and near-real-time CCOPS visibility.
- 80% reduction in camera-trap processing time after AI integration.
- Rapid detection of canopy loss and illegal activity via automated alerts.
- Trained local trainers sustaining operations and maintenance.

Table of Contents

1. Executive Summary & Strategic Vision
2. Baseline Assessment & Operational Context
3. Strategic Framework & Technical Architecture
4. Core Implementation Pillars
   4.1 Patrolling & Law Enforcement Monitoring (LEM)
   4.2 Ecological & Environmental Monitoring
   4.3 Conservation Social Science & Safeguarding
   4.4 Data Science, Cartography & Impact Dashboards
5. Hardware, Sensors & Integration Architecture
6. Technical Support Structure & Technical Forums
7. Phased Implementation Roadmap (2026–2028)
8. Training Plan & Capacity Building
9. References
10. Annexes (Budget outline, Hardware lists, SOPs)

---



1. Executive Summary & Strategic Vision

The Okapi Wildlife Reserve (OWR), a UNESCO World Heritage Site located in the Ituri region in the north-east of the Democratic Republic of the Congo, is one of the most intact and biodiverse forests in Central Africa. It boasts high species endemism (15%), holds the second largest forest elephant population in the country, and serves as the global stronghold for the endemic okapi (Okapia johnstoni), a forest giraffe. The region also hosts abundant populations of 14 species of forest ungulates (including 6 duiker species), 15 species of primates including eastern chimpanzees, 58 species of fish, 376 species of birds, and over 2,500 known plant species.

Protecting this massive, ecologically dense landscape against pervasive threats—such as illegal bushmeat hunting, elephant poaching, artisanal gold mining, and agricultural encroachment—demands a modern, highly synchronized conservation technology infrastructure. The primary vision of this strategy is to empower OWR field staff, managers, and community partners with the software, sensors, analytical pipelines, and visualization platforms needed to capture, manage, analyze, and act upon mission-critical data in near real-time.

WCS IMPACT DASHBOARD MANDATE & VISION
WCS programs are generating a lot of scientific data. An Impact Dashboard is an information management tool that we use to monitor KPIs (Key Performance Indicator), metrics, and other mission critical data points relevant to our work.

Through its integrated use of data visualizations, maps, and other media, dashboards simplify and empower stakeholders and decision makers to explore complex datasets from multiple sources in one easy to use platform - often in near real time - to provide them with a wider understanding of the impact WCS is delivering.

Conservation Technology enables WCS field programs with the tools, training and support to quickly build and deploy their own impact dashboards. We can help you organize and translate your data into compelling analytics and visualization to show the impact of their work.

2. Baseline Assessment & Operational Context

2.1 Recent Operational Upgrades (December 2025 Implementation)
In December 2025, EarthRanger was implemented to support the assessment of operational systems, strengthen patrol coordination, improve data management, and establish a centralized platform for conservation and security management. The system is now fully operational and actively used to support field operations, monitoring, coordination, and decision-making.

2.2 Legacy & Existing Operational Systems
Garmin Explore is currently used by CCOPS (Centralized Control and Operations) to monitor patrol movements in real time in the field, alongside the use of SMART Patrol. SMART Desktop has also served as the primary platform for data collection and analysis for many years and continues to function effectively for operational reporting and monitoring.

2.3 Key Operational Challenges & Data Bottlenecks
Despite these advanced systems being in place, the data collection process remains largely manual, with ranger teams relying on paper-based observation records and manually captured GPS coordinates from Garmin inReach devices. This relies on time-consuming data entry, causes reduced operational efficiency, and creates potential gaps in data quality.

SMART Desktop remains the primary tool for data collection, processing, and analysis. However, the system presents significant challenges in its field data collection methodology when disconnected from mobile digital intake. EarthRanger functions as the primary real-time operational platform for protected area management and patrol monitoring, integrating GPS tracking, field reports, and incident alerts to support rapid response and coordinated decision-making. In addition, PTT (Push-to-Talk) communication devices were deployed to strengthen field communication and operational coordination.

As a result of these deployments, CCOPS now benefits from real-time situational awareness of ranger activities, improved communication between field teams and the operations center, and enhanced patrol coordination, supervision, operational efficiency, and donor reporting through more reliable and transparent performance data. However, fully bridging the remaining gap between paper field logs and live digital ingestion remains the immediate operational priority.

3. Strategic Framework & Technical Architecture

To avoid confusion and align across inter-agency stakeholders, it is critical to delineate Conservation Technology within the broader ecosystem of environmental technologies:

Sustainable Technology: Innovations designed to meet current needs without compromising future generations, emphasizing long-term resource management and minimal environmental impact (e.g., renewable energy, sustainable agriculture).

Environmental Technology: Tools and techniques specifically aimed at reducing human impact on the environment, including pollution control, waste management, and carbon emissions reduction.

Green Technology: A subset of environmental technology focusing on environmentally friendly products and processes (e.g., electric vehicles, green building materials).

Conservation Technology: Specifically geared towards preserving and protecting biodiversity, ecosystems, and natural habitats. It utilizes specialized tools like camera traps, drones, AI, remote sensing, eDNA, and law enforcement monitoring (LEM) systems to monitor wildlife, prevent poaching, and manage protected areas.

3.1 Strategic Goals

Goal 1 — Rapid Data Lifecycle: Deliver scalable field conservation solutions that enable OWR to capture, manage, and analyze data quickly.
Goal 2 — Enhanced Field Operations: Strengthen field operations and real-time CCOPS dispatch capabilities through integrated sensor arrays and communications.
Goal 3 — Evidence-Based Governance: Manage and leverage multi-source datasets to drive tactical decision-making and promote WCS's conservation mission.
Goal 4 — Local Capacity Building: Develop institutional capacity and ensure long-term technical sustainability across local Congolese field personnel and park authorities.

4. Core Implementation Pillars

Pillar I: Patrolling & Law Enforcement Monitoring (LEM)

Law Enforcement Monitoring forms the frontline defense of Okapi Wildlife Reserve. The strategy shifts all patrol teams from manual paper logs to a unified digital reporting stream.

CyberTracker / SMART Mobile: Primary platform for mobile data collection in the field. Eliminates paper forms by allowing rangers to log observations, human activity, carcasses, and illegal sign digitally on rugged mobile devices.

SMART Desktop & SMART Connect: Central data repository for managing, querying, and reporting spatial patrol effort, threat distribution, and ranger coverage metrics.

PAWS (Predictive Analytics): Integrates machine learning (Protection Assistant for Wildlife Security) to model poaching risk maps and suggest optimal, randomized patrol routes for CCOPS deployment.

EarthRanger: Serves as the live command-and-control visual platform at CCOPS. Integrates PTT communications, Garmin Explore tracking, real-time ranger locations, and incident alerts into one unified operational map.

Gundi: Interoperability integration engine that automatically routes hardware sensor feeds (telemetry, vehicle trackers, acoustic arrays) directly into EarthRanger and SMART.

Pillar II: Ecological & Environmental Monitoring

Rigorous scientific monitoring is essential to measure population dynamics of key species (okapi, forest elephant, chimpanzees, duikers) and track forest health across OWR's vast rainforest.

Camera Trapping: Used extensively across sample grids to capture elusive and nocturnal wildlife. Photos are managed and processed via AI tools.

Wildlife Insights: Cloud platform that provides data management infrastructure and AI models to automatically identify wildlife species in camera trap images and filter out blank photos, drastically reducing processing time.

Unmanned Aerial Vehicles (UAVs / Drones): Thermal and multispectral drones deployed to survey inaccessible canopy areas, track large mammal movements, observe forest clearings (bais), and support real-time poacher detection.

Environmental DNA (eDNA) & Genomics: Non-invasive sampling of water and soil to detect species presence (including cryptic ungulates and aquatic fauna) via genetic sequencing.

Acoustic Monitoring: Deployment of acoustic arrays to capture wildlife vocalisations, track nocturnal species, and automatically detect gunshot sounds across remote reserve sectors.

Biologging & Telemetry: Attaching electronic tags and tracking collars to key focal species (e.g., elephants) to track movement corridors and human-wildlife interaction in real time.

Global Forest Watch & Remote Sensing: Near real-time satellite remote sensing to detect canopy loss, illegal mining clearings, and agricultural encroachment inside OWR boundaries.

Statistical Suite (R, DISTANCE, PRESENCE, MARK, DENSITY): Specialized quantitative toolsets supported for rigorous survey design, transect analysis, occupancy, and population density estimation.

Pillar III: Conservation Social Science & Safeguarding

Sustainable conservation in Okapi Wildlife Reserve requires deep collaboration with local communities, indigenous Mbuti and Efe peoples, and surrounding agricultural settlements. The Conservation Social Science Partnership (ConSoSci) provides an integrated toolkit for socio-economic monitoring and safeguarding.

KoboToolbox: Mobile survey platform deployed for digital household data collection, community consultations, and governance assessments.

OpenFN: Data transformation and integration middleware that routes survey submissions automatically into central analytical pipelines.

ConSoSci Connect: Central data management, analysis, and visualization platform delivering rich social science insights within minutes of data collection.

Basic Necessities Survey (BNS): Standard survey modules deployed to monitor household socio-economic well-being, poverty alleviation, and community perceptions over time.

Natural Resources Governance Toolkit (NRGT): Evaluates local natural resource rights, institutional transparency, and community-level decision-making dynamics.

Pillar IV: Data Science, Cartography & Impact Dashboards

Translating massive streams of field data into compelling, actionable intelligence is the ultimate goal of the Conservation Technology strategy.

Data Science & Cartography
"A picture is worth a thousand words," as the saying goes. Maps help people understand concepts in a way that words cannot. Our team can step in to help when your program has a capacity gap, or when peaks in workload require additional help, whether the need is a map for a grant proposal, donor report, fundraising publication, conference presentation or a web map for widespread public viewing. We can create maps that align with the WCS map style, or alternatively we can create a new map style for your specific project. We can also create map templates that your program can use going forward, and modify as needs change. We can produce both Spanish and English products.

Data Science & Story Maps
A story map is a visually-engaging multimedia site you can use to tell your conservation story. An ArcGIS Online product that combines text, photos, videos, maps, web maps and web apps, a story map can be designed to reach a narrow or broad audience. Conservation Technology staff can work with you to design and publish story maps to inform, educate and engage donors, governments, and the global public.

OWR Integrated Impact Dashboard Architecture
The OWR Impact Dashboard aggregates data from SMART Connect, EarthRanger, Wildlife Insights, Global Forest Watch, and ConSoSci Connect into a single interactive web interface. Decision-makers can explore near real-time operational indicators (patrol km, coverage density, threat alerts), biological health indicators (species encounter rates, camera trap detections), and socio-economic governance metrics.

5. Hardware, Sensors & Integration Architecture

Hardware deployment in Okapi Wildlife Reserve is engineered for durability under high-humidity, dense-canopy tropical conditions. Key sensor hardware includes:

Patrol Hardware: Handheld GPS units, Garmin inReach satellite communicators, and Push-to-Talk (PTT) radios operating across CCOPS repeaters.

Field Sensors: eDNA water sampling kits, bio-acoustic recorders (e.g., Audiomoths / Swift units), cellular/satellite poacher cameras, and satellite collars.

Gundi Sensor Integration: Integrates data from telemetry, vehicle tracking, acoustic arrays, poacher cams, and field sensors directly into SMART and EarthRanger. WCS actively collaborates with research partners to scale technological innovations (such as Instant Detect 2.0 and thermal drones) into sustainable field outcomes.

6. Technical Support Structure & Technical Forums

To ensure continuity, capacity building, and rapid problem resolution, OWR staff can leverage dedicated global communities and internal WCS support channels:

SMART / CyberTracker / PAWS — SMART Community Forum, WCS Conservation Tech Request Portal
Capture-Recapture & Occupancy — PhiDot Forum, WCS Statistical Support & Analysis Team
Distance Sampling Analysis — Distance Sampling Google Group
Wildlife Insights & Forest Watch — Wildlife Insights User Community, WCS Conservation Tech Helpdesk

7. Phased Implementation Roadmap (2026 – 2028)

Phase 1: Full Ingestion Digitization (Q3-Q4 2026)
Phase out paper patrol forms; issue SMART Mobile rugged handhelds to 100% of ranger teams.
SMART Mobile, CyberTracker, CCOPS PTT — KPI: 100% digital patrol logging; 0 paper transcriptions.

Phase 2: Sensor Ingestion Streamlining (Q1-Q2 2027)
Deploy Gundi middleware to route inReach, telemetry, and camera trap feeds into EarthRanger live map.
Gundi, EarthRanger, Garmin Explore — KPI: Near real-time tracking of 100% field units at CCOPS.

Phase 3: AI & Ecological Automation (Q3-Q4 2027)
Integrate Wildlife Insights AI for camera traps; automate Global Forest Watch canopy loss alerts.
Wildlife Insights, GFW, R, Distance — KPI: 80% reduction in camera trap processing bottleneck.

Phase 4: Impact Dashboard & Story Maps (Q1-Q2 2028)
Build OWR Impact Dashboard and publish interactive ArcGIS Story Maps for donors and public.
WCS Impact Platform, ArcGIS Online — KPI: Live executive dashboard operational & accessible.

8. Collected Online Resources (Top 25 selection)

1) WCS Impact Dashboards
URL: https://impact.wcs.org/en-us/Dashboards
Summary: WCS Impact platform for dashboards and monitoring (site returned 404 during fetch; include link as provided in original doc).

2) SMART Conservation Tools
URL: https://www.smartconservationtools.org
Summary: SMART is an open-source suite for conservation monitoring and LEM (data collection, evaluation, reporting); community resources and documentation available on the SMART site.

3) EarthRanger
URL: https://www.earthranger.com
Summary: EarthRanger provides a live command-and-control mapping platform for protected area operations, supporting GPS tracking, incident management, and multi-source sensor ingestion.

4) Wildlife Insights
URL: https://www.wildlifeinsights.org
Summary: Cloud platform using AI to classify camera-trap images and manage camera trap datasets, aimed at accelerating species detection and reducing manual processing.

5) Global Forest Watch
URL: https://www.globalforestwatch.org
Summary: Interactive global forest monitoring platform for canopy loss, land use change, and alerts for deforestation events.

6) CIEEM — Conservation Technology overview
URL: https://cieem.net/conservation-technology-a-game-changer-rewilding-tech/
Summary: A sector blog discussing opportunities, challenges, and ethical considerations for conservation technology adoption.

7) WILDLABS — State of Conservation Technology
URL: https://wildlabs.net/state-of-conservation-technology
Summary: WILDLABS resources and state-of-the-field synthesis for conservation technology innovation and community collaborations.

8) CyberTracker
URL: https://www.cybertracker.org
Summary: Tools and research for non-literate field data collection and tracker-friendly mobile UIs for field observations and species monitoring.

9) KoboToolbox
URL: https://www.kobotoolbox.org
Summary: Mobile survey platform for humanitarian and field data collection; supports offline collection and integration with analytical workflows (403 on fetch but widely used).

10) OpenFn
URL: https://openfn.org
Summary: Integration middleware for routing and transforming form/submission data into downstream systems using secure SaaS connectors.

11) AudioMoth (project page)
URL: https://audiomoth.github.io
Summary: Low-cost, open hardware acoustic recorder (site returned 404 on direct fetch; link included as a known resource for bioacoustics).

12) Wildlife Acoustics
URL: https://www.wildlifeacoustics.com
Summary: Commercial provider of bioacoustic monitoring hardware and software for wildlife surveys and automated acoustic analyses.

13) GBIF — Global Biodiversity Information Facility
URL: https://www.gbif.org
Summary: International open-data platform for biodiversity occurrence data (403 on fetch; site often has bot protections but is a central data repository).

14) Movebank
URL: https://www.movebank.org
Summary: Online platform for animal movement data, project hosting, and sharing telemetry datasets.

15) TDWG — Biodiversity Information Standards
URL: https://www.tdwg.org
Summary: Organization producing international data standards and best practices for biodiversity data exchange and metadata.

16) Google Earth Engine
URL: https://earthengine.google.com
Summary: Planetary-scale geospatial analysis platform for satellite imagery & remote sensing workflows used in deforestation and land-change monitoring.

17) ArcGIS / StoryMaps
URL: https://www.arcgis.com
Summary: Esri ArcGIS Online platform enabling story maps, hosted web maps, and interactive dashboards for public-facing and donor-focused visualizations.

18) ODK (Open Data Kit)
URL: https://getodk.org
Summary: Open-source mobile data collection suite for offline-capable forms and deployment in low-connectivity field contexts.

19) DataONE
URL: https://www.dataone.org
Summary: DataONE provides distributed infrastructure and best-practice resources for open Earth observational data and data management.

20) Zenodo
URL: https://zenodo.org
Summary: General-purpose open research data/software repository for publishing datasets, DOIs, and preserving research outputs.

21) Figshare
URL: https://figshare.com
Summary: Research data repository and sharing platform for datasets, figures, and supplementary materials.

22) OpenStreetMap
URL: https://www.openstreetmap.org
Summary: Open global mapping resource for base mapping, roads, and community-contributed geospatial features that support field navigation and mapping contexts.

(Additional sources can be added to reach 25 on request — some sites returned protections or redirects when fetched; can retry specific pages.)

9. Next steps to produce final Word document

- Review and confirm the included online resources (OK to include the 22 above; add 3 more if needed to meet 25).
- Convert this consolidated markdown into a Word (.docx) file and save as "Okapi_Wildlife_Reserve_Conservation_Technology_Strategy_with_resources.docx" in the repository.
- Optionally commit the new DOCX to the repo and include a commit message describing the update.


## Annex A: Integrated RFO Data Protocol (summary)

This annex synthesizes key elements from the RFO "DATA PROTOCOL" (Draft) found in the OWR repository. It formalizes data handling expectations across collection, processing, quality control, storage, visualization, and sharing.

A.1 Purpose & Scope
- Formalize how WCS/OWR collects, manages, analyzes, and publishes program data to ensure confidentiality, integrity, and usability for decision-making and reporting.
- Applies to operational (patrols, incidents), ecological (camera traps, acoustic, eDNA), social science (Kobo/household surveys) and remote-sensing datasets produced by OWR programs.

A.2 Key Roles & Responsibilities
- MEAL Team / Data Manager: primary custodians for data ingestion, cleaning, validation, and archiving.
- Database/IT: platform administration, access control, and backups.
- Program Leads: dataset owners who approve dataset release and use.
- CCOPS / Conservation Tech: responsible for operational sensor feeds, EarthRanger integrations, and near-real-time alerts.

A.3 Data Collection & Tools
- Approved collection tools: Kobo Collect (surveys), SMART/CyberTracker (patrols/LEM), Garmin/telemetry (tracking), camera trap platforms, acoustic recorders, eDNA sampling kits.
- Use coded Unique Identifier Codes (UICs) for sensitive social data to separate personal identifiers from research datasets and protect confidentiality.
- Recording: obtain consent for interviews/FGDs; audio recordings transcribed then deleted after transcription per the protocol.

A.4 Data Flow & Ingestion
- Primary ingestion pipeline: field tools → secure upload (Kobo/SMART/Device sync) → centralized staging (SharePoint / WCS-hosted DB) → cleaning/validation → approved clean datasets exported to analysis and dashboards (PowerBI, EarthRanger, StoryMaps).
- For sensor data (camera traps, telemetry, acoustic): follow established ingestion routes into Wildlife Insights / EarthRanger / Gundi middleware for real-time or batched handling.

A.5 Metadata, Formats & Standards
- Capture metadata automatically where possible (device ID, start/end timestamps, GPS, operator ID).
- Use standard export formats: CSV, XLSX, GeoJSON/Shapefiles for geodata, JSON/XML for APIs. Follow TDWG and other biodiversity metadata conventions where relevant.

A.6 Data Processing & Deliverables
- Data processing steps: initial QC, standard cleaning scripts, metadata enrichment, analysis-ready exports.
- Expected deliverables: cleaned datasets, PowerBI/Impact dashboards, SMART reports, NRGT site reports, and periodic Data Audit Reports.
- Estimated data volumes: plan for monthly volumes (50–1000 MB) depending on sensor deployments.

A.7 Data Quality & Review
- Implement Data Audit Forms (DAF) and quarterly Data Quality Audit Reports summarizing problems, corrective actions, responsible staff, and timelines.
- Core QC checks: completeness, conformity, consistency, accuracy, eligibility.

A.8 Storage, Archiving & Preservation
- Raw and cleaned data stored with role-based access on SharePoint / WCS-hosted storage; archived copies retained according to project retention schedules.
- Identify datasets for destruction and assign an archiving steward responsible for long-term preservation.

A.9 Data Sharing & Diffusion
- During project: controlled sharing among WCS project teams for analysis and operational response.
- After project: publish non-sensitive datasets to public repositories (Zenodo, Figshare, GBIF where appropriate) with DOIs and clear licensing; sensitive data withheld or shared under data-sharing agreements.

A.10 Visualization & Reporting
- Use PowerBI, ArcGIS StoryMaps, and the WCS Impact Dashboard for internal and external reporting.
- Define update frequency and dashboard roles (editors/viewers) and align data refresh schedules with ingestion cadence.

A.11 Update Frequency & Governance
- Review and update the Data Protocol annually or when major technical/operational changes occur.
- Maintain a change log and dataset registry documenting versions, stewards, and access rules.

A.12 Next steps for technical integration
- Incorporate RFO protocol metadata and DAF templates into the OWR Data Governance folder.
- Automate ingestion pipelines for Kobo, SMART, and camera-trap exports; connect to Gundi/EarthRanger where applicable.
- Schedule MEAL–ConservationTech joint workshops to operationalize QC checks, DAF usage, and archiving responsibilities.

---

## Annex B: Drone Protocol (RFO) — key points

This annex summarizes operational and ethical guidance from the Protocole Drone RFO (DRAFT V4) to ensure safe, secure, and scientifically rigorous drone deployments across OWR.

B.1 Purpose & Role
- Drones are deployed for tactical reconnaissance, biosurveillance, habitat mapping, and to reduce risk to ground teams in insecure areas; mission types include species counts, thermal surveys, deforestation mapping, and patrol support.

B.2 Operating Principles
- Conform to ICCN and CCOPS-RFO security directives; minimize disturbance to wildlife and communities; apply One Health and ethical considerations in mission design.
- Use appropriate sensors (thermal radiometric, multispectral/optical) matched to objectives; prioritize minimal-visibility flight profiles.

B.3 Mission Planning (POP)
- Define objectives, select payload, obtain clearances, design routes avoiding sensitive zones, and set emergency retraction/exfiltration plans.
- Pre-flight checks: battery thresholds (min 80%), sensor calibration, SD card formatting (U3), telemetry verification.

B.4 Flight Parameters & Safety
- Altitude: 50–120 m recommended; maintain VLOS with pilot/observer; avoid flights in heavy precipitation or winds >35 km/h.
- Satellite/GPS minimum: 12 satellites; battery rule of thirds for safe return.

B.5 Roles & Organization
- Unit Lead: mission approval and liaison with CCOPS.
- Pilot (certified): aircraft operation and safety.
- Visual Observer: airspace/ground safety and radio comms.
- Data Steward (GIS/Analyst): secure retrieval, QA, encryption, and archiving.

B.6 Data Handling & Security
- Immediate post-mission: decrypt/sanitize, transfer to encrypted server, and log mission metadata (timestamps, coordinates, sensor settings, incidents) in Operations Journal.
- Restrict publication/sharing of precise species/locality coordinates; anonymize or aggregate sensitive locations before external release.
- Store media in secure, climate-controlled storage; enforce encryption on portable media.

B.7 Ethical & Community Considerations
- Never image civilians or Indigenous peoples without consent; avoid sacred/cultural sites; pause flights if community disturbance is detected.

B.8 Maintenance & Logistics
- Climate-aware battery care (avoid storage >48h at full charge in high heat/humidity); use Pelican cases and desiccants; follow LiPo safety protocols.

B.9 Incident Management
- Record GPS last-known for crashes; prioritize team safety in recovery; if drone compromised by hostiles, do not attempt risky retrieval.
- Document cybersecurity incidents and switch to manual/ATTI mode if anomalous behavior detected.

B.10 Training Implications
- Integrate drone SOPs into training modules: pre-flight checks, mission planning, ethics, emergency response, data security, maintenance, and post-mission processing.
- Certify a cadre of pilots, observers, and data stewards as part of the Train-the-Trainer program.

---

## References

1. WCS Impact Dashboards — Wildlife Conservation Society. https://impact.wcs.org/en-us/Dashboards
2. SMART Conservation Tools — SMART Partnership. https://www.smartconservationtools.org
3. EarthRanger — Vulcan Inc. / EarthRanger Platform. https://www.earthranger.com
4. Wildlife Insights — Smithsonian, Microsoft & partners (AI camera-trap platform). https://www.wildlifeinsights.org
5. Global Forest Watch — World Resources Institute (forest monitoring & alerts). https://www.globalforestwatch.org
6. CIEEM — Conservation Technology overview (analysis & sector commentary). https://cieem.net/conservation-technology-a-game-changer-rewilding-tech/
7. WILDLABS — State of Conservation Technology (community hub & syntheses). https://wildlabs.net/state-of-conservation-technology
8. CyberTracker — Field data collection for non-literate trackers. https://www.cybertracker.org
9. KoboToolbox — Mobile data collection for field and humanitarian contexts. https://www.kobotoolbox.org
10. OpenFn — Integration middleware for humanitarian & conservation data. https://openfn.org
11. AudioMoth — Low-cost acoustic recorder project. https://audiomoth.github.io
12. Wildlife Acoustics — Commercial bioacoustics solutions. https://www.wildlifeacoustics.com
13. GBIF — Global Biodiversity Information Facility (occurrence data). https://www.gbif.org
14. Movebank — Animal movement data repository and tools. https://www.movebank.org
15. TDWG — Biodiversity Information Standards (data & metadata standards). https://www.tdwg.org
16. Google Earth Engine — Planetary-scale geospatial analysis. https://earthengine.google.com
17. ArcGIS / StoryMaps — Esri ArcGIS Online & StoryMaps for visualization. https://www.arcgis.com
18. ODK (Open Data Kit) — Offline-capable mobile forms and ecosystem. https://getodk.org
19. DataONE — Distributed infrastructure for Earth observational data. https://www.dataone.org
20. Zenodo — Open research data repository (DOIs). https://zenodo.org
21. Figshare — Research data sharing platform. https://figshare.com
22. OpenStreetMap — Community mapping platform and basemap. https://www.openstreetmap.org
23. Zooniverse — Citizen science platform for classification & annotation. https://www.zooniverse.org
24. Conservation X Labs (CXL) — Innovation hub accelerating conservation tech. https://conservationxlabs.com
25. Re:wild — Conservation organization focused on species recovery. https://www.rewild.org

Notes: URLs were accessed during draft compilation; some sites apply bot protections or redirects. Include DOIs or archived copies when required for formal citation.
23) Zooniverse
URL: https://www.zooniverse.org
Summary: Global citizen-science platform enabling public participation in data annotation and species identification workflows; useful for scaling image/audio classification and engaging communities in verification.

24) Conservation X Labs (CXL)
URL: https://conservationxlabs.com
Summary: An innovation hub that accelerates conservation technology solutions and market-based approaches to protect ecosystems; useful for partnerships, prototyping, and tech-for-good initiatives.

25) Re:wild
URL: https://www.rewild.org
Summary: Global conservation organization focused on species recovery and landscape-scale protection; a partner and funder resource for large-scale conservation projects.

9. Expanded Training Plan (OWR Conservation Technology Capacity Building)

Objectives
- Equip ranger teams, CCOPS staff, and community monitors with practical skills to operate, maintain, and troubleshoot deployed hardware and software.
- Build local trainers to sustain systems and reduce external dependence.
- Improve data quality, timeliness, and analytic capacity for evidence-based decisions.

Curriculum Modules
- Device operation & field best-practices: Garmin devices, rugged smartphones, camera trap deployment, acoustic recorder handling, power management.
- SMART / CyberTracker mobile workflows: form design, offline sync, QA checks, incident reporting.
- EarthRanger & CCOPS dashboard use: live monitoring, incident triage, sensor integration, alerting.
- Camera trap & Wildlife Insights pipeline: deployment protocols, image management, basic AI review and validation.
- Acoustic & eDNA basics: deployment, sample chain-of-custody, metadata standards.
- Data governance, metadata, and open-data practices: TDWG standards, data licensing, sensitive data handling.
- GIS & dashboard storytelling: basic QGIS/ArcGIS Online tasks, map creation, and preparing story maps for stakeholders.

Training Approach
- Phase 1: Intensive 10-day in-person bootcamps for core staff (rangers, CCOPS, data team).
- Phase 2: Two-week field mentorships pairing local trainers with teams during routine patrols and sensor deployments.
- Phase 3: "Train-the-Trainer" certification: select 8–10 local staff for trainer certification and refresher schedule.
- Continuous: Quarterly remote refresher workshops and annual assessment exercises.

Assessment & KPIs
- # staff trained and certified (target: 100% of ranger teams trained by end of Phase 1).
- Data latency reduction (target: 80% of patrol reports ingested digitally within 24 hours).
- Data quality metrics: percentage of complete records, GPS accuracy, correct species IDs after AI validation.

Budget & Resources (high-level)
- Training materials, translation/localization, per diems, and travel for trainers.
- Spare hardware kit per team (batteries, SD cards, charging banks, spare sensors).
- Modest budget for cloud processing credits (Wildlife Insights, GFW alerts) and internet connectivity at CCOPS.

Next steps (updated)
- Append three new resources and training plan into the DOCX.
- Regenerate Word doc and commit the updated files.

(End of draft)