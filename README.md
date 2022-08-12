# Janus space mission 

The Janus satellite provides information that supports ground exploration missions on Mars. 

# Short description of the example dataset. 

The dataset are in the file SatelliteDataSet.csv

- power: power consumption measurements
- sa: angle of Janus solar panels' normal
- sx: solar angle of the X axis of satellite
- sy: solar angle of the Y axis of satellite
- sz: solar angle of the Z axis of satellite
- sunmars_km: the distance in kilometers between the Sun and Mars
- earthmars_km: the distance in kilometers between the Earth and Mars
- sunmarsearthangle_deg: Sun-Mars-Earth angle in degrees
- solarconstantmars: solar constant at Mars in W/m2W/m2
- eclipseduration_min: total durations of all eclipses in the day, in minutes
- occultationduration_min: total durations of all occultations in the day, in minutes
- flagcomms: TRUE if any communication device was used, else FALSE.
- the remaining of columns are spacecraft pointing events (Flight Dynamics TimeLine). They are pointing and action commands that can impact the attitude of the satellite, thus they also may impact the solar aspect angles of the orbiter and/or the switch ON/OFF of some instrumentation.
