# MSD
Mobile phone screen surface defect segmentation dataset.<br/>
This dataset contains 3 types of surface defects: Oil, Scratch and Stain. It consists of 1200 images and 400 images for each defects. The defects are made by ourselves. The images are collected by industrial camera and the resolution is 1920×1080. The dataset is randomly divided into train:val:test=6:2:2. The dataset format is PASCAL VOC.<br/>
The dataset is made and presented by Open Lab on Human Robot Interaction, Peking University. <br/>

Image Capture<br/>
<img src="./images/camera.jpg" width="30%" height="30%">

Samples<br/>
<img src="./images/samples.png" width="90%" height="90%">

## Download
[MSD.zip](https://1drv.ms/u/s!AhqlXalcO8TlgRKyInEuzzgqRyX_?e=PGrti1) (1.57GB, OneDrive) <br/>
[Visualiztion.zip](https://1drv.ms/u/s!AhqlXalcO8TlfDDVBBg32DIno0U?e=5vP1Pe) (79.0MB, OneDrive) for visualization.<br/>
## Citation
If you find this work is helpful in your research, please cite:
````
@inproceedings{zhang2022fdsnet,
  title={FDSNeT: An Accurate Real-Time Surface Defect Segmentation Network},
  author={Zhang, Jian and Ding, Runwei and Ban, Miaoju and Guo, Tianyu},
  booktitle={ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={3803--3807},
  year={2022},
  organization={IEEE}
}
````
## Related work
**MVTec AD** ([website](https://www.mvtec.com/company/research/datasets), [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Bergmann_MVTec_AD_--_A_Comprehensive_Real-World_Dataset_for_Unsupervised_Anomaly_CVPR_2019_paper.pdf))<br/>
**DAGM** ([website](https://conferences.mpi-inf.mpg.de/dagm/2007/prizes.html))<br/>
**NEU surface defect database** ([website](http://faculty.neu.edu.cn/songkechen/zh_CN/zhym/263269/list/index.htm))
