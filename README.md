The original GitHub link is here: https://github.com/matterport/Mask_RCNN

# Steps to Use This Code #

1. Download and unzip the files
2. Open up a terminal (Mac) or Command Prompt (windows) in the folder where you have saved all the files
3. Run this command: pip install -r requirements.txt
4. Run this command: python setup.py install
5. Still in terminal/command prompt, go into the cocoapi-master folder and then into the PythonAPI folder
6. Run this command: pip install cython
  6a. If you get an error with the above command, try uninstalling and then reinstalling cython.
7. Run this command: pip install tensorflow_gpu or conda install tensorflow_gpu
8. Run this command: python setup.py build_ext install
9. Go to this link: https://github.com/matterport/Mask_RCNN/releases
10. Download the file called mask_rcnn_coco.h5 under assets at the very bottom of the page
11. Put the .h5 downloaded file into the folder you have everything
12. Then run this command if you want to run the program on a live video camera feed: python video_demo.py
13. Or run this command if you want to run the program on a saved video file: python video_demo.py *FILENAME OF VIDEO*
