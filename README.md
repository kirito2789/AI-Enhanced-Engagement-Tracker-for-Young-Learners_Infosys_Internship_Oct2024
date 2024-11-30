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
