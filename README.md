# Data Analysis Project: COVID-19 & The Impact on Human Habits

## Team Members
* Jack Griffin
* Shadee Tabasi
* Manuel Mejia
* Rizky Gamal

# Our Initial Questions
* How has wine taste & consumption behaved during COVID compared to years past?
* Are there other quantifiable factors to be considered?
* Have other recreational habits been impacted from COVID as well?

# Our Refined Questions
* How has alcohol consumption behaved during COVID compared years past?
* Have lockdowns played a part in alcohol consumption, or more broadly COVID-cases?
* Has marijuana and video-game consumption been impacted as well?

# How did we collect data?
* As we searched for data, it led to more more specific questions and interests, but was limited to the data we could find
* To find our data, we took multiple approaches:
** Internet searches
** Emailing data sources (with varying success)
** Government databases
** Existing databases on Github

# What were our data sources?
* National Institute on Alcohol Abuse and Alcoholism, Alcohol Epidemiologic Data System
* CDC, COVID Data Tracker
* Blavatnik School of Government, COVID-19 Government Response Tracker (OxCGRT)
* Ballotpedia, Partisan Composition of Governors
* Headset.io
* COVID-19 Canada

# What were some of the challenges we faced?
* Getting data 
* Getting data in a way it could be merged / combined easily
* Formatting data programmatically 
* Addressing seasonality
** For example, alcohol consumption typically increases in the Spring, which coincided with rise in COVID

# Observations & Visualizations
* **Alcohol Consumption & COVID Relationship**
  * It appears that on the aggregate, 2020 alcohol sales have generally been higher than years past, especially in the summer months.
  
![allstateslinear](https://github.com/shadeetabasi/data-analysis-project-1/blob/main/final/All_states_alcohol_consumption_by_year.png)

   * Looking at a blox pot, we see the average alcohol consumption per capita for 2020 is slightly higher than in previous years, with higher outliers.
  
![boxplot](https://github.com/shadeetabasi/data-analysis-project-1/blob/main/final/Images/yoy_box_plot.png)

   * A linear regression analysis also shows a positive correlation between cumulative number of new COVID-19 cases and per capita alcohol consumption

![covidlinearregression](https://github.com/shadeetabasi/data-analysis-project-1/blob/main/final/Images/per_capiita_vs_new_vases.png)


* **Political Influence & Lockdown Stringency Effect on Alcohol Consumption**
  * States with Republican governors have consistently added more cases than Democratic-run states.
  * Democratic states have traditionally consumed more alcohol than Republican states.
  * It does not immediately appear that COVID-19 has had a direct effect on alcohol consumption between Democratic and Republican-run states
  
![politics1](https://github.com/shadeetabasi/data-analysis-project-1/blob/main/final/Exccess%20COVID%20Cases%2C%20Republicans%20versus%20Democrats.png)
  
  * However, when measuring lockdown stringency, there does appear to be a slight positive correlation.
![politics2](https://github.com/shadeetabasi/data-analysis-project-1/blob/main/final/Images/per_capita_vs_stringency.png)

* **Cannabis Consumption & COVID Relationship**
[MANNY INSERT BULLETS & IMAGES HERE - FOLLOW ABOVE FORMAT)

* **GAMING CONSOLE SALES & COVID Relationship**
[RIZKY INSERT BULLETS & IMAGES HERE - FOLLOW ABOVE FORMAT)

* **Learnings & Limitations**
  * The legal Cannabis industry is not as robust as the alcohol or video game console industries which limited the accessibility to more diverse data such as demographics data.
  * Because of how recent the data we needed to collect was,  we were limited to data for only 13 states, missing major players such as New York, California, etc.
  * The data was different across the board so for the COVID data we had only through August 2020 but for the Cannabis data we had through November 2020 and in some instances December 2020 making observations of one relation to another lost for those months.
  
  # PLEASE FIND OUR PRESENTATION IN THE LINK BELOW:
  https://docs.google.com/presentation/d/1AmetNay4OrZXgM9kplj_kPtWHX-mjCC-y5cwNFaPOik/edit?usp=sharing



