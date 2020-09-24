# THE DATA

Data used for this study will be the **Collisions** dataset recorded by the SDOT (Seattle Department of Transport), Washington. It has records of all road accidents that have occured from the year 2004 in the city of Seattle.
The dataset is a collection of all accidents occured in the study period which include the severity of the accident, weather conditions, traffic events etc.

## DESCRIPTION

The dataset consists of 194673 rows and 38 attributes. The target variable to be predicted will be the **SEVERITYCODE** which indicates the severity of the accident.
Some of the attributes that can be used to predict the target variable are:

### ADDRTYPE
This indicates the type of address where the collision happened (Alley, Block, Intersection). 

### PEDCOUNT
Number of Pedestrians at the scene of the accident

### VEHCOUNT
Nuber of vehicles involved in the crash.

### INCDTTM
The date and time of the collision

### UNDERINFL
Indicates whether the driver involved was under the influence of alcohol.

### WEATHER 
Describes the weather conditions observed at the timme and location of the collision.

### ROADCOND
Indicates the condtion of the road

### LIGHTCOND
Describes the lighting conditions at the scene of the accident

The dataset is observed to be skewed which means that there is data supporting one of the conditions ore than the others which makes it imbalanced. Hence sampling techniques have to be implemented before training to get proper results.
 