# 5V DC Power Supply Circuit Design and PCB Layout Using Proteus 9

## 📌 Project Overview

This project focuses on designing a 5V DC power supply circuit and its PCB layout using Proteus 9. The circuit uses a 7805 voltage regulator to provide a regulated 5V DC output from a suitable DC input voltage.

The design includes rectifier diodes, filtering and decoupling capacitors, input and output connectors, and a buzzer as an output indicator. The PCB layout was created to understand component placement and PCB routing.

## 🎯 Objectives

- Design a 5V regulated DC power supply circuit.
- Understand voltage regulation using the 7805 IC.
- Learn about rectifier diodes and capacitor filtering.
- Design a PCB layout using Proteus 9.
- Practice component placement and PCB track routing.
- Explore using a buzzer as an output indicator.

## 🛠️ Components Used

| S.No. | Component | Specification | Purpose |
|---|---|---|---|
| 1 | Voltage Regulator | 7805 | Provides regulated 5V DC output |
| 2 | Rectifier Diodes | 1N4001 × 4 | Rectification |
| 3 | Electrolytic Capacitor | 470 µF | Power supply filtering |
| 4 | Ceramic Capacitor | 100 nF | Decoupling and noise reduction |
| 5 | Buzzer | 5V DC (as intended) | Audible indication |
| 6 | Input Connector | J1 | Power input connection |
| 7 | Output Connector | J2 | Power output connection |
| 8 | PCB Layout | Designed in Proteus 9 | Component placement and routing |

## 💻 Software Used

- Proteus 9
- Proteus ISIS – Circuit design
- Proteus ARES – PCB layout design

## ⚙️ Working Principle

1. **Input Supply:** The circuit receives power through the input connector.
2. **Rectification:** Four 1N4001 diodes are arranged as a bridge rectifier to convert AC input into pulsating DC, if an AC input is used.
3. **Filtering:** The 470 µF capacitor helps smooth the rectified DC voltage.
4. **Voltage Regulation:** The 7805 voltage regulator provides a regulated 5V DC output when supplied with a suitable input voltage.
5. **Decoupling:** The 100 nF capacitor helps reduce high-frequency noise and improve supply stability.
6. **Output Connection:** The regulated output is available through the output connector.
7. **Buzzer:** A buzzer is included as an indicator. Its operation depends on the actual circuit connections and the buzzer's voltage and current ratings.

## 🖥️ Circuit Design

The circuit was designed in Proteus 9 using the selected electronic components. The schematic represents the connections between the rectifier, capacitors, voltage regulator, buzzer, and connectors.

## 🔌 PCB Layout Design

The PCB layout was developed using Proteus ARES.

PCB design activities included:

- Assigning suitable PCB footprints to components.
- Arranging components on the PCB.
- Planning electrical connections.
- Routing PCB tracks.
- Reviewing component placement and board layout.

## 📚 Key Learnings

- Understanding regulated DC power supplies.
- Learning the function of the 7805 voltage regulator.
- Understanding rectification and capacitor filtering.
- Working with electronic components in Proteus.
- Assigning PCB footprints to schematic components.
- Creating a PCB layout and routing tracks.
- Understanding the relationship between a schematic and a physical PCB.

## 🚀 Applications

A regulated 5V power supply can be used in suitable low-voltage electronic circuits, including:

- Microcontroller projects.
- Basic embedded systems.
- Electronic testing and experimentation.
- Low-power digital circuits.
- Educational electronics projects.

The actual applications depend on the power supply's current capacity, input voltage, thermal performance, and protection requirements.

## 🔮 Future Improvements

- Verify the circuit through simulation and hardware testing.
- Measure the input and regulated output voltages.
- Check the output ripple and voltage stability.
- Add suitable input and output protection.
- Verify PCB track widths and component clearances.
- Optimize component placement and PCB routing.
- Test the buzzer's operation under the intended supply conditions.

## 👨‍💻 Project Information

**Project Title:** 5V DC Power Supply Circuit Design and PCB Layout Using Proteus 9

**Software:** Proteus 9

**Project Area:** Electronics, Circuit Design, and PCB Development

**Project Type:** Circuit Simulation and PCB Layout Design

## 📌 Note

This repository documents the circuit design and PCB layout. Successful simulation, hardware operation, and PCB fabrication should be verified separately before the design is used in a real application.

Ensure that the input supply, diode arrangement, capacitor polarity, regulator ratings, buzzer specifications, and PCB connections are correct before powering the circuit.

## 📄 License

This project is shared for educational and learning purposes. Add a suitable open-source license if you want others to reuse, modify, or distribute the project.

---

⭐ If you find this project useful, consider starring the repository!
