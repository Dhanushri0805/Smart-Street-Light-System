# Smart Street Light System Using renewable energy

## Problem Statement

Conventional street lights depend on electricity supplied by the power grid, which increases energy consumption and electricity costs. Continuous use of non-renewable energy sources also contributes to environmental pollution and carbon emissions. Therefore, there is a need for an energy-efficient and sustainable street lighting system that utilizes renewable energy.

## Objective

To design and develop a Renewable Energy Based Smart Street Light System using solar energy.
To reduce dependence on conventional electricity by utilizing renewable energy.
To store solar energy in a rechargeable battery for use during low-light conditions.
To provide an energy-efficient and eco-friendly street lighting solution.
To promote the use of renewable and sustainable energy for outdoor lighting.
Short Version (for one slide)
---

## Components Required

1.5V Solar Panel: Converts sunlight into electrical energy.
3.7V Battery: Stores the generated electrical energy.
Battery Holder: Holds the battery securely.
1N4007 Diode: Prevents reverse current flow from the battery to the solar panel.
10kΩ Resistor: Provides proper biasing and circuit stability.
IRFZ44N MOSFET: Acts as an electronic switch to control power flow.
LEDs: Provide illumination with low power consumption."
---

## Algorithm

Start the system.
The 5V solar panel receives sunlight.
Convert solar energy into electrical energy.
Charge the 3.7V battery through the 1N4007 diode.
The diode prevents reverse current from the battery to the solar panel.
The battery stores the generated electrical energy.
When lighting is required (such as at night), the IRFZ44N MOSFET switches ON.
The stored energy from the battery is supplied to the LEDs.
The LEDs glow and provide street lighting.
Repeat the charging and lighting process daily.
Stop.
---

## Flowchart

          Start
            │
            ▼
   Solar Panel Receives Sunlight
            │
            ▼
 Convert Sunlight to Electricity
            │
            ▼
Charge 3.7V Battery through Diode
            │
            ▼
Battery Stores Energy
            │
            ▼
Is Lighting Required?
        /           \
      No             Yes
      │               │
      ▼               ▼
 Continue        MOSFET Switches ON
 Charging             │
                      ▼
               LEDs Turn ON
                      │
                      ▼
                    End
---

## Circuit Diagram

Upload the file named:

Circuit_Diagram.png

After uploading, add:

![Circuit Diagram](Circuit_Diagram.png)

---

## Source Code

The Renewable Energy Based Smart Street Light System is a hardware-based project that operates using electronic components. The solar panel charges the battery, and the stored energy powers the LEDs through the IRFZ44N MOSFET. Since no microcontroller (such as Arduino, ESP32, or Raspberry Pi) is used, no source code is needed.

---



## Result

The system successfully turns ON the street light during darkness and turns it OFF during daylight conditions.

---

## Conclusion

The Renewable Energy Based Smart Street Light System is an efficient and environmentally friendly solution for outdoor lighting. It utilizes solar energy to generate and store electrical power, reducing dependence on conventional electricity. The system is simple, cost-effective, and supports the use of renewable and sustainable energy. It can be effectively used for street lighting in urban as well as rural areas, helping to conserve energy and reduce environmental pollution.
    delay(100);
}
