# 🔥 Awesome-IRSTD-Datasets

A curated list of public datasets for Infrared Small Target Detection (IRSTD), Tracking, and Segmentation, categorized by data source (Real-World vs. Synthetic) and sorted by release year.

## I. Real-World Datasets

This section lists publicly available datasets collected using real infrared sensors, suitable for IRST, tracking, or segmentation tasks, and sorted by release year.

### 📅 2020

#### 1. SIRST
* **Description:** Dedicated to Single-Frame Infrared Small Target (SIRST) detection. Images are selected from hundreds of infrared sequences under diverse scenes.
* **Target Type:** UAVs, Birds, etc.
* **GitHub/Project Link:** [Link](https://github.com/YimianDai/sirst?tab=readme-ov-file)

#### 2. Anti-UAV 300
* **Description:** Contains 318 RGB-T video pairs (RGB and TIR). Covers diverse flight scenarios (DJI and Parrot UAVs, day/night, various backgrounds: buildings, clouds, forests). Each video is 25FPS and stored in MP4 format.
* **Target Type:** UAVs
* **Download Link:** [Baidu Pan](https://pan.baidu.com/share/init?surl=A1-ynecLWfkEetRsPnh6rw) (Password: `u4ca`)
* **GitHub/Project Link:** [Link](https://github.com/ucas-vg/Anti-UAV)
* **Note:** Video data.

#### 3. Air/Ground Background Infrared Small Aircraft Target Detection and Tracking Dataset
* **Description:** Jointly constructed by NUDT and the 25th Research Institute of CASIC. Scenes cover sky, ground, and multiple backgrounds. Includes 22 data segments, 30 tracks, 16,177 frames, and 16,944 targets.
* **Target Type:** Small Aircraft
* **Download/Project Link:** [Link](https://www.scidb.cn/en/detail?dataSetId=720626420933459968)

### 📅 2021

#### 4. Anti-UAV 410
* **Description:** Includes 410 video sequences with over 438k bounding boxes, designed for UAV tracking challenges. Focuses on small UAV tracking at long range in real-world scenarios (forests, mountains, lakes), which introduces dynamic clutter.
* **Target Type:** UAVs
* **Download Link:** [Baidu Pan](https://pan.baidu.com/s/1R-L9gKIRowMgjjt52n48-g?pwd=a410) (Password: `a410`)
* **GitHub/Project Link:** [Link](https://github.com/HwangBo94/Anti-UAV410)
* **Note:** Video data.

#### 5. Infrared Image UAV Detection Dataset
* **Description:** A public UAV dataset containing infrared images from different cameras and resolutions, along with corresponding XML annotation files.
* **Target Type:** UAVs
* **Download Link:** [Mega](https://mega.nz/file/aro2VZCK#0qcLqHvfc7X-SV3caVkvCypWF4Hl9QxhCfCv1xv2vY0)
* **GitHub/Project Link:** [Link](https://github.com/purbaditya/Drone-Detection-Dataset)

#### 6. Drone detection (Multi-Sensor)
* **Description:** A multi-sensor dataset for UAV detection and tracking, including infrared and visible light videos, as well as audio files. Covers categories such as UAVs, birds, aircraft, helicopters, and background noise.
* **Target Type:** UAVs, Birds, etc.
* **Download/Project Link:** [Link](https://github.com/DroneDetectionThesis/Drone-detection-dataset?tab=readme-ov-file)
* **Note:** Includes IR, visible video, and audio files.

### 📅 2022

#### 7. IRSTD-1k
* **Description:** Published in 2022 at the **Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)** by the team led by **Mingjin Zhang** and **Rui Zhang** from the **University of Sydney** and **Xidian University**.
* **Target Type:** UAVs, Birds, etc.
* **Download Link:** [Google Drive](https://drive.google.com/file/d/1JoGDGF96v4CncKZprDnoIor0k1opaLZa/view)
* **GitHub/Project Link:** [Link](https://github.com/RuiZhang97/ISNet?tab=readme-ov-file)

#### 8. SIRST v2
* **Description:** An improved version of the SIRST dataset.
* **Target Type:** UAVs, Birds, etc.
* **GitHub/Project Link:** [Link](https://github.com/YimianDai/open-sirst-v2)

#### 9. ISDD (Infrared Ship Detection Dataset)
* **Description:** A public dataset with 1284 IR remote sensing images and 3061 ship instances (500x500 resolution). Images are sourced from the Landsat8 satellite, after pre-processing with radiometric calibration and FLAASH atmospheric correction. Contains 373 inshore scenes and 911 offshore scenes.
* **Target Type:** Ships (Inshore and Offshore scenes)
* **Download Link:** [Baidu Pan](https://pan.baidu.com/share/init?surl=VfCbiWnjPoXoI4MaH0VkXw) (Password: `asdf`)
* **GitHub/Project Link:** [Link](https://github.com/yaqihan-9898/ISDD)

### 📅 2023

#### 10. Anti-UAV 600
* **Description:** High-quality, full-HD thermal infrared UAV video sequences released by the VPR 2023 Workshop 3rd Anti-UAV Challenge.
* **Target Type:** UAVs
* **Download/Project Link:** [ModelScope](https://modelscope.cn/models/iic/3rd_Anti-UAV_CVPR23/summary)
* **GitHub/Project Link:** [Link](https://anti-uav.github.io/dataset/)
* **Note:** Video data.

#### 11. IR Small Targets Dataset (Kaggle)
* **Description:** A public Kaggle dataset. Contains infrared spectrum images and labels (bounding box coordinates) for UAVs, aircraft, and helicopters.
* **Target Type:** UAVs, Aircraft, etc.
* **Download/Project Link:** [Kaggle](https://www.kaggle.com/datasets/llpukojluct/ir-small-target)

#### 12. NUDT-SIRST-Sea
* **Description:** A real space-based remote sensing IR image dataset. Images are sourced from the Landsat8 satellite, reflecting maritime ship targets after pre-processing. Known for extremely large image size and small, dim targets.
* **Target Type:** Large cruise ships, oil recovery wells, small yachts, tiny ships
* **Download Link:** [Baidu Pan](https://pan.baidu.com/s/1cDLlkQb8STkjp74Y7YBA2w) (Password: `ad7w`)
* **GitHub/Project Link:** [Link](https://github.com/TianhaoWu16/Multi-level-TransUNet-for-Space-based-Infrared-Tiny-ship-Detection)

### 📅 2024

#### 13. MMFW-UAV
* **Description:** A multi-sensor, multi-view fixed-wing UAV dataset designed for air-to-air vision tasks. Includes 147,417 fixed-wing UAV images captured using various sensors (including thermal).
* **Target Type:** UAVs
* **Download/Project Link:** [Link](https://www.scidb.cn/en/detail?dataSetId=edb443cfcfa142019499bbfd68542cc9)
* **Note:** Multi-modal image data, includes IR images.

### 📅 2025 (Projected/Latest Research)

#### 14. SIRST-UAVB
* **Description:** Contains 3000 IR images for UAVs and birds, collected across different seasons, weather conditions, and complex backgrounds. Targets are manually annotated via trajectory.
* **Target Type:** 1742 bird and 2955 UAV BBox labels.
* **Download Link:** [Baidu Pan](https://pan.baidu.com/share/init?surl=FIg6BU8jlZogEQYWx_-ubQ&pwd=0558) (Password: `0558`)
* **GitHub/Project Link:** [Link](https://github.com/JN-Yang/PConv-SDloss-Data)

#### 15. RealScene-ISTD
* **Description:** A cross-domain IR small target dataset developed by Guangdong University of Technology. Includes 739 UAV-captured images, covering targets of various scales, multi-motion states, and complex backgrounds.
* **Target Type:** Various small targets from a UAV perspective
* **Download Link:** [Baidu Pan](https://pan.baidu.com/s/1BAY9N4xEtw57_v3TjHrSpg?pwd=trnh#list/path=%2F)
* **GitHub/Project Link:** [Link](https://github.com/luy0222/RealScene-ISTD)

***

## II. Synthetic/Semi-Synthetic Datasets

This section lists publicly available datasets created using synthetic or semi-synthetic techniques, sorted by release year.

### 📅 2019

#### 1. MDvsFA
* **Description:** High-resolution IR natural scene images are collected from the network as a background library and cropped to form diverse backgrounds. Real targets separated from images or targets synthesized by a 2D Gaussian function are then superimposed onto the backgrounds.
* **Target Type:** Synthetic Targets
* **GitHub/Project Link:** [Link](https://github.com/wanghuanphd/MDvsFA_cGAN)
* **Note:** Semi-Synthetic.

### 📅 2021

#### 2. NUDT-SIRST
* **Description:** A fully synthetic dataset containing 1327 images with $256 \times 256$ resolution.
* **Target Type:** Synthetic Targets
* **Download Link:** [Baidu Pan](https://pan.baidu.com/share/init?surl=WdA_yOHDnIiyj4C9SbW_Kg&pwd=nudt) (Password: `nudt`)
* **GitHub/Project Link:** [Link](https://github.com/YeRen123455/Infrared-Small-Target-Detection?tab=readme-ov-file)
* **Note:** Fully Synthetic.

### 📅 2023

#### 3. NUST-MIRSDT
* **Description:** A fully synthetic dataset containing 120 sequences. 80 sequences are used for training and 20 sequences are used for testing.
* **Target Type:** Synthetic Targets
* **Download Link:** [Baidu Pan](https://pan.baidu.com/s/1pSN350eurMafLiHBQBnrPA?pwd=5whn) (Password: `5whn`)
* **GitHub/Project Link:** [Link](https://github.com/TinaLRJ/Multi-frame-infrared-small-target-detection-DTUM?tab=readme-ov-file)
* **Note:** Fully Synthetic.

### 📅 2024

#### 4. Semi-Synthetic Dataset for IR Small Moving Target Detection in Complex Backgrounds
* **Description:** Targets airborne infrared detection platforms. Data is collected using a small UAV equipped with an IR detector, and **synthetic targets are embedded** to simulate long-distance airborne targets. Contains 350 image sequences and 150,185 images.
* **Target Type:** Synthetic Targets
* **Download/Project Link:** [Link](https://www.scidb.cn/en/detail?dataSetId=720626420933459968)
* **Note:** Semi-Synthetic.

#### 5. SIRST-5k
* **Description:** Proposes a negative sample enhancement method for self-supervised learning. The algorithm generates a fully synthetic SIRST-5K dataset containing a large amount of pseudo-data and corresponding labels.
* **Target Type:** Synthetic Targets
* **Download Link:** [Google Drive](https://drive.google.com/file/d/13aIrY5azO4bPwSGzDCzmgpwtpmYsysaD/view)
* **GitHub/Project Link:** [Link](https://github.com/luy0222/SIRST-5K?tab=readme-ov-file)
* **Note:** Fully Synthetic.

#### 6. DenseSIRST
* **Description:** The first IRST dataset to include both dense targets and background semantic annotation. Contains 1024 high-quality IR images, annotating 13,655 densely distributed small targets. Includes a simulated dense small target image and a corresponding sky segmentation version for each pair.
* **Target Type:** Simulated Dense Small Targets
* **Download Link:** [Google Drive](https://drive.usercontent.google.com/download?id=1PY0d1WuCjf_3wAIjDSNhYxREVK27OLzl&export=download&authuser=0)
* **GitHub/Project Link:** [Link](https://github.com/GrokCV/DenseSIRST)
* **Note:** Fully Synthetic.
