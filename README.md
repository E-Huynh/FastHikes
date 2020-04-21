# Fast Hikes
[Deployed Link](https://e-huynh.github.io/FastHikes/)

[Github Repo](https://github.com/E-Huynh/FastHikes)

## Contact

Erik.W.Huynh@Gmail.com

[LinkedIn](https://www.linkedin.com/in/erik-huynh-228321196/)

[Portfolio](https://e-huynh.github.io/portfolio-gram/)

## Project Description
The purpose of this application is to provide a way for a user to quickly see what hikes are around them that they can get to, complete, and get back from in the time the specify.

### Background
Currently most, if not all, hiking applications will return a list of hikes based on proximity to a geographic location, but they do not factor in travel time to and from the point of origin of the search and the trail head itself, and leave filtering and sorting by hike length as a secondary step the user must perform.  This means that for any hike that is displayed, the user has no idea at a glance if they have the time needed to actually complete it, without first checking the hike length itself and then using a seperate service to get travel time information.

### Solution
Our Application automitically takes time into account as the most important factor when trying to fit a hike into an already busy day.  By only showing hikes that can be driven to, completed, and driven back from in the timeframe specified, we eliminate the burden of having to filter or use alternate platforms to gather more information about whether any given hike is able to be completed in time or not.

## Instructions
Simply put in your current location(or hit the geolocation button) and how much time you have to hike, and a list of hikes that you can get to, hike, and get back from in the alloted time will be returned to you.

## Technologies
* JQuery
* Bootstrap
* CSS Grid and FlexBox
* [HikingProject API](https://www.hikingproject.com/data)
* [Google Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/intro?hl=en_US)

### Gallery
First draft website sketchup:<br>
<img src="assets/images/Webpage Sketching/homePageSketch.jpg" alt="home sketch" title="Home page sketch" width="300" height="300"/>
<img src="assets/images/Webpage Sketching/resultsPageSketch.jpg" alt="results sketch" title="Results page sketch" width="300" height="300"/>
<br>
Final Draft: <br>
<img src="assets/images/Webpage Sketching/finishedIndex.PNG" alt="home sketch" title="Home page sketch" width="500" height="300"/>
<img src="assets/images/Webpage Sketching/finishedResults.PNG" alt="home sketch" title="Home page sketch" width="500" height="300"/>

