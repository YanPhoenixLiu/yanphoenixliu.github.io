---
layout: archive
title: "Patents and Softwares"
permalink: /patentsandsoftwares/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="height: 1.5em;"></div>

Patents
===
**Authorized Chinese patents**
1. CN115786891B. Reproduction method of corrosion product depositions in PWR core. (2025).
2. CN115691708B. Neutron simulation method for CRUD axial linear cross-section variation of pressurized water reactor. (2023).
3. CN114199064B. Wettability temperature-sensitive adaptive heat transfer surface for enhanced boiling heat transfer and its preparation method, enhanced boiling heat transfer method. (2022).

<div style="height: 1.0em;"></div>

Softwares
===
Independently developed software:

1. **ICBA** Innovative nuclear system laboratory code for Crud Boron Analysis

<div style="padding-left: 2.0em; text-align: justify;">
ICBA is a high-fidelity simulation platform designed to investigate CRUD formation, solute transport, and their multi-physics interactions in pressurized water reactors (PWRs). Developed at Shanghai Jiao Tong University, ICBA employs a finite volume method (FVM) framework for solving coupled convection, diffusion, and reaction processes in one-dimensional and two-dimensional domains. The code offers both homogenized and feature-encrypted meshing capabilities, enabling precise geometric representation of complex flow and deposition patterns.
</div>
<div style="height: 1.0em;"></div>
<div style="padding-left: 2.0em; text-align: justify;">
ICBA incorporates a comprehensive physical and chemical database covering key PWR solutes, including boron, zinc, lithium, nickel, and iron. This database facilitates dynamic generation of thermodynamic and kinetic parameters during simulations, allowing accurate modeling of solute-specific transport behaviors and reaction pathways under various thermal-hydraulic conditions. In particular, ICBA extends beyond boron transport to analyze the thermodynamic and kinetic evolution of zinc, supporting assessments of zinc injection strategies aimed at mitigating CRUD-induced power shift (CIPS).
</div>
<div style="height: 1.0em;"></div>
<div style="padding-left: 2.0em; text-align: justify;">
To capture the influence of CRUD layers on reactor performance, ICBA features a dynamic porous media model that accounts for morphological evolution of CRUD deposits. This model considers the impact of evolving porosity and permeability on local flow resistance, heat transfer, and capillary-driven transport within the porous structure. Furthermore, the code resolves fine-scale solute distributions and evaluates their feedback on neutron physics, enabling detailed studies of localized multi-physics effects.
</div>
<div style="height: 1.0em;"></div>
<div style="padding-left: 2.0em; text-align: justify;">
ICBA supports both steady-state and transient simulations, making it suitable for investigating CRUD growth, solute precipitation and dissolution, and the associated thermal-hydraulic and neutronic responses over reactor operation cycles. Its modular architecture also allows for integration with other system-level analysis tools, providing a versatile platform for advanced CRUD behavior research and mitigation strategy development.
</div>
