
## Description of the Dataset:

The dataset "NYC_Motor_Vehicle_Collisions_to_Person," sourced from the official website of the Massachusetts Registry of Motor Vehicles, will be utilized for this project. This dataset was selected for its relevance in the context of a worrying increase in road accidents over the past 30 years. Analyzing this data could reveal patterns that would enable the creation of algorithms or models capable of predicting crashes. Such predictive tools could significantly aid in preventing accidents and potential fatalities. By examining this data, we aim to contribute by identifying the places and times where accidents are likely to occur, thereby enhancing public safety and ensuring safer travel experiences.

The dataset comprises 72 dimensions, including Crash Number, City/Town Name, Crash Date, Crash Severity, Crash Time, Crash Year, Maximum Injury Severity Reported, Age of the Youngest Known Driver, and Age of the Oldest Known Driver, among others.


```{r}
#| label: load-dataset
#| message: false
library(here)
crash <- read.csv(here('Data','NYC_Motor_Vehicle_Collisions_to_Person.csv'))
crash|>glimpse()
```





