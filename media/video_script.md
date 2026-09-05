# 🎬 TellMAX.AI — Master Video Submission Script (10 min)
## Cisco Partner Innovation Challenge 2026

> [!IMPORTANT]
> **Format & Time Budget:** Maximum 10-minute MP4 video for official portal submission.
> **Interleaved Narrative Flow:** Víctor's customer testimonial is split into 2 strategic parts — **Part 1 (The Problem)** sets the real-world pain before the demo, while **Part 2 (The Impact)** validates the real-world results after the demo.

---

## 📊 Interleaved Master Video Breakdown

| Seg | Section | Presenter / Source | Duration | Recording & Storyline Role |
|---|---|---|---|---|
| 1 | **Project Pitch & Market Problem** | Voiceover + Motion Graphics | 1:45 | Set macro IT/OT alert fatigue & MTTR bottleneck |
| 2 | **Víctor Testimonial — Part 1: The Problem** | Víctor (IT Director - Cap Vermell) | 0:45 | **Customer Real-World Problem** (pre-demo pain) |
| 3 | **Cisco Tech Alignment & Architecture** | Voiceover + Web Scroll | 1:30 | Explain Splunk + Meraki + 2-Phase UCS Architecture |
| 4 | **José's Intro & KIW Innovation Track Record** | José Plá (KIW Founder) | 1:15 | José intro, KIW challenge history & vision |
| 5 | **Working Code & Real-Time API Integrations** | Screen Recording + IDE | 1:30 | Splunk SPL, Meraki API, Catalyst & Cisco Duo |
| 6 | **Live Working Demo (Chat & ToIP Voice AI)** | Screen Recording + Phone | 1:45 | Live Webex/Telegram + Room Ext 1999 Voice AI |
| 7 | **Víctor Testimonial — Part 2: The Impact** | Víctor (IT Director - Cap Vermell) | 0:45 | **Customer Real-World Impact** (-85% MTTR proof) |
| 8 | **Executive Closing & Call to Action** | José Plá (KIW Founder) | 0:45 | Final pitch & "Just Tell MAX" call to action |
| | **TOTAL TIME** | | **10:00** | |

---

## 🎬 SEGMENT 1 — EXECUTIVE PITCH & MARKET PROBLEM (1:45)
**Visual Style:** Dynamic B-roll of NOC screens, alert cascades, factory lines, hospital wards, and animated data cards.  
**Audio:** Voiceover (English).

**Script (Voiceover):**
> *"Every day, enterprise IT operations and Managed Service Partners are drowning in alert fatigue. Modern critical infrastructure environments generate thousands of daily telemetry events across fragmented networking, security, and building management tools.
>
> Recent industry research reveals that 74% of IT teams suffer from severe alert fatigue, while average incident resolution times (MTTR) stretch from 45 to 90 minutes because engineers must manually cross-reference data across isolated dashboards.
>
> The financial cost is staggering: in Manufacturing, unplanned downtime costs factory operators $39,000 per minute ($2.3M+ per hour) in lost SCADA production. In Healthcare, hospital outages cost up to $15,000 per minute across 15 to 20 connected medical IoT devices per bed. In Finance, outages cost $5.6M per hour, compounded by strict EU DORA regulatory penalties."*

---

## 🎬 SEGMENT 2 — VÍCTOR TESTIMONIAL: PART 1 — THE PROBLEM (0:45)
**Visual Style:** On-site video recording of Víctor at Cap Vermell Grand Hotel (5-star luxury resort in Mallorca).

**Varsha's Interview Questions (Part 1):**
1. *"Before TellMAX.AI, what did a typical day look like when something went wrong on the network?"*
2. *"How long did it usually take to figure out what was wrong and fix it?"*
3. *"What did that delay actually cost you in time, stress, or customer complaints?"*

