# Roadmap

Below we provide the **project roadmap**. 

The workflow followed to develop the SoC template with CAN IP is divided into 3 steps.
* The RTL design flow
* The OpenLANE flow 
* The Caravel integration

The whole process is illustrated in below workflow:

![macro-workflow](./../attachment/macro-workflow.png)

...

## Milestone 1 — RTL design flow

- **Estimated duration:** 4 months
- **Costs:** 5,000 Euros
- **Tasks:** This process starts with the common RTL design flow in which each module along with its testbench is developed with HDL language. Then each module is tested, synthesized, and wrapped in a top module, which is also tested. Yosys can be used to test and synthesize each module.

...

## Milestone 2 — OpenLANE flow 

- **Estimated Duration:** 4 months
- **Costs:** 15,000 Euros
- **Tasks:** After the RTL design flow, the Verilog files will be loaded to OpenLANE with the proposal to make the flow RTL to GDSII with the best layout optimization, additionally, OpenLANE requires the Process Design Kit (PDK) technology, Skywater130in this case, then OpenLANE generates the GDSII files of our module.

...

## Milestone 3 — Caravel integration

- **Estimated Duration:** 4 months
- **Costs:** 20,000 Euros
- **Tasks:** Finally, the integration will be done through Caravel, OpenLANE will be used to combine caravel with the Top Module CAN gds file,
Top Module CAN refers to the module that combines and routes CAN IP.

...

## Milestone 4 — Chip fabrication

- **Estimated Duration:** 4 months
- **Costs:** 10,000 Euros
- **Tasks:** Final step is to get chip fabricated and delivered by companies like Efabless.

...