# Transport & Mobility

GTFS/GTFS-RT feeds, rail and bus APIs, traffic sensor data, and cycling infrastructure data.

---

### Transport Infrastructure Ireland (TII) Open Data Portal
- **URL:** http://data.tii.ie/
- **Coverage:** ROI
- **Type:** Portal
- **Theme:** Transport
- **Licence:** Verify at source
- **Format:** CSV, XML, web services
- **Access notes:** Also operates live TII Traffic site (tiitraffic.ie) with travel bulletins and motorway camera feeds
- **Status:** active
- **Description:** Range of datasets from TII covering national road infrastructure, traffic counts, and associated services.

---

### Transport For Ireland GTFS
- **URL:** https://www.transportforireland.ie/transitData/PT_Data.html
- **Coverage:** ROI
- **Type:** Dataset
- **Theme:** Transport
- **Licence:** Verify at source (NTA terms)
- **Format:** GTFS
- **Access notes:** Static GTFS feeds for Irish Rail, Bus Eireann, Dublin Bus, and Luas
- **Status:** active
- **Description:** General Transit Feed Specification data for Ireland's main public transport operators, published by the National Transport Authority.

---

### Irish Rail Realtime API
- **URL:** http://api.irishrail.ie/realtime/
- **Coverage:** ROI
- **Type:** API
- **Theme:** Transport
- **Licence:** Public-use terms; confirm reuse terms per endpoint documentation
- **Format:** XML
- **Access notes:** Provides current train locations from central signalling and scheduled times from local signalling
- **Status:** active
- **Description:** Realtime train movement and timing data from Iarnrod Eireann's signalling systems.

---

### Dublin Bus GTFS-R Realtime API
- **URL:** https://developer.nationaltransport.ie/api-details#api=gtfsr&operation=gtfsr-v2
- **Coverage:** Local (Dublin)
- **Type:** API
- **Theme:** Transport
- **Licence:** NTA Developer terms
- **Format:** GTFS-Realtime (Protocol Buffers)
- **Access notes:** Replaced deprecated RTPI API (September 2020); provides realtime bus information, timetables, and stops
- **Status:** active
- **Description:** GTFS-Realtime standard API for Dublin Bus providing vehicle positions, trip updates, and service alerts.

---

### Luas Forecasting API
- **URL:** http://luasforecasts.rpa.ie/analysis/view.aspx
- **Coverage:** Local (Dublin)
- **Type:** API
- **Theme:** Transport
- **Licence:** Unclear
- **Format:** XML
- **Access notes:** Near-realtime estimated arrival times for Red and Green Line stops
- **Status:** active
- **Description:** Tram arrival forecasting API for Dublin's Luas light rail system.

---

### TII National Roads Weather Station Data
- **URL:** https://data.gov.ie/dataset/national-roads-weather-station-data
- **Coverage:** ROI
- **Type:** Dataset
- **Theme:** Transport / Environment
- **Licence:** Irish PSI General Licence (via Data.gov.ie)
- **Format:** XML (DATEX II)
- **Access notes:** 80+ stations updated every 5 minutes; content feed at data.tii.ie/Datasets/Its/DatexII/WeatherData/Content.xml
- **Status:** active
- **Description:** Realtime feed from TII's national network of road weather stations providing air temperature, precipitation, wind, and road surface temperature.

---

### Dublin Multi-Story Car Parking Availability
- **URL:** https://data.smartdublin.ie/dataset/multi-story-car-parking-space-availability
- **Coverage:** Local (Dublin)
- **Type:** Dataset
- **Theme:** Transport
- **Licence:** Verify at source (Smart Dublin terms)
- **Format:** JSON/CSV
- **Access notes:** Updated every 5 minutes; Dublin City Council live parking spaces service
- **Status:** active
- **Description:** Realtime car park occupancy data from multi-storey car parks across Dublin city.

---

### JCDecaux Bike API (Dublinbikes)
- **URL:** https://developer.jcdecaux.com/#/opendata
- **Coverage:** Local (Dublin)
- **Type:** API
- **Theme:** Transport
- **Licence:** JCDecaux API terms
- **Format:** JSON
- **Access notes:** API key required; query for Dublin contract to get Dublinbikes station data
- **Status:** active
- **Description:** International bike-sharing API providing station availability data for the Dublinbikes scheme.

---

### Dublin City Council Traffic Cameras
- **URL:** https://www.dublincity.ie/dublintraffic/
- **Coverage:** Local (Dublin)
- **Type:** Viewer
- **Theme:** Transport
- **Licence:** Unclear
- **Format:** Image feeds (web viewer)
- **Access notes:** Offline since May 2017
- **Status:** archived
- **Description:** Central Dublin traffic camera feeds from Dublin City Council (currently offline).