**Script (Víctor — Talking Head / In Situ):**
> *"Hola, soy Víctor, Director de IT en Cap Vermell Grand Hotel, un resort de gran lujo de 5 estrellas en Mallorca.
>
> Antes de contar con TellMAX.AI, cuando surgía una incidencia de red o de climatización en las villas, nuestros técnicos tenían que revisar manualmente múltiples pantallas de Meraki y del sistema de gestión de la edificación. Identificar el origen del problema y enviar a un técnico llevaba entre 30 y 45 minutos, lo que generaba fricción y estrés en la experiencia del huésped."*

---

## 🎬 SEGMENT 3 — CISCO TECH ALIGNMENT & 2-PHASE ARCHITECTURE (1:30)
**Visual Style:** Screen recording scrolling through `https://pic26.kiw.one/draft.html?preview=pic26dev`, animating the architecture diagrams and Cisco product stack.  
**Audio:** Voiceover (English).

**Script (Voiceover):**
> *"TellMAX.AI captures a historic moment: the strategic unification of Cisco and Splunk. MAX is an Autonomous AI Operations Assistant that acts as a digital clone of the network engineer — continuously analyzing telemetry, diagnosing root causes, and executing automated closed-loop fixes in seconds.
>
> Splunk Enterprise serves as MAX’s central nervous system, ingesting NetFlow, Syslog, and Meraki MT IoT sensor telemetry via Splunk HEC. When an anomaly occurs, MAX acts as Splunk's 'frontal lobe' — translating complex SPL queries into natural conversation and executing remediation via Meraki Dashboard APIs, Catalyst Center APIs, and Cisco Spaces location density APIs.
>
> TellMAX.AI follows a 2-Phase Architecture: Phase 1 provides instant cloud-hybrid onboarding without hardware lead times, while Phase 2 enables regulated enterprises to deploy 100% on-premise on Cisco UCS AI Pod servers for complete local data sovereignty."*

---

## 🎬 SEGMENT 4 — JOSÉ'S EXECUTIVE INTRO & KIW TRACK RECORD (1:15)
**Visual Style:** José Plá (KIW Team Leader) talking head on camera, professional office/tech background, overlaying logos of past Cisco Challenge submissions.

**Script (José Plá — Camera):**
> *"Hi, I'm José Plá, Founder and Team Leader at KIW Intercloud, a specialized Cisco Partner based in Spain.
>
> For years, KIW has proudly participated in the Cisco Partner Innovation Challenge, bringing real-world solutions that push the boundaries of networking, observability, and automation. We understand firsthand the challenges that Cisco MSPs and IT teams face every day: complex infrastructure, alert fatigue, and a shortage of senior L2/L3 engineering talent.
>
> We built TellMAX.AI to solve this exact gap. MAX isn't just another passive Q&A chatbot sitting on top of the network — MAX is an autonomous execution engine that understands operational context, reasons using domain-specific technical playbooks, and takes direct, closed-loop action through Cisco APIs.
>
> Let me show you MAX running live in production."*

---

## 🎬 SEGMENT 5 — WORKING CODE & REAL-TIME API INTEGRATIONS (1:30)
**Visual Style:** Split screen: VS Code editor on the left showing Python/MCP connectors; terminal windows on the right showing live REST API responses.

**Script (José Plá — Screen Recording & Voiceover):**
> *"Let's look under the hood. MAX is built on modular microservices powered by Model Context Protocols (MCP).
>
> Here in the terminal, you can see our real-time telemetry pipeline. MAX constantly ingests Meraki MT IoT environmental readings — temperature, humidity, water leak detection — via the Meraki Dashboard API v1.
>
> Concurrently, MAX interfaces with Splunk Enterprise via the REST API using Search Processing Language (SPL). When Splunk flags a network anomaly or VLAN traffic spike, MAX cross-references live sensor data and queries Catalyst Center APIs to perform TDR cable tests and verify switch port health.
>
> Everything MAX does is governed by strict Zero-Trust security rules, integrating with Cisco Duo and Cisco ISE for role-based access control. Let's see this in action."*

