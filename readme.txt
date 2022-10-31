# Testing with image like 'dog.jpg'
./darknet detector test obj.data yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_final.weights data/dog.jpg

# See 'predictions.jpg'

# Testing with video stream like *.mp4
./darknet detector demo obj.data yolov4-tiny-obj.cfg backup/yolov4-tiny-obj_final.weights -dont_show bear.mp4 -i 0 -out_filename bear_results.avi

# see 'bear_results.avi'
