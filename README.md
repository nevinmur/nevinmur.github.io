# Introduction to Data Visualization with Matplotlib 

## 1. Introduction to Matplotlib
First you create the figure
```
import matplotlib.pyplot as plt 
fig, ax = plt.subplots()
```
Then you add the temperratures
```
ax.plot(seattle_weather["MONTH"], seattle_weather["MLY-PRCP-NORMAL"])    
```
```
ax.plot(austin_weather["MONTH"], austin_weather["MLY-PRCP-NORMAL"])

```
![Capture](https://user-images.githubusercontent.com/43359238/197871742-e775dd3d-65f6-48f5-aa9e-e4b8ac81b5a5.JPG )|width=200
