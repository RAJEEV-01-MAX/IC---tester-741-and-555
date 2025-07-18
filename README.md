# IC Tester for IC-741 & IC-555

An Arduino Uno–based tester designed to verify the functionality of two commonly used ICs: the **IC 741 operational amplifier** and the **IC 555 timer**.

## 🎯 Objective

To test IC-741 in inverting & non-inverting modes, and IC-555 in astable mode, using programmed signal inputs and output verification via Arduino.

## 🔧 Components

- **Arduino Uno**: Controls test logic and reads outputs
- **IC 741**: Tested for amplification behavior
- **IC 555**: Tested for square wave generation in astable mode
- **Resistors & Capacitors**: Define gain and timing parameters
- **Digital Multimeter** *(optional)*: Manual verification
- **Breadboard & Jumper Wires**: Circuit assembly
- **LEDs (optional)**: Visual pass/fail indication
- **Power Supply**: Powers the entire circuit

## ⚙️ How It Works

### IC 741 Test
- **Inverting Mode**: Input via inverting pin; output should be amplified and inverted.
- **Non-Inverting Mode**: Input via non-inverting pin; output should be amplified and non-inverted.
- **Output is read by Arduino** and compared with expected values.

### IC 555 Test
- **Astable Mode**: External RC network sets square wave frequency (~1kHz).
- **Arduino reads the waveform** and checks timing intervals.
- **Success is indicated via LED** if frequency and duty cycle are valid.

## 👥 Contributors

- Yashasvi Kaushik (2023ELE1013)  
- Rajeev Aswal (2023ELE10XX)  
- Disha Thakur (2023ELE1015)  
Project Guide: Mrs. Nirupama Kapoor
