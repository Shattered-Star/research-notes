Things needed:
- [x] methodology: **solid & very very specific**
- [x] title
- [ ] related literature
	- thoroughly study RRLs
-  unfamiliar terms
	- [ ] Water Flow Sensor
	- [ ] LoRa & LoRaWAN
- [ ] why this research
- [x] who would benefit from this
- [x] whats different

---
#### Methodology

###### Water Flow Recorder
- measure water flow using an arduino water flow sensor
	- water flow sensors we might possibly use	
		- G1/4" Water Flow Sensor
		- yf-s-01 
- the arduino board records all pulses received from the water sensor
	- arduino boards we might possibly use
		- The Launchpad
		- Arduino mini
	- possible power supplies (button batteries)
		-  CR2430 (might be changed)
- after doing it for 30 seconds, the arduino board will forward the number of pulses received from the water flow sensor along with an identifier id to the server using LoRa & LoRaWAN
###### Server
- the server will receive the count of pulses and calculate the liters of water used at that specific time of the day; then store this data
	- were gonna use python to receive the data and to manage it.
- we can do many things with this data such as:
	- calculate the expected water bill
		- probably use some api or maybe webscraping to get the price of water
	- see the trends on water consumption. for example, see at which day of the week and which hour of the day the water consumption the highest
	- check which water outlet consumes the greatest water and at what day and hour
	- create graphs

---
#### aNoNg nAiIbA Sa rEsEaRcH NiYo
- cheap and easy to use
- meant for widescale use
- data is easily available and can be managed easily

---
#### Research Title
- **Real-Time Water Consumption Monitoring** Using **Arduino and LoRaWAN**
- Development of a Low-Cost **Water Flow Measurement System** Using **Arduino and LoRa**
- **Utilizing LoRaWAN** for **Efficient Water Usage Tracking** in Residential Areas
- Design and Implementation of a **Water Flow Recorder** for **Efficient Water Management**
- Investigating **Water Consumption Patterns** Through **IoT-Enabled Water Flow Sensors**
- Development and Implementation of an **Arduino-Based Water Flow Monitoring System**
- Analysis of Household **Water Consumption Trends** **Using LoRa & LoRaWAN Technology**
- **Real-Time Water Usage Monitoring** and Billing Estimation with **Arduino and Python**
- Investigating **Water Consumption Patterns** through **IoT-Enabled Sensors**
- **Optimizing Water Usage** through **Real-Time Monitoring and Data Analysis**

- Real-Time Water Consumption Monitoring
- Arduino and LoRaWAN/LoRa
- Water Flow Measurement System
- Water Flow Recorder
- Efficient Water Management
- IoT-Enabled Water Flow Sensors
- Real-Time Water Usage Monitoring
- Optimizing Water Usage
- Real-Time Monitoring and Data Analysis

- Data Analysis and Monitoring of Water Consumption Using Arduino and LoRaWAN

----
#### Background of The Study

#### Risk Assessment

