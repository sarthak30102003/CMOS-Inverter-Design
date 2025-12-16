# CMOS Inverter Design — Full Custom IC Design Flow

## Overview

This repository documents the complete **full custom CMOS inverter design flow** implemented using **Cadence Virtuoso** with **GPDK 90nm technology**. The work focuses on schematic-to-layout consistency, physical verification, and post-layout performance validation.

## Design Summary

* CMOS inverter schematic designed with appropriately sized NMOS and PMOS devices
* Custom symbol created for modular and hierarchical usage
* Testbench configured with pulse input and DC biasing
* DC and transient simulations performed to verify VTC and switching behavior
* Full custom layout implemented following GPDK 90nm design rules
* Layout verified to be **DRC-clean** and **LVS-matched**
* Post-layout RC extraction performed and simulated
* Observed approximately **4–5 ps** additional propagation delay due to parasitic effects

## Tools and Technology

* Cadence Virtuoso
* Spectre Simulator
* GPDK 90nm PDK

## Key Outcomes

* Functional equivalence between schematic and post-layout views
* Validation of layout-induced parasitic impact on delay
* Improved understanding of full custom IC design methodology

## Future Scope

* Design and layout of complex logic gates
* Performance optimization through sizing and layout refinement
