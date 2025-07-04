# LLM-Based-Code-Generation-on-Energy-Dataset
## Author: 
Namya Vyas
## Exercise detail: 
It is expected to write natural language queries about the energy data, and use an LLM to generate pandas code that answers them. The code must be tested and verified for correctness.
## Dataset used: 
UCI Household Power Consumption Dataset
Link: https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption
## Groq used:
Gemma2-9b-it
## Summary of the tasks:
1. Loaded and preprocessed the dataset (df) as specified, indexed by datetime.

2. Generated and executed code (via LLM) to:
    a) Calculate the average Global_active_power for March 2007.
    b) Identify the hour with the highest power usage on Christmas 2006.
    c) Compare average Global_active_power between weekdays and weekends.
    d) Find days where total energy consumption exceeded 5 kWh.
    e) Plot the energy usage trend for the first week of January 2007.
    f) Calculate the average Voltage for each day of the first week of February 2007.
    g) Compute and display the correlation matrix between Global_active_power and the three sub-metering columns.

3. Verified execution accuracy for all tasks by validating outputs against the dataset
