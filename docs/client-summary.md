# Client Summary

## Project Name
Electric Bottle Topper

## Project Purpose
The Electric Bottle Topper is a concept for an electro-hydraulic machine designed to apply and rotate a bottle top onto a bottle in a controlled manner. The project combines hydraulic actuation, force and pressure monitoring, operator-adjustable controls, and safety-focused shutdown concepts.

## Concept Overview
The current concept includes a hydraulic system that drives a spindle mechanism to create rotational motion while also applying controlled force to the bottle top. A gripping and guiding head is intended to help align the top during application and reduce the chance of misalignment or breakage.

The system is envisioned as a PLC-controlled machine with a local HMI for operator interaction, process visibility, and parameter adjustment.

## Key Proposed Features
- Hydraulic pump and motor control system
- Main hydraulic cylinder mechanically linked to a spindle gear for rotational motion
- Forward and reverse electrically controlled hydraulic motion
- Three smaller cylinders arranged in a circular gripping head to help guide and grip the bottle top
- Circular beveled housing to assist in self-guiding the top onto the bottle
- Adjustable pressure reducing valves to control force and reduce the chance of bottle breakage
- Pressure monitoring using 4-20 mA transducers
- Return pressure monitoring for differential pressure awareness
- Load cell integration for force measurement
- Torque monitoring or estimation based on force and mechanical geometry
- Emergency stop and pressure fault shutdown concepts
- PLC-based control architecture
- HMI-based parameter viewing and adjustment
- Possible future support for remote monitoring features

## Primary Design Goals
- Apply bottle tops consistently and in a controlled manner
- Combine rotational and downward application motion
- Reduce the risk of glass breakage through pressure management
- Monitor process pressure and force
- Provide adjustable process parameters through an HMI
- Create a foundation for a robust controls and safety design

## Current Project Phase
The project is currently in the concept and documentation phase. The repository is being used to collect notes, define requirements, document assumptions, identify risks, and organize future engineering work.

## Major Subsystems Under Consideration
1. Hydraulic power unit
2. Spindle rotation mechanism
3. Three-cylinder gripping/guiding head
4. Pressure regulation and manifold system
5. Sensor and instrumentation package
6. PLC control system
7. Local HMI
8. Safety shutdown functions

## Instrumentation and Monitoring
The current concept includes:
- supply pressure monitoring
- return pressure monitoring
- differential pressure awareness
- load cell measurement
- torque estimation or calculation
- fault and alarm indication
- operator-adjustable settings through HMI

## Safety Considerations
The current concept includes planning for:
- emergency stop functionality
- high-pressure shutdown behavior
- low-pressure shutdown behavior
- directional control interlocking
- pressure limiting using mechanical hydraulic components
- controlled fault response and reset concepts

A final implementation would require detailed engineering review and safety validation.

## Future Possibilities
The client also expressed interest in future expansions such as:
- remote monitoring
- camera viewing
- server-connected data visibility
- broader operating visibility for larger-scale use

These items are currently being treated as future-phase features rather than part of the initial base concept.

## Current Documentation Focus
The project documentation currently covers:
- overview
- client notes
- requirements
- system architecture
- safety notes
- hydraulic notes
- controls notes
- instrumentation notes
- mechanical notes
- open questions
- risks
- assumptions
- future features

## Next Steps
- continue refining requirements
- confirm bottle and cap types
- define process targets such as force, torque, and cycle time
- identify preferred control hardware platforms
- develop preliminary schematics and I/O concepts
- move from concept documentation into engineering definition