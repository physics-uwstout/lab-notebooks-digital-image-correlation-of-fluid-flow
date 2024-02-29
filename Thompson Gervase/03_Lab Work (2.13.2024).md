We cannot run the experiment ourselves yet. There is not enough copper sulfate to make the ionic solution. Once that material is here, we can do some test-runs.

Continuing to work through the [[Student Lab Notebooks/Thompson Gervase/PDFs/Digital Imaging of Fluid Flow/PIV Guided Notebook.ipynb|PIV Guided Notebook]] and learn what is going on when breaking down the video files. We were able to work through all of the code with the video provided ([[Student Lab Notebooks/lab-notebooks-digital-image-correlation-of-fluid-flow/Thompson Gervase/Misc Files/PIVCleanData.mp4]]). It was interesting working through the data filtering process within the given script. 

The rest of the lab time, we read through the following research paper, [[Kelley and Ouellette - 2011 - Using particle tracking to measure flow instabilit.pdf]].
	- Experimental Setup Notes
		- Acrylic Base: 248mm x 286mm
		- Solution Depth: 5mm 
		- Magnets Used: Neodymium-iron-boron (NdFeB) grade N52 (B = 0.3 T)
		- Electrolyte Solution
			- 10% mass solution of $CuSO_4$ in water
				- Mixed with glycerol (20% by volume) -- increases viscosity 
		- Power Supply
			- To produced the flows described in this paper, we need a power supply capable of 200 mA at 40V.
		- They used 80 $\mu$m fluorescent polystyrene spheres
			- Density is low enough to float on electrolyte surface 
			- Surface tension can create some issues
				- Can be minimized by keeping the seeding density low and adding a small amount of surfactant such as a drop of dish soap


-------------------------------------------------------------------------------

Questions that came up today:
	- What is Signal-to-noise ratio?
		- It is desirable to have a high signal-to-noise ratio...
	-Python Error
		- module 'numpy' has no attribute 'warnings'
			- solution: suppress warnings
			- Python code: 
				- import numpy, warnings numpy.warnings = warnings