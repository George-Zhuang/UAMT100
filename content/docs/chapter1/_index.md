---
# Title, summary, and page position.
linktitle: Brief introduction
summary: A brief introduction to videos and attribute distribution in UAMT100 benchmark.
weight: 1
icon: book
icon_pack: fas

# Page metadata.
title: Brief introduction
date: "2021-09-15T00:00:00Z"
type: book  # Do not modify.
---

## UAMT100 dataset

![](/images/system.png)

The UAMT100 benchmark is designed for evaluation of  UAM tracking methods. It consists of 100 image sequences, which are captured from UAM perspectives. For subsequent tasks of UAM tracking, such as grasping, it represents various possibilities of UAM’s tracking the object in an indoor environment. 16 kinds of objects are involved, and 11 attributes are annotated for each sequence. The objects include ball, battery, bear (toy), bottle, box, duck (toy), express, gate (model), milk, minions, pen, penholder, and radar. The videos are recorded at 10 frames per second (fps), with the JPG image resolution of 800×600 pixels.

![](/images/dataset.png)

This figure demonstrates four scenarios of UAM tracking in UAMT100. The first row is from the third perspectives, while below are captured by UAM camera,  with frame number marked above. 100 well-annotated  image sequences from  are provided in the link below. 

{{< icon name="download" pack="fas" >}} <a href="https://drive.google.com/file/d/1V-_EWT-zj4acxR2Uz6SvvZDcZkV4ALFO/view?usp=sharing">Google Drive</a>

{{< icon name="download" pack="fas" >}} <a href="https://pan.baidu.com/s/1f6ytf9ZYtg9ff8J_PuznLw">BaiduYun (pw:v4r0)</a>

If the videos from the first or third perspective are required, please contact <a href="https://zhengguangze.netlify.app/">Guangze Zheng</a>.

## UAMT100 attributes

UAMT100 benchmark covers common challenges of UAV tracking and also introduces attributes peculiar to practical UAM tracking.  The attributes include common challenges of object tracking, i.e., aspect ratio change (ARC), background clutter (BC), low illumination (LI), object blur (OB), out-of-view (OV), partial occlusion (POC), scale variation (SV), similar object (SOB), and viewpoint change (VC). Besides, some challenging scenarios especially for UAM tracking are also considered, e.g., UAM attack (UAM-A) and wind disturbance (WD). Among WD, an industrial fan is used. Besides, wind speed and wind direction are taken into account. The distribution of the attributes is shown in this histogram.

![](/images/attribute.png)

