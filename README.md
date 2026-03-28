# Electric Bottle Topper

Electric Bottle Topper is a concept repository for an electro-hydraulic bottle topping machine. The project is intended to capture design notes, requirements, architecture ideas, safety considerations, and future control concepts for a machine that presses and rotates bottle tops using hydraulic actuation and sensor feedback.

## Current Purpose
This repository is currently being used to:
- collect client notes
- organize project requirements
- document system ideas
- capture safety and controls considerations
- prepare for later design and build phases

## Concept Summary
The current concept includes:
- a hydraulic pump and motor control system
- high-pressure and low-pressure shutdown logic
- forward/reverse electric control of a hydraulic cylinder
- a return pressure sensor for differential pressure monitoring
- an emergency stop circuit
- a load cell for force measurement
- torque estimation based on load and spindle geometry
- a spindle gear driven by a hydraulic cylinder to create rotation
- a three-cylinder gripping assembly to guide and grip the bottle top
- adjustable pressure reducing valves to avoid damaging the bottle or cap
- PLC-based monitoring and control
- HMI-based parameter viewing and adjustment
- possible future remote monitoring features

## Repository Status<span class="ml-2" /><span class="inline-block w-3 h-3 rounded-full bg-neutral-a12 align-middle mb-[0.1rem]" />
For a high-level client-facing summary, see `docs/client-summary.md`.
