## Lab Quick Start Guide


#### 1. Open your broswer to go to PI connect
```
https://connect.raspberry.com
```

#### 2. Select device "RX5F-HAPS" and choose "Screen sharing"
```
Login PI-Connect Username: support@heswiki.com
Login PI-Connect Password: xxxxxxxx (by request)
```

#### 3. Open a terminal and execute demo script
```
$ cd ~/hailo-rpi-examples
$ source ./setup_env.sh
$ make
$ make pos    (Pose Estimation using recorded video)
$ make pos-u  (Pose Estimation using USB camera)
$ make det    (Object Detection using recorded video)
$ make det-u  (Object Detection using USB camera)
$ make seg    (Instance Segmentation using recorded video)
$ make seg-u  (Instance Segmentation using USB camera)
...

Press Ctrl-C in the terminal to stop demo
```
 
