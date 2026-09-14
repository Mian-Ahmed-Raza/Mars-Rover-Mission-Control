# Non-Functional Requirements

## Mission: Analyze the Engineering Note

Non-functional requirements describe the quality attributes, constraints, security requirements, performance requirements, and operational characteristics of the system.

| ID     | Non-Functional Requirement                                                                             |
| ------ | ------------------------------------------------------------------------------------------------------ |
| NFR-01 | The system shall continue operating despite temporary communication interruptions.                     |
| NFR-02 | Only authenticated Mission Control operators shall be permitted to issue rover commands.               |
| NFR-03 | Command processing should normally complete within 5 seconds after a command is received by the rover. |
| NFR-04 | The system should support communication with multiple rovers simultaneously.                           |

## Requirement Analysis

### NFR-01 — Communication Reliability

The system should remain operational even when temporary communication interruptions occur.

This requirement focuses on the reliability and availability of the system.

### NFR-02 — Operator Authentication

Only authenticated Mission Control operators should be able to issue commands to the rover.

This requirement focuses on system security.

### NFR-03 — Command Processing Performance

Command processing should normally be completed within 5 seconds after the rover receives a command.

This requirement defines a performance expectation.

### NFR-04 — Multiple Rover Support

The system should be capable of communicating with multiple rovers simultaneously.

This requirement defines a scalability and operational capability.

## Summary

These requirements define important quality and operational characteristics of the Mars Rover Mission Control system, including reliability, security, performance, and scalability.
