# Yixiao Jiang & Shaohan Wang STAT184 Final Project

### Guiding Question
**What are the factors that might impact the spread of COVID-19 virus?**

### Two Data Sources
**Primary data**
- covid_19_data: <https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/>

**Other data sources**
- covid19_weather_data: <https://www.kaggle.com/hbfree/covid19formattedweatherjan22march24/>

### Become Acquainted with Data Sources
**1. Where did you find them?**
- We obtained covid_19_data dataset from Kaggle. <https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/>
- The covid19_weather_data dataset is also from Kaggle. <https://www.kaggle.com/hbfree/covid19formattedweatherjan22march24/>

**2. Who collected/maintains them?**
- The covid_19_data dataset was extracted from the Johns Hopkins University and it continuously updates. 
- The covid19_weather_data dataset was made with the weather data collected from World Weather Online API and was inspired by Weather Impact on COVID19 Spread by JHU. 

**3. When & Why were they originally collected?**
- This Coronavirus data is available from Jan. 22nd, 2020. It was collected to predict how and when the virus would end and provide timely condition of the spreading of the virus to the public.
- The covid19_weather_data is available from Jan. 22nd, 2020 and up to Mar. 24th, 2020 (60 days). It was collected to help understand of COVID19 and viral transmission by some important climate features.

**4. What does a case represent in each data source, and how many total cases are available?**
- For covid_19_data, the case represent an individual exposed to the virus. There are 11299 cases in total. 
- For covid19_weather_data, the case represents an individual province/state of different countries in each of the 60 days with detailed covid-19 cases information and local weather features. 

**5. What are some of the variables that you plan to use?**
- For covid_19_data, there are a total of 8 variables, and we planned to use "Country/Region",  "Deaths", and "Recovered" to discover the research question. 
- For covid19_weather_data, there are a total of 22 variables, and we planned to use "lat", "long", "temperature" and "humidity" to proceed and solve the project questions.

### Intuition Related to Research Question
**Describe preliminary observations and intuition about the research question**
- Some factors contributed to the spread of COVID-19 virus might deal with the corresponding humidity and weather temperature in those regions.
