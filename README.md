#               MAPLOTLIB

* Matplotlib is a graph plotting library in python which is used a visualization tool.
* This library also comes with extensions like numpy and packages like seaborn adn pandas plotting function.

##for example:

import matplotlib.pyplot as plt
import numpy as np
x = np.array([2020, 2021,2022, 2023,2024])
y1 = np.array([0,1,2,3,4])

line_style = dict(marker='v', 
                  markersize=5,
                  markerfacecolor= 'Green',
                  markeredgecolor= 'Red',
                  linestyle='solid',
                  linewidth=2,
                  color= 'Blue')

plt.plot(x, y1,**line_style)
plt.show()

This will produce a line plot with:

- Blue solid line.

- Downward-pointing green markers.

- Red marker edges.

Dont forget to check my work so you can find lots of plotting questions and more.