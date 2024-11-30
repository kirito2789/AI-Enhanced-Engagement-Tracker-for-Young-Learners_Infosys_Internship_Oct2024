# Dinesh_Datta_AI-Enhanced-Engagement-Tracker-for-Young-Learners_-Infosys_Internship_Oct2024
## Image Processing
### Libraries or Frameworks Used
- **OpenCV**: Version 4.10.0.84
- **NumPy**: For array manipulation
# AI Enhanced Engagement Tracker

## Overview

**AI Enhanced Engagement Tracker** is an intelligent system designed to monitor and analyze user engagement levels in real time. By leveraging AI and data analytics, it provides actionable insights to enhance productivity and interaction. This tool is ideal for educators, marketers, and workplace managers seeking to optimize engagement strategies.

---

## Project Structure

The project is divided into four main parts:

1. **Image Processing**
2. **Video Processing**
3. **Annotations**
4. **Face Recognition**

---

### 1. Image Processing

Image processing involves techniques for analyzing, enhancing, and transforming images to extract useful information or improve visual quality. It encompasses tasks like noise reduction, image sharpening, segmentation, and object recognition.

#### **Libraries or Frameworks Used**
- OpenCV  
  **Version:** 4.10.0.84  

#### **Developed Features**

| **Feature**                | **Description**                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------|
| **Image Noise Removal**     | Reduces random variations (noise) in an image to enhance clarity.                                |
| **Closing Gaps**            | Fills small holes or gaps in an image to create continuous regions.                              |
| **Image Template**          | Matches specific patterns or samples in a target image.                                          |
| **Color Image**             | Processes images in RGB or HSV color spaces.                                                    |
| **Image Concatenation**     | Combines images horizontally or vertically.                                                      |
| **Image Contour**           | Detects outlines or boundaries of objects.                                                      |
| **Image Cropping**          | Trims specific portions of an image.                                                            |
| **Image Detection & Erosion** | Identifies features and reduces boundaries in binary images.                                  |
| **Edge Detection**          | Highlights boundaries or edges within an image.                                                 |
| **Image Equalization**      | Enhances contrast by adjusting intensity distribution.                                           |
| **Image HSV**               | Converts images to Hue-Saturation-Value color space.                                            |
| **Image Morphing**          | Transforms one image into another.                                                              |
| **Image Resizing**          | Adjusts the dimensions of an image.                                                             |
| **RGB to Grayscale**        | Converts RGB images to grayscale.                                                               |
| **Single Image Processing** | Performs operations on individual images.                                                       |
| **Image Blurring**          | Smoothens images by reducing sharp edges.                                                       |
| **Image Rotation**          | Adjusts the orientation of images by specified angles.                                          |

---

### 2. Video Processing

Video processing involves manipulating and analyzing video data to improve quality, extract information, or enable specific functions like motion detection and object tracking.

#### **Libraries or Frameworks Used**
- OpenCV  
  **Version:** 4.10.0.84  

#### **Developed Features**

| **Feature**                 | **Description**                                                                                   |
|-----------------------------|---------------------------------------------------------------------------------------------------|
| **Multi-Video**             | Simultaneous display or processing of multiple video streams.                                    |
| **Video FPS**               | Measures and displays Frames Per Second for smooth playback.                                     |
| **Video Save**              | Saves processed video to a specified format and location.                                        |
| **Video Stacking (Horizontal/Vertical)** | Combines multiple video clips side-by-side or stacked vertically.                 |
| **Video Stream**            | Real-time video playback or streaming over networks.                                             |

---

### 3. Annotations

Annotations are additional labels or notes added to data, such as images or text, for supervised learning and data organization.

#### **Libraries or Frameworks Used**
- OpenCV (v4.10.0.84)  
- LabelImg (v1.8.6)  

#### **Developed Features**

| **Feature**                     | **Description**                                                                              |
|---------------------------------|----------------------------------------------------------------------------------------------|
| **Data Segregation**            | Organizes images based on matching label files.                                              |
| **Bounding Box Drawing**        | Draws bounding boxes around detected objects using YOLO format labels.                       |
| **Label Manipulation**          | Updates class IDs in YOLO-format label files.                                                |

---

### 4. Face Recognition

Face recognition identifies or verifies individuals by analyzing facial features in images or videos. It detects faces, extracts unique features, and compares them to a database.

#### **Libraries or Frameworks Used**
- OpenCV (v4.10.0.84)  
- Face_Recognition (v1.3.0)  
- Dlib (v19.24.6)  
- Pandas (v2.2.3)  
- NumPy (v2.1.2)  
- Datetime (v5.5)  
- Imutils (v0.5.4)  

#### **Developed Features**

