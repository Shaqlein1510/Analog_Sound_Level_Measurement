# Analog Sound Level Measurement Using Electret Microphone and 4–20 mA Industrial Standard

## Project Overview
This project focuses on developing an analog sound level measurement system using an electret microphone and analog signal-conditioning circuits. The system processes the detected sound signal and converts it into a 4–20 mA industrial current-loop output.

The project demonstrates the application of analog electronics and industrial instrumentation for sound monitoring.

## Objectives
- Detect sound using an electret microphone.
- Amplify and filter the microphone signal.
- Convert the AC signal into a DC level using rectification and averaging.
- Convert the processed signal into a 4–20 mA current-loop output.
- Simulate the circuit using LTspice.
- Assemble and test the hardware prototype.

## Components Used
- Electret Condenser Microphone
- AD620 Instrumentation Amplifier
- TL084 Operational Amplifier
- OP07 Precision Operational Amplifier
- 2N3904 NPN Transistor
- 1N4148 Signal Diodes
- Resistors and Capacitors
- 100 Ω Current-Sense Resistor
- LM7812 and LM7912 Voltage Regulators
- Breadboard and Connecting Wires
- DC Power Supplies

## Working Principle
1. Sound Detection: The electret microphone converts sound pressure into a small electrical signal.
2. Signal Amplification: The AD620 amplifies the microphone signal.
3. Filtering: Sallen-Key filters reduce unwanted low- and high-frequency components.
4. Rectification: A precision rectifier converts the AC signal into a unidirectional signal.
5. Averaging: An RC network smooths the rectified signal into a DC voltage.
6. Signal Conditioning: The OP07 circuit adjusts the signal gain and offset.
7. Current Conversion: A voltage-to-current converter generates the 4–20 mA industrial output.

## Simulation and Hardware
- Circuit simulation using LTspice.
- Hardware implementation using a breadboard.
- Circuit output observation using digital multimeters.

## Applications
- Industrial noise monitoring.
- Machinery condition monitoring.
- Sound monitoring near pumps, compressors, and fans.
- Detection of abnormal acoustic events.
- Potential integration with PLC and SCADA systems.

## Limitations
- Calibration against a reference sound source is required before interpreting the output in decibels (dB).
- The circuit output is approximately amplitude-proportional rather than linear in dB.
- Accuracy may be affected by amplifier offsets, noise, and microphone sensitivity.
- The system is not a standards-compliant sound-level meter.
- Further testing and calibration are required to validate the intended 60–90 dB SPL measurement range.

## Future Improvements
- Improve calibration and measurement accuracy.
- Add logarithmic conversion for decibel measurement.
- Implement A-weighting and defined time response.
- Design a printed circuit board (PCB).
- Add a local display for sound-level indication.
- Improve industrial interfacing and isolation.

## Project Details
- College: L. D. College of Engineering, Ahmedabad
- University: Gujarat Technological University (GTU)
- Subject: Industrial Measurement II
- Subject Code: BE05000041

## Project Team
- Mansuri Mohammedshaqlein
- Aaditya Choudhary
- Ansari Juned
- Ansari Nizamuddin
- Ladva Nikhil

## Conclusion
This academic project demonstrates analog signal conditioning, sound measurement principles, and the application of the industrial 4–20 mA current-loop standard.
