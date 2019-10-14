### Ellis Saupe ems236 lab 4

## My gihub repo is here https://github.com/ems236/urdf_lab

## Comments on the lab
This lab was pretty straight forward so I don't have many details to write up.  
I define the xacro file as described and have a launch file that will generate the urdf file from the xacro and display it in RVIS.
It does seem a little inconvenient to have to publish an initial joint state for continuous joints. You would think that that initial value could be published from reading the urdf along with the values for all the static joints. 

The Jennings computers do not appear to have the velodyne description installed, so I could not use that xacro file.  I downloaded the file from https://bitbucket.org/DataspeedInc/velodyne_simulator/raw/506664dd478984aa6645d8210802a4a7ddc40629/velodyne_description/urdf/VLP-16.urdf.xacro and included that in my package.

## A video of my launch file working is included at this url.  