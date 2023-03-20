# Mapping_Earthquakes

# Overview 

The purpose of this project is to provide Basil and Sadhana earthquake data as it relates to the location of tectonic plates on the earth and specifically, would like to see a map of earthquakes with a magnitude greater than 4.5.  

Deliverable 1:  Map of Tectonic Plates around the world

<img width="1864" alt="Map1" src="https://user-images.githubusercontent.com/119356418/226469624-902d13b3-6a98-44f8-9d54-7c14a18a07bb.png">

- The tectonic plate data is added as a second layer group 
- The tectonic plate data is added to the overlay object 
- The d3.json() callback is working and does the following: 
    - The tectonic plate data is passed to the geoJSON() layer
    - The geoJSON() layer adds color and width to the tectonic plate lines
    - The tectonic layer group variable is added to the map
- The earthquake data and tectonic plate data displayed on the map when the page load




Deliverable 2:  Major Earthquake Data

<img width="1860" alt="MajorEarthquakes" src="https://user-images.githubusercontent.com/119356418/226472279-c097af63-5d0e-4f86-b71e-6de67eb1371f.png">

- The major earthquake data is added as a third layer group 
- The major earthquake data is added to the overlay object 
- The d3.json() callback is working and does the following: 
  - Sets the color and diameter of each earthquake.
  - The major earthquake data is passed to the geoJSON() layer.
  - The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  - The major earthquake layer group variable is added to the map
- All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off 

Earthquake Data

<img width="1858" alt="Earthquakes" src="https://user-images.githubusercontent.com/119356418/226472338-ed88f320-ddc6-4a3a-973a-8a82a32bc97b.png">




Deliverable 3:  The addition of another map

<img width="1868" alt="Map3_dark" src="https://user-images.githubusercontent.com/119356418/226469880-272d84e1-e300-45d4-a66d-93634de2ee0b.png">

- A third map tile layer is created 
- The third map is added to the overlay object 
- All the earthquake data and tectonic plate data are displayed on the all maps of the webpage 



Summary:

Interactive map:  http://127.0.0.1:5500/

As you toggle through the options on the top right hand corner, you can choose to show data based off of topography maps and 3 options of data types:  tectonic plates, eartherquakes and major earthquakes.  
