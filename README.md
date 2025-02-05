# Voronoi Corridor
![main image](/References/7.png)


## Summary
The voronoi component in Grasshopper generates surfaces/lines around 
a set of points, while maximising the space between these points. 

This file generates a 3D voronoi pattern from a given surface,
then cuts it onto the surface and extrudes it.
Possible applications on corridor/hallway design. 
A possibility is also to export components to excel/sheets for 3-D printing / manufacture

## Usage
Open .ghx file in Rhino 8, via Grasshopper in command line
View >> remote control panel to view inputs. 

## Description of Procedure
1) Overlay a 3-D voronoi pattern on pre-selected surface
![picture 1](/References/1.png)
![picture 2](/References/2.png)
![picture 3](/References/3.png)

2) Cut the surface with the pattern, and extrude by a specified thickness.    
![picture 4](/References/4.png)
![picture 5](/References/5.png)

4) Split generated surface into multiple components with an alternate splitting pattern. 
![picture 6](/References/6.png)
![picture 7](/References/7.png)

5) Optional: Add measurements across surface lines. 

## Log

### 05/02/2024
Pictures added and readme updated. Remote control in GH file added. 

### 15/12/2024
Readme (Description of Procedure) updated. 3DM file for base surface added.
.ghx: Basic voronoi generation complete. Excel import to be added.
Updated images to be added. 

### 31/12/2024
Readme updated. Image added. Progress with .ghx file. 

### 25/12/2024
Progress with .ghx file.

### 11/12/2024
First upload.

