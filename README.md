# DataProcess

During printing multiple datasets are being recorded: 

    * Water flow L/min
    * Pump speed RPM
    * Water temperature
    * Pump temperature
    * X Y Z coordinates
    
A script is made that reads in the .csv file from the local folder where the data is saved and the outputs are graphs for waterflow, pump frequency, water and pump temperatures.

In addition XYZ coordinates are saved - for this a script is made to save these coordinates as .txt file that can be used as input in Rhino/Grasshopper to visualize a print path. A g-code is used to make a toolpath for the printer. A cript is also made to evaluate the script for visualizing a print path beforehand.

Finally a plotting script is done to read in pull-out results and make graphs out of it.
