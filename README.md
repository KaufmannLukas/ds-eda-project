# DS-EDA-PROJECT

This is an Explorative Data Analisation Project that was done at the Data Science Bootcamp at the Spiced Academy in September 2023.

The explored dataset contains information about housing (houses and sales) in King County, Seattle (USA).

I extracted the data via DBeaver with SQL queries, joining the existing two tables (house details and sales details).
The initial data set contains > 21.000 rows and > 20 columns.

The client/task I chose for this EDA project is called 'William Rodriguez'.

The Buyers are two persons, who want to buy two houses:
- They want to buy one house in a country/rural area, for which they want to know the best timing when to buy.
- They also want to buy a house in a city/central area, that is fast/easy to reach.
- I created additional restrictions to be able to filter the data accordingly. 

The project goal is to generate and answer hypotheses concerning the overall data, as well has providing recommendations for the client.


## EDA process

The process is documented in the EDA-file.

---

Step 0: Research Questions

- What do I want to find out?
 
    -> Generate Hypotheses 

---

Step 1: Data Understanding / Exploring

- Dataframe shape
- head, tail, columns
- dtypes
- describe
- info, etc.

---

Step 2: Data Cleaning 

- Remove unneccessary columns 
- Identifying duplicated rows/columns
- Renaming Columns
- Turn integers into date-time-objects
- Check/handle missing values
- Look for and handle possible errors

---

Step 3: Data Preparation 

- filter houses according to clients needs and wishes
- Make decisions about which houses to recommend
   to clients

---

Step 4: Feature Understanding & Relationships -
		  Data Visualisation

- Map locations
- Boxplots
- Scatterplots
- Heatmap
- Pairplots
- (Multi-)Lineplots
- Compare Top Houses 

---

Step 5: Answer questions about the data

- When is the best time to buy the country house?
- Show top three country and city houses
- Insights and recommendations for client


## Presentation

The final presentation slides are located at the presentation folder.


## Requirements

- pyenv
- python==3.11.3