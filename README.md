# Camper_HMI
Node code for camper HMI, DCS and CANBUS networking

The Nodes that are needed are:

 - Data logger
    - used to log data to a SD for trending on the HMI
    * also could be used as a Web server interface (Future plans)  

- HMI (Connects to the TSC relays messages from the CANBUS to the displays and vise versa)
    - used to interface with the HMI touch screen
    - has a atmospheric sensor to feed into the heating control

- Battery Monitor
    - used to measure battery voltage
    - measure current in and out of the battery
    - measure current to each circuit
    - totallise the energy for each circuit

 - Heating controller
    - interfaces the CAN bus with the heater 
 
 - IR blaster (also has PIR for the WC and atmospheric seonsor)
    - used to 
 
 - Tank level monitor (Also include external atmospheric sensor)
     - used to measure the fresh and brown water tank levels
     - used to measure the external atmospheric pressure, temperature, humidity 
 
 - Lighting module
     - used to controll the lighting in the camper
 
  - bed side control
     - used as a low level HMI for limited control of
     - lights
     - heating 
