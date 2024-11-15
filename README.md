# Florence+SAM2: Human Face Identification and Censorship

Florence+SAM2; experimenting computer vision project that combines the power of Florence 2 and SAM2 to identify human faces in images, detect speakers, and apply censorship to passerby faces. The project demonstrates how to filter out passerby faces from speaker images and apply pixelated masking to protect privacy.

## Project Overview

### 1. Face Identification with Florence 2
Using Florence 2, we identify all human faces in a given image. 

![Florence Result](result/Florence_result.png)  

### 2. Speaker Detection with Florence 2
We then use Florence 2 to identify speakers' faces from another image.

![Florence Result](result/Florence_Result_main_speaker.png) 

### 3. Filtering Passerby Faces
By overlapping the detected speaker images with the human faces identified earlier, we can filter out passerby faces that are not related to the speakers and apply SAM2 model.

![SAM2 Result](result/SAM2_Result_MaskPasserby.png)


### 4. Censorship with SAM2
SAM2 (Segment Anything Model 2) is used to mask the passerby faces. We apply pixelated censorship to the faces we filter out, ensuring privacy is protected.
The output is saved as a new video file. Below is an example of the censored video:

`output/blur_video.mp4`
[Demo Video](output/blur_video.mp4)


