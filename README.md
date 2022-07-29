# (Bird Strike Data Exploration)
## by (Ekwunife Mmesoma)

![myimage-alt-tag](https://news.cornell.edu/sites/default/files/styles/story_thumbnail_xlarge/public/2021-08/0819_birds.jpg?itok=O3XmpH6D)

## Dataset

The data contains 45,000 bird strike cases in the United States from 1990 to 2021 including species, airports, states, indicated damage, longitude, latitude, etc. The dataset can be gotten from kaggle with this link [bird strike](https://www.kaggle.com/datasets/mohammedilyasahmed/a-bird-eye-view-of-bird-strikes-version2)


### Objective
Generate at least 15 worthwhile visualizations from the univariate, bivariate and multivariate exploratory data analysis and glean meaningful information from it using the question, visualization, and observation approach.

### Data Dictionary

<table>
<tr>
<td>FEATURES</td>
<td>COLUMN DESCRIPTION</td>
</tr>
<tr>
<td>AMO</td> 
<td>International Civil Aviation Organization code for Aircraft Model</td>
</tr>  
<tr>
<td>EMA</td>
<td>Engine Make Code</td>
</tr> 
<tr>
<td>EMO</td>
<td>Engine Model Code</td>
</tr> 
 <tr>
<td>AC_CLASS</td>
<td>Type of aircraft</td>
</tr> 
<tr>
<td>AC_MASS</td>
<td>1 = 2,250 kg or less: 2 = ,2251-5700 kg: 3 = 5,701-27,000 kg: 4 = 27,001-272,000 kg: 5 = above 272,000 kg</td>
</tr> 
<tr>
<td>NUM_ENGS</td>
<td>Number of engines</td>
</tr> 
<tr>
<td>TYPE_ENG</td>
<td>Type of power A = reciprocating engine (piston): B = Turbojet: C = Turboprop: D = Turbofan: E = None (glider): F = Turboshaft (helicopter): Y = Other</td>
</tr> 
<tr>
<td>ENG_1_POS</td>
<td>Where engine # 1 is mounted on aircraft</td>
</tr> 
<tr>
<td>ENG_2_POS</td>
<td>Where engine # 2 is mounted on aircraft</td>
</tr> 
<tr>
<td>DAY</td>
<td>Day strike occurred</td>
</tr> 
<tr>
<td>YEAR</td>
<td>Year strike occurred</td>
</tr> 
<tr>
<td>TIME_HOUR</td>
<td>Hour in local time</td>
</tr> 
<tr>
<td>TIME_MIN</td>
<td>Minute in local time</td>
</tr> 
<tr>
<td>HEIGHT</td>
<td>Feet Above Ground Level</td>
</tr>
<tr>
<td>DISTANCE</td>
<td>Nautical miles from airport</td>
</tr> 
<tr>
<td>PHASE_OF_FLT</td>
<td>Phase of flight during which strike occurred</td>
</tr>
<tr>
<td>INGESTED</td>
<td>Engine ingested the bird/ animal</td>
</tr>
<tr>
<td>SKY</td>
<td>Type of cloud cover, if any</td>
</tr> 
<tr>
<td>PRECIP</td>
<td>Precipitation</td>
</tr>
<tr>
<td>SPECIES</td>
<td>Common name for bird or other wildlife</td>
</tr>
<tr>
<td>INDICATED_DAMAGE</td>
<td>Indicates whether or not aircraft was damaged</td>
</tr>
<tr>
<td>FAAREGION</td>
<td>FAA Region where airport is located</td>
</tr>    
<tr>
<td>SIZE</td>
<td>Size of bird as reported by pilot is a relative scale. Entry should reflect the perceived size as 
opposed to a scientifically determined value. If more than one species was struck, larger bird is entered.</td>
</tr>    
</table>

#### Problem Statement

As a Data Analyst working for "American Airlines", you have been asked to help the 
team with the analysis of the incident data. The dataset contains records of aircraft incidents 
caused by wild birds. Your task is to generate insights from the dataset and also recommend some
preventive measures to curb the bird strike attack on aircrafts.

#### Dataset summary

* There are 45039 rows in this dataset.

* There are 32 features (columns) in this dataset.

* The height column contains misssing values.

* There are 11 numeric variables (continuous and discrete) and 21 categorical variables.

* The data is tidy.

#### Preliminary Data Wrangling

* The missing values in the height column were filled using the mean height.

* The erroneous data types of some variables were changed to their correct datatype.

* A new variable, Season was engineered to aid the analysis.


## Summary of Findings

The univariate, bivariate and multivariate plots were all used for this analysis.

#### Plots used for the exploratory data analysis

Bar chart, Pie chart, Histogram, Adapted bar chart, Scatter plot and Facet grid.

Visuals from the exploratory data analysis showed that only 30.2% of bird strikes resulted to aircraft damage while the remaining 69.8% were just bird strikes. I discovered that small sized birds caused the most bird strikes while the medium sized birds damaged the aircrafts. The United States experienced more bird strikes in the year 2018 and 2019 but it decreased significantly in the year 2020 and that could be due to covid which reduced the traveling rate of people. Summer and fall had the most bird strikes and aircraft damage respectively while winter had the least bird strikes and aircraft damage. Bird strikes mostly occur in the day around 8-10 am but further investigation showed that it also occurs at night around 22-23 pm. 
The top three airports in the United States that had the most aircraft damage were Salt Lake City, Sacramento and Dallas/Fort Worth International airports. Mourning dove, gulls, barn swallow, european Starling, horned lark caused the most bird strikes while the bird species that caused most aircraft damage were gulls, white-tailed deer, canada goose, mourning dove and red-tailed hawk. California and Denver international airport in the United States experienced the most bird strikes.


## Key Insights for Presentation

For the presentation, I focused on the airports, state and seasons that had the most bird strikes and aircraft damages. Further analysis showed the size of species and bird species that caused the bird strikes and the time distribution across the different months that it occurred. I also included recommendations to help curb bird strike attack on aircrafts which includes putting extra precautions in place during the summer and fall period and also rescheduling flights to exclude the times (8-10 am and 22-23 pm).
