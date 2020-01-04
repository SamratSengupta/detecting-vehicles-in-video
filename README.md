Before any road construction, the government needs to determine the width and strength of the road, along with numerous other factors. These factors are determined by counting and categorising the vehicles that would run on the road once it's built. Earlier, manual surveys were conducted by counting the number of vehicles passing through the lane and categorising vehicles as a car, a truck, etc.

Vehicle detection:

The first step is to break a video into individual frames.
Then, make an imaginary (virtual) line across the lane.
To keep the track of the vehicles, increase the vehicle count by one whenever a vehicle crosses the imaginary line.
 

Vehicle classification:

Crop the vehicle that just passed the imaginary line.
Classify the cropped vehicle using a CNN classifier.

Functionalities:

Mouse_click_event.ipynb is used for segmenting a video to generate a marker for crossing line beyond which vehicles are to be tracked
Tracking+notebook+tutorial.ipynb is used for tracking a vehicle once it crosses the marker
ML Neural Nets demo - Vehicle Classification.ipynb for vehicle classification using cnn.
ML Neural Nets demo - Identification of vehicles.ipynb for identification of vehicles.

 

