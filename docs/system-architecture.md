# System Architecture

## Summary
The Electric Bottle Topper is currently envisioned as an electro-hydraulic system made up of motion, sensing, control, and safety subsystems.

## Major Subsystems

### 1. Hydraulic Power Unit
Provides hydraulic pressure for the machine.
Potential elements:
- hydraulic pump
- motor
- reservoir
- relief protection
- manifold

### 2. Spindle Rotation Mechanism
A primary hydraulic cylinder drives a spindle gear to create rotational motion used during the bottle topping process.

### 3. Gripping / Guiding Head
A gripping head at the spindle end uses three smaller cylinders in a circular arrangement to grip and guide the bottle top as it is rotated and pressed.

### 4. Pressure Regulation
Pressure reducing valves are used to control gripping and pressing force to reduce risk of glass breakage.

### 5. Sensing
The system may include:
- supply pressure transducer
- return pressure transducer
- high-pressure switch or limit
- low-pressure switch or limit
- load cell

### 6. Control System
A PLC is expected to serve as the main controller for:
- motor control
- valve outputs
- sensor monitoring
- alarms
- process logic

### 7. Operator Interface
A local HMI is expected to provide:
- system status
- pressure readings
- load readings
- torque display
- alarm display
- parameter adjustment

### 8. Future Connectivity
Possible future features may include:
- data logging
- status dashboards
- camera viewing
- remote monitoring

Any future connectivity should remain secondary to local machine control and safety design.

## Current State
This architecture is conceptual and subject to change as the project is defined further.
