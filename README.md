# Light-Intensity-Detector-Using-IoT
A project that measures the intensity of light of the Surrounding and notifies user about the changes in intensity of light at different time intervals that helps user to know about the precise intensity of light .

**Hardware Required**
1 x Bolt IoT Module
1 x Micro USB Cable
1 x LDR (2 legged devicewith a red wave pattern disk on top)
1 x 10k Ohm Resistor (brown black orange color code)
The resistance of an LDR varies inversely with light, i.e., the resistance decreases as the intensity of light falling on the LDR increases.

**Connecting the LDR Circuit to the Bolt**
Step 1: Insert one lead of the LDR into the Bolt Module 's 3v3 Pin.
Step 2: Insert other lead of the LDR into the A0 pin.
Step 3: Insert one leg of the 10k Ohm resistor into the GND pin.
Step 4: Insert the other leg of the resistor also into the A0 pin.

**Software Code:**
plotchart("time_stamp"."light");

This code gives us the plotchart of different light intenity as it varies along with different time stamp
