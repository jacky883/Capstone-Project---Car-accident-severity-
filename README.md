# Capstone-Project---Car-accident-severity-

# Introduction

Every year there are thousands of car accidents occured in the city of Seattle. People's health and properies are damaged, and a great amount of public resources are spent to deal with those accidents, especially the severe one. As a result The government of Seattle is trying to study how we could reduce the rate and severity of car accidents based on the data collected on hand. Our goal is to analyze the data provided by the city government and predict the severity of the accidents based on different independent variables. The model we built would served as a reference for the city government, driver's educations, police departments as well as insurance companies to create rules and guidelines to reduce the rate and severity of the car accidents.

# Data

We will use the collision record history of the city of Seattle provided by the SPD from 2004 to present. The dataset contains 37 attributes and 194,673 individual traffic accident cases. We would drop all the irrelvant attributes and only keeping the following attributes:

Attributes  | Description
------------- | -------------
LOCATION:  | The X and Y coordinates of the collision.
SEVERITYCODE:  | A code that corresponds to the severity of the collision:3—fatality 2b—serious injury 2—injury 1—prop damage 0—unknown 
COLLISIONTYPE:   | Types of collision
ADDRTYPE:  | 3 Types of location where the collision occured: Alley, Block, Intersection.
WEATHER: |The weather condition when collision occured.
LIGHTCOND: |The light condition during the collision.
ROADCOND: |The road condition during the collision.

The SEVERITYCODE would be used as dependent variable and the rest of the attributes would be used as independent variables.


          

