# sensor-fusion
A repo used to document sensor fusion mechanisms and experiments


### Key elements of sensor fusion
1. Multiple sensors: 
    sensor fusion fundamentally requires two or more sensors
    e.g., cameras, radar, lidar, GPS, gyroscopes, accelerators, and etc.
2. Data sychronization:
    the data from multiple sensors must be sychronized in time and space, this can involve aligning the data timestampes, adjusting for sensor orientation and position and converting the data into a common coordinate system
3. Data preprocessiong:
    the raw data from each sensors requires preprocessing to remove noise, filter out irrelevant information and normalize data to a common format
4. Data fusion algorithms:
    the data fusion algorithm is used to combine the preprocessed data from multiple sensors
    the algorithms range from simple averging to complex machine learning algorithms taken into account the uncertainties and correlations between the sensor data
5. Calibration:
    the sensors must be calibrated to ensure their measurements are accurate and consistent
    e.g., sensor biases, scaling factors
6. System validation:
    the system must be validated under various conditions to ensure that it meets the required specification
    e.g., different lightning, weather, terrain
    and then compare the system output with the ground truth data