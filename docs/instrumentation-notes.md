# Instrumentation & Sensor Notes

## 4-20 mA Pressure Transducers
- **Supply Pressure:** Measures pressure entering the directional valve.
- **Return Pressure:** Measures pressure leaving the cylinder.
- **Differential Pressure Calculation:** 
  `Diff_Press = Supply_Press - Return_Press`
- *Note:* The PLC will need to scale the raw 4-20 mA signal into actual PSI or Bar.

## Load Cell & Torque Calculation
- The load cell measures linear force (lbs or Newtons).
- Torque must be derived based on the mechanical linkage to the spindle.
- **Basic Formula:** `Torque = Force × Radius`
- If gearing is involved, the formula must account for the gear ratio:
  `Output_Torque = Force × Radius × Gear_Ratio × Efficiency`

## Pressure Reducing Valves (PRVs)
- These are mechanical valves, but their setting is critical to the sensors.
- The PRV physically limits the maximum hydraulic pressure to ensure the gripping head does not crush the glass bottle. 
- The electronic pressure transducers will monitor to confirm the PRV is working correctly.