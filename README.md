**LDR-BASED HOME SECURITY LIGHTING SYSTEM**

# **Aim**

To design and construct a light-sensing home security system using a Light Dependent Resistor (LDR), which automatically switches on an LED (representing a security/porch light) when the surrounding light level drops, simulating an automatic security light that activates after dark.

# **Components Required**

| S.No | Component | Qty | Specification |
| :---- | :---- | :---- | :---- |
| 1 | LDR (Light Dependent Resistor) | 1 | Standard 5mm LDR |
| 2 | Sensor / driver module | 1 | Onboard comparator with threshold potentiometer |
| 3 | LED (indicator/security light) | 1 | Green, 5mm |
| 4 | Breadboard | 1 | Standard solderless breadboard |
| 5 | Battery | 1 | 9V / battery pack |
| 6 | Jumper wires | Several | Male-male |
| 7 | Model house (demo enclosure) | 1 | Cardboard and chart paper |

# **Procedure**

# 1\.   Insert the 1 kΩ resistor into the breadboard as the current-limiting element.

# 2\.   Connect the potentiometer in series with the resistor.

# 3\.   Insert the LED with correct polarity — anode (long leg) toward the resistor, cathode (short leg) toward the negative rail.

# 4\.   Connect the 9V battery's positive terminal to the potentiometer and negative terminal to the LED's cathode side.

# 5\.   Verify all connections against the circuit diagram.

# 6\.   Connect the battery and observe the LED.

# 7\.   Rotate the potentiometer knob and note the change in brightness.

# **Working:**

The circuit operates on Ohm's Law (I \= V/R). The battery drives current through the potentiometer, resistor, and LED in series. The fixed 1 kΩ resistor always limits current to protect the LED. The potentiometer adds a variable 0–10 kΩ in series — as its resistance increases, total circuit resistance rises and current (hence brightness) falls; as it decreases, current rises and the LED brightens. This gives manual, continuous control of LED brightness without any digital circuitry.

# **Observation**

# •     LED lights up immediately on connecting the battery, confirming correct polarity.

# •     Brightness increases as the potentiometer resistance is decreased (current ≈ 5.8 mA at 0 Ω).

# •     Brightness decreases as resistance is increased (current ≈ 0.53 mA at 10 kΩ).

# •     LED brightness varies smoothly and reversibly across the pot's full range.

# 

# 

