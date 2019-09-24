The original GitHub link is here: https://github.com/matterport/Mask_RCNN

# Steps to Use This Code #

1. Download and unzip the files
2. Open up a terminal (Mac) or Command Prompt (windows) in the folder where you have saved all the files
3. Run this command: pip install -r requirements.txt
4. Run this command: python setup.py install
5. Still in terminal/command prompt, go into the cocoapi-master folder and then into the PythonAPI folder
6. Run this command: python setup.py build_ext install
7. Run this command: pip install cython
  7a. If you get an error with the above command, try uninstalling and then reinstalling cython.
8. Then run this command if you want to run the program on a live video camera feed: python video_demo.py
9. Or run this command if you want to run the program on a saved video file: python video_demo.py *FILENAME OF VIDEO*
