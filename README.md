# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: K.Sai Santhosh Reddy

*INTERN ID*: CT04DF611

*DOMAIN*: PYTHON

*DURATION*: 4 WEEKS (MAY 30TH,2025 TO JUNE 30TH,2025)

*MENTOR*: NEELA SANTOSH.

##  COVID-19 Data Visualization Task – Description

This Python project is designed to **fetch, process, and visualize COVID-19 data** for any country using real-time data from an online API. It presents a simple but informative dashboard using **matplotlib**, showing how the pandemic unfolded over time. Here's a breakdown of what the code does:

##  Tools Used:

* **`requests`** – To fetch data from the internet.
* **`matplotlib.pyplot`** – To plot graphs.
* **`datetime`** and **`matplotlib.dates`** – To handle and format date-based data.

##  What the Program Does:

1. **Fetches COVID-19 historical data** from the `disease.sh` API for a user-specified country.
2. **Processes the data** to calculate:

   * Daily new cases
   * Daily new deaths
   * Cumulative totals over time
3. **Visualizes the results** using a 3-part dashboard:

   * Daily new cases graph
   * Daily new deaths graph
   * Total cumulative cases and deaths over time

##  How it Works:

* The user is prompted to enter a **country name**.
* The script then:

* Sends a request to the COVID API.
* Parses and cleans the data.
* Plots graphs using `matplotlib`, with formatted date labels and styled layout.

##  Learning Objectives:

* Use of external APIs and data fetching with `requests`
* Data cleaning and transformation
* Time-series plotting with `matplotlib`
* Handling exceptions and user input in Python

