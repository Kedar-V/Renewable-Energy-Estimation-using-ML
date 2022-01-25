# Renewable-Energy-Estimation-using-ML

## Task :

Renewable sources of energy can be the soultion for the ever growing demand for energy. Unlike conventional sources, their output depends on environmental conditions and therefore is not constant and fluctuates all the time, making it unreliable. 
In order to maintain the stability of the grid, whenever the output of the plant is reduced it needs to be balanced by supplying the required amount of power using conventional sources, which is costly. Conversely whenver the production is more than the demand it needs to be stored in a battery or is wasted.
The goal of the project is to create a machine learning model that can predict the output of a given renewable energy plant, this information can be used by the plant operator to help optimize the stability of the grid as well as the cost of operation.

## Dataset :

The dataset folder contains the following files:
<li> train.csv: 28200 x 22 </li> 
<li> test.csv: 12086 x 21 </li> 
<li> sample_submission.csv: 5 x 3 </li> 
<br/>

The dataset contains the following columns:
| Feature | Description  | 
| ------- | --- |
| tracking_id	| Represents a unique identification number of a windmill |
| datetime	| Represents the date and time of a record |
| wind_speed(m/s) | Represents the speed of wind (in meter per second) |
| atmospheric_temperature(°C)	| Represents the temperature (in degree Celcius) of a town or village that the windmill is present in |
| shaft_temperature(°C)	| Represents the temperature of the shaft (in degree Celcius) |
| blades_angle(°)	| Represents the angle of the blades of a wind turbine (in degrees) |
| gearbox_temperature(°C)	| Represents the temperature of a gearbox  (in degree Celcius)|
| engine_temperature(°C) | Represents the temperature of an engine (in degree Celcius) |
| motor_torque(N-m) | Represents the torque of a motor (in Newton meter) |
| generator_temperature(°C) |	Represents the temperature of a generator (in degree Celcius)
| atmospheric_pressure(Pascal) | Represents the atmospheric pressure (in Pascals) in that area |
| area_temperature(°C) | Represents the temperature (in degree Celcius) of the area within a 100 m radius of the windmill |
| windmill_body_temperature(°C) |	Represents the temperature of the body of a windmill (in degree Celcius) |
| wind_direction(°)	| Represents the direction of the wind (in degrees) |
| resistance(ohm)	| Represents the resistance against the wind |
| rotor_torque(N-m)	| Represents the torque of a rotor (in Newton meter) |
| turbine_status | Represents the status of the turbine (masked) |
| cloud_level	| Represents the following levels of the cloud in the sky on a particular day: <li> Extremely low </li> <li> Low </li> <li> Medium </li> |
| blade_length(m)	| Represents the length of the blades of a windmill (in meter)|
| blade_breadth(m) | Represents the breadth of the blades of a windmill (in meter)|
| windmill_height(m) | Represents the height of the blades of a windmill (in meter)|
| windmill_generated_power(kW/h)|	Represents the power generated (in Kilo Watt per hour)|
