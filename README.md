# MAVREC: Multiview Aerial Visual Recognition

## Overview
MAVREC (Multiview Aerial Visual Recognition) is a comprehensive dataset that aims to enhance aerial visual perception through multi-view data integration, featuring synchronized scenes from ground and drone-mounted cameras and is designed to improve object detection models by providing a diverse set of aerial and ground-view images captured in various European landscapes.

**MAVREC got accepted in CVPR 2024 🔥🔥**


<!-- Image before Dataset section -->
![Overview of MAVREC](assets/cvpr_poster_Aritra_edits_final-min.png)

## Dataset
The MAVREC dataset includes approximately 2.5 hours of high-quality 2.7K video, over 0.5 million frames, and 1.1 million annotated bounding boxes, making it a substantial resource for advancing aerial object detection technologies.

### Download
The dataset can be downloading from [HuggingFace](https://huggingface.co/datasets/rjccv/MAVREC).

### Dataset Preview
![MAVREC Dataset](assets/MAVRECDatasetPresentationExample-2-ezgif.com-optimize.gif)

### Training

+ To run semi-supervised approach in curriculum learning look at this [Curriculum Learning]().
+ To run YoloV7 approach look here : [YoloV7](yolov7/MAVREC_README.md)
+ To run D-DETR approach look here : [Deformable-DETR](Deformable-DETR-Finetune/MAVREC_README.md)

### Citation
```
@InProceedings{Dutta_2024_CVPR,
    author = {Dutta, Aritra and Das, Srijan and Nielsen, Jacob and Chakraborty, Rajatsubhra and Shah, Mubarak},
    title = {Multiview Aerial Visual RECognition (MAVREC): Can Multi-view Improve Aerial Visual Perception?},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month = {June},
    year = {2024},
    pages = {22678-22690}
}
```
### Usage LICENSE :

The dataset is protected under the CC-BY license of Creative Commons, which allows users to distribute, remix, adapt, and build upon the material in any medium or format, as long as the creator is attributed. The license allows MAVREC for commercial use. As the authors of this manuscript and collectors of this dataset, we reserve the right to distribute the data.





