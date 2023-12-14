# EDA Project - Data Analysis & Visualisation

This project is centered around exploratory data
analysis techniques and presentation of results to a client.


## The data

- The King County Housing dataset contains information about home sales in King County (USA).
- The data was accessed via DBeaver and different tables were joint via SQL.
- The initial data set contains > 21.000 rows and > 20 columns.
- I created additional restrictions to the clients characteristics to be able to filter the data accordingly. 
- The description of the column names can be found in the `column_names.md` file.


## The client

_Note: The client is made up (any resemblance to present people is absolutely random), assumptions about answers the client would give to specific questions are therefore also made up. (i.e. How do you define a rich neighborhood? -> take the zipcodes with most houses in upper 10% percentile)._

| name                | type | characteristics                                                                                                                                                                 |
| ------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| William Rodriguez   | Buyer       | 2 people, country (best timing & non-renovated) & city house (fast & central location), wants two houses                                                                        |

<br>

---
<br>


The project goal is to generate and answer hypotheses concerning the overall data, as well has providing recommendations for the client.


<br>
<br>

# EDA process

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
The requirements can be found in the 'requirements.txt' file

- pyenv
- python==3.11.3
