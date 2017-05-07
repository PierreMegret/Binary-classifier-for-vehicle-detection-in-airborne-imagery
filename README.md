# Binary-classifier-for-vehicle-detection-in-airborne-imagery
## The project
Building a classifier to recognize cars in typical aerial images. Such pattern recognition systems have a wide scope of applications ranging from urban space management to emergency response, where large volumes of remotely sensed imagery data have to be processed automatically.
Python was the programming language for this project.
## The code
The project is organized as follow: a python script to read the image and collect the dataset of car and non-car samples (Data collection) and another to build the model and test it.
## The data
The dataset was an image of a typical parking in the Bay Area in PNG format (parking_train.png). There are 4 bands in the image (R, G, B, T). The T band is a transparency mask that does not carry any information here.
## Testing
The performance of the classifier was demonstrated on a testing dataset. A part of the testing image was provided (parking_test_preview.png) as well as an example set of locations (test_locations_and_labels_preview.np), however, the exact testing image and the sample locations for testing were not available prior to the submission of the project.
## The Scoring System (max available points: 112.5)
2 points were given for every car classified correctly and 0.5 points subtracted for every non-car classified as a car (i.e. for every “false alarm”) as well as for every car missed. Each correctly identified non-car brought 0.25 points. There were 100 pre-set locations within the testing image (50 cars and 50 non-cars).
## Final Score
On the complete testing dataset, my classifier had a final score of 102.5, meaning an accuracy of 91%.
