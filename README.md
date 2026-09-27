# automotive-fuel-system-cad-design
AUtomotive Fuel System CAD Design

# Automotive Fuel Tank System Assembly Design (CATIA V5 / 3DEXPERIENCE)

## Project Overview
This project presents an industry-standard, production-ready **Automotive Fuel Tank System Assembly** developed within a PLM-centric workflow. The design emphasizes packaging space optimization, structural integrity for crashworthiness, regulatory compliance (evaporative emissions), and manufacturing feasibility (blow molding and sheet metal stamping).

### Key Highlights Covered from Job Requirements:
*   **3D Modeling & Assemblies:** Complex surface modeling (Generative Shape Design) and assembly constraints in CATIA V5.
*   **GD&T Application:** 2D engineering drawings completely constrained utilizing ISO 1101 / ASME Y14.5 standards.
*   **DFMEA & Engineering Quality:** Proactive failure mode mitigation for fuel system sealing, permeation, and structural failures.
*   **PLM & Change Management:** Structured Bill of Materials (BOM) alongside a standard Engineering Change Request (ECR) framework.

---

## Technical Specifications & Tools
*   **CAD Platforms:** CATIA V5 (R21/V5-6R2019) & Dassault Systèmes 3DEXPERIENCE
*   **Workbenches Used:** Part Design, Assembly Design, Generative Shape Design (GSD), Drafting
*   **Regulatory Targets:** ECE R34 (Prevention of Fire Risks), EPA Evaporative Emission Standards
*   **Materials Selected:** 
    *   *Tank Shell:* High-Density Polyethylene (HDPE) with an EVOH barrier layer (6-layer co-extrusion blow molding).
    *   *Mounting Brackets:* FeP04 Deep Drawing Steel (Stamping).

---

## Repository Structure & Deliverables
*   `/CAD_Models/STEP_Exports/`: Cross-platform neutral 3D files for visual review.
*   `/Drawings_2D/`: High-precision manufacturing prints featuring comprehensive **GD&T** blocks, datum reference frames, and tolerance stack-ups.
*   `/BOM/`: Production-ready Product Lifecycle Management structure detailing part numbers, hierarchy, and quantities.
*   `/Documentation/`: Engineering validation artifacts including **DFMEA** spreadsheets and **ECR/ECO** logs simulating an OEM design workflow.

---

## Engineering Analysis & Validation Showcase
### 1. Packaging & Interface Integration
The fuel tank geometry was constrained within the vehicle-level underbody environment, maintaining a minimum clearance of **25mm** from exhaust heat shields and **15mm** from dynamic rear suspension moving parts.

### 2. Digital Mock-Up (DMU) Interference & Clearance Checks
*   Performed a matrix-based clash analysis across the assembly.
*   Verified a clearance gap fitment of **2.0mm ± 0.5mm** at the fuel pump module O-ring sealing compression flange to guarantee zero fuel vapor trace leaks.

### 3. GD&T Strategy Example (Mounting Bracket)
*   **Primary Datum A:** Interface mating face to vehicle chassis (Flatness control: 0.1mm).
*   **Secondary Datum B:** Main positioning locator hole (2× Position boundary control: ∅ 0.2mm at MMC).
*   
```
automotive-fuel-system-cad-design/
├── README.md
├── .gitignore
├── BOM/
│   └── PLM_Bill_of_Materials.csv
├── CAD_Models/
│   ├── STEP_Exports/
│   │   ├── FT-01-00_Fuel_Tank_Assembly.stp
│   │   ├── FT-01-01_Plastic_Shell_Blow_Molded.stp
│   │   ├── FT-01-02_Fuel_Pump_Module_Flange.stp
│   │   └── FT-01-03_Mounting_Bracket_RH.stp
│   └── CATIA_V5_Native/
│       └── PLACEHOLDER.md
├── Drawings_2D/
│   ├── FT-01-00_Assembly_Drawing.pdf
│   ├── FT-01-01_Blow_Molded_Tank_GD&T.pdf
│   └── FT-01-03_Mounting_Bracket_Detailed.pdf
├── Documentation/
│   ├── DFMEA_Fuel_System_Assembly.md
│   └── Engineering_Change_Request_ECR_01.md
└── Media/
    ├── assembly_render_isometric.png
    ├── interference_check_clearance.png
    └── tank_wall_thickness_analysis.png
```
