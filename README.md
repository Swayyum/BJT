# BJT
ECGR 3131, Fall 2022 Project One – BJT Amplifier
Submission Due Thusday: November 18, 2022
1. Given and Required Specifications
The design of the amplifier shall be performed for the Fairchild Q2N3904 NPN Transistor.
Specifications can be obtained from the datasheet for the Fairchild Q2N3904 and are typically
given in a variety of ways. Minimum and maximum operating conditions are found in a table at
the beginning of the datasheet. Regions of operation and performance characteristics are given
in graphs toward the end of a datasheet. Spice models that contain useful parameters are
included somewhere in the middle. Other datasheets may have circuit configurations, packing
options, or physical drawings. Students will need to acquire β from the Current Gain (hfe) vs.
Collector Current in the datasheet. The early voltage can be found in the SPICE parameters
under VAF. There may be other relevant information included on the datasheet needed for the
project which will be responsibility of the student to determine.
Specifications for Amplifier:
• AV = vO/vI ≥ 150 V/V
• RL = 5 kΩ
• VCC = 16 V (rail voltage, single supply)
• Power Consumption = VCC * ICC ≤ 200 mW
• Swing = 10 V pk to pk
• RInput = any value
• ROutput = any value
Requirements for Project:
• One Partner Allowed
• Hand Analysis
▪ DC Biasing
▪ AC vs DC Load Line
▪ AC Gain
▪ RInput
▪ ROutput
• PSpice Simulation of Amplifier
▪ DC Biasing
▪ AC Gain
▪ Transient Response
▪ RInput
▪ ROutput
• Build and Test in Lab
▪ DC Biasing
▪ AC Gain
▪ Transient Response
▪ RInput
▪ ROutput
▪ Must demonstrate to TA or Professor
• Write a Technical Report in the form of IEEE Journal Publication
2. Building the circuit on P-Spice
Draw the circuit in any computer simulator (PSpice, Simulink etc.) of your choice that is
available on MOSAIC. Add the necessary libraries you will be able to select and add parts to the
schematic. If this particular BJT is not available in the lab use the one that is similar to build your
circuit.
2.1 DC Analysis
Compare the simulated DC currents and voltages to the values obtained using your hand
calculation. Make sure that they are within a few percentages of each other.
Include a schematic annotated with the simulated DC voltages and currents. Also include
a table comparing the calculated DC voltage and currents to the simulated values and the
ones obtained during the lab testing of the circuit. Show the percent error. Explain any
differences in the values.
2.2 AC Analysis
Run the circuit by setting the AC voltage to 1V. The AC analysis is the point where the input
and output impedance can be obtained. Using Ohm’s Law, the input and output impedance can
be found using the input and output voltage and current.
Include a plot of Gain vs. Frequency in Magnitude and dB in the report. Label the value
at F-3db low, F-3db high, max gain, and bandwidth. The values should include both the
gain and the frequency. Be sure to include enough points per decade for a smooth plot.
Include a plot of Phase vs. Frequency in the report. Label the value of the phase where
the dominant two f-3db points occur. Be sure to include enough points per decade for a
smooth plot.
Include a plot of Rin vs. Frequency in the report. Label the value of Rin. Explain why Rin
increases as frequency decreases. Be sure to include enough points per decade for a
smooth plot.
Include a plot of Rout vs. Frequency in the report. Label and value the Rout. Explain why
Rout increases as frequency decreases. Be sure to include enough points per decade for a
smooth plot.
Include a table comparing the calculated voltage gain, input impedance, and output
impedance to the simulated values and the ones obtained during the lab testing of the
circuit. Show the percent error. Explain any differences in the values.
2.3 Transient Analysis
Replace the VAC with VSIN if used. Edit the VSIN source to set the frequency to the peak gain
frequency, VAMPL to 1 mV, and VOFF to 0V. From the PSpice tab (for those using PSpice),
select edit simulation profile, set the simulation profile to transient and set the run time to span
over two periods of the peak gain frequency. Set your step size small enough to get a smooth
sine wave. Place voltage level markers at the input and the output terminals of the circuit. Now
run the circuit by clicking on the icon. Calculate the gain from the simulation. Edit the VSIN
source to the appropriate amplitude to check the swing of the amplifier.
Include the plot in the report of the gain at 1 mV. Also include a plot showing the swing
of the amplifier.
3. IEEE Journal Publication Style
The IEEE Journal Publication style can be found on the IEEE website using the link below. The
website includes resources for references, images, titling, and even templates that may be used to
create the paper. The paper should include various sections such as:
• Introduction
• DC Analysis
• AC Analysis
• Results
• Areas for Future Research / Improvement
• Conclusion
• References
IEEE Journal Publication Style Website
4. Results to Include
The plots and tables previously asked for in section 2 should be included in the results section.
Discussion about what is happening with the plot or table should be included. The following
about the frequency response should also be included in the results section for both simulated
and measured.
Range of frequency of operation: ______________ Hz to ______________ Hz
3dB Bandwidth of the circuit: _____________________ Hz
Peak Gain Frequency: _____________________ Hz
5. Conclusion
A discussion of the circuit and how it performed should be included in the conclusion. The
following questions should also be addressed:
Why is there a difference between the hand calculated gain, the simulated gain, and the measured
gain?
At what value does the swing become unsymmetrical and why is that?
How did you approach solving this design problem (remember to write in passive voice)?
