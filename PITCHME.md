## Python Visualization Workshop


Northwestern IT Research Computing Services  
July 9, 2018  

Jim Griffin

---
## Outline

* Intro Slides
  * matplotlib organization
  * plot anatomy
  * types of plots  
* Simple examples
* Styling plot elements  
* Plotting with **Pandas** dataframes  
* Pretty plots (**Seaborn**, colorpalettes)  

---

## Matplotlib.pyplot Objects
  * Figure  
  * Axes  
<img src="Images/plotparts.png" style="max-height: 400px;"/>

---

### Preferred (Object-oriented) approach:

  1. Create figure and axis objects
  2. Use figure and axis methods to modify visual elements

---

### Example matplotlib syntax

```python
  import matplotlib.pyplot as plt

  fig, ax = plt.subplots()

  ax.plot(x,y, ***kwargs)
  ax.set_xlabel('x label')

  fig.savefig('path/to/file.png')
```
@[1](Matplotlib import statement)
@[3](Create figure and axis objects)
@[5](Axes objects have methods for most common plot types</br>(i.e. line, scatter, bar, pie))
@[6](Axes methods also control labels, titles, limits, tick properties)
@[8](Figure methods control axes layout and saving)
---

#### Detailed plot anatomy

<img src="Images/anatomy1.png" style="max-height: 550px;"/>

---

### Common plot types

add something

---
##### Stack Overflow Is Better At Programming Than Us

The most valuable thing you can learn in this class is what things are called and how they are organized so that you can google:  
 **"site:stackoverflow.com matplotlib THING"**


---
### Additional Resources:

* [Tufte, The Visual Display of Quantitative Information](https://github.com/yowenter/books/blob/master/Design/Edward%20R%20Tufte%20-The%20Visual%20Display%20of%20Quantitative%20Information.pdf)
* [NUIT Python Workshops](https://github.com/nuitrcs/pythonworkshops)
* [Python graph gallery](https://python-graph-gallery.com/)
