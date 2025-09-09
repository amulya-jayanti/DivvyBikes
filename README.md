# Divvy Bikes Usage Analysis

This repository contains an exploratory data analysis (EDA) project on data from **Divvy**, Chicago's public bike-sharing system. The goal is to uncover patterns in bike usage, understand user behavior, and derive actionable insights for optimizing the service. 

---

### **Overview**

Divvy provides a convenient and eco-friendly transportation option for residents and visitors in Chicago. This project explores its data to understand usage trends, identify popular stations, and assess differences between various user types. The insights gained can help improve operations, plan future expansions, and enhance customer satisfaction.

---

### **Dataset**

The dataset used for this analysis includes:

* **Ride Details:** `start_time`, `end_time`, and `ride_duration`.
* **Station Information:** `start_station_name` and `end_station_name`.
* **Categorical Data:** `user_type` (subscriber or casual rider).

Station names were retained for geographical analysis, while optional data such as latitude and longitude were removed.

---

### **Analysis Goals**

The project focuses on the following key areas:

* **Temporal Patterns:** Categorizing usage into different times of day to identify peak usage periods.
    * **Rush Hour:** 7–9 AM and 3–6 PM.
    * **Night:** 9 PM–6 AM.
    * **Other:** All non-peak daytime hours.
* **Popular Stations:** Identifying the top stations for starting and ending rides.
* **User Behavior:** Analyzing average and median ride durations and comparing the usage habits of casual riders versus subscribers.
* **Monthly and Weekly Trends:** Examining how ride usage changes over the course of the year and week.

---

### **Technology Stack**

This project leverages the following tools and libraries:

* **Python:** The core programming language for the analysis.
* **Pandas:** Used for data wrangling, cleaning, and manipulation.
* **Matplotlib & Seaborn:** Employed for creating data visualizations and plots.
* **Jupyter Notebook:** Provides an interactive environment for step-by-step analysis.
* **Git:** For version control and collaborative development.

---

### **How to Use**

1.  **Clone the repository:**
    ```
    git clone [https://github.com/amulya-jayanti/DivvyBikes.git](https://github.com/amulya-jayanti/DivvyBikes.git)
    ```
2.  **Install dependencies:**
    ```
    pip install -r requirements.txt
    ```
3.  **Explore the notebooks:**
    Navigate to the `notebooks` folder to follow the analysis step-by-step and view the visualizations.

---

### **Contributing**

Contributions, suggestions, and feature enhancements are welcome. Please feel free to open a pull request or issue.

---

### **Acknowledgments**

* **Divvy Bikes** for making this public data available.
* The **City of Chicago** for their commitment to public transit innovation.
* The **Python community** for providing a rich ecosystem of open-source tools.
