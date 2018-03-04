Read me File:

1.) To run the code, install following dependencies:
sklearn, skimage, keras, matplotlib, moviepy, numpy, scipy

2.) The whole code is integrated in the main.py file, on running the main.py file from the terminal or from any IDE, the following pipelines are executed:
a.) CNN for vehile detection
b.) HOG for vehicle detection
c.) Lane detection

3.) The create_video() function call processes he video available inside test_videos folder and writes the output video in output_videos file. One sample output is attached is already available in the folder

4.) The CNN model need not be trained as we have included the saved weights inside the dataset folder, to train the network from scratch, go to the main.py file and uncomment line # 47,48 ..advisable to take a backup of the already available weights before doing so.

5.) Since the dataset is not included in the submission folder, the test_random function call(line # 56) in the main.py file has been commented. This funtion tests the random files for vehicle/non-vehicle classification

6.) Since the HOG extraction method is dependent upon the dataset so it is commented (line # 75,76) int the main.py file. In presence of data, the import statment runs the HOG pipeline and performs the vehicle detection.