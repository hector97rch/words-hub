# Instructions for runing the project

* Clone the projec on the server.

## Words hub project, banco folder.
    * create an image 
     in the terminal enter the next command **docker build -t words-hub:0.1.0 .**
    * run the project 
    in the terminal enter the next command **docker run --network host words-hub:0.1.0**
    * stop the project
    1. in a new terminal enter **docker ps** and copy the id of the  words-hub image.
    2. enter **docker stop id**


