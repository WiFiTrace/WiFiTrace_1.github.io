## WiTrace : WiFi based Contact Tracing
#### Exploiting Enterprise WiFi Networks for Contact Tracing of Infected Persons by Sensing Mobility Patterns 

**WiTrace** is a **server side ready to deploy tool** that uses Enterprise WiFi logs for contact tracing. A Server side tool means there is no need to install any battery draining apps on the mobile phones of users or periodically gather location data. 

### WiTrace Pros:
* Server Side Tool Ready to Deploy
* No need to install any battery draining apps on user mobile phones
* No active monitoring/recording needed
* No need to install sensors or perform infrastructure upgrade
* No laborious fingerprinting of existing infrastructure needed.

### WiTrace Features:

* Infected Person location visit report
* Co-locators summary report (list of co-locators with duration and location of co-location)
* Detail Co-location report of each co-locator
* Capability to identify user visits to locations with active pathogens even after patient departure from the location
* Configurable Patient visit duration parameter
* Configurable pathogen activity parameter

WiTrace is a complete solution including reporting the locations visited by an infected patient, co-location reporting of other users with the infected patient, configurable timing for pathogen active time period, configurable constraints on patient visit durations, implementation on a Enterprise WiFi Network; and extensive evaluation under many conditions including varying pathogen time window, patient visit durations.

### How is WiTrace different from other apps and tools?

Many tools and apps have been developed for contact tracing using bluetooth, GPS, and self/active recording of locations visited by users. Despite a plethora of apps, we lack a method to perform passive contact tracing without installing any apps on mobile devices or actively mapping locations.

WiTrace has the capability to perform contact tracing of patients with users co-located at the same place and same time and also to identify users who visited the location after the departure of the infected person while the pathogens spread by the infected person are still alive.



### How does WiTrace Work?


