# DC_5V_charger
# 5V DC Charger Project

This repository contains the design and implementation details of a 5V DC charger using basic electronic components. The project involves converting an AC signal to a regulated 5V DC output suitable for charging or powering low-voltage devices.

## Components Used

1. **Transformer (1 unit)**  
   Converts the high-voltage AC (e.g., 220V) to a lower AC voltage (e.g., 12V).

2. **Full-Wave Bridge Rectifier**  
   Converts the AC signal to pulsating DC.

3. **Capacitor**  
   Smoothens the DC signal by reducing ripples.

4. **LED**  
   Indicates power status.

5. **220kΩ Resistor (connected to the LED)**  
   Limits current through the LED to protect it.

6. **Inductor**  
   Reduces high-frequency noise in the DC signal.

7. **Buck Module**  
   Steps down the voltage from 12V to 5V DC for final output.

## Working Principle

1. **AC to DC Conversion**  
   - The transformer reduces the input AC voltage to a lower AC voltage (e.g., 12V).
   - The full-wave bridge rectifier converts the AC voltage to a pulsating DC signal.

2. **DC Smoothing**  
   - A capacitor is used to filter out the ripples and smoothen the DC signal.
   - The inductor further eliminates high-frequency noise in the DC output.

3. **Voltage Regulation**  
   - The buck module steps down the DC voltage from 12V to a stable 5V output suitable for powering USB devices or other low-voltage circuits.

4. **Status Indication**  
   - An LED connected via a 220kΩ resistor indicates the charger is powered and operational.


## Circuit Diagram

Include a simple diagram here (or upload it as an image file in your repository and link to it).

---

## How to Use

1. Connect the AC input to the transformer.  
2. Ensure the circuit is properly soldered and insulated to avoid short circuits.  
3. Plug in your USB cable or device to the 5V output of the buck module.  
4. Check the LED indicator to ensure the circuit is operational.

---

## Notes

- **Safety Precautions**: Ensure proper insulation and handling when working with high-voltage AC inputs.  
- **Component Ratings**: Ensure that the components used can handle the input voltage and current requirements.  
- **Testing**: Use a multimeter to verify the 5V output before connecting any sensitive devices.

---

## Future Improvements

- Adding overvoltage and overcurrent protection.  
- Implementing a heat sink for the buck module for better thermal management.  
- Adding USB ports for convenient charging.

---

## Contributing

Feel free to fork this repository and suggest improvements via pull requests.

---

