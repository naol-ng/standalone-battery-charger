\# Standalone Configurable Li-Po / Li-Ion Battery Charger



A compact, standalone lithium-polymer (Li-Po) and lithium-ion (Li-Ion) battery charger circuit engineered with configurable charging current modes ($100\\text{ mA}$, $300\\text{ mA}$, and $500\\text{ mA}$) and integrated PMOS reverse polarity protection.



\---



\## Technical Specifications



| Parameter | Specification |

| :--- | :--- |

| \*\*Controller IC\*\* | BQ2409x Series Linear Charger |

| \*\*Input Voltage Range\*\* | $4.35\\text{ V}$ – $6.4\\text{ V}$ (USB / External DC) |

| \*\*Supported Chemistries\*\* | Single-Cell Li-Po / Li-Ion ($4.2\\text{ V}$ nominal termination) |

| \*\*Configurable Charge Currents\*\* | $100\\text{ mA}$, $300\\text{ mA}$, $500\\text{ mA}$ (selectable via jumper/resistor network) |

| \*\*Protection Circuitry\*\* | AO3401A P-Channel MOSFET Reverse Polarity Protection |

| \*\*Status Indicators\*\* | Dual-LED indication (Charging / Charge Complete) |



\---



\## Design Overview \& Features



\* \*\*Configurable Fast-Charge:\*\* $I\_{CHG}$ selection via precision programming resistors tailored to standard small-capacity single-cell batteries.

\* \*\*Integrated Hardware Protection:\*\* Reverse battery insertion protection prevents circuit damage without significant voltage drop.

\* \*\*Production-Ready Deliverables:\*\* Includes `.OutJob` configuration for single-click generation of fabrication (Gerbers/NC Drill) and assembly documentation.



\---



\## Project Repository Structure



```text

├── Standalone Battery Charger.PrjPcb  # Altium Project File

├── sbattery.SchDoc                   # Schematic Sheet

├── sbattery.PcbDoc                   # PCB Layout \& Stackup

├── sbattery.SchLib                   # Custom Schematic Library

├── sbattery.PcbLib                   # Custom Footprint Library

├── Manufacturing.OutJob              # Automated Output Job Setup

└── README.md                         # Documentation
tool Altium designer 



