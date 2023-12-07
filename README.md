# Unix Project - Web Server using a VPS

### Project Description and Goals
Our goal was to create a website hosted on a virtual private server that will allow the user to download the available games. 
The website shows the number of visits that you've made to it, and this number is updated automatically. 

### Basic System Setup and Security
Some security measures that we have implemented into our project include : 
* Changed the default http port (80) - > since this opens the server up to being targeted by hackers
* Implemented SSH - key based authentication

### Service Management / Scheduling
Our Plan was to: 
* Rotate the games in the website every few minutes.
* Pull changes from git every few minutes.
  
The Result: 
* Changed the background color of the website at a certain time interval. 

### Automated Task
Our plan was to:
* Count the number of total visits to our website

The Result: 
* Instead of counting no of total visits,  we count the amount of times each person visits the site.
