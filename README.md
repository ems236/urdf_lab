### Ellis Saupe ems236 lab 5

This repository and package are poorly named because we reused the lab 4 package.
All updated code is on branch master.

## Lab info
To launch lab 4 display: 
```roslaunch urdf_lab display.launch load_map:=false config_file_name:=config_lab4.rviz use_lab_5:=false use_sim_time:=false use_rqt_bag:=false```


To launch the display with the lasers and no map [you must select all topics to publish in rqt_bag and click play]:
```roslaunch urdf_lab display.launch load_map:=false config_file_name:=config_lasers_decay.rviz```


To launch the display with the robot moving around the map: 
```roslaunch urdf_lab display.launch```


## Demo Video
https://drive.google.com/file/d/126GBYTuqMwTELgzOnakyHsI5k7Nj4b1h/view?ts=5db89542