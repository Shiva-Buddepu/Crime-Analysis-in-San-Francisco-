#  Crime Analysis in San Francisco  
A comprehensive Exploratory Data Analysis (EDA) of crime incidents in San Francisco using the dataset **Police_Department_Incidents_Previous_Year_2016.csv**.  
This project visualizes crime trends across categories, time, locations, districts, and geographical hotspots.

---

##  Project Overview  
This project analyzes crime data from San Francisco for the year 2016. It focuses on identifying crime patterns, understanding the distribution of incidents across time and regions, and visualizing hotspots using geospatial techniques.

---

##  Dataset  
**Filename:** `Police_Department_Incidents_Previous_Year_2016.csv`  
**Columns Included:**

- `IncidntNum`
- `Category`
- `Descript`
- `DayOfWeek`
- `Date`
- `Time`
- `PdDistrict`
- `Resolution`
- `Address`
- `X`, `Y` (Coordinates)
- `Location`
- `PdId`

---

##  Steps Performed

### 1. Importing Required Libraries  
Used Python libraries such as:
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Folium  
- Squarify  

---

### 2. Loading and Inspecting the Dataset  
- Read the CSV file  
- Checked shape, data types  
- Displayed first few rows  

---

### 3. Checking for Missing Values  
- Verified null values  
- Performed cleaning if required  

---

### 4. Exploratory Data Analysis

#### ✔ Different Categories of Crime  
- Count of each crime category  
- Visualized using bar plots  

#### ✔ Treemap of Crime Categories  
- Used `squarify` to plot crime distribution  

#### ✔ Crime Description Analysis  
- Frequency of crime descriptions  

#### ✔ Regions with High Crime Counts  
- District-wise crime distribution  

#### ✔ Top 15 Crime-Prone Addresses  
- Count of crimes by address  

#### ✔ Crimes by Day of Week  
- Inspected which days recorded most crimes  

#### ✔ Crimes by Month  
- Extracted month from date  
- Visualized monthly crime trends  

#### ✔ Crime Occurrence by Time  
- Hourly distribution of crimes  

#### ✔ District vs Category  
- Countplot showing crime type by police district  

---

## 5. Geospatial Analysis

###  Geographical Visualization  
- Used coordinates (`X`, `Y`) to plot incident points on a map  
- Utilized Folium for interactive mapping  

###  Crime Density Map  
- Kernel Density Estimation (KDE)  
- Heatmap of crime hotspots in San Francisco  

---
