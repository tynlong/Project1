


### Overview
This technical paper explores the relationship between the SAT and ACT participation rates, as well as the scores in the years 2017-2018. The first part of the paper mainly deals with cleaning and shaping the data into an appropriate form. Next, exploratory data analysis is conducted, then visualizations are created, and further analysis and research concludes the paper.


---

### Datasets

#### Provided Data

For this project, two datasets were used

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**


Data dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|column name|int/float/object|ACT/SAT|This is an example|
|state|object|ACT|State list|
|participation_act_2017|float|ACT|The percentage the state who sat for the ACT|
|english_act_2017|float|ACT|Average English ACT scores of the partipants in the state|
|math_act_2017|float|ACT|Average math ACT scores of the partipants in the state|
|reading_act_2017|float|ACT|Average reading ACT scores of the partipants in the state|
|science_act_2017|float|ACT|Average science ACT scores of the partipants in the state|
|composite_act_2017|float|ACT|Average composite ACT scores of the partipants in the state|
|participation_sat_2017|float|ACT|The percentage the state who sat for the ACT|
|evidence-based reading and writing_sat_2017|int|ACT|Average English ACT scores of the partipants in the state|
|math_sat_2017|int|ACT|Average math ACT scores of the partipants in the state|
|total_sat_2017|int|ACT|Average reading ACT scores of the partipants in the state|
|participation_act_2018|float|ACT|The percentage the state who sat for the ACT|
|english_act_2018|float|ACT|Average English ACT scores of the partipants in the state|
|math_act_2018|float|ACT|Average math ACT scores of the partipants in the state|
|reading_act_2018|float|ACT|Average reading ACT scores of the partipants in the state|
|science_act_2018|float|ACT|Average science ACT scores of the partipants in the state|
|composite_act_2018|float|ACT|Average composite ACT scores of the partipants in the state|
|participation_sat_2018|float|ACT|The percentage the state who sat for the ACT|
|evidence-based reading and writing_sat_2018|int|ACT|Average English ACT scores of the partipants in the state|
|math_sat_2018|int|ACT|Average math ACT scores of the partipants in the state|
|total_sat_2018|int|ACT|Average reading ACT scores of the partipants in the state|

