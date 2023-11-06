#Cleantech-Solar
This repository contains Python code to generate a graph illustrating the performance evolution of a photovoltaic (PV) plant over time. The graph includes the following features:

30-day Moving Average Line: The red line on the graph represents the 30-day moving average of the plant's Performance Ratio (PR), showing trends over time.

**Scatter Points:** Scatter points depict the PR value of each day, with colors indicating the level of daily irradiation (GHI).

**Budget Line:** The dark green line represents the dynamically calculated budget line. The budget values decrease by 0.8% each year from the start date.

**Color-Coded Points:** Scatter points are color-coded based on daily GHI values:

Navy blue: GHI < 2
Light blue: 2 <= GHI < 4
Orange: 4 <= GHI < 6
Brown: GHI >= 6
Average PR: The graph displays the average PR for the last 7, 30, 60, and 90 days.

##Getting Started
**Dataset:** The provided dataset consists of three columns: Date, PR (Performance Ratio), and GHI (Irradiation).

**Dependencies:** Ensure you have the necessary Python libraries installed using the command:
   ```bash
pip install pandas matplotlib numpy
```
**Code:** The Python code in the repository generates the graph based on the dataset and instructions.

**Customization:** Adjust the code to match your dataset and specific requirements.

##Usage
Clone this repository to your local machine.

Place the dataset (Assignment_Dataset.xlsx) in the same directory as the code.

Run the Python script using a Python interpreter.

The generated graph will be displayed, illustrating the performance evolution of the PV plant.

##Notes
The code dynamically calculates the budget line values based on the provided formula and dataset.

The graph may not exactly match the provided example due to slight changes in the data.
