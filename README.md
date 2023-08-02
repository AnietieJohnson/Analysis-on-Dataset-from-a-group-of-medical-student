# TASK 1
## Introduction
Pivot tables are dynamic data analysis tools that unravel insights from complex datasets. They empower users to make informed decisions by transforming raw data into actionable patterns and trends, benefiting analysts, researchers, and decision-makers across industries. In week 2, my first class focused on how to create and understand pivot tables. The task at the end of the class was to work with a Medical student dataset with column headings: Student ID, Age, Gender, Height, Weight, Blood Type, BMI, Temperature, Heart Rate, Blood Pressure, Cholesterol, Diabetes, Smoking. The data set was filled with Blanks (empty cells within the dataset), so I filled appropriate data in by highlighting the column From the **_Home tab_**, then I clicked the small arrow beside _find & select_, I selected _Go to Special_ , selected _Blanks_, then Okay, I filled first cell highlighted with the value, then populated for the rest, I did same for each column in the Dataset.
## Task
Using the Medical Students Data, create Pivot Tables displaying the following:
- Average values for the following for Male and Females (Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol)
- Average Height and Weight for both Genders (in 2 decimal places)
- Number of students across the different Blood Groups
- Number of Students who smoke and those who don’t
- Number of Students who have diabetes and those who don’t
## Concept Demonstrated
1. Key features of Pivot tables
2. Using pivot tables
## Raw Datasets
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/raw%20medical%20data%20set.png)
## Dataset After Cleaning
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Medical%20data%20set%20after%20cleaning.png)
## Task Solutions
For the first question, I created the pivot table by Selecting the data range, Then from the **_Insert tab_** I chose _PivotTable_ and set it to new worksheet. For _Rows Field_ I selected gender and for _Values Field_ I selected (Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol), I then set the Value field setting to average for each of the parameters in the Value field. In the screenshot below, the pivot table representing this is the very first pivot table.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Average%20values%20per%20gender.png)
The second question Average Height and Weight for both Genders (in 2 decimal places), was done by creating pivot table by Selecting the data range, Then from the **_Insert tab_** I chose _PivotTable_, this time I used existing worksheet. I referenced the worksheet I had used for the first question. For _Rows Field_ I selected gender and for _Values Field_ I selected ( Height and Weight), I then set the Value field setting to average for each of the parameters in the Value field, after which I formatted the values for each gender to two decimal place. In the screenshot below, the pivot table representing this is the Second pivot table to the left as highlighted by cell box.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Average%20Height%20and%20weight%20per%20gender.png)
For question 3, Number of students across the different Blood Groups, I created the pivot table by Selecting the data range, Then from the **_Insert tab_** I chose _PivotTable_ and set it to Existing worksheet, still referencing the same report sheet. For _Rows Field_ I selected Bloodgroup and for _Values Field_ I selected Bloodgroup as well, I then set the Value field setting to Count, so as to count the number of student that falls under each differing bloodgroup. In the screenshot below, the pivot table representing this is the third pivot table to the left as highlighted by cell box.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Number%20of%20student%20per%20Blood%20type.png)
For  Number of Students who smoke and those who don’t, I created the pivot table by Selecting the data range, Then from the **_Insert tab_** I chose _PivotTable_ and set it to Existing worksheet, still referencing the same report sheet. For _Rows Field_ I selected Smoking and for _Values Field_ I selected Smoking as well, I then set the Value field setting to Count, so as to count the number of student that have yes for smoking and those with No for smoking. In the screenshot below, the pivot table representing this is the second pivot table to the right as highlighted by cell box.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Number%20of%20student%20that%20smoke%20and%20those%20that%20dont.png)
For Number of Students who have diabetes and those who don’t, I created the pivot table by Selecting the data range, Then from the **_Insert tab_** I chose _PivotTable_ and set it to Existing worksheet, still referencing the same report sheet. For _Rows Field_ I selected Diabetes and for _Values Field_ I selected Diabete as well, I then set the Value field setting to Count, so as to count the number of student that have yes for diabetes and those with No for diabetes. In the screenshot below, the pivot table representing this is the third pivot table to the right as highlighted by cell box.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Number%20of%20student%20with%20diabetes%20and%20those%20without.png)

