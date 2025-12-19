# 3D_jakarta

A Python implementation to load and visualize 3D displacement velocity vectors, including their error ellipses, over Jakarta. The data were obtained from strap-down decomposition and a GNSS-based connection to the Sunda Plate Fixed Frame.

## Reference

*(Include your reference or publication here)*

## Requirements

This project depends on the following Python packages:

* `numpy`
* `pandas`
* `matplotlib`
* `contextily`
* `geopandas`
* `shapely`
* `pykrige`
* `mpl_toolkits` (for `axes_grid1.inset_locator`)

### Optional for Advanced Visualization

* `matplotlib.patches` (for `Ellipse` and `Rectangle`)
* `matplotlib.colors` (for `LinearSegmentedColormap`)
* `matplotlib.ticker` (for `mticker`)

## Data

To generate the displacement velocity vectors including error ellipses, you need the following dataset:

* A set of estimated displacement parameters including 6 variance and covariance values.

An example set of parameters is available through 4TU.ResearchData, with DOI: {UPDATE}. Users can download the data and the metadata from that repository to plot the corresponding displacement vectors using this repository.
