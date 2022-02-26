3D Printable RC Race Track
Licensed under CC BY-SA

**Summary**

This repo provides a set of printable "lengths" or "lines" which can be combined to form the markings of a 1/10 scale RC car racetrack.

Size and design of the racetrack supports the use of Computer Vision with autonomous robotic platforms.

**Challenge**

Often when building autonomous robots based on RC Car platforms, a large amount of space is required for a suitable track. This track is often created useing tape of some kind.
When testing, access to a track is iteratively required. Where it is not possible to leave tape affixed, a portable and rapidly deployable 'racektrack' is required. 

The goal is to be able to deploy line markings:
* quickly;
* onto a hard surface (concrete, carpet, asphalt etc);
* requiring minimum use of adhesive;
* which leave no trace after deployment; and
* are reusable.

**Proposed Solution** 

The solution presented here uses 3D Printing (FDM) to create a series of inter-linking plastic components which can form the desired track.

The targeted 3D printer has a build area of 25cm x 20cm. The minimum track roughtly occupies a 6m x 6m space. Hence many pieces are required. 

For the outside lines each piece is roughly 20cm long and forms either a straight line or a curve with either 1.2m radius or 2.4m radius.

Each piece interlocks with each other piece in a uniform manner. Any individual piece can be flipped over and still interlock. 

To secure the connection and prevent pieces moving apart, a printable clip is included which is supported in the design without creating a visual protrusion. 

![Initial test of outside pieces](https://github.com/DingoOz/3D-Printable-RC-Race-Track-/blob/master/Track_layout1.jpg)

**Design**

The design attempts to comply with the DIYrobocar rules (se "Track Specs here": https://diyrobocars.com/110th-scale-race-rules/)

The outside line markings are white, with the inside centre line yellow and black.

Deviations from the rules include:
* the centerline is only 25mm width not 35mm-55mm


**Printing**

Recommended to use .2mm layers. No supports are required. Suggest printing in batches as large as the print surface allows.

The use of PLA has been tested successfully. The clip requires a small amount of flexability which PLA is capable of providing.

![Printing Yellow Lines](https://github.com/DingoOz/3D-Printable-RC-Race-Track-/blob/master/Printing%20centerlines.jpg)

**Usage**
The outside lines are intended to just sit on the ground (using gravity).

For a 90 degree curve you will need:
* 9x 1.2m radius curve pieces (outside / white)
* 18x 2.4m radius curves pieces (outside / white)

Each outside join requires two clips if using clips to secure them (recommended).

Note: That to make a curve alternate a "LEFT" with an inverted (flipped) "RIGHT" curve piece (see filename). Therefore the 18 2.4m pieces referred to above are 9 left and 9 right. Therefore it does not matter which direction the curve takes, the same pieces can acheive clockwise or counter-clockwise by flipping them.

The Centerline is intended to be used with 25mm wide black "gaffer" tape. Each black section can be affixed with 25mm black gaffer tape over the middel section as well as over the joint toungue with the yellow sections.




 
 
