# nyx_pose_estimation

To recreate the project in your local. 

- copy the link of the project and open a terminal. 
- go to the directory you want to download the project in your terminal
- type in ```git clone https://github.com/georgepaul007/nyx_pose_estimation.git```
- now, you can open the file on anaconda jupyter notebook.
- it should open in your browser and go to the directory of the project and open the model file
- then, you can run the project on any video just save the new video in the project directory under the name "shoplifting_video"

Models Used: 
readNetFromCaffe - used to find the people present in the video. I have chosen this pre-trained model because it has better accuracy than self trained models on kaggle datasets and they are highly efficient and this can be scaled into real time detection in the future (real world use of this project is only on real time detection)
readNetFromTensorflow - used to do pose estimation on the person. This is also a pretrained model which can detect the 8 extreme parts of the body to detect any changes in the actions of the user. 

References: 

-> https://github.com/IBM/action-recognition-pytorch/tree/master
-> https://github.com/1amitos1/Shoplifting-Detection#ADS-PIPELINE-Demo
-> https://towardsdatascience.com/fall-detection-using-pose-estimation-a8f7fd77081d
-> https://learnopencv.com/deep-learning-based-human-pose-estimation-using-opencv-cpp-python/
