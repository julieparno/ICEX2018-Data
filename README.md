# ICEX2018-Data
Data to accompany the manuscript "Observations of Stress-Strain in Drifting Sea Ice at Floe Scale"

### Reflector Positions
Data were collected using a Leica TM50 high precision robotic total station. Each CSV file contains the time series data for a single reflector. Note that the data provided have been post-processed and corrected as described in the manuscript. CSV file names correspond to the reflector number, as mapped in Figure 1 of the manuscript. Column descriptions are provided in the table below.

| Column | Description |
|--------|-------------|
| `Epoch` | Timestamp of observation |
| `Refl_Number` | Reflector number |
| `Ref_Time` | The reference time series applied to all reflectors to tie cycle observations together |
| `SlopeDistance` | A time series of the range data (meters) |
| `HzAngle` | A time series of the angular data (radians) |
| `x_fixed` | A time series of the position data, converted to Cartesian coordinates (x, meters) and based on an ice-fixed reference frame with the total station at (0,0) |
| `y_fixed` | A time series of the position data, converted to Cartesian coordinates (y, meters) and based on an ice-fixed reference frame with the total station at (0,0) |
| `utmEast` | A time series of the position data in UTM coordinates (East) based on total station position on 21 March 2018 |
| `utmNorth` | A time series of the position data in UTM coordinates (North) based on total station position on 21 March 2018 |

### Stress
Data were collected with vibrating wire stress gages (Cox & Johnson, 1983). Each CSV file contains the time series data for a single stress gage. Note that the data provided have been post-processed and corrected as described in the manuscript. CSV file names correspond to the gage number, as mapped in Figure 1 of the manuscript. Column descriptions are provided in the table below.

| Column | Description |
|--------|-------------|
| `Epoch` | Timestamp of observation |
| `p` | Principal stress (kPa) |
| `q` | Secondary stress (kPa) |
| `theta` | Angle of principal stress (radians) |
| `Tice` | Temperature of ice measured by gage thermistor (deg C) |
| `Sensor_Name` | Sensor name referred to in manuscript |
