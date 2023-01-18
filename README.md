# napari_plugin_intro_workshop
Workbook based on the workshop introducing the napari plugin engine. For tutorial source, see the [napari-workshops site](https://alisterburt.github.io/napari-workshops/SwissBIAS-1121/intro.html).


## Overview:

### **Notebook: [Introduction to bioimage visualisation in python]('https://github.com/jazwilson/bioimage_visualisation_in_python')**
- Implementing napari viewer in python 
- Exploring and modification of image layers through both the GUI and python
- 2D and 3D rendering 

### **Notebook: [Segmenting nuclei with the cellpose napari plugin]('https://github.com/jazwilson/bioimage_visualisation_in_python/blob/main/ch_1_segmenting_and_measuring_nuclei.ipynb')**
- Segmentation of cell nuclei implenenting cellpose napari plugin through python
- Quantification of nuclei shape using the output of the segmentation mask and feeding data into scikit-image **regionprops_table** function to measure area/perimeter of detected nuclei

### **Notebook: [Interactive analysis with jupyter notebook, napari, scikit-image, and scipy]('x')**
- Application of high pass gaussian filter to de-noise biological images.
- Implement blob detection algorithm from sci-kit image to detect_spots(). This will return a numpy array with coordinates for each spot and a numpy array for spot diameter. 