Today we started out trying to run the videos we collected from [[11_Lab Work (3.19.2024)]] through the particle tracking script. However, we noticed that the flow pattern of these videos were off from previous groups in the past.

That led us to realize that we had the magnets and copper strips oriented relative to each other incorrectly. A schematic of the correct orientation is shown below. What was causing the issue with our setup was the fact that we had the copper strips and magnets 90$\degree$out of phase (relative to the image below). This was causing unexpected flow and some very disruptive eddy currents. 
![[Student Lab Notebooks/lab-notebooks-digital-image-correlation-of-fluid-flow/Thompson Gervase/Misc Files/Experimental Setup/Magnet and Copper Strips/Orientation #1.png]]

Once we corrected the orientation of the experimental setup, we collected data under four different parameters. 

**Video #1 Parameters**
- Voltage: 30.6 [V]
- Current: 0.14 [A]
![[Lab_12_30.6V_0.14A.MOV]]

**Video #2 Parameters**
- Voltage: 61.4 [V]
- Current: 0.62 [A]
![[Lab_12_61.4V_0.62A.MOV]]

**Video #3 Parameters**
- Voltage: 92.3 [V]
- Current: 1.53 [A]
![[Lab_12_92.3V_1.53A.MOV]]

**Video #4 Parameters**
- Voltage: 123.02 [V]
- Current: 3.03 [A]
![[Lab_12_123.02V_3.03A.mov]]


Now that we have recorded videos with the correct experimental setup, we can try and run [[Student Lab Notebooks/lab-notebooks-digital-image-correlation-of-fluid-flow/Thompson Gervase/Misc Files/PIV Guided Notebook.ipynb|PIV Guided Notebook]] script to analyze the videos.