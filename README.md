# Individual Household Electric Power Consumption Dataset

## About Dataset
The dataset contains measurements of individual household electric power consumption collected through submeters placed in three distinct areas of a home.

### Dataset Updated
**February 16, 2024**

### Dataset Provided By
**data.world, Inc.**

### Authors
**Jonathan Ortiz**

---

## Data Description

### Attribute Information

1. **date**: Date in the format `dd/mm/yyyy`.
2. **time**: Time in the format `hh:mm:ss`.
3. **global_active_power**: Household global minute-averaged active power (in kilowatts).
4. **global_reactive_power**: Household global minute-averaged reactive power (in kilowatts).
5. **voltage**: Minute-averaged voltage (in volts).
6. **global_intensity**: Household global minute-averaged current intensity (in amperes).
7. **sub_metering_1**: Energy sub-metering No. 1 (in watt-hours of active energy). Corresponds to the kitchen appliances (dishwasher, oven, microwave). Note: hot plates are gas-powered.
8. **sub_metering_2**: Energy sub-metering No. 2 (in watt-hours of active energy). Corresponds to the laundry room appliances (washing machine, tumble dryer, refrigerator, and light).
9. **sub_metering_3**: Energy sub-metering No. 3 (in watt-hours of active energy). Corresponds to an electric water heater and air conditioner.

### Notes

1. The formula `(global_active_power * 1000 / 60 - sub_metering_1 - sub_metering_2 - sub_metering_3)` calculates the active energy consumed per minute (in watt-hours) by household electrical equipment not measured in sub-meterings 1, 2, and 3.
2. Approximately **1.25% of the rows** in the dataset contain missing values. Missing values are represented by the absence of a value between two consecutive semicolon (`;`) separators. For example, missing values are observed on **April 28, 2007**.

---

## Original Source

- **Georges Hébrail**  
  Senior Researcher, EDF R&D, Clamart, France  
  Email: georges.hebrail@edf.fr

- **Alice Bérard**  
  TELECOM ParisTech Master of Engineering Internship at EDF R&D, Clamart, France

