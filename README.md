# Module_6_python_api_challenge

# **WeatherPy**
---
## Module 6- Python API Challenge- Part I
### By: Zack Crowley
#### 11/7/22

### **Analysis**
---
####  Discussion of Temperature vs. Latitude Linear Regression Plots:
- For the northern hemisphere, there is a strong negative relationship between temperature and latitude. As latitude increases, the max tempature goes down. This makes perfect sense, as you travel north from the equator, max temperatures will get lower and lower. 
- For the southern hemisphere, there was a fairly strong positive relationship between temperature and latitude. Since the southern hemisphere is contains all negative latitude, as latitude increases, getting closer to the equator, max temperatures increase. This is simple an inverse of the relationship between temperature and latitude in the northern hemisphere. As you move away from the equator, max temperatures decrease. 
- Interestingly, the relationship between temperature and latitude is weaker for the southern hemishpere (r=0.60), compared to the northern hemisphere (r=-.86). This is probably due to the fact that the northern hemisphere has greater landmass than the southern hemisphere. When citipy generates the list of cities, it gathered 381 cities from the northern hemishere and 175 from the southern hemisphere. So the data was biased to the northern hemisphere and the linear regression was stronger for that analysis. If I had more time, I would have found a way to have citipy return a more balanced list of cities between the two hemispheres. 

####  Discussion of Humidity vs. Latitude Linear Regression Plots:
- For the northern hemisphere, there was a weak positive relationship humidity and latitude(r=.29). As latitude increases, going farther north away from the equator, the humidity slightly goes up.
- For the southern hemisphere, there was also a weak positive relationship humidity and latitude(r=.27). As latitude increases, the humidity slightly goes up. However, this means that as you move closer to the equator, humidity goes up, which is opposite the trend of the northern hemisphere.
- The differences in the relationship between humidity and latitude is probably attributable to the fact that the northern hemisphere is moving into the fall/winter season and the southern hemisphere is moving into the spring/summer season. The jet streams are probably switching whereby more wet air is farther north in the northern hemisphere farther from the equator and also in the southern hemispher more wet air is north but this is closer to the equator.
  
####  Discussion of Cloudiness vs. Latitude Linear Regression Plots:
- Again for the northern hemisphere, there was a weak positive relationship cloudiness and latitude(r=.22). As latitude increases, going farther north away from the equator, cloudiness slightly goes up.
- For the southern hemisphere, there was also a weak positive relationship cloudiness and latitude (r=.32). As latitude increases,  cloudiness percentage slightly goes up. However, this means that as you move closer to the equator, cloudiness goes up, which is opposite the trend of the northern hemisphere.
- Similar to humidity, the differences in the relationship between cloudiness and latitude is again likely due to the seasons being opposite in that the northern hemisphere is moving into the fall/winter season and the southern hemisphere is moving into the spring/summer season. The jet streams are probably switching whereby more clouds are farther north in the northern hemisphere, farther from the equator and also in the southern hemisphere more clouds gather in the north but this is closer to the equator.
  
####  Discussion of Wind Speed vs. Latitude Linear Regression Plots:
- The relationship betwen wind speed and latitude is the opposite of that of temperature and latitude, and very weak. For the northern hemisphere, there is a very weak positive relationship between wind speed and latitude(r=.17). As latitude increases, wind speed goes up. 
- For the southern hemisphere, there was a very weak negative relationship between temperature and latitude(r=-.22). As latitude increases, getting closer to the equator, wind speds decrease. This is simple an inverse of the relationship between wind speed and latitudein the northern hemisphere. As you move away from the equator, wind speeds increase. 
- Wind speeds are probably stronger as you move away from the equator because of the jet streams or because there is more wind where hot and cold air meet, which is generally farther north in the northern hemisphere and farther south in the southern hemisphere.
---

# VacationPy
---
## Module 6- Python API Challenge- Part II
### By: Zack Crowley
#### 11/7/22
---
- I had a very hard time with this part of the assignment, we didn't use hvplot at all in class and I could not get gmaps to work for the size/color of the cities. I used AskBCS and I worked with them for over 2 hours. 
- It was only after I got off of Zoom with them that I figured out a work around by using teh instrucions in the hvplot documentation to set up a new conda env with very specific module installs. I wanted to pass along this feedback because I don't think an assignment should be based off of a module we didn't learn at all and a lot of my classmates had very similar issues so it should probably be something that is changed in the future. The same for the Geoaphify, we only used Google places in class so that is what I used for this assignment.