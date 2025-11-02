# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
## NAME : DHARSHAN R
## REG NO : 212224230060
# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
## CODING
```


 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```
## LINE PLOT
```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```
## OUTPUT
<img width="725" height="1088" alt="image" src="https://github.com/user-attachments/assets/8595dfbb-61db-4cd9-ad56-d10ca5e4dddc" />

## SCATTER PLOT
```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```
## OUTPUT
<img width="709" height="1092" alt="image" src="https://github.com/user-attachments/assets/5c46f49a-8162-4ea2-a68d-f88e4cda144e" />

## PIE CHART
```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

## OUTPUT
<img width="569" height="1033" alt="image" src="https://github.com/user-attachments/assets/ac3d5a0d-8c75-4d76-9cb1-f772abcbf33d" />

## AREA CHART
```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```
## OUTPUT
<img width="934" height="803" alt="image" src="https://github.com/user-attachments/assets/dcce2cff-d219-4ea3-8acc-d3d3a52afbe9" />

## BAR CHART
```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['red', 'green'] 
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```

## OUTPUT
<img width="792" height="843" alt="image" src="https://github.com/user-attachments/assets/879b4dc2-d5aa-4069-8a53-1b6c4b4d79ce" />

## HISTOGRAM
```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

## OUTPUT
<img width="778" height="631" alt="image" src="https://github.com/user-attachments/assets/071b9efd-7336-4ae3-aa94-c4dd6325ec5a" />

## BOXPLOT
```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
 ```
## OUTPUT
<img width="802" height="552" alt="image" src="https://github.com/user-attachments/assets/1e80e1fe-41a1-47dc-b50a-2510a5b001e4" />


```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
 ```
## OUTPUT
<img width="820" height="755" alt="image" src="https://github.com/user-attachments/assets/16804e10-fdc2-4f9d-9d6b-3c05668e6ae7" />





# Result:
    Thus, all the data visualization techniques of matplotlib has been implemented.
