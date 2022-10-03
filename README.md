# 2022_WECJ_Paper_Simulation-Based-Evaluation-of-CI_Open-Data
Open data on charging behavior at public charging stations. Publication: Simulation-based Assessment of Charging Concepts: The Park-and-Ride Case. https://doi.org/10.3390/wevj13080151 

The data provided is part of the Jorunal publication "Simulation-Based Evaluation of Charging Infrastructure Concepts: The Park and Ride Case"   https://doi.org/10.3390/wevj13080151

The data reflect the probability distribution of the amount of energy demanded by electric vehicles at public charging stations for a defined connection duration. The data is based on approximately 800,000 charging events at 640 public AC and DC charging stations in the years 2020 and 2021 in the urban area of Munich. The connection duration is plotted on the x-axis in 15-minute increments and the amount of energy transferred is plotted on the y-axis in 1 kWh increments. Thus, for a considered connection duration of 24 hours or an energy amount of 100 kWh, there are 960 cells in the area. The color of each cell indicates the probability of how often the charging event occurred with the corresponding connection duration and energy quantity. White means that the combination of connection time and amount of energy transferred did not occur in any CE. According to the color spectrum used, the probability increases from blue to red.  For better understanding, interpretation examples of the probability matrix are given below. With a connection time of 0 to 15 minutes, the probability that 0 to 1 kWh of energy has been transmitted is very high for both the AC and DC distribution. The first cell at the bottom left is therefore colored red in both diagrams. In contrast, the probability of transferring between 99 and 100 kWh of energy in these 15 minutes is 0 in both cases, since this is technically impossible due to the available charging power of the CPs used. It should be noted that the nominal charging power of the AC charging points used is 22 kW and for the DC charging points is 50 kW. In each case, this corresponds to the first linear range from the left for the AC and DC charging events. The formation of the additional linear ranges results from reduced vehicle-specific charging power that occurred primarily for AC charging events.

X-axis
- Connection duration in hours
- Interval values in 0.25 h steps from 0 to 0.25 h .... 23.75 to 24.00 h

Y-axis
- Amount of energy transmitted in kWh
- Interval values in 1 kWh steps from 0 to 1 kWh .... 99 to 100 kWh
