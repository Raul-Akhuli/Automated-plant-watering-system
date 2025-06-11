<h1 align="center">AUTOMATED PLANT WATERING SYSTEM</h1>
<p align="center">An autonomous plant watering system that uses sensors, machine learning, and automated controls to monitor soil moisture, identify plant types, and dispense water efficiently based on plant-specific needs..</p>

<h2>Project Overview</h2>
<p>
  Traditional plant care often involves manual monitoring of soil moisture and environmental conditions, which can be time-consuming and inconsistent. Over-watering or under-watering plants is a common problem, leading to poor plant health and wasted resources. Many people struggle to provide the right amount of water, especially those with busy schedules or limited gardening knowledge.
</p>
<p>
Our Automated Plant Watering System addresses this problem by automating the entire watering process, ensuring that plants receive the precise amount of water they need, based on real-time environmental data. The system leverages a machine learning (ML) model to predict the water requirements of plants. This ML model, which runs on a Raspberry Pi, takes inputs such as soil moisture, temperature, and humidity readings to determine the optimal watering amount.
</p>
<p>
The system is designed with Arduino controlling the watering mechanism. Various sensors are used to monitor the soil moisture and environmental conditions, and Arduino communicates with the Raspberry Pi to obtain the predicted water amount from the model. Based on this prediction, Arduino manages the water pump to dispense the right amount of water, ensuring efficient plant care with minimal manual intervention. The integration of Raspberry Pi and Arduino allows seamless communication between the sensors and the watering system, making it a fully automated solution for plant care.
</p>
<h2>Features</h2>
<p>
<li><strong>Machine learning based water prediction</strong>
The system uses a trained ML model on the Raspberry Pi to predict the precise watering amount based on sensor data.
</p>
<p>
<li><strong>Real-time environmental monitoring:</strong>
Soil moisture, temperature, and humidity are continuously monitored using sensors to provide accurate input for water prediction.
</p>
<p>
<li><strong>Automated water dispensing:</strong>
The Arduino controls the water pump to dispense the predicted amount of water, ensuring proper plant hydration.
</p>
<p>
<li><strong>Efficient sensor communications:</strong>
Arduino sends sensor data to Raspberry Pi, receives the predicted water amount, and controls the watering process accordingly.
</p>
<p>
<li><strong>Minimal manual intervention:</strong>
The system automates plant watering, reducing the need for constant monitoring and manual care.
</p>


  
   

<h2>Hardware requirements</h2>
<p>
<li><strong>Raspberry Pi</strong> (for running the ML model)
<li><strong>Arduino</strong>  (for controlling sensors and the watering mechanism)
<li><strong>Soil Moisture Sensor</strong>  (to measure soil moisture levels)
<li><strong>DHT11 Sensor </strong> (to measure temperature and humidity)
<li><strong>Water Pump </strong> (to dispense water)
<li><strong>Relay Module</strong>  (to control the water pump)
<li><strong>Water Level Sensor </strong> (to measure the water level in the tank)
<li><strong>Water Tank</strong>  (to store water for the system)
<li><strong>USB Cable</strong>  (for communication between Raspberry Pi and Arduino)
<li><strong>LED Indicators</strong>  (To alert the system about the water level in the tank red(empty tank) and green (full tank)
<li><strong>Power Supply or Batteries</strong>  (to power the Arduino, Raspberry Pi, and sensors)
<li><strong>Connecting Wires and Jumper Cables</strong>  (for circuit connections)
<li><strong>Breadboard</strong> (for assembling the components)
<li><strong>16x2 LCD Display Module</strong>  (to display system status and sensor readings)

<h2>Software requirements</h2>
<p>
<li><strong>Operating System for Raspberry Pi:</strong>
</p>
<p>
	Raspberry pi OS.
</p>
<p>	
<li><strong>Programming Languages:</strong>
</p>
<p>
	Python: For ML model implementation and Raspberry Pi programming.
</p>
<p>
	C/C++: For Arduino programming.
</p>
<p>
<li><strong>Arduino IDE:</strong>
</p>
<p>
	For writing, compiling, and uploading code to the Arduino.
</p>
<p>
<li><strong>Machine Learning Libraries:</strong>
</p>
<p>
	1. <strong>pandas:</strong>For data manipulation and analysis.
</p>
<p>
	2.<strong> numpy: </strong>For numerical computations and handling multi-dimensional arrays.
</p>
<p>
	3. <strong>matplotlib.pyplot:</strong> For data visualization.
</p>
<p>
	4. <strong>sklearn.model_selection (train_test_split):</strong> For splitting the dataset into training and testing sets.
</p>
<p>		  
	5. <strong>sklearn.linear_model (LinearRegression):</strong> Implements a linear regression model for predicting the target variable (water amount).
</p>
<p>
	6. <strong>sklearn.metrics (mean_absolute_error, mean_squared_error)</strong>:For evaluating the accuracy and performance of the ML model.
</p>
<p>	
<li><strong>Arduino Libraries:</strong>
</p>
<p>
	1.<strong>LiquidCrystal:</strong> For controlling the 16x2 LCD display module.
</p>
<p>
	2.<strong>Wire.h:</strong> For I2C communication (if required for the LCD display).
</p>
<p>
	3.<strong>DHT.h:</strong> For interfacing with the DHT11 sensor.
</p>
<p>
<li><strong>Dataset Preparation Tools:</strong>
</p>
<p>
	1.<strong>Excel:</strong> For preparing and organizing the dataset.
</p>
<p>
	2.<strong>VS Code:</strong> For preprocessing the dataset and implementing the ML model.
</p>
<p>

 
