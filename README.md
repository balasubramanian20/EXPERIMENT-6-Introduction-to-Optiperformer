# Exp 6 Simulation of Optical Communication System
# AIM:
Download and install OptiPerformer software on your computer and run a sample file.

# EQUIPMENTS REQUIRED:
Optisystem Software – OptiPerformer 22.0

# THEORY:
Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students. In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course. Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.

# PROCEDURE:
Download and install OptiPerformer from the optiwave.com web site.

Copy the ‘Introduction_OptiPerformer.osp’ file to your PC

Start OptiPerformer

Use either the File menu or the Open File button to open the Fiber Optic System File.

Study the layout, which includes some text and boxes to identify the three components of the fiber optic system.

The “transmitter” section includes a binary source (PRBS or pseudo-random bit sequence generator), an electrical pulse generator, a laser diode and an external modulator.

The receiver section includes a photodiode, a low-pass filter and a decision circuit, which includes a BER analyzer. We will cover these components in more detail later in the course.

Run the simulation by pushing the start button. 

The progress of the simulation will be displayed and the message “Calculation Finished!” will appear when the simulation runs to completion.

Double click on the optical power meter and the BER analyzer and move the windows as necessary for clarity.

Check the box next to “Show Eye Diagram” in the BER window. 

The optical power meter shows the power at the input to the photodiode in both watts and dBm.

The BER window displays the “eye diagram” and several quantities including the “Max Q Factor” and the “Min BER”.

The simulation is set to run 5 “iterations”, with the fiber length varying from 50 to 150 km in 5 steps.

The index is displayed in the upper right corner of the layout. To step through the iterations, use the forward and reverse buttons in the lower left of the window.

Note the change in received power and BER display (eye diagram, Q factor and BER) with fiber length.

# Report:
Cover sheet (as per attached example).

Tabulation of received power, Q factor, and BER for 5 fiber lengths.

Plot of received power, Q factor, and BER vs. fiber length. 

Description of eye diagram changes with increasing fiber length.

# Tabulation:
<img width="1600" height="1112" alt="image" src="https://github.com/user-attachments/assets/3ab85952-e3d1-4db7-a3e4-0a545b0e6c92" />

# CIRCUIT:
<img width="917" height="458" alt="image" src="https://github.com/user-attachments/assets/1812adca-422f-48f2-80b2-bc138b6c4334" />

Graphs:
<img width="1912" height="1100" alt="image" src="https://github.com/user-attachments/assets/2f93d915-80b1-44c6-977b-d3a9f5787ada" />
<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/830bc7cb-da7c-4513-9b20-a85b24e93150" />
<img width="1072" height="797" alt="image" src="https://github.com/user-attachments/assets/5ec42e55-2475-4fc1-bcc6-c0ef89655b42" />


# RESULT:
The optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed:

Received optical power decreased due to fiber attenuation. Q-factor gradually decreased, indicating signal quality degradation. Bit Error Rate (BER) increased with distance, showing higher error probability. The eye diagram became more closed at longer fiber lengths, confirming dispersion and noise effects. Hence, the simulation verified that optical signal performance deteriorates with increasing fiber length due to attenuation and dispersion losses
