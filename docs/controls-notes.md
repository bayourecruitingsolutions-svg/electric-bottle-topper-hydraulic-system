# Controls & PLC Notes

## Operating Modes
1. **Manual / Jog Mode:** For maintenance and setup. Allows operator to slowly jog the spindle and gripping cylinders.
2. **Auto Mode:** Normal production cycle.
3. **Remote Mode (Future):** Read-only monitoring. Hazardous motion should be locked out from remote actuation.

## Safety Interlocks (Hardware & Software)
- **E-Stop:** Drops power to the pump motor contactor and dumps hydraulic pressure.
- **Directional Interlock:** Forward and Reverse valve solenoids must never be energized at the same time.
- **Pressure Fault:** If pressure spikes above safe limits, drop motion commands immediately.

## HMI Screen Ideas
- **Main Dashboard:** Shows current cycle status, live torque (lb-in), and pass/fail result.
- **Settings/Recipe Screen:** Operator can adjust target pressure, torque limits, and cycle timers.
- **Alarms Screen:** Displays active and historical faults (e.g., "Low Supply Pressure", "E-Stop Pressed").
- **I/O Diagnostics:** Shows raw status of all sensors and valves for easy troubleshooting.