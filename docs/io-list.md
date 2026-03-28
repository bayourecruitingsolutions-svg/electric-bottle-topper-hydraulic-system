# I/O List

## Purpose
This document is used to track possible PLC inputs and outputs for the Electric Bottle Topper project. This is an early draft and will be refined later.

## Digital Inputs
- Emergency stop circuit healthy
- Start pushbutton
- Stop pushbutton
- Reset pushbutton
- Auto mode selector
- Manual mode selector
- High pressure fault switch
- Low pressure fault switch
- Guard/door interlock status
- Pump motor overload status

## Analog Inputs
- Supply pressure transducer (4-20 mA)
- Return pressure transducer (4-20 mA)
- Load cell signal
- Optional spindle position feedback
- Optional cylinder position feedback

## Digital Outputs
- Pump motor contactor
- Forward valve solenoid
- Reverse valve solenoid
- Grip cylinder solenoid A
- Grip cylinder solenoid B
- Grip cylinder solenoid C
- Alarm horn
- Stack light / indicator light

## HMI / Internal Tags
- Calculated differential pressure
- Calculated torque
- Active fault code
- Current machine state
- Recipe number
- Operator-entered setpoints

## Notes
- Final I/O count depends on selected PLC and machine design.
- Safety I/O may require separate safety relay or safety PLC hardware.