# predictive_maintenance_project-

UID: A unique identifier ranging from 1 to 10,000.

productID: Consisting of a letter (L, M, or H) indicating the product quality variant (low, medium, or high) and a variant-specific serial number.

air temperature [K]: Generated using a random walk process and normalized to a standard deviation of 2 K around 300 K.

process temperature [K]: Generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.

rotational speed [rpm]: Calculated from power of 2860 W, overlaid with normally distributed noise.

torque [Nm]: Torque values are normally distributed around 40 Nm with a standard deviation of 10 Nm and no negative values.

tool wear [min]: Tool wear values are dependent on the product quality variants, where H/M/L add 5/3/2 minutes of tool wear, respectively.

'machine failure' label: Indicates whether the machine has failed in this particular data point for any of the following failure modes.


#Features
Target : Failure or Not

Failure Type : Type of Failure
