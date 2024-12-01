# 2024 Roadmap

## Project Roadmap

- **Total Estimated Duration:** Duration of the whole project would be approximately 6 to 7 months.

- **Total Costs:** Requested amount in Euro for the whole project is 50,000 Euros. 


### Milestone 1 — OS abstraction layer setup

- **Estimated duration:** 2 months
- **Costs:** 20,000 Euros
- **Tasks:** This process starts with the common OS abstraction layer setup over Litex which can support CAN driver over both Linux and Zephyr.

Specfic details of features planned are listed below :


#### Cross-Platform CAN Hardware Abstraction

##### Hardware Abstraction Layer (HAL)

- Unified API for CAN controller access
- Platform-independent driver interface
- Support for CTUCAN controller in Litex
- Standardized register access methods


#### Linux to Zephyr RTOS Porting

##### Device Tree Adaptation

- Conversion of Linux DTS CAN nodes to Zephyr format
- Mapping of pin configurations and controller properties
- Clock and timing parameter translation
- Interrupt handling configuration


#### Driver Architecture

##### Separation of platform-specific and common code
###### Implementation of Zephyr driver API callbacks

- can_configure() for bitrate and timing settings
- can_send() for message transmission
- can_add_rx_filter() for message filtering
- can_remove_rx_filter() for filter management


##### Resource Management

- Memory allocation strategy adaptation
- DMA configuration differences
- Buffer management optimization
- Interrupt priority mapping


##### Power Management

- Sleep mode configuration
- Wake-up source handling
- Power state transitions
- Low-power mode optimization


##### Error Handling

- Bus-off recovery procedures
- Error status reporting
- Fault containment mechanisms
- Error counter management


...

### Milestone 2 — Standard programming constructs over CAN 

- **Estimated Duration:** 2 months
- **Costs:** 20,000 Euros
- **Tasks:** Basic CAN communication over Linux, is already supported in Litex. We would enhance it by adding a streamlined interface for sending/receiving CAN frames and a Code-based listener attachment and detachment system.

Specfic details of features planned are listed below :

#### Message Handling Framework

- Dynamic frame registration and deregistration
- Priority-based message queuing
- Automatic message scheduling for cyclic transmissions


#### Event-Driven Architecture

- Lightweight listener pattern implementation
- Multiple callback support per CAN ID
- Configurable filtering mechanisms
- Zero-copy message handling for optimal performance


#### Error Management

- Sophisticated error detection and handling
- Bus-off recovery mechanisms
- Automatic retransmission configuration
- Error statistics and logging


#### Configuration Features

- Bit timing configuration
- Acceptance filtering setup
- Transmission buffer management
- Bus load monitoring

...

### Milestone 3 — Diagnostics over CAN

- **Estimated Duration:** 2 months
- **Costs:** 10,000 Euros
- **Tasks:** The next steps on our roadmap include  Diagnostics over CAN bus supporting flashing via Unified Diagnostic Services (UDS).

#### Diagnostic Support

- Built-in support for UDS (Unified Diagnostic Services)
- ISO-TP (ISO 15765-2) protocol implementation
- Multiple addressing modes (physical, functional, extended)
- Response pending handling

...
