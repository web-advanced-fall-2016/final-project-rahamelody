# Final Assignment

For the final, I worked on the front-end of a website for a startup in DUMBO called Carmera with a backend developer names James Yeh (https://github.com/jamesclyeh). 
For background, Carmera is a company aiming to get the freshest street imagery and sensor data of New York using cameras and sensors that they place on top of commercial vehicles that often drive all over the city daily. Their data is as fresh as 7-30 days. They challenges us to create a prototype of a project that finds a good use for all of this raw information they have gathered. In the last few weeks of school, we have been building a website for "city decision makers" i.e. architects, urban planners, realtors, etc. This user base can use our web platform in the following ways:

* See the street imagery and sensor data of certain areas based on specific filters including: the radius from a certain address, neighborhood, or entire city, the time of day (Morning, Afternoon, Evening, Night), date taken (single day, last 90 days, 30 days, 7 days), image and/or video content included, and specific tags can be typed in such as: "firehydrants", "buildings", "people", "cars", etc. 
* For people and cars, a heatmap shows up on the map to indicate the densest areas, for everything else, pins are dropped on the map. When pins are on the map, the user will be able to hover over any image of interest to a) get more info about the image such as it's ID number, the angle at which it was taken, and they exact date and time it was captured, and b) to move the map that appears to the left of the imagery to the correct corresponding pin, which turns orange on hover from it's original blue color.
* Other than filtering these images, users are also able to press a button labeled "Select Images" which then allows them to select as many of the images pertinent to a city decision maker's personal projects, which are availble to them in a seperate navigation button on the left side of the screen. There are two navigation options: the initial option is where you filter and select a certain area to view the available data and imagery for it, and the second is where you save images to projects that you name and create (we have not built this section out yet). In this second tab, you also have the ability to download the imagery and metadata that you have saved in each project.
* When you click on a specific image rather than just hovering on it, you are navigated to a new page with a larger version of the image, detailed information from the sensor data, the ability to take notes on that image, and the ability to annotate the image itself with a pen tool. Users will also be encouraged to help crowdsource tags by using the tag tool to tag pertinent objects, as it will be helpful to them when they are counting up the number of these objects in their area of interest, while simultaneously increasing the accuracy of the website. The website uses a neural network/computer vision (implemented by James Yeh) to recognize  certain objects. However, the neural network is not always accurate and makes mistakes. User feedback and tags will help fix these problems.

#### APIs used
* The main API used was the Carmera API for the street imagery and sensory data. I can't link it here as they are still in stealth-ish mode.
* Mapbox API
* The Leaflet heatmap plugin
* A simple drawing editor: https://github.com/ianli/raphael-sketchpad



