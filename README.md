# TwinPave Robotics Lab  
**Twin-Guided Robotic Pavement Overlays (T-GRO): Safer, Faster, Cleaner Resurfacing**

> **ARPA-I Ideas & Innovation Challenge – Stage 1 Winner**  
> Concept: *Twin-Guided Robotic Pavement Overlays (T-GRO)* – $20,000 prize award (Stage 1), invited to Stage 2 and ARPA-I Ideas Bootcamp.

---

## 1. Vision

**What if DOTs could renew pavements overnight—keeping traffic moving—by pairing a live digital twin with robotic paving fleets that cut lane closure hours in half while still delivering pay-factor quality?**

TwinPave Robotics Lab is building exactly that: a **digital twin–guided robotics platform** for lane-level pavement resurfacing, turning overlays from slow, manual construction projects into **data-driven, semi-autonomous, QA-closed-loop operations**.

---

## 2. Problem

Pavement overlays are the backbone of highway preservation, but today they are:

- **Disruptive** – multi-night lane closures, detours over weight-restricted bridges, shockwaves on urban arterials.
- **Process-constrained** – narrow temperature windows for HMA placement and compaction; plant output, haul cycles and paver speed tightly bound throughput.
- **Quality-fragile** – thermal segregation, roughness, and joint defects when trucks are late, weather shifts, or rolling is not properly sequenced.
- **Manually managed** – intelligent compaction, thermal profilers and profilers exist, but they run in silos with no real-time feedback loop.
- **Risky work zones** – high-speed differentials, complex tapers, and large on-foot crews drive crash risk and worker exposure.

Agencies often extend closures to protect quality, **trading more delay and exposure** for a modest reduction in risk. There is no integrated way to jointly optimize **traffic, construction, robotics, and QA** at corridor scale.

---

## 3. Solution: Twin-Guided Robotic Pavement Overlays (T-GRO)

**T-GRO** combines:

1. 🛰 **Corridor Digital Twin (2–72 hours)**  
   - Lane-specific demand and geometry  
   - Plant production, truck dispatch cycles, and fleet telemetry  
   - Pre-overlay condition: IRI, rutting, historical distress  
   - Encoded guardrails: MUTCD lane-closure charts, pay-factor specs, OSHA rules, HOS/haul limits, agency doctrine  

2. 🤖 **Robotic Paving Fleets (Overlay Work-Cells)**  
   - 3D-controlled mills and pavers with screed & thermal control  
   - Leader–follower intelligent compaction (IC) rollers  
   - Robotic ATMA/TMA protection and smart tapers/cones  
   - Semi-autonomous work-cells supervised by operators, not micromanaged by them  

3. 🧠 **Generative AI Planning + Physics-in-the-Loop Scoring**  
   - Graph-based generative planner samples **thousands of nightly overlay portfolios**  
   - Feasibility discriminator filters out non-constructible or non-compliant plans  
   - Surrogate models score queues, delay, worker exposure, density/smoothness risk, and CO₂e  
   - Multi-objective optimization (e.g., NSGA-II/III) selects **Pareto-optimal plans**

4. 🔁 **Model Predictive Control (MPC) with Embedded QA**  
   - During execution, the twin ingests:
     - IC values, thermal segregation maps, and on-the-fly IRI snapshots  
   - MPC updates convoy speed, rolling patterns, and detour/VSL settings to:
     - Keep density and smoothness on target  
     - Hold spillback and worker exposure below thresholds  
     - Hit reopen times with ≥95% reliability  

---

## 4. Target Outcomes

T-GRO is designed to deliver **order-of-magnitude improvements in how overlays are planned and executed**:

- ⏱ **≥50% fewer lane-closure hours**  
- 🚚 **≥30% lower user delay** (truck and system delay)  
- 🦺 **≥40% fewer worker exposure hours** in live traffic  
- 🌱 **≥20% lower CO₂e** from haul, idling, and stop-go traffic  
- 🛣 **≥2 pay-factor grade improvements** in density and smoothness  
- 📈 **≥95% “reopen reliability”** – lanes open when the plan says they will

These metrics align directly with DOT priorities: safety, mobility, cost, and decarbonization.

---

## 5. Stage 1 Scope (ARPA-I Concept)

The ARPA-I Stage 1 concept paper focuses on two pilot use cases:

1. **Urban arterial night overlay** with constrained detours  
2. **Interstate mainline overlay** with heavy truck volumes  

Key Stage 1 milestones:

- Build a **2–72 hour corridor twin** and guardrail engine  
- Implement **Generative Planner v1** + feasibility discriminator  
- Integrate **physics-in-the-loop scoring** for traffic, QA, exposure, and CO₂e  
- Demonstrate **shadow operations** and **supervised robotic trials** (e.g., leader–follower IC rollers + ATMA tail)  
- Achieve:
  - ≥100 rule-clean nightly plans per forecast  
  - ≥40% lane-closure-hour reduction vs. baseline  
  - ≥30% worker exposure reduction  
  - Travel-time prediction error ≤10%  
  - Successful supervised run of a robotic overlay cell

---

## 6. This Repo

This repository currently hosts the **public landing page** for TwinPave Robotics Lab and the T-GRO concept:

- `index.html` – single-page site describing:
  - TwinPave vision and value proposition  
  - T-GRO concept & core components  
  - Key metrics and target outcomes  
  - Contact path for pilots, collaborations, and investors  

GitHub Pages is used for fast iterations and transparent, lightweight deployment.

---

## 7. Roadmap (High-Level)

**Near term (0–12 months)**  
- Refine concept with ARPA-I Stage 2 engagement and pilot DOT feedback  
- Build early corridor twin + guardrail engine prototype  
- Integrate with representative IC/thermal/ATMA data streams  
- Run simulation-based “virtual pilots” to de-risk metrics

**Medium term (12–36 months)**  
- Field pilots on selected corridors (night work + daytime operations)  
- Expand robotics integrations (multiple OEMs; mixed fleets)  
- Harden safety case, cybersecurity posture, and auditability  
- Develop a repeatable deployment playbook for DOTs and large contractors

**Long term (36+ months)**  
- Position TwinPave as a **standard capability** for resurfacing programs  
- Evolve from “tooling” to **performance-based resurfacing platform**  
- Extend to airfield pavements, complex interchanges, and multi-contractor corridors

---

## 8. Contact

Interested in:

- DOT or contractor **pilot deployments**  
- OEM or data partnerships (pavers, rollers, ATMA/TMA, IC, thermal, IRI)  
- **Venture or strategic investment** aligned with construction robotics & infrastructure AI  

Reach out via:

- GitHub: [@franklin02](https://franklin02.github.io/twinpave-site/)  
- Project site: `https://twinpave.ai` (via this repository’s GitHub Pages)

---

> **TwinPave Robotics Lab** is the studio behind the ARPA-I Stage 1 winning concept  
> *“Twin-Guided Robotic Pavement Overlays (T-GRO): Safer, Faster, Cleaner Resurfacing.”*