# TASK 2
## Introduction
Data visualization is the art of representing complex information visually. By translating raw data into intuitive charts, graphs, and diagrams, it enhances understanding, reveals patterns, and communicates insights effectively. From business analytics to scientific research, data visualization is a powerful tool for informed decision-making and impactful storytelling. My second class detailed on data visualization and good practices when it comes to choosing charts. 
## Task
- Visualize the insights gotten from the Pivot Tables created in TASK 2 using the ‘Medical Students’ Data
## Concept Demonstrated
1. Importance of Data Visualization
2. Design Principles
## Dataset Used
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Medical%20data%20set%20after%20cleaning.png)
## Task Solution
**READING FROM LEFT TO RIGHT on the report containing the visuals**
Dashboard
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Dash%20board%20for%20visuals.png)
The first pivot table shows Average values of Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol Per Gender. I created the chart using **_pivot table analyze Tab_** on the report sheet, I clicked on _Pivot chart_ and chose _Column chart_ because it gave a better representation to my data. I removed the fields on the chart that were not giving meaning to my visuals from _chart element_. Then I used Format chat area to give diferring color shades toeach of my chart bars. This helps to highlight that the bars represent different information connected to the gender. I also used text box to write a suitable title and insight for the visual. The Horizotal axis label shows gender and my legend shows the parameters being described.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Average%20of%20vitals%20taken%20across%20gender.png)
The second pivot table shows Average Height and Weight for both Genders, I created the chart using **_pivot table analyze Tab_** on the report sheet, I clicked on _Pivot chart_ and chose _Column chart_ because it gave a better representation to my data. I removed the fields on the chart that were not giving meaning to my visuals from _chart element_. Then I used Format chat area to give diferring color shades to each of my chart bars. This helps to highlight that the bars represent different information connected to the gender. I also used text box to write a suitable title and insight for the visual. The Horizotal axis label shows gender and my legend shows the parameters being described.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Average%20height%20and%20weight%20for%20both%20gender.png)
To create a visual for Number of students across the different Blood Groups, I created the chart using **_pivot table analyze Tab_** on the report sheet, I clicked on _Pivot chart_ and chose _Bar chart_ because it gave a better representation to my data. I removed the fields on the chart that were not giving meaning to my visuals from _chart element_. Then I used Format chat area to give diferring color shades to each of my chart bars with the highest number, showing the blood group with highest number of student. I also used text box to write a suitable title and insight for the visual. The Verical axis label shows the different blood groups.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/Number%20of%20student%20per%20blood%20type%20visuals.png)
To create a visual for Number of Students who smoke and those who don’t, I created the chart using **_pivot table analyze Tab_** on the report sheet, I clicked on _Pivot chart_ and chose _Pie chart_ because it gave a better representation to my data. I removed the fields on the chart that were not giving meaning to my visuals from _chart element_. Then I used Format chat area to give diferring color shades to each portion of my chart, showing the Number of dtudent with "yes" and number with "no" on Smoking. I also used text box to write a suitable title and insight for the visual.
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/student%20that%20smoke%20and%20those%20that%20don't%20visuals.png)
To create a visual for Number of Students who have diabetes and those who don’t, I created the chart using **_pivot table analyze Tab_** on the report sheet, I clicked on _Pivot chart_ and chose _Pie chart_ because it gave a better representation to my data. I removed the fields on the chart that were not giving meaning to my visuals from _chart element_. Then I used Format chat area to give diferring color shades to each portion of my chart, showing the Number of dtudent with "yes" and number with "no" on Diabetes. I also used text box to write a suitable title and insight for the visual. 
![](https://github.com/AnietieJohnson/Week2-Excel-task/blob/main/visuals%20for%20student%20with%20diabetes%20and%20without.png)
## Conclusion
Mastering data visualization has empowered me to transform intricate data into compelling narratives. Through engaging charts and graphics, insights become accessible, fostering better decision-making and communication. The journey from raw data to impactful visualization has helped me unlock new dimensions of my understanding of Data analysis. 🙂
