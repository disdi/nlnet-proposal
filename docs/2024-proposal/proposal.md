# Librecar Control 2024 

## Project Overview :page_facing_up:

Nlnet funded development of Librecar Control in 2023 round.

* [[Archeivements]] - details of outcome project archeived in 2023.

### Overview

LibreCar Control aims to democratise knowledge to control an an automotive vehicle. To make this possible, following measures were taken as pert of this project:

- Integrate opensource CAN-Bus (Controller Area Network) IP in FPGA.
- Test opensource CAN-Bus with real industrial and automotive devices.
- Provide documentation how to integrate it in new FPGA based products.

### Project Details

The next natural step is to make CAN-Bus IP ready for ASIC integration. All opensource tools are intended to be used to archieve this goal. 

The recent introduction of open source PDKs like 130nm BiCMOS process from IHP, the SOI-CMOS PDK from Minimal Fab, 130nm mixed-signal CMOS SKY130 from Skywater and GlobalFoundries' 180nm has opened several opportunities for circuit designers. The conventional PDKs from TSMC, UMC etc. are quite expensive and involve strict licensing process, making them difficult to access for all. OpenPDK has removed the roadblocks for ASIC designing, providing access to make custom chips for free initially for faster development cycle or at very low-cost eventually.

This project aims to archeive the functionality of fully open source CAN-Bus digital IP to be built into an ASIC using Skywater 130nm Open PDK which is already synthesized and proven in FPGA as part of NLNET 2023 funding.

#### 2024 Objectives

* First open source CAN-Bus IP with 1 Mb/s capabilities.
* Use, for the first time, an open source PDK, skywater 130 nm, for the realization of CAN Controller.
* To illustrate the importance of open source hardware and synthesizable design techniques, motivating their adoption in circuit design.

### Target Consumers

The project attempts to help solve the need for open source Hardware.

Open source hardware refers to a hardware, an ASIC, or even, a circuit that has provided access to its entire design, specifications, and documentations, which can be used, altered, or distributed by anyone. 

Like source code in case of open source software, all the schematics, logic designs, layout-data, and netlists need to be made available for revisions by anyone, who has access to the tools to read, manipulate and update the existing design with new features, usually aiming for better performance and share the improved design back to the community for further enhancements/evaluations.

This effort will help the opensource community in folowwing ways:

- Access to an opensource CAN-Bus IP in ans ASIC and its entire design, specifications, and documentations. 
- Knowledge how to integrate any FPGA based design to an opensource ASIC with access to all logic designs, layout-data, and netlists.
- Access to Schematic and Board Design for communicating with autmotive and industrial deveices.
- Enables software developers to effectively optimize their source codes based on fully accessible hardware details of CAN-Bus IP.


## Development Roadmap :nut_and_bolt:

Below we provide an **example roadmap**. 

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 12 months)

- **Total Costs:** Requested amount in Euro for the whole project is 50,000 Euros. 

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language, and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


## Future Plans

Please include here

- how you intend to finance the project's long-term maintenance and development,
- how you intend to use, enhance, and promote your project in the short term, and

