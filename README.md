# Sign-Language-recognitation

Project Description -

The proposed system implements the sign language recognition using CNN. It has been designed for the two-way communication. Dataset is created on our own for 10 different alphabets. Initially server starts running and the client connects to the server using IP and port. After the connection is established, both the system starts receiving the video frames. I have used socket programming to implement the server-client architecture. The webcam captures the image of the gesture from the bounding box created on the screen. Then the image undergoes pre-processing stages like cropping, conversion of RGB to HSV color space and finally applying mask operation on it. Then the masked image is given to the CNN model for features extraction. Finally, the predicted gesture will be displayed on the screen.

10 alphabets classified -

![image](https://user-images.githubusercontent.com/95165705/177188457-aadfb5e5-1c52-48f5-91b3-65c9e1dca6ab.png)


Overall Design -

![image](https://user-images.githubusercontent.com/95165705/177188412-f01848f1-99f7-4590-933d-666ac77622f2.png)


Results -


![image](https://user-images.githubusercontent.com/95165705/177188340-de05b787-c5cf-4d1a-8989-e5afbc6f62a4.png)
