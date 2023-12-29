# Oliver-Pharr
Analysis of nanoindentation for Biomaterials grad course. 
For this project, we were asked to implement the Oliver-Pharr model of nanoindentation analysis
to find the elastic modulus of both a healthy and newly formed bone. 

Data was collected and uploaded into an Excel file. It was extracted using methods in Pandas and created a data frame. 
Units were converted and data was plotted to view findings. 
The slopes of the unloading portions of the force-displacement curves were calculated using Numpy polyfit and then re-plotted
the curves to include the newfound slopes. 

Modulus could then be found using the slopes. 

To learn more about the Berkovich tip, follow: https://en.wikipedia.org/wiki/Berkovich_tip
To learn more about nanoindentation, follow: https://en.wikipedia.org/wiki/Nanoindentation
