# SNIP_Pedestrian-Detection

## Introduction

This project is to re-implement the top-performing multi-scale method for generic object detection [SNIP](http://openaccess.thecvf.com/content_cvpr_2018/papers/Singh_An_Analysis_of_CVPR_2018_paper.pdf) on the pedestrian detection task. 
We use [Adapted Faster RCNN](openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_CityPersons_A_Diverse_CVPR_2017_paper.pdf) as the base detector on CityPerson dataset, which achieves remarkable improvement using a multi-scale test setting. 
We add ignore region handling into a [faster pytorch](https://github.com/jwyang/faster-rcnn.pytorch) implementation of faster R-CNN to implement the Adapted Faster RCNN. 
The code will be released soon.
