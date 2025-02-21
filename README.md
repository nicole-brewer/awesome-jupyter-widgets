# awesome-jupyter-widgets
A curated list of awesome Jupyter widget packages and projects in Python

## Contents

- [Interactive Widgets](#interactive-widgets)
  - [Interactive Jupyter Widget Ecosystem](#interactive-jupyter-widget-ecosystem)
  - [Create Your Own Widget with JavaScript](#create-your-own-widget-with-javascript)
  - [Autogenerate a User Interface](#autogenerate-a-user-interface)
  - [Data Viz Frameworks with Interactive Jupyter Integrations](#data-visualization-frameworks-with-interactive-jupyter-integrations)
- [Data Dashboards and Web Applications](#data-dashboards-and-web-applications)
- [Sharing Interactive Notebooks](#sharing-interactive-notebooks)
  - [Venues for PUblication](#venues-for-publication)
- [Packages for Development](#packages-for-development)
  
## Interactive Widgets

### Interactive Jupyter Widget Ecosystem

- [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/) - basic widgets and nestable containers
- [ipyvuetify](https://github.com/widgetti/ipyvuetify) - basic widgets in the style of Google user interfaces
- [ipyevents](https://github.com/mwcraig/ipyevents) - a widget for returning mouse and keyboard events
- [pythreejs](https://github.com/jupyter-widgets/pythreejs) - 3D visualizations (Three.js)
- [bqplot](https://github.com/bqplot/bqplot) - 2D plotting
- [ipympl](https://github.com/matplotlib/ipympl) - interactive Matplotlib
- [ipyvolume](https://github.com/widgetti/ipyvolume) - 3D plotting using WebGL
- [K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter) - 3D plotting using WebGL
- [perspective](https://github.com/finos/perspective) - real time visualization large and/or streaming datasets
- [ipydatagrid](https://github.com/bloomberg/ipydatagrid) - spreadsheets
- [ipyparaview](https://github.com/NVIDIA/ipyparaview) - ParaView rendering 
- [jupyter-scatter](https://github.com/flekschas/jupyter-scatter) - 2D scatter plots that scale to millions of points
- [ipycanvas](https://github.com/jupyter-widgets-contrib/ipycanvas) - interactive drawing canvas using the browser's canvas API
- [ipygany](https://github.com/jupyter-widgets-contrib/ipygany) - display 3D meshes in a widget

#### Maps and Geospatial Visualization
- [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) - maps (Leaflet.js)
- [mapwidget](https://github.com/opengeos/mapwidget) - 2D/3D maps using Cesium, Mapbox, MapLibre, Leaflet, and OpenLayers 

#### Networks
- [ipycytoscape](https://github.com/cytoscape/ipycytoscape) - graph visualizations (cytoscape.js)
- [ipysigma](https://github.com/medialab/ipysigma) - designed to work with either networkx or igraph (sigma.js)

#### Astronomy
- [pyESASky](https://github.com/esdc-esac-esa-int/pyesasky) - visualize and download public astronomical data
- [astrowidgets](https://github.com/astropy/astrowidgets) [IN DEVELOPMENT] - leveraging the Astropy ecosystem

#### Biology and Chemistry
- [nglviewer](https://github.com/nglviewer/nglview) - visualize molecular structures and trajectories
- [clustergrammer2](https://github.com/ismms-himc/clustergrammer2) -  "Dimensionality-increasing" data visualization tool for single-cell data

#### Health and Human Sciences
- [niwidgets](https://github.com/nipy/niwidgets) - neuroimaging widgets
- [itkwidgets](https://github.com/InsightSoftwareConsortium/itkwidgets) - visualize images, point sets, and meshes in 2D and 3D

### Autogenerate a User Interface
- [ipyautoui](https://github.com/maxfordham/ipyautoui) - automate the creation of widget forms

### Create Your Own Widget with JavaScript

- [cookiecutter](https://github.com/jupyter-widgets/widget-cookiecutter) - for creating a custom Jupyter widget project
- [widget-ts-cookiecutter](https://github.com/jupyter-widgets/widget-ts-cookiecutter) - highly opinionated cookiecutter template for ipywidget extension
- [anywidget](https://github.com/manzt/anywidget) - custom jupyter widgets made easier
- [jp_proxy_widget](https://github.com/AaronWatters/jp_proxy_widget) - support many types of javascript libraries and interactions


### Data Visualization Frameworks with Interactive Jupyter Integrations

- [Solara](https://solara.dev/) - build web apps using ipywidgets that work both inside the Jupyter Notebook and as standalone web apps with frameworks like FastAPI
- [Plotly](https://plotly.com/python/getting-started/) - 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases (plotly.js)
- [Altair](https://altair-viz.github.io/user_guide/interactions.html#interactive-charts) - declarative statistical visualization library built on top of the powerful [Vega-Lite](https://vega.github.io/vega-lite/) grammar
- [Bokeh](https://github.com/bokeh/jupyter_bokeh) - beautiful visualizations for modern web browsers

## Data Dashboards and Web Applications

- [Voilà](https://github.com/voila-dashboards/voila) - turns notebooks into standalone web applications by hiding code cells
- [nbdev](https://github.com/fastai/nbdev) - a package for developing literate Python packages from within Jupyter Notebooks (well-suited to developing complex workflows, data dashboards, and web applications)
- [nbdev_app_template](https://github.com/nicole-brewer/nbdev_app_template) - an opinionated template for building scientific web applications with nbdev + Voilà
- [voici](https://github.com/voila-dashboards/voici) - a tool for generating static dashboards from Jupyter Notebooks

## Sharing Interactive Notebooks
- [Binder](https://mybinder.org/) - turn a Git repo into a sharable collection of interactive notebooks (free hosting)

### Venues for Publication
- [US-RSE Conference](https://us-rse.org/usrse23/participate/notebooks/) - a research software engineering conference that accepts for computational notebook submissions for peer-reivew
- [Earthcube Annual Meeting](https://www.earthcube.org/notebooks) - an annual meeting that accepts peer-reviewed Jupyter notebooks showcasing geoscience data tools, software, services, and libraries

## Packages for Development

- [jupyterlab](https://github.com/jupyterlab/jupyterlab) - multipane notebook development environment
- [jupyterlab-sidecar](https://github.com/jupyter-widgets/jupyterlab-sidecar) - sidecar output widget for JupyterLab
- [jupyterlab-ide](https://github.com/nicole-brewer/jupyterlab-ide) - a set of packages and extensions to give JupyterLab IDE superpowers
