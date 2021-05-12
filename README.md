# Drowsiness_Detection
Drowsiness and Yawning Detection using OpenCV and 

Dependencies

1.Python3
2.OpenCV
3.Dlib
4.imutils
5.scipy
6.numpy
7.argprase

Run
Python3 Drowsiness_Detecter -- webcam 0		                                                                                //For external webcam, use the webcam number accordingly
                                                                                                                               //For rasberry pi just change the webcam index to 1

Setups

Change the threshold values according to your need

EYE_AR_THRESH = 0.3
EYE_AR_CONSEC_FRAMES = 30
YAWN_THRESH = 10`                               	                                                                          //change this according to the distance from the camera

Additionals
Espeak                                                                                                                                                    //Converts text to voice
Cmake			                                                                                                                                        //Should be downloaded with dlib	
Webcam.py                                                                                                                      // File shows how actually the shape predictor works
