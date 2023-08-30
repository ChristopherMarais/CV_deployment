# CV_deployment
A Repo to test deploying a CV model using flutter and a pytorch model. 

The idea is to host a webapp using flutter that accesses the user's webcamp live feed. The frames from the live feed are then sent to a python api that processes the frames as images, doing segmentation and classificaiton. The result is then returned to the flutter app and displayed. It should be possible to host both the python api and the flutter web app in docker containes on the same server. THe python api will be hosted using flask. 

Not each frame has to be used, the FPS of the camera can be reduced to be quite low ~10FPS