---

## 🎬 SEGMENT 6 — LIVE WORKING DEMO (CHAT & TOIP VOICE AI) (1:45)
**Visual Style:** Screen recording of Webex / Telegram chat interface alongside a live video overlay of a Cisco IP Phone dialing extension 1999.

**Demo Flow & Script:**

1. **Natural Language Incident Triage (0:00 - 0:55):**
   - **Engineer types in Webex:** *"@MAX check Wi-Fi degradation in Building 3 Assembly Line."*
   - **MAX Response (in <3 sec):** *"Analyzed Meraki MR Wireless Health API and Splunk ITSI. AP-04 is experiencing 82% RF channel congestion due to local radar interference. Recommended Action: Execute auto-channel re-assignment on 5GHz radio. Do you approve?"*
   - **Engineer clicks / types:** *"Approved."*
   - **MAX Execution:** Programmatically invokes Meraki Dashboard API, re-assigns radio channel, and logs audit trail to Splunk HEC.
   - **José Voiceover:** *"Notice how MAX required human-in-the-loop approval before executing the remediation, completing the entire triage and fix in under 5 seconds."*

2. **Interactive Hands-Free Voice AI Call (0:55 - 1:45):**
   - **Field Engineer / Guest dials Ext. 1999 on Cisco IP Phone.**
   - **Cisco CUBE SIP Gateway routes call to MAX Voice Engine.**
   - **MAX Voice (Audio):** *"Hello, this is MAX Operations Assistant. How can I help you with Room 76?"*
   - **Engineer speaks:** *"The Wi-Fi access point seems offline and the HVAC is set too low."*
   - **MAX Voice (Audio):** *"I queried Meraki Dashboard API: Port 12 on Switch-02 lost PoE link. I also checked BACnet BMS: room temp is 18°C. I am bouncing Port 12 and adjusting thermostat to 22°C now."*
   - **José Voiceover:** *"Hands-free voice operational control routed natively through Cisco CUBE and Webex Calling — eliminating friction for technicians on the move."*

---

## 🎬 SEGMENT 7 — VÍCTOR TESTIMONIAL: PART 2 — THE IMPACT (0:45)
**Visual Style:** On-site video recording of Víctor at Cap Vermell Grand Hotel (5-star luxury resort in Mallorca).

**Varsha's Interview Questions (Part 2):**
1. *"Can you walk us through a specific incident MAX caught or resolved?"*
2. *"How much faster is resolution now, roughly?"*
3. *"Would you trust MAX to run unsupervised — why or why not?"*

**Script (Víctor — Talking Head / In Situ):**
> *"Con TellMAX.AI y KIW, la operativa ha cambiado por completo. Ahora, el personal de recepción o mantenimiento puede reportar la incidencia por Webex, WhatsApp o llamando desde el propio teléfono IP de la habitación. MAX diagnostica el puerto de switch o el termostato en tiempo real y ejecuta la corrección en menos de 5 segundos.
>
> Ha reducido nuestros tiempos de resolución en más de un 85% y ha incrementado la satisfacción del cliente en un 30%. Es una herramienta indispensable en nuestra operativa diaria."*

---

## 🎬 SEGMENT 8 — EXECUTIVE CLOSING & CALL TO ACTION (0:45)
**Visual Style:** José Plá talking head on camera, closing graphic overlay with TellMAX.AI logo and Cisco Partner Innovation Challenge 2026.

**Script (José Plá — Camera):**
> *"TellMAX.AI turns Cisco's entire portfolio into an active, conversational brain. For Cisco Partners, it's L0 superpowers that expand contract ARR by 25% to 40%. For Cisco, it's a software layer that guarantees customer adoption, retention, and subscription renewals.
>
> What you saw today is not a concept — it's a working system running in live production.
>
> Just Tell MAX. Thank you."*
