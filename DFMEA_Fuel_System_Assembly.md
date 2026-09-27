# Design Failure Mode and Effects Analysis (DFMEA)
**System:** Powertrain Integration - Fuel Delivery Subsystem  
**Design Lead:** Fuel CAD Portfolio Project  

| Part / Function | Potential Failure Mode | Potential Effect of Failure | S (Sev) | Potential Cause | Prevention Controls | D (Det) | RPN | Recommended Actions |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **FT-01-01 Tank Shell** / Containment of liquid fuel | Wall thinning at deep-draw pinch-off zones during blow molding. | Structural rupture during rear crash barrier testing; rapid fuel spill risk. | **9** | Suboptimal parison thickness programming distribution. | Use FEA blow molding simulation to optimize parison programming profile. | **4** | **36** | Mandate ultrasonic wall thickness checks on pilot production tooling runs. |
| **FT-01-02 Flange Interface** / Sealing component | Fuel vapor leak across module mating interface. | Vehicle failing EPA evaporative emissions compliance limits; fuel smell. | **7** | Dimensional distortion / warp of injection molded POM surface profile. | Finite element cooling analysis; Add structural reinforcement ribbing to flange. | **3** | **21** | Apply Profile of a Surface GD&T tolerance limit of 0.1mm relative to primary datum. |
| **FT-01-03 Mounting Bracket** / Structural securing | Fatiguing/cracking at structural bend radii under dynamic vehicle loads. | Fuel tank shifts/drops from chassis mount, leading to fuel line tension strain failures. | **8** | Bend radius chosen is tighter than recommended minimum for sheet steel thickness. | Enforce minimum inner bend radius rules ($R \ge 2\times t$) during sheet metal modeling stage. | **3** | **24** | Run dynamic PSD vibration fatigue analysis on structural mount assemblies. |
