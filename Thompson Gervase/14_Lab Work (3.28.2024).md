Looking back at the magnet setup for this experiment, we finally understand what is going on underneath the tape. I was incorrect in my representations of the magnets from previous lab days. The magnet board being used can be seen below. The magnets are held in place by the tape in the center which makes it very difficult to see the actual magnets
![[Magnet Board.png]]
The correct magnet orientations can be seen in the representation below.
![[Magnet_Board_Annotated.png]]

Following that, we started to play with the Open PIV script and we ran some of our videos through.
It took some time to adjust the parameters to fit our experimental setup. Below are the parameters we used.

**Cross-Correlation Algorithm Parameters**
* winsize = 20  [pixels]
* searchsize = 25 [pixels]
* overlap = 10 [pixels]
* dt = 1/30 [seconds]
* Scaling Factor = 12.6 [pixels/mm]
**Vector Validation**
- Threshold = 1.15

It took some time to set those parameters, but once we got them set up, the results were decent. Below are some of the resulting plots sourced from an experiment ran at 30 [V].

**Raw Data Velocity Field Plot** 
![[Raw Data.jpg]]
**Filtered Data Velocity Field Plot**
![[Filtered Data.jpeg]]

The lines in the image above represent the flow of the fluid relative to the magnets. The pattern makes sense since the direction shown by the arrows alternate.

