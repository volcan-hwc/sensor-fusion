# sensor-fusion
A repo used to document sensor fusion mechanisms and experiments


### Key elements of sensor fusion
1. Multiple sensors: <br/> 
    sensor fusion fundamentally requires two or more sensors<br/> 
    e.g., cameras, radar, lidar, GPS, gyroscopes, accelerators, and etc.<br/> 
2. Data sychronization:<br/> 
    the data from multiple sensors must be sychronized in time and space, this can involve aligning the data timestampes, adjusting for sensor orientation and position and converting the data into a common coordinate system<br/> 
3. Data preprocessiong:<br/> 
    the raw data from each sensors requires preprocessing to remove noise, filter out irrelevant information and normalize data to a common format<br/> 
4. Data fusion algorithms:<br/> 
    the data fusion algorithm is used to combine the preprocessed data from multiple sensors<br/> 
    the algorithms range from simple averging to complex machine learning algorithms taken into account the uncertainties and correlations between the sensor data<br/> 
5. Calibration:<br/> 
    the sensors must be calibrated to ensure their measurements are accurate and consistent<br/> 
    e.g., sensor biases, scaling factors<br/> 
6. System validation:<br/> 
    the system must be validated under various conditions to ensure that it meets the required specification<br/> 
    e.g., different lightning, weather, terrain<br/> 
    and then compare the system output with the ground truth data<br/> 