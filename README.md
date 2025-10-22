#               MAPLOTLIB

* Matplotlib is a graph plotting library in python which is used a visualization tool.
* This library also comes with extensions like numpy and packages like seaborn adn pandas plotting function.

## for example:

import matplotlib.pyplot as plt
import numpy as np

# Sample data
import matplotlib.pyplot as plt
import numpy as np

x = np.array([2020, 2021, 2022, 2023, 2024])
y1 = np.array([0, 1, 2, 3, 4])

<<<<<<< HEAD
# Define line style properties in a dictionary
line_style = dict(
    marker='v',                 # Marker style ('v' = downward-pointing triangle)
    markersize=5,               # Size of the markers
    markerfacecolor='Green',    # Fill color of the marker
    markeredgecolor='Red',      # Border color of the marker
    linestyle='solid',          # Line style ('solid', 'dashed', 'dotted', etc.)
    linewidth=2,                # Thickness of the line
    color='Blue'                # Color of the line
)

# Plot using the defined line style
plt.plot(x, y1, **line_style)
plt.show()

This will produce a line plot with:

- Blue solid line.

- Downward-pointing green markers.

- Red marker edges.

Dont forget to check my work so you can find lots of plotting questions and more.
