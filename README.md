# Florence-SAM2

# Florence+SAM2: Human Face Identification and Censorship

Florence+SAM2 is experimenting computer vision project that combines the power of Florence 2 and SAM2 to identify human faces in images, detect speakers, and apply censorship to passerby faces. The project demonstrates how to filter out passerby faces from speaker images and apply pixelated masking to protect privacy.

## Project Workflow

### 1. Face Identification with Florence 2
Using Florence 2, we identify all human faces in a given image. 

*Insert Image Here*  
(Example of face identification using Florence 2)

### 2. Speaker Detection with Florence 2
We then use Florence 2 to identify speakers' faces from another image.

*Insert Image Here*  
(Example of speaker detection with Florence 2)

### 3. Filtering Passerby Faces
By overlapping the detected speaker images with the human faces identified earlier, we can filter out passerby faces that are not related to the speakers.

### 4. Censorship with SAM2
SAM2 (Segment Anything Model 2) is used to mask the passerby faces. We apply pixelated censorship to the faces we filter out, ensuring privacy is protected.

*Insert Demo.mp4 Here*  
(Example of video demonstrating the censorship process)

## Installation

To run this project locally, you will need to install the necessary dependencies.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Florenc
