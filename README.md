# HackCovid19
Before executing num_plate_detect.py file we need to download "lapi.weights" file from the drive link https://drive.google.com/open?id=1oZsKdva-IUTVFBFegM8h3HlC_w0SqfBY (since lapi.weights file is really large we wee not able to upload it on Github)

To execute num_plate_detect.py we need to pass argument in terminal in such manner:

if detection is to be done on photo then:

1) python num_plate_detect.py --image image_name.jpg

if detection is to be done on video then:

2) python num_plate_detect.py --video video_name.mp4

the output file generated will be saved in /static

3) start flask server by executing python m.py on terminal

4) go to http://127.0.0.1:5000/ on your browser to see the images

PS:

1) If some library is not found, please go through requirement.txt file.

2)the flask app is working but not fully integrated with the project
