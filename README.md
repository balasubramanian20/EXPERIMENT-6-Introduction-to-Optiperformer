
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.
In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.
Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.

PROCEDURE:
1.	Download and install OptiPerformer from the optiwave.com web site.
2.	Copy the ‘Introduction_OptiPerformer.osp’ file to your PC
3.	Start OptiPerformer
4.	Use either the File menu or the Open File button to open the Fiber Optic System File.
5.	Study the layout, which includes some text and boxes to identify the three components of the fiber optic system. The “transmitter” section includes a binary source (PRBS or pseudo-random bit sequence generator), an electrical pulse generator, a laser diode and an external modulator. The receiver section includes a photodiode, a low-pass filter and a decision circuit, which includes a BER analyzer. We will cover these components in more detail later in the course.
6.	Run the simulation by pushing the start button. The progress of the simulation will be displayed
and the message “Calculation Finished!” will appear when the simulation runs to completion.
7.	Double click on the optical power meter and the BER analyzer and move the windows as necessary for clarity. Check the box next to “Show Eye Diagram” in the BER window. The optical power meter shows the power at the input to the photodiode in both watts and dBm. The BER window displays the “eye diagram” and several quantities including the “Max Q
Factor” and the “Min BER”.
8.	The simulation is set to run 5 “iterations”, with the fiber length varying from 50 to 150 km in 5 steps. The index is displayed in the upper right corner of the layout. To step through the iterations, use the forward and reverse buttons in the lower left of the window. Note the change in received power and BER display (eye diagram, Q factor and BER) with fiber length.


## Tabulation

**Transmission Analysis Across Fiber Lengths**
![f66062ab-0c21-421a-a7a4-05722a3f19d0](https://github.com/user-attachments/assets/575b1416-8180-48db-8836-c67f6aa2419b)


---

## Graphs
<img width="1912" height="1100" alt="513039598-566a99a6-5102-48bc-9e9a-da70cd664c39" src="https://github.com/user-attachments/assets/af5488d4-e3db-4a64-b190-09984a9bf49c" />
<img width="1909" height="975" alt="513040432-c07e2dac-efe7-420a-9ce3-c07f8af41f87" src="https://github.com/user-attachments/assets/a1d06e23-3380-44ef-9f9e-8c4807e23700" />
<img width="1919" height="980" alt="513040666-e25a0844-1a26-4026-aad6-9584f15d2a96" src="https://github.com/user-attachments/assets/9b18ad42-0b94-47b2-ab66-a8e81ef46bf9" />

---

## RESULT
Result: The optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed:

Received optical power decreased due to fiber attenuation.
Q-factor gradually decreased, indicating signal quality degradation.
Bit Error Rate (BER) increased with distance, showing higher error probability.
The eye diagram became more closed at longer fiber lengths, confirming dispersion and noise effects.
Hence, the simulation verified that optical signal performance deteriorates with increasing fiber length due to attenuation and dispersion losses.
