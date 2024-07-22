# PLL-Design
PLL stands for Phase-Locked Loop, an electronic circuit designed to synchronize its output frequency with an input frequency by adjusting both phase and frequency parameters.

PLLs find widespread application in digital circuits, telecommunications, and radio communication systems. They serve the crucial functions of extracting timing and frequency details from noisy input signals and generating stable, precise clock signals for digital systems.

Key components of a PLL include a voltage-controlled oscillator (VCO), a phase detector, and a loop filter. The phase detector compares the phase of the input signal with the VCO's output, while the loop filter ensures the VCO's frequency adjusts appropriately to minimize phase differences. The VCO's output frequency then becomes the synchronized output signal.

Modern electronics utilize PLLs extensively for tasks like frequency synthesis, clock generation, and phase modulation/demodulation.

Technology  fdsoi28nm 
Frequency Obtained for 10Mhz input:    6GHz

Duty Cycle obtained:     49.6% at 6GHz

![image](https://github.com/user-attachments/assets/3099930d-8e79-4cff-8ed5-06c6860bc91b)

### Phase Detector
A phase detector plays a crucial role within a phase-locked loop (PLL), which functions as a control system to produce an output signal synchronized with an input signal. The input signal typically varies in frequency and phase over time, and the PLL generates an output signal that adjusts to these variations to maintain synchronization.

The phase detector compares the input signal phase with the PLL's output signal phase. It generates an error signal proportional to the phase difference between these signals. This error signal guides the PLL's control circuitry in adjusting the output signal's frequency and phase to minimize the phase difference and uphold synchronization.

Different types of phase detectors are utilized in PLLs, such as analog phase detectors, digital phase detectors, and mixers. The selection of the phase detector depends on specific application needs and the characteristics of the input and output signals.
### testbench of PFD
![image](https://github.com/user-attachments/assets/cdda3372-acc4-49fa-8b7d-a058638c5ed3)

### Result of PFD

### Schematics of Dflipflop
![image](https://github.com/user-attachments/assets/60779a71-6e73-41c6-8914-c7b4127f435a)
### Simulation result of flipflop
![image](https://github.com/user-attachments/assets/93d8e01c-acb2-4b13-864a-a0d501f3d9e0)

### AND gate schematics
![image](https://github.com/user-attachments/assets/35a171ce-c448-4c25-849f-bc47c2e1a06a)

### Resul

### Charge Pump
A charge pump is an electronic circuit designed to convert a DC voltage level to either a higher or lower DC voltage. This is achieved by periodically charging and discharging one or more capacitors to generate a voltage different from the input.

The core mechanism of a charge pump involves a switching network that transfers charge between capacitors in a specific sequence, thereby altering the voltage level. In a step-up charge pump, for instance, the input voltage alternates between two capacitors, allowing the charge to build up across a series of capacitors, which produces a higher output voltage.

Charge pumps are widely used in various electronic applications, including voltage converters, LCDs, and flash memory programming. They are favored for their efficiency, cost-effectiveness, and simplicity compared to other voltage conversion methods.
# VCO
### Schematics of csvco
![image](https://github.com/user-attachments/assets/c0cbc2fe-f203-4126-a059-c22306f9ea8c)

### Simulation Result of CSVCO
![image](https://github.com/user-attachments/assets/58719908-a4d8-4a82-8bc7-9f364ea92ebb)

### Frequency Divider
A frequency divider is an electronic circuit that takes an input signal of a certain frequency and generates an output signal with a lower frequency. This is accomplished by dividing the input frequency by a fixed integer value, known as the division ratio

There are several frequency dividers, including binary dividers, divide-by-n dividers, and programmable dividers. Binary dividers divide the input frequency by powers of two, while divide-by-n dividers divide the input frequency by a fixed integer value. As the name suggests, programmable dividers allow the division ratio to be programmed or changed dynamically.

Frequency dividers can be implemented using various electronic components, such as digital logic gates, flip-flops, and counters. Some modern frequency dividers are also implemented using digital signal processing (DSP) techniques, which can provide greater flexibility and accuracy.
#### Application of Frequency Divider
1. It is being used in digital electronics, telecommunications, and instrumentation.
2. They are often used in frequency synthesizers, which are electronic circuits that generate a precise frequency output by combining the output of a frequency divider with a stable reference frequency
### Schematics of Dflipflop
![image](https://github.com/user-attachments/assets/60779a71-6e73-41c6-8914-c7b4127f435a)
### Simulation result of flipflop
![image](https://github.com/user-attachments/assets/93d8e01c-acb2-4b13-864a-a0d501f3d9e0)

### TB of Frequency divider
![image](https://github.com/user-attachments/assets/e6a287de-74c1-4341-995f-07093737591b)
### Simulation Result of Frequency Divider(By 4)
![image](https://github.com/user-attachments/assets/80ce51b1-bc25-4127-8b5f-366075eebeb9)

### PLL Testbench
![image](https://github.com/user-attachments/assets/16936cdf-4b17-4223-ac52-fc9dc4758cd8)

### PLL Result
![image](https://github.com/user-attachments/assets/749a720a-d0b9-49ad-8350-d2a279bac3ce)

![image](https://github.com/user-attachments/assets/569677c2-14c5-43cb-8f84-8c56a4f31132)







