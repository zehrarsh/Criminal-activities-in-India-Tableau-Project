# Criminal-activities-in-India-Tableau-Project

## Introduction
Welcome to the Criminal Activities in India Tableau project! This project aims to analyze and visualize data related to criminal activities in India using Tableau. By leveraging interactive dashboards and visualizations, we can gain insights into various aspects of crime trends, patterns, and distribution across different states and regions in India.
## Main Topics to be Covered  are-
1. Summary of  what we have analyse about CRIMINAL ACTIVITIES IN INDIA 
2. Summary of what we have analyse about MURDERS IN INDIA
3.Summary of what we have analyse about TOTAL CRIMES IN INDIA AND SOME OF THE MAIN CITIES
4. Summary of what we have analyse about KIDNAPS AND VIOLENT IN INDIA

## Analysis
1. First, take ‘crime_women_children’ file
Under this there are two files "crime_against_children_(State-UT-wise) _2019-2021.csv" and "crime_against_women_(State-UT-wise) _2019-2021.csv”.
crime_against_women_(State-UT-wise) _2019-2021.csv 
crime_against_women_(State-UT-wise) _2019-2021.csv
2. Files are cleaned by removing all null values from it by using dropna() command in python and then replacing those values with number and checking for outliers saving the cleaned values to excel
3. FIVE QUESTIONS then I have created for this file are-
a) Explain the flow of rate of crime against children and women in each state?
In this question name is dragged to rows and measure values that is rate of crime against woman and children is put on columns and through show me we have put side by side graph in it. We also dragged measure values to text to show the details and used tooltip to show information when we hover on graph. For this question we have filtered out states from states/UT. We have formatted the whole sheet with beautiful colours and graphs with two colours.
b) Explain the flow of rate of crime against children and women in each Union Territory?
In this question name is dragged to rows and measure values that is rate of crime against woman and children is put on columns and through show me we have put side by side graph in it. We also dragged measure values to text to show the details and used tooltip to show information when we hover on graph. For this question we have filtered out UT from states/UT. We have formatted the whole sheet with beautiful colours and graphs with two colours.
c)What are the total number of cases from 2019-2021 in each state for crimes with children and woman?
For this question I have dragged name in   columns and count of crimes against children and woman in each year from 2019-2021 in rows and from show me we have put them in table row format. For this question we have filtered states from states/UT. We have formatted the whole sheet by aligning them to centre and used different colours for shading the table.
d) What are the total number of cases from 2019-2021 in each union territory for crimes with women?
For this question I have dragged name in   columns and count of crimes against children and woman in each year from 2019-2021 in rows and from show me we have put them in table row format. For this question we have filtered states from states/UT. We have formatted the whole sheet by aligning them to centre and used different colours for shading the table.
e) What is the charge sheet rate in each state and union territory for women and children? Compare with the help of graph
For this question we have used context filter to show chargesheet of states and UT separately so according to the charge sheet against woman and children graph will be seen for that particular category. We have put then name in rows and chargesheet of woman and children in columns and put them in side-by-side bar graphs. 
DASHBOARD- We dragged all the sheets in dashboard in floating manner so that we can align them nicely. We have created action for rate of crime against woman and children in states and UT with their counts. Whenever we click particular state or UT from the two graphs its count of crime against both population for that particular place can be seen on right hand side along with its chargesheet details for selected state of UT.
4. Now second file is of murder cases,
Under this there are two files ‘murder_cases_(State-UT-wise)_2019-2021’ and ‘victims_of_murder_(Gender_Age_Group-wise)_2021’.
5. First, we will clean these files and remove null values, replacing with 0 and checking for outliers.
6. Now five questions for this file can be-
a) What is rate of murder in each state and UT and which one is highest in eachtell through line graph.
Putting name of all states and UT in columns and rate of murder in rows and then from mark settings we can change it to line to have a line graph. Also, by applying context filter on States/Ut we can analyse results according to our wish. From line graph highest peak tells us highest state or UT with murder.
 b)What are total number of murders in each state and UT from the year 2019-21?
