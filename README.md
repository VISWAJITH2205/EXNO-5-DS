# NAME : VISWAJITH LALITHRAM R.V
# REG.NO : 212224240187

---

# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
  __________________________________________________

---

# Aim:
  ___
  
  To Perform Data Visualization using matplot python library for the given datas.

---

# EXPLANATION:
  ___________
  
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

---

# Algorithm:
  _________
  
## STEP 1:

Include the necessary Library.

## STEP 2:

Read the given Data.

## STEP 3:

Apply data visualization techniques to identify the patterns of the data.

## STEP 4:

Apply the various data visualization tools wherever necessary.

## STEP 5:

Include Necessary parameters in each functions.

---

# Coding and Output:
  _________________


```
# NAME : VISWAJITH LALITHRAM R.V
# REG.NO : 212224240187

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

## LINE PLOT :

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

<img width="576" height="262" alt="1" src="https://github.com/user-attachments/assets/511a1cfa-4de7-4564-aee2-dbb4cdb00bf1" />

<img width="541" height="808" alt="2" src="https://github.com/user-attachments/assets/35b4484c-926e-4510-ba34-da303db771f8" />

## SCATTER PLOT :

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

<img width="517" height="241" alt="3" src="https://github.com/user-attachments/assets/ec9a01b9-7c71-4bce-bed1-54e715a329c3" />

<img width="522" height="811" alt="4" src="https://github.com/user-attachments/assets/90ceb92c-29ad-4f7f-98a4-b317966955dc" />

## PIE CHART :

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

<img width="910" height="227" alt="5" src="https://github.com/user-attachments/assets/dd7ebdea-77d9-41f1-ada9-839e8c24695b" />

<img width="915" height="778" alt="6" src="https://github.com/user-attachments/assets/0a732913-7623-43ae-b0e4-bd9ba525b8a3" />

## AREA CHART :

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

<img width="542" height="597" alt="7" src="https://github.com/user-attachments/assets/4a559a49-c8a8-410e-b145-bbc4b2188633" />

## BAR CHART :

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

<img width="545" height="627" alt="8" src="https://github.com/user-attachments/assets/1fd4e28d-a0a2-4583-9525-47b65e1c9082" />

## HISTOGRAM :

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='PINK', alpha=0.5)
plt.show()
```

<img width="516" height="477" alt="9" src="https://github.com/user-attachments/assets/8a6af87c-d1b6-4f9c-8e23-c9eb7b25ec2d" />

## BOX PLOT :

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="531" height="411" alt="10" src="https://github.com/user-attachments/assets/d4768893-6138-4391-a289-6d0dc667a848" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="542" height="565" alt="11" src="https://github.com/user-attachments/assets/07fa6194-f28a-4242-98a0-f8d62d1f57fb" />

---

# Result:
  ______

  Thus, all the data visualization techniques of matplotlib has been implemented
