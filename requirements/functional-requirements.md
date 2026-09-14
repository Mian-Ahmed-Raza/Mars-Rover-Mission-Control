# Functional Requirements

## Mission: Analyze the Engineering Note

Functional requirements describe the functions and behaviors that the Mars Rover Mission Control system must perform.

| ID    | Functional Requirement                                                                             |
| ----- | -------------------------------------------------------------------------------------------------- |
| FR-01 | The rover shall receive commands from Mission Control and execute valid commands.                  |
| FR-02 | The rover shall report its current position, battery level, temperature, and communication status. |
| FR-03 | The system shall reject invalid or unauthorized commands.                                          |
| FR-04 | If the rover detects a critical battery or thermal condition, it shall enter Safe Mode.            |
| FR-05 | Mission Control shall receive the command execution status.                                        |
| FR-06 | All commands and critical rover events shall be recorded with a timestamp and operator ID.         |

## Requirement Analysis

### FR-01 — Command Execution

The rover must receive commands from Mission Control and execute them when the commands are valid.

### FR-02 — Rover Status Reporting

The rover must report important information including its position, battery level, temperature, and communication status.

### FR-03 — Command Rejection

The system must reject commands that are invalid or issued by unauthorized users.

### FR-04 — Safe Mode

The rover must enter Safe Mode when a critical battery or thermal condition is detected.

### FR-05 — Command Execution Status

Mission Control must receive information about whether a command was successfully executed.

### FR-06 — Event Recording

The system must record all commands and critical rover events together with the timestamp and operator ID.

## Summary

These requirements define the main functions that the Mars Rover Mission Control system must perform.
