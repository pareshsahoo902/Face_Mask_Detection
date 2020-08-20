# Face_Mask_Detection


step 1:
Download the Dataset from this link: https://drive.google.com/drive/folders/1WCxe1EuxLo6qyGVpupcEMTgN83xpgHM_?usp=sharing

step 2:
clone or download the source code from this repository

step 3:
install all the requirments in requirments.txt by using  pip instal -r requirments.txt

step 4:
add your dataset folder path in line 26 in train_mask_detector.py

step 5 :
Run detect_mask_video.py and check if it works or not.
note: add source of your video in line 69 in detect_mask_video.py
" vs = VideoStream(src=0).start() " where 0=inbuilt webcam , 1= usb connected so on...