Putting name in rows and year hierarchy beside it number of murders in each year can be analyse. In dashboard I have created action such that when we click the state or UT corresponding number of murders come in its right side.
c)Give an insight of charge sheet of murders in different state and UT?
Putting names in rows and chargesheet rate beside it. In dashboard to simplify we created a search bar with the help of parameter and calculated field so that over there we can search and then that state or UT’s charge sheet number will come.
d)Tell total number of adult and child victims in each state and UT.
First, we will group the names of all states and UT according to its category by creating group. Then we will put grouped names on row column and beside it we will put the names so that it can be grouped accordingly and then we will put total adult victims and total child victims along its side.
e)Give comparison between every population in terms of victims of murder in whole age group.
Creation of graphs between male, female and trans with name of states which are grouped in states and UT by creating group and in another axis whole age group are given. I created action so that in dashboard when we click any state or UT name from total counts sheet then we can see graph of every population in its right-hand side.
Dashboard- I linked both the dashboard with a navigation button in dashboard 1 to see murders preview and dragged whole sheets in dashboard 2 of murder so that we can see whole preview along with actions.
7. Now we will see through third file that is about IPC crimes
Under this there are 3 files-IPC_crimes_(City-wise)_2019-2021.csv, IPC_crimes_(State-UT-wise)_2019-2021.csv and Total_Complaints_Received_2019-2021.csv.
We will clean these files and remove null values and replace it with files without null values.
8. Now we will create five questions for this file-
a)What is the number of population victim of IPC crimes by middle of the year in each state and UT?
First, we will put states/UT in filters and apply it to context and show filter. Then dragged names to columns and midpupulation in rows and select circle graph plot from show me and showed the text of population.
b)What is the sum of IPC crimes state and UT wise from the year 2019-21?
Dragged names of state and UT in rows and sum of victims from 2019-21 beside it in text form. Create an action of filter from previous question sheet to this sheet to filter out details of the state or UT which has been selected from previous sheet.
c)Explain about charging sheet and rate of Cognizable crimes state wise?
Dragged names of states or UT to columns and rate of cognizable crimes and charging sheet in rows and from show me selected side by side bar graph. In this sheet also we created actions by selecting state name or UT name from 1St questions sheet graph of that will be filtered.
d)Now tell what is the number of populations in the middle of the year in some of the main cities along with its average number from the year 2019-21?
Dragged city names in columns and population in rows. Converted its measure from sum to average and from show me selected bar graph to show graph visual of it.
e)Explain about charging sheet and rate of these cognizable crimes city wise now which you have selected in previous questions?
Dragged city names to columns and both measure values that is rate of cognizable crimes in city and charging sheet rate in columns and from show me selected circle graph. Created actions from question 4’s sheet to this question. If we select any city from that graph of measure values of selected city will be filtered.
Dashboard- All sheets along with its actions are dragged to dashboard to see insights of IPC crimes and from previous dashboard a button is created to navigate to this dashboard. I also created one more sheet to see the type of complaints that have been issued with their numbers throughout the years with their numbers. From this dashboard we created a button so that when it is clicked, we can see the information about that also.
9.  Now comes the fourth file about violent crimes,
First the two files “kidnapping_abduction_(State-UT-wise)_2019-2021.csv” and “violent_crimes_(State-UT-wise)_2021.csv” are cleaned by removing null values in python and downloading cleaned files.
10. Now we will create five questions for this file-
a) What is the number of population victim of kidnaps by middle of the year in each state and UT?
Dragged states/UT to filter and apply it to context and show that filter. Now dragged names of states and UT to rows and Population rate at the middle of the year in the columns and converted the mark option to line and showed text of population and change the format.
b) Explain about charging sheet and rate of kidnaps state wise?
Dragged names of states and UT to rows and charging sheet rate and rate of kidnap crimes to columns and from show me selected side by side graph. Here we created action so that when we select any state or UT from previous question then the corresponding charging sheet rate and rate of crime graph will come of that selected state or UT.
c) What is the number of population victim of violent crimes by middle of the year in each state and UT?
Dragged states/UT to filter and apply it to context and show that filter. Now dragged names of states and UT to rows and Population rate at the middle of the year in the columns and converted the mark option to line and showed text of population and change the format.
d) Explain about charging sheet and rate of violent crimes state wise?
Dragged names of states and UT to rows and charging sheet rate and rate of kidnap crimes to columns and from show me selected side by side graph. Here we created action so that when we select any state or UT from previous question then the corresponding charging sheet rate and rate of crime graph will come of that selected state or UT.
e)What are the sum of population of victims of both the crimes discussed above from the year 2019-21?
Dragged names of UT and states to rows and on its side sum of crimes of kidnaps from year 2019-21 by creating hierarchy and sum of crimes from year 2019-21 of violence on its rows on its side in text form from show me and change its format.
Dashboard- Now in 4th dashboard drag all the sheets from question 1 to 4 in floating manner in specific alignment. Create a navigation button in this dashboard of whenever we click on it navigates us to question no. 5 sheet where sum of crimes of 2019-21 of kidnaps and violence will be written and created an action in that sheet to navigate to the dashboard again. We created another button to navigate to first sheet which will be starting of the presentation.

## Conclusions
It is concluded from whole project that-
1. Delhi is the most prone place to all types of crimes among all Union territories and strict rules should be applied to it and more security should be established in it.
2. Among states Uttar Pradesh is the most prone area to all the crimes and government should have strict guidelines for this place too to control such crimes.
3. We can also conclude despite of high rate of crimes these places have low charging sheets that is people are ignoring these crimes which should not be there and  everyone should take stand for it and complain about it to associated police officers so that all criminals can be put behind the bars and such crimes can be controlled.
4. Places like Sikkim and A&N islands should also have strict guidelines side by side as flow rate of crimes in these areas are also increasing.
5. It can also be concluded that in some places people are taking awareness towards such crimes and taking necessary action and filing charge sheet against them like in Andhra Pradesh, Kerala and A&N islands.
## Contact Information
For inquiries or support regarding this project, please contact Arsh Zehra at zehrarsh@gmail.com.


