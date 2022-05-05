
<img src="https://user-images.githubusercontent.com/92499217/167004618-c64b16b0-f170-416f-90a0-9f8b0979edc7.PNG" data-canonical-src="https://user-images.githubusercontent.com/92499217/167004618-c64b16b0-f170-416f-90a0-9f8b0979edc7.PNG" width="1500" height="250" />

# Introduction

66 million years ago, a large asteroid colliding with earth caused a calamitous end to 75% of the Earth’s animals including dinosaurs. Asteroids, the irregularly shaped rocky bodies that orbit the sun, have a very remote probability of striking the Earth and causing damage. However, when these collisions occur, the devastating consequences can last for decades. Hence, detecting and mitigating the threat in time is essential. 

The focus of this research was to find a precise model for predicting hazardous asteroids. Machine Learning techniques such as Logistic Regression, Naïve Bayes, KNN, Random Forest etc. are used. Boosting, Bagging and Stacking were also explored. Furthermore, hyperparameter tuning and feature selection was also performed to get the most optimum result. 10 models were built using these classification techniques. Accuracy, Precision, Recall were used to compare and find the best model. 

# Dataset

The data has 40 attributes with 4687 records. The dataset contains a boolean variable called Hazardous which classifies each record into hazardous or non-hazardous categories. The data contains descriptions of the asteroid such as minimum and maximum estimated diameter. These are approximate values as the objects are irregularly shaped. 

A detailed description of each feature is given below:

- Neo Reference ID - Near Earth Object (NEO) reference ID number for an asteroid
- Name - 'Name' of asteroid
- Absolute Magnitude - A measure of the asteroid's luminosity (in H) (the brightness of an asteroid if it is 1 astronomical unit away from both the Sun and the observer, and the angle between the Sun, asteroid, and Earth is 0 degrees)
- Est Dia in (in KM, M, Miles, and Feet) (min) - Minimum estimated diameter of the asteroid
- Est Dia in (in KM, M, Miles, and Feet) (max) - Maximum estimated diameter of the asteroid
- Close Approach Date - Date at which the asteroid approaches close to Earth
- Epoch Date Close Approach - Date at which the asteroid approaches close to Earth (in epoch time)
- Relative Velocity (in km per sec, km per hr, and miles per hour) - Asteroid's velocity relative to earth
- Miss Dist. (in Astronomical, lunar, km, and miles) - Distance by which the asteroid misses Earth
- Orbiting Body - Planet which the asteroid orbits
- Orbit ID - An ID of JPL NEA orbit that JPL Nasa uses in its analysis
- Orbit Determination Date - Date at which the asteroid's orbit was determined
- Orbit Uncertainty - A measure of the uncertainty ('measurement errors') in the calculated orbit
- Minimum Orbit Intersection - The closest distance between Earth and the asteroid in their respective orbits (in astronomical units)
- Jupiter Tisserand Invariant - A value used to differentiate between asteroids and Jupiter-family comets
- Epoch Osculation - The instance of time at which the asteroid's position and velocity vectors (from which its osculating orbit is calculated) is specified
- Eccentricity - A value which specifies by how much the asteroid's orbit deviates from a perfect circle
- Semi Major Axis - The longest radius of an elliptical orbit; a measure of the asteroid's average distance from the Sun (asteroids orbit the Sun)
- Inclination - Measures the tilt of the asteroid's orbit around the Sun
- Asc Node Longitude - Angle in the ecliptic plane between the inertial-frame x-axis and the line through the ascending node
- Orbital Period - Time taken for asteroid to complete a single orbit around the Sun
- Perihelion Distance - Distance of point in asteroid's orbit which is closest to the Sun
- Perihelion Arg - The angle (in the body's orbit plane) between the ascending node line and perihelion measured in the direction of the body's orbit
- Aphelion Dist - Distance of point in asteroid's orbit which is farthest from the Sun
- Perihelion Time - Length of time of asteroid's passage through the perihelion stage
- Mean Anomaly - The product of an orbiting body's mean motion and time past perihelion passage
- Mean Motion - The angular speed required for a body to make one orbit around an ideal ellipse with a specific semi-major axis
- Equinox - An astronomical standard to measure against (currently 'J2000.0')
- Hazardous - Is the asteroid hazardous? (True or False)

# Project Cycle

![Project Cycle](https://user-images.githubusercontent.com/92499217/167001962-34c63fb7-7413-4acf-959e-85cc3788f0c1.PNG)

# List of Models

- KNN
- Naïve Bayes
- Logistic Regression
- Random Forest
- AdaBoost
- Gradient Boost
- XGBoost
- Combined Prediction (AdaBoost, Gradient Boost, XGBoost)
- Stacking Classifier
- Save Earth

# Conclusion

The table below summarizes all 10 models that have been developed. 

![Conclusion](https://user-images.githubusercontent.com/92499217/167003795-41c8c0e4-5885-42a8-90b4-e89c9a02af5a.PNG)

It can be seen that the misclassified percentage is low for the ensemble models except for XGBoost. In terms of accuracy score for the test, the highest is found to be 0.998 of the Save Earth Model followed by Combined Prediction Model. 


