# Unix Project - Web Server using a VPS

## Project Description and Goals
Our goal is to create a website hosted on a virtual private server that will allow the user to download the available games. 
The website shows the number of visits that you've made to it, and this number is updated automatically. 

## Basic System Setup and Security
Some security measures that we have implemented into our project include : 
    Changing the default ssh port (22)
    Changing the default http port (80) - > since both of these opens the server up to being targeted by hackers
    Implemented SSH - key based authentication

## Service Management / Scheduling
    A service (scheduled task): check every minute if changes have been made to the git repository and pull them. 
    Service that rotates the order of the games every hour, making the homepage different by showing different games. 



