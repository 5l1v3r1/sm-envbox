# SM-EnvBox (v. alpha 2)

ESP32 based mini enviromental monitoring station prototype.
It can analyze a wide range of environmental data in order to determine possible environmental threats and health hazards and perform meteorological analysis and seismic surveys.
It has an LCD color display and it's USB type-C powered.
The monitoring data and analysis details could be shown directly on the integrated display, or it could be connected to a PC through a wired or wifi connection or to Android devices using wifi connection.

The included sensors (and related features) vary according the version.


###### PLATINUM
- Humidity, temperature and atmospheric pressure sensor (Bosch *BME280*);
- Lightning storms sensor (AMS *AS3935*);
- Dust\particulate sensor （Shinyei *PPD42NS*）;
- Atmospheric composition analysis through a custom array of gas sensors (Hanwei *MQ-4*, *MQ-8*, *MQ-9*, *MQ-131*, *MQ-135*, *ME2-O2*);
- Detector for ionizing radiations *alpha*, *beta* and *gamma* (Teviso *AL53*);
- Electromagnetic sensor (Honeywell *HMC5883L*);
- Light sensor (PIN diode);
- Acoustic sensor (Maxim *GY-MAX4466*);
- Inertial sensor (InvenSense *MPU-6050*);

###### PRO
- Humidity, temperature and atmospheric pressure sensor (Bosch *BME280*);
- Lightning storms sensor (AMS *AS3935*);
- Dust\particulate sensor （Shinyei *PPD42NS*）;
- Atmospheric composition analysis through a custom array of gas sensors (Hanwei *MQ-4*, *MQ-8*, *MQ-9*, *MQ-135*);
- Detector for ionizing radiations *beta* and *gamma* (custom PIN diodes solid state sensor);
- Electromagnetic sensor (Honeywell *HMC5883L*);
- Light sensor (PIN diode);
- Acoustic sensor (Maxim *GY-MAX4466*);
- Inertial sensor (InvenSense *MPU-6050*);

###### BASIC
- Humidity, temperature and atmospheric pressure sensor (Bosch *BME280*);
- Dust\particulate sensor （Shinyei *PPD42NS*）;
- Atmospheric composition analysis through a custom array of gas sensors (Hanwei *MQ-4*, *MQ-9*, *MQ-135*);
- Detector for ionizing radiations *beta* and *gamma* (custom PIN diodes solid state sensor);
- Electromagnetic sensor (Honeywell *HMC5883L*);
- Light sensor (PIN diode);
- Acoustic sensor (Maxim *GY-MAX4466*);
- Inertial sensor (InvenSense *MPU-6050*);


This project is licensed under Creative Commons, CC BY-NC-ND 3.0, if you need a differend kind of license for commercial projects, contact me.
The full open material will be released during the public beta stage (unless change of plan). 