##### **Face Recognition: Barack Obama**
- **Attendance Tracking:** Logs attendance using facial recognition.  
- **Real-Time Recognition:** Identifies and labels Barack Obama in video feeds.  
- **Attention Scoring:** Analyzes attentiveness based on head pose and logs the data.  

##### **Face Recognition: Dinesh Datta**
- **Automated Attendance:** Tracks and logs attendance in real-time.  
- **Attention Analysis:** Quantifies and logs attention metrics in Excel files.  
- **Landmark Detection:** Identifies and tracks key facial features.  

### Developed Logics:
#### A) Image Concatenation
Resizes two images to a specified pixel range and merges them both horizontally and vertically, displaying the results in separate windows.
- **Input**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-2.jpeg" alt="concat" width="400" style="margin-right: 20">

- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/vertical_merge.jpg" alt="concat" > <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/horizontal_merge.jpg" alt="concat" >

#### B) Image Contour Detection
Identifies contours in a grayscale image using a binary threshold and `cv2.findContours()`. Draws these contours on the original image in green.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" width="400" style="margin-right: 20">

- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/contoured_image.jpg" alt="concat" >

  #### C) Image Dilation & Erosion
Performs morphological operations to enlarge and shrink image features, enhancing and reducing specific areas respectively.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/dilated_image.jpg" alt="concat" > <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/eroded_image.jpg" alt="concat" >

  
#### D) Edge Detection
Uses the Canny edge detection algorithm to highlight edges within a grayscale image.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/Edge_Detected_Image.jpeg" alt="concat" >

#### E) Histogram Equalization
Improves the contrast of a grayscale image through histogram equalization.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" width="400" style="margin-right: 20">
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/Histogram_Equalized_Image.jpeg" alt="concat" >

#### F) HSV Conversion
Converts a color image from the BGR format to the HSV color space.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic_HSV.jpeg" alt="concat" >

#### G) Morphological Transformations
Applies opening and closing operations on a grayscale image to minimize noise and fill small gaps.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" width="400" style="margin-right: 20">
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car_morph_transformed.jpeg" alt="concat" >

  
#### H) RGB to Grayscale Conversion
Transforms a color image to a grayscale representation.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic_Grayscale.jpeg" alt="concat" >


#### I) Image Rotation
Rotates an image 90 degrees around its center point.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic_Rotated.jpeg" alt="concat" >

#### J) Image Blurring
Applies a Gaussian blur to an image to reduce noise and soften details.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic_Blurred.jpeg" alt="concat" >

#### K) Template
This function performs template matching to locate a template image within a larger image.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/My_Pic.jpeg" alt="concat" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/Detected_Faces_Image.jpeg" alt="concat" >

  
#### L) image_noise_removal & closing_gaps
Removes noise and closes gaps in an image using morphological operations.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" >
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car_opening_noise_removal.jpeg" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car_closing_fill_gaps.jpeg" alt="concat" width="400" style="margin-right: 20">


## Video Processing

### Libraries and Frameworks Utilized
- **OpenCV**: Version 4.10.0.84 

### Developed Logics:

#### A) Video_processing
A real-time video capture and processing function.

#### B) Video_fps
A real-time video capture function that displays a live video feed while calculating and showing the frames per second (FPS) for performance monitoring.
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/Screenshot%202024-11-27%20at%2011.39.17.png" alt="concat" >

#### C) Video_save
Captures live video from the webcam and writes it to a specified output file, allowing easy recording and saving of video content.

#### D) Video_stack
Reads two separate video files, resizes them, and combines them side by side for synchronized dual-video playback, ideal for comparing footage.
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/collage_output.png" alt="concat" >

#### E) Video_stream
Captures and streams live video feed from the webcam, displaying it in real-time. Useful for basic video streaming applications.
- **Output**:
  <br>
  <img src="https://github.com/user-attachments/assets/3ef6f39c-c1cd-4671-9cab-0138695de63e" alt="concat" >

## Annotations Project Overview

### Libraries and Frameworks Utilized
- **OpenCV**: Version 4.10.0.84 for advanced image processing
- **LabelImg**: Version 1.8.6 for image annotation

### Developed Logics:

#### A) data_segregate
Organizes images and label files into separate directories for matched and unmatched pairs, aiding in dataset preparation for ML projects.
- **Input**:
  <br>
  <img src="https://github.com/user-attachments/assets/f2b358cf-261e-47de-86d9-e04096c421ac" alt="concat" width="400" style="margin-right: 20">
- **Output**:
  <br>
  <img src="https://github.com/user-attachments/assets/a0b7f7b0-9e0c-447b-a261-ad0642b266fc" alt="concat" width="400" style="margin-right: 20"> <br>
  <img src="https://github.com/user-attachments/assets/180c5f6b-a40c-46f2-ac49-8ed0a74644da" alt="concat" width="400" style="margin-right: 20">

