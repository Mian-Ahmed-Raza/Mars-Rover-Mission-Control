# Mars Rover Mission Control

## Software Verification and Validation Lab

This repository contains the Software Verification and Validation (SVV) lab work for the **Mars Rover Mission Control** system.

The system is responsible for remotely controlling Mars rovers and receiving their location and health information through a communication link.

## Mission Objectives

The system must:

* Send movement commands to rovers.
* Receive rover location and health data.
* Detect communication failures.
* Prevent unauthorized commands.
* Place the rover into Safe Mode when a critical fault is detected.
* Record mission events for later investigation.
* Continue operating despite temporary communication interruptions.
* Support communication with multiple rovers.

## Repository Structure

```text
Mars-Rover-Mission-Control/
│
├── README.md
│
├── requirements/
│   ├── functional-requirements.md
│   └── non-functional-requirements.md
│
└── change-requests/
    ├── CR-01-Emergency-Safety.md
    ├── CR-02-Mission-Expansion.md
    └── CR-03-Security-Upgrade.md
```

## Lab Tasks

### Mission 1 — Analyze the Engineering Note

The engineering notes were analyzed to identify:

* Functional Requirements
* Non-Functional Requirements

At least six functional requirements and four non-functional requirements were identified.

### Mission 2 — Analyze Change Requests

Three requirement changes were analyzed:

* **CR-01 — Emergency Safety**
* **CR-02 — Mission Expansion**
* **CR-03 — Security Upgrade**

The changes were analyzed from a Software Verification and Validation perspective, focusing on clarity, measurability, testability, security, safety, and scalability.

## Key SVV Concepts

The change requests demonstrate the importance of making requirements:

* Specific
* Clear
* Measurable
* Testable
* Less ambiguous

## Conclusion

This repository documents the requirements analysis and change-request analysis for the Mars Rover Mission Control system as part of the Software Verification and Validation laboratory work.
