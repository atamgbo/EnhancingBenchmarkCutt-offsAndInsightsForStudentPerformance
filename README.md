# Enhancing Benchmark Cutt-offs and Predictive Insights for Student Performance

## Introduction
This project is focused on performing comprehensive analsysi to explore the alignment between Rocketship Public Schools' internal benchmark cutt-offs and the California Assessment of Student Performance and Progress (CAASPP) proficiency levels.

## Skills 
- Advanced Excel
- Data Cleaning and Transformation: Using sorting, filtering, conditional formatting, COUNTBLANK, and COUNTA function in Excel showed some of the discrepancies with missing values and standardization. The missing values in TestScores and CAASPP_Level were replaced using descriptive statistics with mean value because the variables were normally distributed. FRPL values were standardized from ‘P’ and ‘R’ to ‘Paid’ and ‘Reduced’ respectively, and the other rows with few missing values in this field were removed because of they were few and will not have an effect on the analyis. The appropriate data types were assigned to each column. Lastly, a new table was created using data by merging data from the 3 tables using CONCATENATE, VLOOKUP, XLOOPUP functions.
- Data Analysis
- Data Visualization using interactive dashboards

## Analysis
The analysis performed in this project includes:

1. Benchmark and CAASPP (California Assessment of Student Performance and Progress) Alighnment: Examining the distribution of internal benchmark scores and CAASPP scores. Utilized Excel to perform correlation analsyis to uncover the differences between the two sets of scores.
2. Socioeconomic Analysis using FRPL(Free or Reduced Priced Lunch Status): Analyzing the relationship between student performance and their socioeconomic status using the lunch status data. This is because students were given a free, reduced price lunch based on their socioeconomic status.
3. School Analysis: Analyzing student performance by schools.
4. Teacher Analysis: Investigating the teacher performance in accordance with internal Round 3 test result (internal test before taking the CAASPP assessment) to identify notable cases and trends.

## Results
The key findings from the analysis include:

- Benchmark Alighnment: The analysis revealed variations between internal benchmark cutt-off and CAASPP proficiency levels. Notably, students performed better at the CAASPP proficiency level compared to the internal performance; almost 65% (588) of students perfrmed "Below Basic" based on the internal benchmark, and approximately 19% (172) were 'Below Basic" in the CAASPP assessment. Also, based on the internal cutt-off less than 4% (30) of students got an "Advanced" score compared to 35% (324) in the CAASPP assessment. This shows an inaccuracy in aligning internal benchmarks with CAASPP standards. 
- Correlation Analysis: The internal benchmark score and CAASPP proficiency level have a correlation coefficient of 0.59, showing that there is a moderate positive relationship between both variables. All other factors such as socioeconomic status, teachers, and schools have a correlation coefficient of less than 0.4.
- Performance Analysis by Schools: Certain schools such as Rocketship Discover exhibit higher internal performance in both ELA and Math compared to others.
- Teacher Performance Analysis: the evaluation of teachers performance in accordance with round 3 test result (Final test result before CAASPP assessment) shows a large variation between the best performing teacher and the least. Note that the least performing teachers are ELA teachers and the best performing teachers are the Math teachers. it would be recommended to consider professional development opportunities, subject-specific workshops, and collaborative learning communities that could enhance ELA teachers literacy skills and encourage ELA teachers to learn successful strategies and techniques from Math teachers.

## Future Works

- Expanded Variables: Incoperating additional variables such as student attendance and study habits to identify a stronger positive relation with the CAASPP proficiency assessment and provide insights into ways of adjusting the internal benchmark cutt-off to align with the CAASPP assessment.
- Longitudinal Analysis: Extending the analysis to encompass multiple academic years to assess the sustainability of adjusted benchmark cutt-offs.