#### B) label
Draws bounding boxes on images based on annotation data, useful for visualizing object detection outcomes.
- **Input**:
  <br>
  <img src="https://github.com/user-attachments/assets/d2f07d2e-28c6-432e-b069-450117a8f2c3" alt="concat">

- **Output**:
  <br>
  <img src="https://github.com/user-attachments/assets/4142b215-f5b5-4d9f-8f58-a93fc7916526" alt="concat" >

#### C) label_manipulate
Updates class numbers within label files, enabling easy reclassification in object detection tasks.
- **Input**:
  <br>
  <img src="https://github.com/user-attachments/assets/a7d278a2-0273-4132-bda3-6551733cc2e3" alt="concat" width="400" style="margin-right: 20">

- **Output**:
  <br>
  <img src="https://github.com/user-attachments/assets/0fec7f48-512a-493a-aae1-18e033216a87" alt="concat" width="400" style="margin-right: 20">  <br>
  <img src="https://github.com/user-attachments/assets/bd51289a-aaa8-419c-87f6-728220d6d130" alt="concat" width="400" style="margin-right: 20">

### Developed Logics:

#### A) Face_recognition

This program utilizes live video streaming to identify "Dinesh Datta" through face recognition and provide instant feedback.
1. **Loading and Encoding Reference Data**: A stored image of "Dinesh Datta" is processed and encoded into a set of facial features, serving as a reference for real-time comparison. 
2. **Camera Initialization**:The program accesses the webcam to capture live video frames for face detection and recognition tasks.  
3. **Face Matching Logic**: Detected faces in the video are encoded, and their similarity to the reference encoding is measured. A match is confirmed if the calculated distance is below the confidence threshold (0.6).  
4. **Real-Time Annotation**: Matched faces are marked with a green rectangle and labeled "Dinesh," while unmatched faces are displayed with "Not Dinesh" for clarity.  
5. **Live Feedback Loop**:The program displays the annotated video feed in real time and stops processing when 'q' is pressed.
   
- **Input**:
This program utilizes live video streaming to identify "Dinesh Datta" through face recognition and provide instant feedback.
1. **Loading and Encoding Reference Data**: A stored image of "Dinesh Datta" is processed and encoded into a set of facial features, serving as a reference for real-time comparison. 
2. **Camera Initialization**:The program accesses the webcam to capture live video frames for face detection and recognition tasks.  
3. **Face Matching Logic**: Detected faces in the video are encoded, and their similarity to the reference encoding is measured. A match is confirmed if the calculated distance is below the confidence threshold (0.6).  
4. **Real-Time Annotation**: Matched faces are marked with a green rectangle and labeled "Dinesh," while unmatched faces are displayed with "Not Dinesh" for clarity.  
5. **Live Feedback Loop**:The program displays the annotated video feed in real time and stops processing when 'q' is pressed.
   
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat"  width="400" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20">


#### B) Attendence_save
This program uses real-time face recognition to track and record attendance via a webcam. It saves recognized face details in an Excel file after detecting a set number of matches.

1. **Loading Known Face**: Loads a known image and extracts facial encodings for comparison.
2. **Camera Initialization**: Captures video from the webcam, processing every second frame to improve performance.
3. **Face Detection and Recognition**: Detects faces in each frame and compares them with the known face encoding. If a match is found, it draws a rectangle around the face and labels it.
4. **Attendance Recording**: If recognized, the name, date, and time are recorded in a DataFrame (`df`). After 5 recognitions, the data is saved to an Excel file (`attendence_Save.xlsx`) and the counter resets.
5. **Real-time Display**: The processed video stream is displayed with face bounding boxes, and "Not Recognized" is shown if no match is found.
6. **Termination**: The video feed stops when the 'q' key is pressed, and any remaining data is saved to the Excel file before the program ends.


- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat"  width="400">
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/Attention%20Score/Attention%20Score%20Screenshots/Attention_score.png" alt="concat" width="400" style="margin-right: 20">
  
#### C) test
This program tracks and logs face recognition in real-time while managing duplicate entries.

1. **Initialization**: Sets up known face encodings, logging DataFrame, and camera capture.  
2. **Frame Processing**: Skips frames for optimized performance and detects faces in the live video.  
3. **Recognition Logic**: Identifies "Dinesh Datta" based on proximity to known face encodings and draws labels.  
4. **Time-Based Entry Rules**: Ensures duplicate entries are avoided unless a 5-minute gap occurs.  
5. **Automatic Data Storage**: Periodically saves attendance logs to an Excel file every 30 seconds.  
6. **Error Handling and Cleanup**: Safely handles exceptions, saves logs, and releases resources on exit. 
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400" >
- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_sc_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### D) tools
This program identifies and logs the presence of a specific individual, "Dinesh Datta," in real-time.

