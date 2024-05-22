# Human-Pose-Estimation
Human pose estimation or human activity recognition (HAR) has received great attention from computer vision researchers in the last decade due to the broad variety of possible applications in different areas, such as automated video surveillance, health care services, human-computer interaction or autonomous driving. By leveraging advanced algorithms and machine learning techniques, computer vision systems are able to analyze and understand human actions, gestures, and movements from visual data.
In this phase, we propose and analyze two implementations of computer vision algorithms in order to classify human activity recognition. First two classic computer vision techniques, followed by several deep learning methods are tested in order to compare them. The comparison is based on the model accuracy and speed, which will be evaluated using plots and reports.

As a second step, frames are extracted from the videos. The value decided for frames per second is a crucial parameter since it not only reflects on the dataset size, but also choosing a high value for framed extracted per second will result in sequential images that hardly differ, which will effect on the learning process later.
The initial number of images was about 4000 images which later reduced to about 2500 images due to filtering.
An instance for each class of the dataset is shown:
<div style="display: flex;">
    <img src="Data\Picture1.png" alt="Image 1">
</div>
Distribution of dataset classes
<div style="display: flex;">
    <img src="Data\Picture2.png" alt="Image 1" style="width: 50%;">
</div>
## Results

HOG feature extractor
<div style="display: flex;">
    <img src="Data\Picture3.png" alt="Image 1">
    <img src="Data\Picture4.png" alt="Image 1">
</div>
_______________________________________________________________________________________

LBP feature extractor
<div style="display: flex;">
    <img src="Data\Picture5.png" alt="Image 1">
    <img src="Data\Picture6.png" alt="Image 1">
</div>
_______________________________________________________________________________________

### Deep learning approaches
CNN model
<div style="display: flex;">
    <img src="Data\Picture7.png" alt="Image 1">
    <img src="Data\Picture8.png" alt="Image 1">
</div>
_______________________________________________________________________________________

Inception-V3 
<div style="display: flex;">
    <img src="Data\Picture9.png" alt="Image 1">
    <img src="Data\Picture10.png" alt="Image 1">
</div>
_______________________________________________________________________________________

YOLOv8
<div style="display: flex;">
    <img src="Data\Picture11.png" alt="Image 1">
</div>
