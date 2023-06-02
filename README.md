# Janus Space Mission Dataset 

The Janus satellite provides information that supports ground exploration missions on Mars.

A sample of the Janus space mission data can be found in the file SatelliteDataSet.csv, with the following columns:

- ut_ms: timestamp.
- power: power consumption measurements.
- sa: angle of Janus' solar panels normal.
- sx: solar angle of the X axis of the satellite.
- sy: solar angle of the Y axis of the satellite.
- sz: solar angle of the Z axis of the satellite.
- sunmars_km: the distance in kilometers between the Sun and Mars.
- earthmars_km: the distance in kilometers between the Earth and Mars.
- sunmarsearthangle_deg: Sun-Mars-Earth angle in degrees.
- solarconstantmars: solar constant at Mars in W/m2W/m2.
- eclipseduration_min: total duration of all eclipses in the day, in minutes.
- occultationduration_min: total duration of all occultations in the day, in minutes.
- flagcomms: TRUE if any communication device was used, else FALSE.

The remaining columns are spacecraft pointing events (Flight Dynamics TimeLine). They are pointing and action commands that can impact the attitude of the satellite, thus they also may impact the solar aspect angles of the orbiter and/or the switch ON/OFF of some instrumentation.
