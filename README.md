# Spring 2025 ECSE Design Methodology Project

Below I will showcase by far the most challenging project I have ever worked on. The course required my 4 randomly assigned teammates and I to complete weekly progress/design deliverables with only little explanation and rigorous documentation for each phase of our design. For the design itself, it could only consist of preapproved parts and be powered by a 24V DC supply.

I refer to myself as a "Lead Designer" on this project and I mean it. Between me and one other teammate, we took the lead on designing, programming, and testing every single one of the individual features. Specifically, I led the Voltmeter, DC Reference, Frequency Measurement, Rotary Encoder, and programming the Square Wave. 

Due to the course repeating projects every 3 years, I cannot go into the exciting technical details of our design. However, I can demostrate what our glorious creation was capable of. 

<img src="Pictures/FullShot1.jpeg" alt="Full View" width="">

### To receive an A in the course, our final design needed to include
----
 - Controllable LCD UI
 - Ohmmeter
 - Internal & External Voltmeter
 - DC Reference 
 - Frequency Measurement
 - Square Wave Generator
 - Sine Wave Generator

## Controllable LCD UI
For this project, our UI was displayed on an LCD screen and controlled by a KY-040 Rotary Encoder. 

<img src="Pictures/FullShot2.jpeg" alt="UI/Connections" height="">

Each function of the workbench utilized its specifically labeled banana jack or female jumper wire connection. 

## Ohmmeter
The Ohmmeter was required to read resistances between 500 and 10k Ohms. An accuracy reading also needed to be tested and displayed on the UI. 

<img src="Pictures/OhmIN.jpeg" alt="Ohmmeter Input" style="width: 70%; display: block; margin: 0 auto;">
<img src="Pictures/OhmUI.jpeg" alt="Ohmmeter Reading" style="width: 70%; display: block; margin: 0 auto;">

## Internal & External Voltmeter
Our Voltmeter had to read both external voltages (from a DC supply) and internal voltages (the DC Reference) within a range of +/-5V and with an accuracy with +/-0.3125V. For this example, the voltage being measured is 3.1V and the 24V is powering the workbench.

<img src="Pictures/VoltExIN.jpeg" alt="Voltmeter Input" style="width: 70%; display: block; margin: 0 auto;">
<img src="Pictures/VoltExUI.jpeg" alt="External Voltmeter Reading" style="width: 70%; display: block; margin: 0 auto;">

## DC Reference 
The DC Reference was required to output a stable +/-5V reference. As mentioned above, this voltage needed to be selected with the UI (the Voltage: line), and measured internally by the Voltmeter (the Meas: line).

<img src="Pictures/VoltInUI.jpeg" alt="DC Reference Internal Measurement" style="width: 70%; display: block; margin: 0 auto;">

<img src="Pictures/DcOut.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">

## Frequency Measurement
For the Frequency Measurement, it was required to measure a positive voltage sine wave between the 1 kHz and 10 kHz. Similarly to the Ohmmeter, an accuracy range needed to be verified and displayed on the UI.

<img src="Pictures/FreqIn.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">
<img src="Pictures/FreqUI.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">

## Square Wave Generator
For the Square Wave Generator, the objective was to create an x-axis centered square wave with a 50% duty cycle with variable amplitude in steps of 0.3125 V and maximum amplitude of ± 10 V. The frequency of this wave needed to be adjustable within a range between 100 Hz and 10 kHz, in steps of 10 Hz.

<img src="Pictures/SquareUI.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">
<img src="Pictures/SquareOUT.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">

## Sine Wave Generator
The Sine Wave Generator had to be able to produce a sine wave with variable amplitude between 0 V and 10 V in steps of 0.625V, and have variable frequency between 1kHz and 10 kHz in steps of 500 Hz.

<img src="Pictures/SineUI.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">
<img src="Pictures/SineOUT.jpeg" alt="DC Reference Output" style="width: 70%; display: block; margin: 0 auto;">
