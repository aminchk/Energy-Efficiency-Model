# Energy-Efficiency-Model

![image](https://user-images.githubusercontent.com/121105876/235116329-6e0f4dc0-2c79-47ad-97a7-c432c42ff187.png)

The study looks at the energy efficiency of residential buildings, in particular the heating and cooling requirements, as a function of architectural characteristics such as wall area, glazing area, orientation, etc.

The dataset used contains eight attributes describing these characteristics for 768 buildings and two target attributes: the heating and cooling loads of these buildings:

• Relative Compactness: This is the relative compactness of the building, which is defined as the ratio of the building's volume to the volume of an equivalent cuboid that encloses the building. This variable ranges from 0.62 to 0.98.

• Surface Area - m²: This is the total surface area of the building, including walls, roof, and windows. This variable ranges from 514.5 to 808.5 square meters.

• Wall Area - m²: This is the total area of the building's walls. This variable ranges from 245 to 416.5 square meters.

• Roof Area - m²: This is the total area of the building's roof. This variable ranges from 110.25 to 220.5 square meters.

• Overall Height - m: This is the height of the building. This variable ranges from 3.5 to 7.0 meters.

• Orientation - 2:North, 3:East, 4:South, 5:West: This is the orientation of the building. The values 2, 3, 4, and 5 represent North, East, South, and West orientations, respectively.

• Glazing Area - 0%, 10%, 25%, 40% (of floor area): This is the total glazing area of the building, expressed as a percentage of the floor area. This variable can take on one of four values: 0%, 10%, 25%, or 40%.

• Glazing Area Distribution (Variance) - 1:Uniform, 2:North, 3:East, 4:South, 5:West: This is the distribution of glazing area across the building. The values 1, 2, 3, 4, and 5 represent a uniform distribution and North, East, South, and West distributions, respectively.

• Heating Load - kWh/m²: This is the heating load of the building, expressed in kilowatt-hours per square meter. This variable ranges from 6.01 to 43.1 kWh/m².

• Cooling Load - kWh/m²: This is the cooling load of the building, expressed in kilowatt-hours per square meter. This variable ranges from 10.9 to 48.03 kWh/m².

The objective of the exercise is to predict the charges for each building, based on the first eight attributes.
