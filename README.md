# matplotlib-arcgis
Matplotlib's new default colormaps as a style file for ArcMap/ArcGIS
For more background and an informational talk, see [this page.](https://bids.github.io/colormap/)

This style file uses the values in https://github.com/BIDS/colormap/blob/master/colormaps.py to build color ramps for ArcGIS.

I used 15 evenly-spaced points along the 256-value colormaps, and assembled them as multi-part algorithmic color ramps using the CIE Lab algorithm.

**Magma:**

![magma](ramp_previews/magma.png)

**Inferno:**

![inferno](ramp_previews/inferno.png)

**Plasma:**

![plasma](ramp_previews/plasma.png)

**Viridis:**

![viridis](ramp_previews/viridis.png)
