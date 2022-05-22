# Multiplex Network Analysis Public Transportation
## University Project
Social Network Analysis Project

### Paper
The paper associated to this project is available [here](https://en.wikipedia.org/wiki/Haversine_formula)

### Multiplex Class
The Multiplex Class written in python is a nx.Graph wrapper for creating multi-layer networks and includes:
* Adding layers to a multiplex
* Linking the layers by proximity using [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula).
* Writing networks back to NetworkX
* Summarizing a multilayer network

### Maps
[Stations and roads](https://matteofasulo.github.io/Paris-Euler/france.html)
[Public transport lines](https://matteofasulo.github.io/Paris-Euler/france_transport.html)
> **Tip:** Our map can be modified using the draw icons in top-left corner and then exported as GeoJSON file through the **export** button

### Datasets
- The GeoJSON file is available at [ComplexNetTSP GitHub](https://github.com/ComplexNetTSP/MultilayerParis)


### Libraries

| Name | Description |
| ------------- | ------------------------------ |
| [Numpy] | package for scientific computing with Python.
| [Pandas]| fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.
| [Folium]| folium builds on the data wrangling strengths of the Python ecosystem and the mapping strengths of the Leaflet.js library.
| [Os]| this module provides a portable way of using operating system dependent functionality.
| [Json]| the json library can parse JSON from strings or files.
| [Math]| access to the mathematical functions defined by the C standard.
| [Random]| pseudo-random number generators for various distributions.
| [NetworkX]| package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
| [PowerLaw]| package for Analysis of Heavy-Tailed Distributions
| [EmpiricalDist]| library that represents empirical distribution functions.
| [Matplotlib]| library for creating static, animated, and interactive visualizations in Python.
| [Plotly]| graphing library makes interactive, publication-quality graphs.
| [Kaleido]| cross-platform library for generating static images (e.g. png, svg, pdf, etc.) for web-based visualization libraries.
| [MPL Toolkits]| matplotlib module for 3d plots.


### Classes:                
         
| Class                   | Description                    |
| -------------------------- | ------------------------------ |
| `ParisTransportation`                       |GeoJSON preprocessing|
| `MapMaker(ParisTransportation)`              |Nodes map creation|
| `TransportMap`              |Public transport line creation + road network|
| `Multiplex`             |Thin nx.Graph wrapper for multi-layer networks|
| `LayeredNetworkGraph`             |3D plot using GraphViz of public transport networks|
----

[os]: <https://docs.python.org/3/library/os.html>
[json]: <https://docs.python.org/3/library/json.html>
[Numpy]: <https://numpy.org/install/>
[Pandas]: <https://pandas.pydata.org/>
[Folium]: <https://python-visualization.github.io/folium/>
[Math]: <https://docs.python.org/3/library/math.html>
[Random]: <https://docs.python.org/3/library/random.html>
[NetworkX]: <https://networkx.org/>
[PowerLaw]: <https://pypi.org/project/powerlaw/>
[EmpiricalDist]: <https://pypi.org/project/empiricaldist/>
[Matplotlib]: <https://matplotlib.org/>
[Plotly]: <https://plotly.com/python/>
[Kaleido]: <https://pypi.org/project/kaleido/>
[MPL Toolkits]: <https://matplotlib.org/stable/tutorials/toolkits/mplot3d.html>
