# Standard ANM Dataset
## Standard Datasets for Autonomous Navigation and Mapping: A Full-Stack Construction Methodology

### Authors: 
[Yuanzhi Liu](https://github.com/lyzrose), [Yujia Fu](https://github.com/yayafu666)†, [Minghui Qin](https://github.com/SJTU-qin)†, [Yufeng Xu](https://github.com/feng15423)†, et al. († Contributed equally)

## Abstract: 
The development of intelligent Vehicles (IVs) requires extensive standard datasets for training, benchmarking, and improvement. Autonomous Navigation and Mapping (ANM), as a critical technology for IVs, imposes exceptionally high demands on dataset construction. This is significant in its requirements for comprehensive sensor calibration, precise time synchronization, and accurate generation of ground truth. Besides, the whole construction workflow also demands intricate knowledge and sophisticated practices, necessitating lengthy learning curves for researchers to attain proficiency. The above challenges have led to a slow production of qualified datasets, directly constraining the advancement of ANM. However, so far, an investigation focused on a mature construction methodology of ANM dataset is still missing. This paper strives to fill the gap. Specifically, based on our systematic reviews and extensive practices, for the first time, a full-stack construction methodology of ANM dataset is proposed, including modules of platform construction, sensor calibration, time synchronization, ground truth generation, synthetic data production, and benchmark criteria, with detailed techniques and methodological routes provided in each step. Several long-standing issues are resolved within the methodology. Importantly, we introduce versatile calibration and synchronization frameworks that attain up to us-level and mm-level precision. Besides, we propose a full-scenario ground truth system that can generate scene-map and trajectory at cm-level accuracy. To verify the effectiveness of our methodology, we design a high-quality dataset and benchmark multiple state-of-the-art algorithms on it. The successful workflow demonstrates that our methodology can significantly reduce the research threshold and help individuals and institutions to construct datasets in a standardized way.

# News!!! 2024-12
### We introduce two new datasets into our standard dataset community: SEIEE + YULAN

## SEIEE Datasets: Office Building (indoor)

* **Specifications**: **10 sequences**, **6.3 km**, **21140 m<sup>2</sup>**
* **Timeslots**: `Night` `Afternoon`
* **Challenges**: `Low-texture` `Degradation` `Lighting Change`
* **Senarios**: `Long Corridor` `White Wall` `Reflective Floor`
* **Sensors**: `Stereo Vision` `Spining+MEMS LiDAR` `IMU` `Wheel Odom`

Stat/Sequence|1010-00|1010-01|1010-02|1010-03|1010-04
:--:|:--:|:--:|:--:|:--:|:--:
Size/GB|24.3/4.8|25.0/5.1|26.3/5.3|41.7/8.2|13.8/2.9
Distance/m|530.9|579.8|615.7|923.9|317.0
Duration/s|481.7|499.3|516.5|808.3|281.0
VLIO-rosbag|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgR8OD_GYDqwF4fUv?e=eZ3tKb) [baidu](https://pan.baidu.com/s/1SsSHVatM52tmVIb9c2JQCA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgR5NdkVvv5-jwg9S?e=BpTw3M) [baidu](https://pan.baidu.com/s/1e1nvLn6kNRXW_8ZkAF-DUw?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgSIMMHWnaIRWOQEh?e=1fTNoL) [baidu](https://pan.baidu.com/s/1LrHyfvJAxyBma82iGaVL7g?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgSC5ZoiW8ff5VxW1?e=RBOYIK) [baidu](https://pan.baidu.com/s/1NohF3MTXmjfKZNMEn3hVdA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgSFxGk-1Y0cnuzGi?e=0L8HcO) [baidu](https://pan.baidu.com/s/1m37eIgWroUVa9jBSDw4NQA?pwd=sjtu)
LIO-rosbag|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgQ_K8PgFz_LvzIiZ?e=PQdgRs) [baidu](https://pan.baidu.com/s/1olc4R9P04dEz8XRQicdWfg?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRXMxjKNsiS-zBZ5?e=75pZVv) [baidu](https://pan.baidu.com/s/1dxjVL6SKLWYkGeObFeWyjQ?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRd_2k4zpH111fZ8?e=w6xjtp) [baidu](https://pan.baidu.com/s/1rg0p53cHUlwh0HN-hMT70w?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRNIbWeKNmQY2WM2?e=5LycAJ) [baidu](https://pan.baidu.com/s/1PIhjam4ld3sIvGiQ6t1bSA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgRDbU7qgJKgHbHab?e=94tdSe) [baidu](https://pan.baidu.com/s/1ss1E3gMQeLkF1dYAPgsNEQ?pwd=sjtu)
GT-pose|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgS_Biux3orZVTdMN?e=3cTevn) [baidu](https://pan.baidu.com/s/1w6-pZgiYUuayqVNZ06AjLw?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgS6Gv7ORcQiXVBGK?e=Y4pNZH) [baidu](https://pan.baidu.com/s/1FZ4B9lHqvmAEp7Bu6sWBHQ?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgTFNhUa1t8UAwOW-?e=LObN5Z) [baidu](https://pan.baidu.com/s/1KaC7Jv9AIiKbyk4if9aWjw?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgTIwW7NjK-WwWf4q?e=ocEbf5) [baidu](https://pan.baidu.com/s/1JeRKOwvSYJtVxuQSJL5Z7g?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgTAY15W3IY99Brww?e=6YuWub) [baidu](https://pan.baidu.com/s/1FRSdtV0A47cnMfL5BcHeBg?pwd=sjtu)

Sensor/Device|Model|Specification
:--:|:--:|:--:
Gray Stereo | DALSA M1930 | 1920*1200, 2/3", 71°×56°FoV, 40Hz
RGB Stereo | DALSA C1930 | 1920*1200, 2/3", 71°×56°FoV, 40Hz
LiDAR | Velodyne VLP16 | 16C, 360°×30°FoV, ±3cm@100m, 10Hz
MEMS LiDAR | Livox AVIA | 70°×77°FoV, ±2cm@200m, 10Hz
D-GNSS/INS | Xsens Mti-680G | 9-axis, 400Hz, GNSS not in use
Consumer IMU | BMI088 | 6-axis, 200Hz, Livox built-in
Wheel Encoder | Scout V1.0 | 4WD, 3-axis, 200Hz
GT 3D Scanner | Leica RTC360 | 130m range, 1mm+10ppm accuracy

<div align="left">
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_00.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_01.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_02.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_00.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_01.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_02.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_03.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_04.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_05.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_03.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_04.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_05.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_06.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_07.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/cam/seiee_rgb_08.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_06.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_07.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/seiee/sem/seiee_sem_08.png" alt="photo" width="30%" />
</div>

## YULAN Datasets: Residential Community (outdoor)

* **Specifications**: **14 sequences**, **9.4 km**, **32665 m<sup>2</sup>**
* **Timeslots**: `Noon` `Afternoon`
* **Challenges**: `GNSS-Denied` `Dynamics`
* **Senarios**: `Dense Building` `Road` `Court` `Car` `Person`
* **Sensors**: `Stereo Vision` `Spining+MEMS LiDAR` `IMU` `Wheel Odom`

Stat/Sequence|1008-00|1008-01|1008-02
:--:|:--:|:--:|:--:
Size/GB|25.9/5.0|36.6/6.9|36.3/6.9
Distance/m|665.8|952.1|932.5
Duration/s|511.4|721.6|711.0
VLIO-rosbag|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgQZWz_hh_SyM1gEz?e=OPmu7n) [baidu](https://pan.baidu.com/s/1bFsLGj4OQZmeNAdku7SXpQ?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgQfe7Gj0PBb4Mut-?e=acEk1l) [baidu](https://pan.baidu.com/s/1IhcZPkvy1QMV2bKDbNc_vQ?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgQhEDtTvt4n0ZM8y?e=ibMQkn) [baidu](https://pan.baidu.com/s/1PlJLajKHAYs1851zGhfWdQ?pwd=sjtu)
LIO-rosbag|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqceDzOQZW98sPX9ZY?e=Gm6gcW) [baidu](https://pan.baidu.com/s/1pRFsUCb7lYqqhUhD-ctrLA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqceRw-abxW2BWHj-w?e=bQogaL) [baidu](https://pan.baidu.com/s/10-tbexKqpz8VyZWr3--WSA?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcej_DEvnbox7f8Fc?e=V7jUNB) [baidu](https://pan.baidu.com/s/1TZ-8F1XMKZS0wybhn2ne5A?pwd=sjtu)
GT-pose|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgThtn__ZfM9RRXeZ?e=sBUEZQ) [baidu](https://pan.baidu.com/s/1W6Xx2tZW1M6kzXZQBDLneg?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgTogvSOPiykObqVi?e=T1rLxE) [baidu](https://pan.baidu.com/s/1TFvYsnbqIWyeTO13ddPK1g?pwd=sjtu)|[onedrive](https://1drv.ms/u/s!AhiXYfoNKvqcgTnOXbY404MTPOsY?e=iJqq8r) [baidu](https://pan.baidu.com/s/16xjsAMstuvUIySO30KsfXA?pwd=sjtu)

Sensor/Device|Model|Specification
:--:|:--:|:--:
Gray Stereo | DALSA M1930 | 1920*1200, 2/3", 71°×56°FoV, 40Hz
RGB Stereo | DALSA C1930 | 1920*1200, 2/3", 71°×56°FoV, 40Hz
LiDAR | Velodyne VLP16 | 16C, 360°×30°FoV, ±3cm@100m, 10Hz
MEMS LiDAR | Livox AVIA | 70°×77°FoV, ±2cm@200m, 10Hz
D-GNSS/INS | Xsens Mti-680G | 9-axis, 400Hz, GNSS not in use
Consumer IMU | BMI088 | 6-axis, 200Hz, Livox built-in
Wheel Encoder | Scout V1.0 | 4WD, 3-axis, 200Hz
GT 3D Scanner | Leica RTC360 | 130m range, 1mm+10ppm accuracy

<div align="left">
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_00.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_01.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_02.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_00.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_01.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_02.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_03.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_04.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_05.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_03.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_04.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_05.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_06.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_07.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/cam/yulan_rgb_08.jpg" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_06.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_07.png" alt="photo" width="30%" />
<img src="./pics/photo_pairs/yulan/sem/yulan_sem_08.png" alt="photo" width="30%" />
</div>

## Citation
If our efforts support your research, please cite: <br />


```
@ARTICLE{liu2024standarddata,
  author={Liu, Yuanzhi and Fu, Yujia and Qin, Minghui and Xu, Yufeng and Cui, Bin and Liu, Kunhua and Chen, Fengdong and Tao, Wei and Vlaminck, Michiel and Goossens, Bart and Sun, Poly Z.H. and Zhao, Hui},
  journal={IEEE Transactions on Intelligent Vehicles}, 
  title={Standard Datasets for Autonomous Navigation and Mapping: A Full-Stack Construction Methodology}, 
  year={2024},
  pages={1-24},
  doi={10.1109/TIV.2024.3360273}}
```