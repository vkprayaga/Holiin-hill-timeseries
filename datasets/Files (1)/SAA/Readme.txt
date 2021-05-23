Shape Accelerometers Arrays data

Location of the eastern and western sensors are given in SAA_coords.csv

Files saa_data_eastern.txt and saa_data_western.txt are the X and Y displacements of the 9 sensors for each location.
Each sensor is installed at specific depth in the 2.5 m borehole.
	Column[1] = date
	Columns[3:11] = Cumulative displacement along x axis (perpendicular to slope) labelled SENSOR_X_1-9
	Columns[11:20] = Cumulative displacement along y axis (downslope) labelled SENSOR_Y_1-9
	Columns[21:29] = Z position of the 9 sensors from the bottom of the borehole
	Sensor 1 is the deepest, sensor 9 the shallowest

files saa_data_eastern_horizontal_displacement.txt and saa_data_western_horizontal_displacement.txt are the X and Y displacements of the 9 sensors for each location.
Each sensor is installed at specific depth in the 2.5 m borehole.
	Column[1] = date
	Columns[2:10] = Cumulative displacement along x and y axis
	Columns names are the depth with respect to the surface
	Sensor 1 is the deepest, sensor 9 the shallowest
