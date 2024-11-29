# Content for README.md

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


#### A) Image Concatenation
Resizes two images to a specified pixel range and merges them both horizontally and vertically, displaying the results in separate windows.
- **Input**:
  <br>
   <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-1.webp" alt="concat" width="400" style="margin-right: 20"> <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/car-2.jpeg" alt="concat" width="400" style="margin-right: 20">

- **Output**:
  <br>
  <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/vertical_merge.jpg" alt="concat" > <img src="https://github.com/kirito2789/AI-Enhanced-Engagement-Tracker-for-Young-Learners_Infosys_Internship_Oct2024/blob/main/Infosys%20Springboard%201/Images/horizontal_merge.jpg" alt="concat" >

