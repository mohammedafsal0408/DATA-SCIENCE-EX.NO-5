# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

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
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
marks = [13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student Name')
plt.show()

student = ['A','B','C','D']
attendence = [90,85,73,88]
plt.plot(student,attendence)
plt.xlabel('Attendence')
plt.ylabel('student Name')
plt.show()
```
<img width="758" height="475" alt="image" src="https://github.com/user-attachments/assets/63bc726e-5920-4053-afc4-b93c2c16b615" />
<img width="734" height="487" alt="image" src="https://github.com/user-attachments/assets/a6a51571-5b72-4e83-8ba3-78785eebe753" />

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

<img width="734" height="470" alt="image" src="https://github.com/user-attachments/assets/1ddbb3be-117f-4ccd-9656-ade5f845bd3c" />
<img width="772" height="511" alt="image" src="https://github.com/user-attachments/assets/b270baa0-849a-4b60-ba06-bc7bc4ad31f8" />

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
<img width="661" height="464" alt="image" src="https://github.com/user-attachments/assets/cde93094-f1a7-4388-8cb6-a3d800d878cf" />
<img width="636" height="472" alt="image" src="https://github.com/user-attachments/assets/d266d88e-c373-40ca-996a-a208f057672a" />

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
<img width="743" height="456" alt="image" src="https://github.com/user-attachments/assets/f50393dc-c3cb-465c-a259-01c020f84ddb" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('bar chart')
plt.show()
```
<img width="756" height="500" alt="image" src="https://github.com/user-attachments/assets/8f2d3d7d-1800-4522-affb-e82abd4ff886" />

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
<img width="652" height="457" alt="image" src="https://github.com/user-attachments/assets/4feb631a-4a86-4a48-98dc-2b0c4aa81515" />

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
<img width="794" height="392" alt="image" src="https://github.com/user-attachments/assets/49828589-058f-4d7f-a83f-8a2247f898f0" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="847" height="543" alt="image" src="https://github.com/user-attachments/assets/15678416-bd97-41e8-b508-564259481006" />


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
