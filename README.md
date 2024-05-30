# Python-File-Reading-Graph-Creation-Search-Algorithms
- Implemented concepts of Python File Reading, Graph Creation, and Searching Algorithms 
- Used pandas libraries to read data from .csv files that contain the list of Texas Cities, and Distance between two cities (if there is a path present)
- Used matplotlib.pyplot, networkkx, matplotlib.image to create the graph that represents the map of Texas and plotted it over an image of the Texas state
- Used concepts of nodes to represent the cities in the graphs
- Performed Breadth First Search Algorithm as an uniformed search agent that traverses through the graph (map of texas) starting from "Three Rivers", In which it hits each city (node) atleast once and records the total distance travelled. This was done to mimic the spread of the virus starting from "Three Rivers." 
- Used A* Algorithm as an informed search agent to find the optimal path from "San Antonio" (start node) to "College Station" (goal node). Implemented calculations of Euclidean Distance as a heuristic function. This was done to mimic the scenario of finding an optimal of transferring a vaccine from San Antonio (city where vaccine is in supply) to College Station ( city,  where vaccine is in demand)
# To Test Code 
- download .ipynb file , and download the two .csv files (distances.csv and cities.csv) and .png file (texas-map-2.png)
- in source code , change the file path, by modifying the basePath variable. The modification should point to a folder that holds the two .csv files and .png files, so that they can be accessed by the code
- basePath = "your_file_path"
- You will now be able to test out the code 
