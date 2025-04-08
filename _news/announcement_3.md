---
layout: post
title: MTech Thesis Poster Presentation in WSAI Annual Research Showcase
date: 2024-05-16 17:46:00-0400
inline: false
related_posts: false
---



### Summary of the Poster: Wireless Sensing Aided Foveation for Surveillance Videos

**Authors:** Jasmin Karki and Ayon Chakraborty  
**Affiliation:** Sensing and Network Systems Engineering (SENSE) Group, Department of CSE, IIT Madras  

---
#### ![**Abstract**](https://docs.google.com/document/d/1HxJAWQGY8p3FQp66MEX4V-EazEKd1pzc/edit?usp=sharing&ouid=113300708854029693901&rtpof=true&sd=true)

---
#### **Objective**
A novel approach to enhance surveillance video processing by leveraging wireless sensing for Region of Interest (RoI) estimation. The work aims to reduce the computational burden on camera hardware while enabling battery-operated solutions for surveillance systems.

---

#### **Key Challenges**
1. **Resource-Intensive RoI Estimation:**  
   - Deep learning-based methods for RoI estimation are accurate but computationally expensive.  
   - Continuous inferencing on modest camera hardware prevents energy-efficient operation, making battery-powered solutions impractical.

2. **Need for Low-Cost Alternatives:**  
   - A low-cost sensing modality is required to determine RoI without relying solely on camera sensors.

---

#### **Proposed Solution**
**Wireless Radios as Sensors:**  
- Wireless signals (WiFi and UWB) are utilized as alternative sensing modalities to estimate RoI in surveillance videos.  
- This approach minimizes the need for continuous camera operation, improving energy efficiency.

---

#### **Methodology**
1. **Wireless Sensing Aided RoI Estimation:**  
   - Wireless signals are analyzed to detect occupancy and activity in the scene, aiding in RoI determination without involving the camera directly.

2. **Dataset Collection:**  
   - Over 7 hours of data were collected, including indoor and outdoor surveillance videos paired with wireless Channel State Information (CSI) traces (2.16 million samples).  
   - Both WiFi (20 MHz bandwidth) and UWB (500 MHz bandwidth) radios were used for sensing.  
   - Ground truth data was obtained using cameras and LiDAR, capturing reflector locations and depth information.

---

#### **Applications**
The proposed system can be applied to various surveillance tasks, such as:  
- Occupancy detection  
- Vehicle classification  
- Number plate recognition  

---
