# Create-a-Tableau-Story
Udacity DAND Project - Create a Tableau Story

**PURPOSE**

To communicate the insights and visualizations produced as a result of exploring the Titanic Dataset.


**SUMMARY:**

The dataset explored contains demographic and passenger information from a subset of the 2224 passengers and crew on board of Titanic. The man objective of visualizations produced is to show the demographics or passenger information between those passengers who survived and those who died

[INITIAL VISUALIZATION](https://public.tableau.com/views/TitanicSurvivalCount/Story1?:embed=y&:display_count=yes)

[FINAL VISUALIZATION](https://public.tableau.com/views/TitanicSurvival_Final/TitanicSurvivals_Final?:embed=y&:display_count=yes&publish=yes)

**DESIGN:**

I have based my visualizations on survival count because it is the main highlights of the Titanic tragedy and created the following charts for the initial visualizations:

1.	Survival Count per Gender
2.	Age Distribution of Titanic Passengers
3.	Survival Count per Ticket Class
4.	Survival Count Based on Embarkation Port

All visualizations have been created using Bar charting because data shown are related to counts of survivals. Also, I have converted (Survived, Fare, Parch, Passenger Id, Pclass, Sib Sp) to Dimensions since Tableau interprets these variables as measures
After receiving the feedback on the initial visualizations, I have added these calculations to improve the story telling:

- Dead --> Count of dead passengers [survived = 0]
- Alive	--> Count of alive passengers [survived = 1]
- Survival Rate % -->	Percentage of passengers who survived: Count of alive passengers / Total Count of passenger

In addition, I have created “Age Range” to address one of the comments in the feedback as below:

- Babies -->	0-1 Years
- Toddlers -->	1-3 Years
- Kids -->	3-5 Years
- Children -->	5-12 Years
- Teens	--> 12-18  Years
- Early Adults -->	18-45 Years
- Middle Adults -->	45-65 Years
- Later Adults -->	65+ Years

The final visualizations contains the following charts:

1.	Passengers Count per Gender
2.	Survival rate per Gender
3.	Survival Rate VS. Age Distribution of Titanic Passengers
4.	Survival Rate per Ticket Class
5.	Survival Rate Based on Embarkation Port

**FEEDBACK:**

Below is the feedback I received from a colleague:
•	What are the survival rates of male and female?
•	What does ‘0’ and ‘1’ mean in the axis?
•	Can you more explain your findings in these charts? What are you trying to communicate?
•	Age chart is condensed.

**RESOURCES:**

1.	https://www.kaggle.com/kabure/titanic-eda-simple-keras-model-acc-0-8575
2.	https://community.tableau.com/thread/129566
3.	http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.html
4.	https://community.tableau.com/thread/156968
5.	https://community.tableau.com/thread/149814
6.	https://github.com/bcko/Ud-DA-Tableau-Titanic/blob/master/writeup.md
7.	https://www.wattpad.com/228490886-revision-book-the-six-life-stages
8.	https://www.healthychildren.org/English/ages-stages/Pages/default.aspx