1. **Face Recognition Initialization**: Encodes a known face image for comparison in live video feed.  
2. **Live Camera Feed**: Captures frames while skipping every second frame to optimize processing.  
3. **Real-Time Face Detection**: Detects faces and identifies Sahil using a confidence threshold.  
4. **Dynamic Data Logging**: Saves recognition details (name, date, time) to an Excel file after five detections.  
5. **On-Screen Labels**: Displays labels "Sahil" or "Not Dinesh Datta" based on recognition results in the video feed.  
6. **Final Data Storage**: Ensures attendance data is saved when the program exits.  
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400">
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_sc_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### E) excel_sc

This program recognizes a specific person (e.g., "Dinesh Datta") using face recognition and logs the details along with screenshots at set intervals.
1. **Face Recognition**: Detects faces and compares them with a known image.
2. **Screenshot Capture**: Saves screenshots of recognized faces at defined intervals (every 2 minutes or after a 5-minute gap).
3. **Data Logging**: Logs recognition data (name, date, time, screenshot path) in an Excel file.
4. **Efficiency**: Processes every other frame to reduce CPU usage.
5. **Face Labeling**: Labels recognized faces as "Sahil" and others as "Not Dinesh Datta".
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400" >
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_sc_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### F) excel_sc_dt

This program captures webcam video, performs real-time face recognition for "Dinesh Datta," saves screenshots, and logs attendance details into an Excel file.
1. **Face Detection and Encoding**:Loads a pre-saved image of "Dinesh Datta," encodes it, and compares it with faces detected in the live webcam feed.  
2. **Recognition Logic**:Uses a confidence threshold to determine if the detected face matches the known encoding. Faces are recognized and logged every 2 minutes, with a 5-minute gap for repeat entries.  
3. **Screenshot Saving**:Captures screenshots of recognized faces with the current date and time, overlays the timestamp, and stores them in a dedicated directory (`screenshots`).  
4. **Attendance Logging**:Logs recognition details, including name, date, time, and screenshot file path, into an Excel file (`excel_sc_dt.xlsx`) for easy access.  
5. **Real-Time Feedback**:Displays a live video feed with bounding boxes around detected faces, labeling recognized faces as "Dinesh Datta" and others as "Not Dinesh Datta."  
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat"  width="400">
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc_dt/excel_sc_dt_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### G) landmark
This program combines face recognition, facial landmark detection, and attentiveness analysis to monitor real-time behavior.

1. **Setup**: Initializes facial detection, landmark predictor, and loads "Dinesh Datta's" face encoding.  
2. **Camera Stream**: Captures live video, processing alternate frames for efficiency.  
3. **Face Recognition**: Matches detected faces with "Dinesh Datta" based on encoding distance.  
4. **Attentiveness Analysis**: Calculates head pose and evaluates attentiveness using yaw and pitch.  
5. **Logging**: Saves screenshots and logs recognition details in an Excel file (`landmark.xlsx`).  
6. **Display and Cleanup**: Shows live feedback and terminates with 'q', releasing resources and saving logs.
7. 
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400" >
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/excel_sc/excel_dt.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/landmark_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### H) atten_score
This program uses real-time face recognition and head pose analysis to evaluate attentiveness based on yaw and pitch. It saves the details of the recognized face, attentiveness score, and screenshots in an Excel file and a designated folder.

1. **Face Recognition**: Detects and matches faces with a known image.
2. **Head Pose Analysis**: Calculates yaw and pitch to assess attentiveness.
3. **Attentiveness Score**: Computes a score based on head pose to determine if the person is attentive.
4. **Screenshot Capture**: Saves a screenshot if the person is attentive.
5. **Data Logging**: Records recognition details and attentiveness in an Excel file.

- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400" >
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/Attention%20Score/Attention%20Score%20Screenshots/Attention_score.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/Attention%20Score/Attention%20Score%20Screenshots/attention_score_dinesh.png" alt="concat" width="400" style="margin-right: 20">


#### I) avg_atten_score
This program uses face recognition and head pose analysis to evaluate attentiveness, saving the results in an Excel file with average attention scores.

1. **Face Recognition**: Matches faces against a known image (e.g., Barack Obama).
2. **Head Pose Analysis**: Detects head yaw and pitch to evaluate attentiveness.
3. **Attentiveness Score**: Calculates an attention score based on head orientation.
4. **Screenshot Capture**: Saves screenshots when the user is attentive.
5. **Data Logging**: Logs recognition and attentiveness data into an Excel file.
6. **Average Score**: Computes and logs the average attentiveness score over time.
- **Input**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/My_Pic.jpeg" alt="concat" width="400" >
- **Output**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/Attention%20Score/Attention%20Score%20Screenshots/Attention_score.png" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Face_Recognition/Avg_Attention_Score/avg_attention_score_dinesh.png" alt="concat" width="400" style="margin-right: 20">
