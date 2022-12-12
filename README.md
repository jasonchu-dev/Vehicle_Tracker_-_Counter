# Vehicle Tracker & Counter

I initiated this project on my own while doing research during the summer so I decided to go back and bring it out. The idea was our group had to sift through several hours of traffic footages and count cars. This also had to be done everyday since new footages kept coming in. Everyone was tired of doing that so a few us speculated that it would be great if there was a program to take care of that. We also figured that our human resources can be a lot more beneficial to our research if placed else where while a program can sift through the footages. So this is how this project came about. This was the first time I've done computer vision/deep learning stuff and I was trying learn through examples and code on my own. Even though this project helped the research, it had absolutely nothing to do with the main missions or goals of the research so this was just a side project that I completely decided to do on my own. Unfortunatly, the program is extremely slow if you don't have hardware acceleration setup (OpenCV dnn module) which is difficult to do. Even then, you also need alot of GPU power or GPUs to speed up the process.

## If you want to run
* Make sure that you download the YOLOv3-320 configuration (cfg) and weights from [here](https://pjreddie.com/darknet/yolo/). 
* Make sure you also have the python modules OpenCV and SciPy.
* And of course a video file with vehicles.

Check out the [other stuff](https://github.com/jasonchu-dev/Summer_Research.git) that I worked on during the research.