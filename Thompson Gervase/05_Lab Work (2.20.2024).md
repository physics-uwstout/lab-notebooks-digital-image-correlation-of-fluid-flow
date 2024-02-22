Today, we are still waiting on our copper sulfate supply to arrive so that we can actually build and run through an experiment. In the meantime, we are going to continue to play with the [[Student Lab Notebooks/lab-notebooks-digital-image-correlation-of-fluid-flow/Thompson Gervase/Misc Files/PIV Guided Notebook.ipynb|PIV Guided Notebook]] and take a deeper look into the "cross-correlation algorithm".  

-------------------------------------------------------------------------------

**Cross-Correlation Algorithm Key Variables**
	- *Interrogation Window Size (winsize)*
		- Establishes the spatial resolution of our measurement
			- i.e. smaller windows give more velocity vectors 
		- Rule of Thumb: pick interrogation window sizes so that there are around 5 particles in a typical interrogation window
	- *Search Size* (searchsize)
		- This is the size of the interrogation window in the second frame
		- Rule of Thumb: Typically this is chosen to be about 25% larger than the winsize
	- *Window Overlap (overlap)*
		- This sets how much adjacent interrogation windows overlap.
		- This increases our data density (velocity vectors per unit area) but also increases our processing time
			- Rule of Thumb/Common Choice: 50-75% of the winsize 
	- *Time step (dt)*
		- This is the time interval between frames and allows us to convert displacements to velocities. This can be computed from the frame rate at which the video was acquired.

-------------------------------------------------------------------------------

*Particle Image Velocimetry (PIV)* is an optical method of flow visualization used in education and research.

Notes on OpenPIV Documentation: [[https://openpiv.readthedocs.io/en/latest/]]
	- Common tracer particle size: 10-100 $\mu$m
	- Parameters that influence Measurement Effectiveness (Huang et al., 1997)
		- Particle Concentration, size distribution, and shape
		- Illumination Source 
		- Recording Device 
		- Synchronization between the illumination, acquisition and recording systems
	- PIV
		- Basic principle is to use two images of the same particles with a small time delay between them


Potential variables we can play with when conducting the experiment
	- Frames per second (FPS)
	- Image Quality 