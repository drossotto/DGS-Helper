# DGS-Helper
The Jupyter Notebook used to run DeepGlycanSite and the Dockerfile used to reproduce a functional distribution of DeepGlycanSite. 

The goal is to keep it super simple and maximize abstraction for our wet-lab biologists. Anything requiring significant installation receives a docker container. This adds tons of overhead, as well as having redundant packages, but we do not care. 

Run Instructions can be found in the 'analysis.ipynb' Jupyter Notebook. Then, 'graph_dgs.ipynb' was used as post-processing. 


Services: 
- DeepGlycanSite: Carbohydrate-binding site predictions through a geometry-based graphical neural network.
  * [Research Article](https://www.nature.com/articles/s41467-024-49516-2)
  * [GitHub](https://github.com/xichengeva/DeepGlycanSite)

