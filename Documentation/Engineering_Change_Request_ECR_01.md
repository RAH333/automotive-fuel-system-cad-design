# Engineering Change Request (ECR)
**ECR Number:** ECR-2026-004  
**Status:** Under Evaluation  
**Date:** September 27, 2026  
**Originator:** Fuel CAD Design Engineer  

## 1. Change Description
Modification of the right-hand fuel tank mounting bracket (**FT-01-03**) base clearance layout. 

## 2. Reason for Change
Clash analysis during vehicle digital layout review caught a **0.8mm clearance interference** between the edge of bracket FT-01-03 and the newly routed rear chassis brake lines during high-articulation suspension travel simulation.

## 3. Proposed Modifications (CAD / Lifecycle Execution)
*   **Part Revision update:** Advance part index from Rev `AA` to Rev `AB`.
*   **3D Geometric update:** Trim the outer corner flange geometry back by **5.0mm** utilizing the GSD split feature tool path.
*   **2D Print update:** Alter drawing sheet 1 zone C3 to reflect updated profile dimensioning limits and adjust localized profile control indicators.
*   **BOM Impact:** None. Part total mass drops by approximately **4.2 grams**.

## 4. Impact Assessment
*   **DFMEA Verification:** Structural stress limits around mounting tabs remain safe within safety margins (SF = 1.6).
*   **Tooling Impact:** Modification requires a simple machining rework of the stamping die block inserts (Steel safe condition).
*   
