# Introduction to Data Visualization with Matplotlib 
1. [Introduction to Matplotlib]
## 1. Introduction to Matplotlib
First you create the figure
```
import matplotlib.pyplot as plt 
fig, ax = plt.subplots()
```
Then you add the two axes
```
ax.plot(seattle_weather["MONTH"], seattle_weather["MLY-PRCP-NORMAL"])          
```
```
ax.plot(austin_weather["MONTH"], austin_weather["MLY-PRCP-NORMAL"])

```
<img src="https://user-images.githubusercontent.com/43359238/197881195-5e3850d5-513c-4e45-908f-373906283367.png" width="300" height="200">

Add markers and linestyle
```
ax.plot(seattle_weather["MONTH"], seattle_weather["MLY-PRCP-NORMAL"], marker="o", linestyle="--", color="r")          
```
```
ax.plot(austin_weather["MONTH"], austin_weather["MLY-PRCP-NORMAL"], marker="v", linestyle="None")

```
For reeference marker styles https://matplotlib.org/stable/api/markers_api.html
Add axes labels 
```
ax.set_xlabel("Time (months)")
ax.set_ylabel("Average temperature")
plt.show()
```
