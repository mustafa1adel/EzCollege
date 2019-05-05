# About this repo
this repo is an assignment of intro-to-docker session at FEHU

## The assignment is
Create A small (Static or dynamic) Web Application that get booted using doker.

## Requirements 
* install Docker
      
      follow this instruction https://docs.docker.com/install/
## How to boot using docker
* Build an image with

      docker build -t mynginx .
    
* Run it 
    
      docker run --name foo -d -p 8080:80 mynginx
    
 * Point your browser at
  
       http://127.0.0.1:8080
     
#### Note: 
* use sudo before the above instractions if you install docker as root/ administrator
     
     
 
         
          
       
