# 🔥 Awesome-IRSTD-Datasets

**Authors:** Dianfang Sun (孙殿芳), Siyu Chen (陈思予), Zhe Chen (陈哲), Zihao Xiong(熊子豪), Yimian Dai (戴一冕)\*

[中文版请见: Awesome IRSTD Dataset](https://grokcv.ai/blog/awesome-irstd-dataset/%E7%BA%A2%E5%A4%96%E5%BC%B1%E5%B0%8F%E7%9B%AE%E6%A0%87%E6%95%B0%E6%8D%AE%E9%9B%86%E6%94%B6%E9%9B%86%E4%B8%8E%E6%95%B4%E7%90%86%E6%8A%A5%E5%91%8A/)

A curated list of public datasets for Infrared Small Target Detection (IRSTD), Tracking, and Segmentation, categorized by data source (Real-World vs. Synthetic) and sorted by release year.

## I. Real-World Datasets Overview

This section lists all public datasets collected using real infrared equipment, suitable for infrared small target detection, tracking, or segmentation tasks, sorted by release year in ascending order.

### Released in 2020

#### 1. SIRST

- **Description:** Published in **IEEE Transactions on Geoscience and Remote Sensing (TGRS)** in **2020** by the team of **Yimian Dai**. SIRST is a dataset specially constructed for single-frame infrared small target detection, in which the images are selected from hundreds of infrared sequences for different scenarios.
- **Target Type:** UAVs, Birds, etc.
- **GitHub/Project Link:** [SIRST GitHub](https://github.com/YimianDai/sirst)

#### 2. Anti-UAV 300

- **Description:** Published in **European Conference on Computer Vision (ECCV)** in **2020** by the team of **Wengang Zhou** from the **University of Chinese Academy of Sciences (UCAS-VG)**. The Anti-UAV dataset contains 318 RGB-T video pairs, each including an RGB video and a TIR video. The dataset covers various flight scenarios, primarily using DJI and Parrot UAVs.
- **Target Type:** UAVs
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/share/init?surl=A1-ynecLWfkEetRsPnh6rw) (Password: `u4ca`)
- **GitHub/Project Link:** [Anti-UAV GitHub](https://github.com/ucas-vg/Anti-UAV)
- **Note:** Data type is video

#### 3. Air/Ground Background Infrared Small Aircraft Target Detection and Tracking Dataset

- **Description:** Jointly constructed by the ATR Key Laboratory of the **National University of Defense Technology** School of Electronic Science and the 25th Research Institute of CASIC. The dataset acquisition scenes cover sky, ground, and multiple scenarios, totaling 22 data segments, 30 tracks, 16,177 frames, and 16,944 targets.
- **Target Type:** Small Aircraft
- **Download/Project Link:** [Science Data Bank](https://www.scidb.cn/en/detail?dataSetId=720626420933459968)

### Released in 2021

#### 4. Anti-UAV 410

- **Description:** Published in **IEEE/CVF International Conference on Computer Vision (ICCV)** in **2021** by the team of **Sungsu HwangBo**. It includes 410 video sequences, totaling over 438k bounding boxes, specifically designed to address UAV tracking challenges. It focuses on replicating anti-UAV tracking issues in real-world scenarios, i.e., small UAV target tracking under long-range imaging.
- **Target Type:** UAVs
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/s/1R-L9gKIRowMgjjt52n48-g?pwd=a410) (Password: `a410`)
- **GitHub/Project Link:** [Anti-UAV410 GitHub](https://github.com/HwangBo94/Anti-UAV410)
- **Note:** Data type is video

#### 5. Infrared Image UAV Detection Dataset

- **Description:** Published in **17th International Conference on Signal Image Technology & Internet based Systems (SITIS)** in **2023** by the team of **P. Bhattacharya**, **P. Nowak**, et al. A public drone dataset containing images of drones from different cameras of different resolutions along with the respective annotation files in xml format.
- **Target Type:** UAVs
- **Download Link:** [Mega.nz Download](https://mega.nz/file/aro2VZCK#0qcLqHvfc7X-SV3caVkvCypWF4Hl9QxhCfCv1xv2vY0)
- **GitHub/Project Link:** [Drone-Detection-Dataset GitHub](https://github.com/purbaditya/Drone-Detection-Dataset)

#### 6. Drone detection (Multi-Sensor)

- **Description:** Published in **Data in Brief** in **2021** by the team of **Fredrik Svanström**, **Fernando Alonso-Fernandez**, and **Christer Englund**. The Drone detection dataset is a multi-sensor UAV detection and tracking dataset, containing infrared and visible light videos and audio files. It covers category labels such as UAVs, birds, aircraft, helicopters, and background noise.
- **Target Type:** UAVs, Birds, etc.
- **Download/Project Link:** [Drone Detection Thesis GitHub](https://github.com/DroneDetectionThesis/Drone-detection-dataset)
- **Note:** Dataset includes IR, visible video, and audio files

### Released in 2022

#### 7. IRSTD-1k

- **Description:** Published in **Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)** in **2022** by the team of **Mingjin Zhang** and **Rui Zhang** from the **University of Sydney** and **Xidian University**. It contains 1000 images captured from real infrared systems. These images cover diverse backgrounds (sky, clouds, ground), with rich variations in target size and SNR, and provide pixel-level segmentation masks.
- **Target Type:** UAVs, Birds, etc.
- **Download Link:** [Google Drive Download](https://drive.google.com/file/d/1JoGDGF96v4CncKZprDnoIor0k1opaLZa/view)
- **GitHub/Project Link:** [ISNet GitHub](https://github.com/RuiZhang97/ISNet)

#### 8. ISDD (Infrared Ship Detection Dataset)

- **Description:** Published in **IEEE Access** in **2022** by the team of **Yaqi Han**. A public dataset containing 1284 IR remote sensing images and 3061 ship instances. Images are sourced from the Landsat8 satellite, after pre-processing with radiometric calibration and FLAASH atmospheric correction.
- **Target Type:** Ships (Inshore and Offshore scenes)
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/share/init?surl=VfCbiWnjPoXoI4MaH0VkXw) (Password: `asdf`)
- **GitHub/Project Link:** [ISDD GitHub](https://github.com/yaqihan-9898/ISDD)

### Released in 2023

#### 9. SIRST v2

- **Description:** Published in **IEEE Transactions on Geoscience and Remote Sensing** in **2023** by the team of **Yimian Dai** et al.
- **Target Type:** UAVs, Birds, etc.
- **GitHub/Project Link:** [Open-SIRST-v2 GitHub](https://github.com/YimianDai/open-sirst-v2)

#### 10. Anti-UAV 600

- **Description:** Released in **CVPR Workshop on Anti-UAV Challenge (VPR 2023)** in **2023** by the team of **Jingjing Ma**. High-quality, full-HD thermal infrared UAV video sequences released by the VPR 2023 Workshop 3rd Anti-UAV Challenge.
- **Target Type:** UAVs
- **Download/Project Link:** [ModelScope Link](https://modelscope.cn/models/iic/3rd_Anti-UAV_CVPR23/summary)
- **GitHub/Project Link:** [Anti-UAV Challenge](https://anti-uav.github.io/dataset/)
- **Note:** Data type is video

#### 11. IR Small Targets Dataset (Kaggle)

- **Description:** A public dataset on the Kaggle website. Contains infrared spectrum images of UAVs, aircraft, and helicopters and their labels (bounding box coordinates).
- **Target Type:** UAVs, Aircraft, etc.
- **Download/Project Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/llpukojluct/ir-small-target)

#### 12. NUDT-SIRST-Sea

- **Description:** Published in **IEEE Transactions on Geoscience and Remote Sensing (TGRS)** in **2023** by the team of **Tianhao Wu** from the **National University of Defense Technology**. A **real space-based** remote sensing IR image dataset. Images are sourced from the Landsat8 satellite, reflecting real-world ship targets in the ocean.
- **Target Type:** Large cruise ships, medium oil recovery wells, small yachts, tiny ships
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/s/1cDLlkQb8STkjp74Y7YBA2w) (Password: `ad7w`)
- **GitHub/Project Link:** [Multi-level-TransUNet GitHub](https://github.com/TianhaoWu16/Multi-level-TransUNet-for-Space-based-Infrared-Tiny-ship-Detection)

### Released in 2024

#### 13. MMFW-UAV

- **Description:** Published on the **Science Data Bank** in **2024** by the team of **Nanjun Huang**. A multi-sensor, multi-view **fixed-wing** UAV dataset designed for air-to-air vision tasks. It contains 147,417 fixed-wing UAV images collected using different types of sensors (including thermal sensors).
- **Target Type:** UAVs
- **Download/Project Link:** [Science Data Bank](https://www.scidb.cn/en/detail?dataSetId=edb443cfcfa142019499bbfd68542cc9)
- **Note:** Multi-modal image data, includes IR images

### Released in 2025

#### 14. SIRST-UAVB

- **Description:** Published in **AAAI** in **2025** by the team of **Jiangan Yang**. Contains 3000 IR images for UAVs and birds, collected across different seasons, weather conditions, and complex backgrounds. Targets are manually annotated via trajectory.
- **Target Type:** 1742 bird and 2955 UAV BBox labels.
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/share/init?surl=FIg6BU8jlZogEQYWx_-ubQ&pwd=0558) (Password: `0558`)
- **GitHub/Project Link:** [PConv-SDloss-Data GitHub](https://github.com/JN-Yang/PConv-SDloss-Data)

#### 15. RealScene-ISTD

- **Description:** Published in **arXiv** in **2025** by the team of **Luyu Song** from **Guangdong University of Technology**. A cross-domain IR small target dataset developed by Guangdong University of Technology, containing 739 **UAV-captured images**, covering targets of various scales, multi-motion states, and complex backgrounds.
- **Target Type:** Various small targets from a UAV perspective
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/s/1BAY9N4xEtw57_v3TjHrSpg?pwd=trnh#list/path=%2F)
- **GitHub/Project Link:** [RealScene-ISTD GitHub](https://github.com/luy0222/RealScene-ISTD)

## II. Synthetic/Semi-Synthetic Datasets Overview

This section lists public datasets created using synthetic or semi-synthetic techniques, sorted by release year in ascending order.

### Released in 2019

#### 1. MDvsFA

- **Description:** Published in **Neurocomputing** in **2019** by the team of **Huan Wang**. High-resolution IR natural scene images are first collected from the network as a background library and cropped to form diverse backgrounds; then, small targets separated from real images or targets synthesized by a 2D Gaussian function are superimposed onto the backgrounds.
- **Target Type:** Synthetic Targets
- **GitHub/Project Link:** [MDvsFA_cGAN GitHub](https://github.com/wanghuanphd/MDvsFA_cGAN)
- **Note:** Semi-Synthetic

#### 2. Semi-Synthetic Dataset for IR Small Moving Target Detection in Complex Backgrounds

- **Description:** Published on the **Science Data Bank** in **2019** by the team of **Bingwei Hui** et al. Targeting airborne infrared detection platforms, data is collected using a small UAV equipped with an IR detector, and **synthetic targets are embedded** to simulate long-distance airborne targets. The dataset contains 350 image sequences and 150,185 images.
- **Target Type:** Synthetic Targets
- **Download/Project Link:** [Science Data Bank](https://www.scidb.cn/en/detail?dataSetId=720626420933459968)
- **Note:** Semi-Synthetic

### Released in 2021

#### 3. NUDT-SIRST

- **Description:** Published in **Pattern Recognition (PR)** in **2021** by the team of **Xingxing Ye** from the **National University of Defense Technology**. NUDT-SIRST is a synthetic dataset containing 1327 images with $256 \times 256$ resolution.
- **Target Type:** Synthetic Targets
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/share/init?surl=WdA_yOHDnIiyj4C9SbW_Kg&pwd=nudt) (Password: `nudt`)
- **GitHub/Project Link:** [IR-Small-Target-Detection GitHub](https://github.com/YeRen123455/Infrared-Small-Target-Detection)
- **Note:** Fully Synthetic

### Released in 2023

#### 4. NUST-MIRSDT

- **Description:** Published in **Remote Sensing** in **2023** by the team of **Runjie Li** from the **National University of Defense Technology**. NUDT-MIRSDT is a synthetic dataset containing 120 sequences. 80 sequences are used for training and 20 sequences are used for testing.
- **Target Type:** Synthetic Targets
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/s/1pSN350eurMafLiHBQBnrPA?pwd=5whn) (Password: `5whn`)
- **GitHub/Project Link:** [Multi-frame-infrared-small-target-detection GitHub](https://github.com/TinaLRJ/Multi-frame-infrared-small-target-detection-DTUM)
- **Note:** Fully Synthetic

### Released in 2024

#### 5. SIRST-5k

- **Description:** Published in **IEEE Transactions on Geoscience and Remote Sensing** in **2024** by the team of **Lu, Yahao**, **Lin, Yupei**, et al. from **Guangdong University of Technology**. A negative sample enhancement method is proposed to generate a large number of negative samples for self-supervised learning. The algorithm generates a synthetic SIRST-5K dataset containing a large amount of pseudo-data and corresponding labels.
- **Target Type:** Synthetic Targets
- **Download Link:** [Google Drive Download](https://drive.google.com/file/d/13aIrY5azO4bPwSGzDCzmgpwtpmYsysaD/view)
- **GitHub/Project Link:** [SIRST-5K GitHub](https://github.com/luy0222/SIRST-5K)
- **Note:** Fully Synthetic

#### 6. DenseSIRST

- **Description:** Published in **arXiv preprint** in **2024** by the team of **Mengxuan Xiao**, **Qun Dai**, et al. It is the first IRST dataset to include both dense targets and background semantic annotation. The dataset contains 1024 high-quality IR images, annotating 13,655 densely distributed small targets. Each image pair includes a simulated dense small target image and its corresponding sky segmentation version.
- **Target Type:** Simulated Dense Small Targets
- **Download Link:** [Google Drive Download](https://drive.usercontent.google.com/download?id=1PY0d1WuCjf_3wAIjDSNhYxREVK27OLzl&export=download&authuser=0)
- **GitHub/Project Link:** [DenseSIRST GitHub](https://github.com/GrokCV/DenseSIRST)
- **Note:** Fully Synthetic

#### 7. WideIRSTD-Weak

- **Description:** Released in **ICPR 2024 Challenge** in **2024** by the team of **Xinyi Ying** from the **National University of Defense Technology**. WideIRSTD is a **comprehensive benchmark** dataset, integrating seven existing public datasets (such as SIRST-V2, IRSTD-1K, **NUDT-SIRST**, **NUDT-SIRST-Sea**, **NUDT-MIRSDT**, Anti-UAV, etc.) and additional data developed by the **National University of Defense Technology team**. It aims to evaluate infrared small target detection performance under resource constraints, covering various target shapes, wavelengths, and imaging resolutions ($256 \times 256$ to $3200 \times 3200$), and includes ground-based, air-based, and **space-based** imaging systems. The "WideIRSTD-Weak" dataset contains 6000 images with coarse point annotations (i.e., GT points around the centroid of the GT mask under a Gaussian distribution) for training, and 500 images for testing.
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/share/init?surl=x7mtLMtxpC8Oxm4sa9Y9mA&pwd=1113) (Password: `1113`)
- **GitHub/Project Link:** [WideIRSTD-Dataset GitHub](https://github.com/XinyiYing/WideIRSTD-Dataset)
- **Note:** Semi-Synthetic

#### 8. WideIRSTD-Full

- **Description:** Released in **ICPR 2024 Challenge** in **2024** by the team of **Xinyi Ying** from the **National University of Defense Technology**. WideIRSTD is a **comprehensive benchmark** dataset, integrating seven existing public datasets (such as SIRST-V2, IRSTD-1K, **NUDT-SIRST**, **NUDT-SIRST-Sea**, **NUDT-MIRSDT**, Anti-UAV, etc.) and additional data developed by the **National University of Defense Technology team**. It aims to evaluate infrared small target detection performance under resource constraints, covering various target shapes, wavelengths, and imaging resolutions ($256 \times 256$ to $3200 \times 3200$), and includes ground-based, air-based, and **space-based** imaging systems. The "WideIRSTD-Full" dataset contains 9000 images with Ground Truth (GT) mask annotations for training, and 2000 images for testing.
- **Download Link:** [Baidu Pan Download](https://pan.baidu.com/s/1qAO67_h46CWCoTyd3sot2Q?pwd=1113#list/path=%2F) (Password: `1113`)
- **GitHub/Project Link:** [WideIRSTD-Dataset GitHub](https://github.com/XinyiYing/WideIRSTD-Dataset)
- **Note:** Semi-Synthetic
