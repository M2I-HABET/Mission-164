# Mission-164
Mission 164 Flights

## Mission
HABET Mission 164 is assigned to support the flights for the 2022 Academic High Altitude Conference (AHAC). The conference was held at Iowa State University on September 28th and 29th.

## Flight information
### HABET Flight L-164-A
Launched September 29th at approximately 0915 from Howe Hall on the campus of Iowa State University

### Spacecraft
The HABET team only provided launch services and used their Backup Emergency Recovery Transmitter (BERT). Other spacecrafts were provided by the University of Minnesota and St. Catherine's University. 

### Payloads
Coming soon

# Data Collected

## BERT Data
An anomaly caused BERT to malfunction during the flight. This prevented BERT from transmitting its data via the SatComm link. However, it appears that BERT did record data during most of the flight. There was a gap in the data collected that appears to have happened shortly after the burst. It should also be noted that the burst happened much sooner than predicted.

### Atmospheric Data
Below is the temperature data recorded. This was recorded with the onboard temperature since located on the Clue board. This board was located in a plastic case with a clear window on it. This would not accurately represent atmospheric temperature.
<img
  src="Plots/bert_temp_plot.png"
  alt="BERT Temperature"
  title="BERT Temperature Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

  Below is the Humidity Data recorded

  <img
  src="Plots/bert_humidity_plot.png"
  alt="BERT humidity"
  title="BERT Humidity Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Below is the Pressure Sensor data recorded. This was in a case that was somewhat sealed.
  <img
  src="Plots/bert_pressure_plot.png"
  alt="BERT Pressure"
  title="BERT Pressure Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Temperature data compared to the altitude as recorded by the GPS.

  <img
  src="Plots/tempalt_plot.png"
  alt="Temperature and Altitude"
  title="Temperature and Altitude Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Temperature and Humidity Plot

<img
  src="Plots/temp_humidity.png"
  alt="Temperature and Humidity"
  title="Temperature and Humidity Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

### GPS Data

The following graphs are generated from the onboard GPS Unit. This includes Lat/Lon and Altitude data. We also plot this on a map using Tilemaps in Python.

<img
  src="Plots/gps_plot_nomap.png"
  alt="GPS Plot"
  title="GPS Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

<img
  src="Plots/3D_Map_View.png"
  alt="3D GPS Plot"
  title="3D GPS Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

We have confirmed that we have valid GPS data, so we can overlay this information using Tilemaps and Open Street Maps.

<img
  src="Plots/gps_plot_map.png"
  alt="GPS Plot on Map"
  title="GPS Plot using Open Street Maps"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

The following is now zooming into the landing spot on the map
  <img
  src="Plots/gps_plot_landing.png"
  alt="GPS Plot Landing"
  title="GPS Plot of the landing"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

### IMU Data
The following plots are data from the 9-DOF IMU that is on the Adafruit Clue Board.

 <img
  src="Plots/gyro_vs_accel.png"
  alt="Gyro"
  title="Gyro vs Accel Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

   <img
  src="Plots/mag_graph.png"
  alt="Mag graph"
  title="Mag Graph"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

   <img
  src="Plots/pitch_roll_accel.png"
  alt="Pitch Roll and Accel"
  title="Pitch Roll and Accel"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

# Wrap up
Additional plots can be found in the Plots directory. You can find a KML file in the KML directory. Finally, the raw CSV file can be found in the Data folder.