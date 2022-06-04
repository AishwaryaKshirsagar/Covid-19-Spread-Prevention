## Please visit my Portfolio website to get detailed explanation - [Covid 19 Spread Prevention](https://aishwaryakshirsagar.github.io/Portfolio_Website/post/chapter-5/)

# India Academia Connect and Nvidia AI Hackathon
* `Goal` → COVID-19 Spread Prevention
* `Training Score` → Accuracy 98%
* `Team` → Data Pirates🏴‍☠️

__GO TO:__  [`Problem Description`](#ProblemDescription) 
[`Library Used`](#Requirements) [`Team Member`](#Team-members)

---
## Problem Description
COVID-19 Spread Prevention using Computer Vision and Deep Learning

#### Social Distance Detection

The Detection will take place in 3 different ways - 

Red - Represents many people are violating Social Distance(Threshold can be set accordingly).
Yellow - Represents 2 people are together.
Green  - Represents individual people who are in Safer Zone.

<img src="https://user-images.githubusercontent.com/67967781/138292103-855aa610-5380-43a3-a65c-27c540ed485d.png" width="700" height ="350"> 

<!-- <img src="https://user-images.githubusercontent.com/67967781/138293539-a829234d-80ab-4634-92d4-cbf392405f9b.png" width="300" height ="500">
 -->
<!--  
 The Training Accuracy is as follows. The training of the Dataset was done on Tesla T100 GPU.
<img src="https://user-images.githubusercontent.com/67967781/138261722-d913bc80-23fb-4b26-96f4-3d921cce8e73.png" width="400" height ="400"> -->
 
 Dashboard 
 
 <img src="https://user-images.githubusercontent.com/67967781/138295712-d269c5d1-0fb1-4b6e-b3f0-80fdef1ca6ab.png" width="260" height ="260"><img src="https://user-images.githubusercontent.com/67967781/138295803-22f6aa87-9d7f-4483-b5b8-40ab29eaaef1.png" width="260" height ="260"><img src="https://user-images.githubusercontent.com/67967781/138295867-4d26fd85-81e6-49fa-bb50-91338b28f14b.png" width="260" height ="260">


The dataset will contain the following:

Train Dataset:
* Model 1 - Face Mask Detection : Kaggle Face Mask Detection Dataset(https://www.kaggle.com/andrewmvd/face-mask-detection) 
* Model 2 - Social Distsnce Detection : Used MS-COCO Dataset to train the model to detect person category from other 80 Categories of COCO.

Submissions are evaluated on Innovation, Accuracy and Real time Application.

## Problem Description

In recent years covid has affected our lives in a very negative way. It took the lives of many of our loved ones; many people lost their parents, children, or relatives. Not to mention our superheroes (police, doctors) who have also lost their lives while serving our country.

Covid not only took millions of lives, but it has also had an impact on many people's lifestyles and businesses; many are in severe debt, and many have had to close their doors.

To address this issue, we must first halt the spread of covid. This can be accomplished with great efficiency by utilizing AI and machine learning.

## Project Overview

In an attempt to save people's live, we tried to build a machine learning model that can detect any covid spreading activities and alert us to reduce the covid spread.

So for this problem, we imagined the scenario of the highly crowded public areas such as airports, railway stations, banks, public meetings, and parties.

<img src='files for readme\1.gif' width='600'>

<br>For finding the suspicious covid spreading activities We tried to use the camera to detect if people are following the basic advised protocols such as social-distancing, and wearing mask. Here are few samples, currently our mask detection is only working for very closed detected face, but we are working on it.

|                        Social-Distance                        |                       Mask-Detection                        |
| :-----------------------------------------------------------: | :---------------------------------------------------------: |
| <img src='files for readme\social-distance.png' width='500'>  | <img src='files for readme\mask-detected.png' width='500'>  |
| <img src='files for readme\social-distance2.png' width='500'> | <img src='files for readme\mask-detected2.png' width='500'> |

Our model measures the distance between each people with each other in a frame to detect if the social-distancing is violeted or not. It classify the people in different risk factor as red, yellow and green zone based on the number of people around them at less then given threshold (1 meter).

|              Social-Distance Sample 1              |              Social-Distance Sample 2              |
| :------------------------------------------------: | :------------------------------------------------: |
| <img src='files for readme\1test.gif' width='600'> | <img src='files for readme\3test.gif' width='600'> |

Apart from this if it detects a given number of people in red zone (high risk) then it takes the snapshot of that particular situation with all peoples position and send an email to a local authority as an alert. Also on that given situation it also make an annoucement to the public (if any speaker were connected) to remind them to maintain their social distance.

<img src='files for readme\mail.jpeg' width='400'>

## Setup

We have used yolov4 for detecting people and measuring social distance, for that we have used

- yolov4.cfg
- coco.names
- yolov4.weights (you have to download this manually from [here](https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT), as github doesn't allow to upload large files)

Also, for face and mask detection we followed the Balaji Srinivasan [tutorial](https://www.youtube.com/watch?v=Ax6P93r32KU&t=835s&ab_channel=BalajiSrinivasan) and his [repository](https://github.com/balajisrinivas/Face-Mask-Detection). But as I mentioned above, this mask detector is not performing well for far away face so we will be modifying it soon.

For the libraries requirement part you can follow uploaded [requirement.txt](https://github.com/animeshdebug7/Nvidia-Covid-19/blob/main/requirements.txt)


[__More Details__](https://gpuhackathons.org/index.php/event/india-academia-connect-ai-hackathon)

## Requirements
| Languguage & Library | version|
| :-------- | :------- |
| `python` | `3.7.11` | 
| `pandas`     | `1.1.5`|
| `numpy`      | `1.19.5`|
| `cv2`      | `4.5.3`|
| `os`      | `--`|
| `tqdm`      | `4.59.0`|
| `sklearn`    | `3.2.2`|
| `tensorflow` | `2.5.0`|
| `keras`      | `2.5.0`|
| `matplotlib` | `0.22.2.post1`|
| `YOLOv4`  |Version 4|
|`OpenCV`|
|`HTML`|
|`CSS`|
|`Flask`|

| Enviroment | Used|
| :-------- | :------- |
| `Editor`  |`JupyterLab`| 
| `Runtime type` | `CPU`| |'GPU'|


## Team Members
__`Data Pirates🏴‍☠️ (Our Team Name)`__
|Members|
|:-|
|[Animesh Singh](https://github.com/animeshdebug7)|
|[Aishwarya Kshirsagar](https://github.com/AishwaryaKshirsagar)(me)| 
|[Darkstar](https://github.com/DarkstarDream)| 
