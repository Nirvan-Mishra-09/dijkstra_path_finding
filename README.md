# dijkstra_path_finding
Implementation of Dijkstra Algorithm in the given map.

................................................................................................

Libraries used:

import cv2

import numpy as np


import heapq

................................................................................................

Code Overview:

Step 1: Using opencv to create a map, with clearance given by the user.

![map](https://github.com/Nirvan-Mishra-09/Motion-Planning-Algorithms/assets/127642231/1da78fa1-47a0-4468-833a-e8b9965f92b1)




Step 2: Create a user interface and check for valid inputs.

Step 3: To define the action set of the point robot, this robot can move in 8 directions up, down, left, right, up_right, up_left, down_right, and down_left. 

The cost of up, down, left, and right moves are '1', on the other hand, the remaining moves have '1.4' as their costs.

![actionset](https://github.com/Nirvan-Mishra-09/dijkstra_path_finding/assets/127642231/2b684585-8463-4e4c-8046-b2a1359147ba)



Step 4: Implementing Dijkstra's algorithm, and finding the shortest path from start point and destination. 

![Untitled Diagram](https://github.com/Nirvan-Mishra-09/dijkstra_path_finding/assets/127642231/3bb6980d-b994-4282-bf15-1ebfc0839944)



Step 5: Results 

User input: 

![results](https://github.com/Nirvan-Mishra-09/dijkstra_path_finding/assets/127642231/c6834084-285d-4224-b9c5-8cc73e9434e9)



Path taken:





https://github.com/Nirvan-Mishra-09/Motion-Planning-Algorithms/assets/127642231/d4177d9d-343c-48b2-996b-fb68dcc3ac8d







