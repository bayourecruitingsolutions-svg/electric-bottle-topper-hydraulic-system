# Requirements

## Purpose
Document current known requirements for the Electric Bottle Topper project.

## Functional Requirements
- The system shall press a bottle top onto a bottle.
- The system shall rotate the bottle top during the pressing process.
- The system shall use a hydraulic cylinder linked to a spindle gear to create rotational motion.
- The system shall include a gripping mechanism at the spindle end.
- The gripping mechanism shall use three smaller cylinders arranged in a circular pattern.
- The gripping mechanism shall guide the bottle top into alignment as it rotates.
- The system shall include adjustable pressure reducing valves to limit applied force.
- The system shall monitor process pressure and load.
- The system shall estimate or display torque based on available measurements.
- The system shall use a PLC for control and monitoring.
- The system shall include an HMI for viewing status and adjusting approved parameters.

## Safety Requirements
- The system shall include an emergency stop circuit.
- The system shall stop or inhibit hazardous motion on E-stop.
- The system shall include high-pressure fault handling.
- The system shall include low-pressure fault handling.
- The system shall prevent conflicting directional commands.
- The system shall be designed to reduce the chance of bottle breakage.
- Safety functions shall not rely only on software.

## Instrumentation Requirements
- The system shall include pressure sensing using 4-20 mA transducers.
- The system shall include return pressure sensing.
- The system shall support differential pressure monitoring.
- The system shall include a load cell with suitable signal conditioning.
- The PLC shall scale and display sensor values in engineering units.

## Control Requirements
- The system shall support forward/reverse control of the hydraulic cylinder.
- The system shall support pump motor control.
- The system shall detect and indicate fault conditions.
- The HMI shall allow parameter viewing and limited adjustment.
- Parameter limits shall be bounded by engineering-defined ranges.

## Documentation Requirements
- Capture client notes
- capture open questions
- define system architecture
- define I/O list
- define safety notes
- define control logic later

## Open Questions
- What bottle and cap sizes are required?
- What torque range is required?
- What force limits are acceptable?
- What pressure ranges are available?
- What cycle speed is needed?
- What PLC and HMI platforms are preferred?
