## Object Detection (using YOLO V5)

#### Use Case - Urban Traffic Monitoring and Safety Enhancement through Object Detection

#### Objective
Implement object detection to enhance urban traffic monitoring, ensuring pedestrian safety and efficient vehicle flow by identifying and analyzing pedestrians, cars, motorcycles, buses, as well as recognizing traffic signals and animals (cat and dog).
Scenario: In a busy urban environment, the object detection system is deployed to monitor traffic and improve safety for pedestrians and drivers alike.

Object Detection:
1.	Pedestrian Detection : The system identifies and tracks pedestrians, ensuring their safety by monitoring crosswalks, sidewalks, and other pedestrian zones.
2.	Vehicle Detection : Cars, motorcycles, and buses are detected and tracked to analyze traffic patterns, optimize signal timings, and improve overall traffic flow.
3.	Animal Detection : The system recognizes the presence of animals, such as cats and dogs, on roads, alerting drivers and contributing to animal safety.
4.	Traffic Signal Recognition : The object detection system is trained to identify and distinguish between red, yellow, and green traffic signals, facilitating adherence to traffic regulations and optimizing vehicle movements.

#### Traffic Management and Safety
•	The data from the object detection system is integrated into a centralized traffic management system, allowing authorities to monitor real-time traffic conditions and respond to potential issues promptly.

•	Adaptive signal control is employed based on the detected objects, optimizing signal timings to alleviate congestion and improve the overall efficiency of urban traffic.

####Benefits
•	Pedestrian Safety : Enhanced pedestrian detection ensures timely interventions and alerts to prevent accidents and promote safer pedestrian crossings.

•	Traffic Flow Optimization : Accurate vehicle detection and signal recognition contribute to smoother traffic flow, reducing congestion and improving overall transportation efficiency.

•	Animal Protection : Animal detection alerts drivers to the presence of animals on the road, mitigating the risk of collisions and enhancing animal safety.

The images are downloaded from Flickr (https://www.flickr.com/photos/tags/flicker/) and the annotation of the objects of interest is performed in Roboflow.  


Objects of interest:

1. Person
2. Car
3. Bus
4. Motorcycle
5. Cat
6. Dog
7. Red Signal
8. Yellow Signal
9. Green Signal

The entire dataset(train, valid, test) and the 'yaml' file are created in Roboflow.