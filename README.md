# The Appliances Energy Prediction Dataset
The dataset for this projct is called the Appliances Energy Prediction data. The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters). The attribute information can be seen below.

# Object of the dataset
The primary purpose of the dataset is to train up model for the prediction of appliances on a building
# Attribute Information:

1. Date, time year-month-day hour:minute:second

2. Appliances, energy use in Wh

3. lights, energy use of light fixtures in the house in Wh

4. T1, Temperature in kitchen area, in Celsius

5. RH_1, Humidity in kitchen area, in %

6. T2, Temperature in living room area, in Celsius

7. RH_2, Humidity in living room area, in %

8. T3, Temperature in laundry room area

9. RH_3, Humidity in laundry room area, in %

10. T4, Temperature in office room, in Celsius

11. RH_4, Humidity in office room, in %

12. T5, Temperature in bathroom, in Celsius

13. RH_5, Humidity in bathroom, in %

14. T6, Temperature outside the building (north side), in Celsius

15. RH_6, Humidity outside the building (north side), in %

16. T7, Temperature in ironing room , in Celsius

17. RH_7, Humidity in ironing room, in %

18. T8, Temperature in teenager room 2, in Celsius

19. RH_8, Humidity in teenager room 2, in %

20. T9, Temperature in parents room, in Celsius

21. RH_9, Humidity in parents room, in %

22. To, Temperature outside (from Chievres weather station), in Celsius

23. Pressure (from Chievres weather station), in mm Hg

24. RH_out, Humidity outside (from Chievres weather station), in %

25. Wind speed (from Chievres weather station), in m/s

26. Visibility (from Chievres weather station), in km

27. Tdewpoint (from Chievres weather station), Â°C

28. rv1, Random variable 1, nondimensional

29. rv2, Random variable 2, nondimensional
