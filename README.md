## Fire Station Location Optimization with Genetic Algorithm: Mumbai Case Study

This repository tackles the crucial challenge of optimizing fire station placement in Mumbai, India, to minimize response times and maximize rescue effectiveness. 

**Problem Description:**

Densely populated areas like Mumbai face an increased risk of fire accidents. Traditional fire station allocation methods might not be optimal, leading to delays and potentially greater damage. This project proposes a solution using a Genetic Algorithm (GA).

**Methodology:**

* **Data Acquisition:**
    * **Demand Data:** This dataset details the required rescue vehicles (fire trucks, ambulances, etc.) for various locations across three time periods (4am-8am, 8am-12pm, 12pm-4pm).
    * **Potential Locations Data:** This data identifies potential fire station locations, including information on compactness, population density, and travel times from various points.
    * **Shapefiles Data:** This data allows for visualizing the locations and distribution of points on a map using 3D visualization tools or computational geometry methods.
* **Data Preprocessing:**
    * Normalization: Travel time and location data are normalized to reduce computational costs when applying the Genetic Algorithm.
    * Details of the preprocessing steps are documented in `Info_data_pre_processing.txt`.
* **Genetic Algorithm Implementation:**
    * The core optimization logic is implemented using a Genetic Algorithm. The details of this implementation are provided in `implementation.txt` and the code itself is located in `implmentation.zip`.
* **Results and Analysis:**
    * The project report (`report_daga_fap.pdf`) presents the findings based on the Genetic Algorithm's output. This includes the optimal locations for fire stations and the number of vehicles required at each station to effectively handle emergencies within nearby areas.

**Repository Contents:**

* `Data Pre Processing.zip`: Compressed file containing data processing scripts.
* `Info_data_pre_processing.txt`: Text file explaining data preprocessing steps.
* `README.md`: This file (you are reading it now!).
* `data.zip`: Compressed file containing the project datasets.
* `implementation.txt`: Text file outlining the Genetic Algorithm implementation.
* `implmentation.zip`: Compressed file containing the Genetic Algorithm code.
* `report_daga_fap.pdf`: Project report with results and analysis.
* `requirments.txt`: Text file listing software dependencies.

**Benefits:**

* Optimized fire station placement based on real-world demand data.
* Improved response times for fire emergencies.
* Potentially reduced property damage and loss of life.

This project demonstrates the effectiveness of Genetic Algorithms for optimizing fire station allocation in urban environments. The provided code and documentation offer a valuable resource for further research and implementation. 
