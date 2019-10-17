### Ellis Saupe ems236 lab 4

## My gihub repo is here https://github.com/ems236/urdf_lab

## Comments on the lab
This lab was pretty straight forward so I don't have many details to write up.  

My files are named exactly as the delivable tree example describes. 
roslaunch urdf_lab display.launch use_xacro:=true GUI:=true will launch the display.

I define the xacro file as described and have a launch file that will generate the urdf file from the xacro and display it in RVIS.
It does seem a little inconvenient to have to publish an initial joint state for continuous joints. You would think that that initial value could be published from reading the urdf similar to how it reads all the static joint locations. 

I downloaded the xacro file for the velodyne becuase it wasn't on the jennings computers, but I have updated the xacro file to use the actual package now.  
I just never deleted the xacro file from my repo.

## A video of my launch file working is included at this url https://drive.google.com/file/d/1B2iqR5TNNQHUP7ElEnzrUylYa5Jri50i/view?usp=sharing.  