# Awesome Closely-Spaced Infrared Small Target Unmixing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources (papers, codes, datasets, etc.) for Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing).

**Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing)** is a critical and challenging task in infrared search and track (IRST) systems. It focuses on separating and detecting multiple small, dim targets that are located very close to each other in the focal plane array, which often leads to them being perceived as a single blob. This repository aims to collect and organize the latest advances in this specific field.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

*The Chinese version can be accessed through 🌐 [中文版本](中文文档.md)*

## Table of Contents

- [Awesome Closely-Spaced Infrared Small Target Unmixing ](#awesome-closely-spaced-infrared-small-target-unmixing-)
  - [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [By Year](#by-year)
      - [2025](#2025)
    - [By Method](#by-method)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  - [Evaluation Metrics](#evaluation-metrics)
  - [Related Research Groups](#related-research-groups)
  - [Other Awesome Lists](#other-awesome-lists)
  - [License](#license)

## Papers

### By Year

#### 2025
-   **[DISTA-Net: Dynamic Closely-Spaced Infrared Small Target Unmixing]()** - *Shengdong Han, Shangdong Yang, Xin Zhang, Yuxuan Li, Xiang Li, Jian Yang, Ming-Ming Cheng, Yimian Dai*, ICCV 2025 \
    [[Paper](https://arxiv.org/abs/2505.19148)]
    [[Code](https://github.com/GrokCV/GrokCSO) :star: ]
-   **[SeqCSIST: Sequential Closely-Spaced Infrared Small Target Unmixing]()** - *Ximeng Zhai, Bohan Xu, Yaohong Chen, Hao Wang, Kehua Guo and Yimian Dai*, TGRS 2025 \
    [[Paper](https://arxiv.org/abs/2507.09556)]
    [[Code](https://github.com/GrokCV/SeqCSIST) :star: ]


### By Method

-   **Model-Based / Optimization Methods**
    -   **Closely spaced object detection utilizing spatial information in spectroastrometric observations** - *J. Zachary Gazak, Ryan Swindle, Zachary Funke, Matthew Phelps, Justin Fletcher*, Sensors and Systems for Space Applications XV. SPIE, 2022 \
        [[Paper](https://neurophotonics.spiedigitallibrary.org/conference-proceedings-of-spie/12121/121210K/Closely-spaced-object-detection-utilizing-spatial-information-in-spectroastrometric-observations/10.1117/12.2625366.full)]

    -   **An infrared super resolution algorithm using split Bregman for closely spaced objects Bregman** - *ZUO Zhiyong*, Telecommunication Engineering, 2020 \
        [[Paper](https://openurl.ebsco.com/EPDB%3Agcd%3A11%3A31617819/detailv2?sid=ebsco%3Aplink%3Ascholar&id=ebsco%3Agcd%3A144824734&crl=c&link_origin=scholar.google.com)]

    -   **The infrared image closely spaced objects super resolution method based on sparse reconstruction under the noise environment** - *J Zeng, J Yang, H Wu*, International Conference on Optical and Photonics Engineering (icOPEN 2016). SPIE, 2017 \
        [[Paper](https://nanophotonics.spiedigitallibrary.org/conference-proceedings-of-spie/10250/102502V/The-infrared-image-closely-spaced-objects-super-resolution-method-based/10.1117/12.2266856.full)]

    -   **Electromagnetic Imaging of Closely Spaced Objects using Matching Pursuit Based Approaches** - *Şenyuva, R. V., Özdemir, Ö., Kurt, G. K., & Anarım*, IEEE Antennas and Wireless Propagation Letters, 2015 \
        [[Paper](https://ieeexplore.ieee.org/abstract/document/7327171/)]

    -   **Bayesian approach to joint super-resolution and trajectory estimation for midcourse closely spaced objects via space-based infrared sensor** - *Liangkui Lin, Weidong Sheng, Dan Xu*, Optical Engineering, 2012 \
        [[Paper](https://www.spiedigitallibrary.org/journals/optical-engineering/volume-51/issue-11/117003/Bayesian-approach-to-joint-super-resolution-and-trajectory-estimation-for/10.1117/1.OE.51.11.117003.full)]

    -   **QPSO-based algorithm of CSO joint infrared super-resolution and trajectory estimation** - *Lin, Liangkui and Xu, Hui and Xu, Dan and An, Wei and Xie, Kai*, Journal of Systems Engineering and Electronics, 2011 \
        [[Paper](https://ieeexplore.ieee.org/abstract/document/6077736/)]
    
    -  **A Gibbs Sampling Approach to Closely Spaced Objects Resolution IR Focal Plane** - *LIU Tao*, Journal of Signal Processing, 2010 \
        [[Paper](https://signal.ejournal.org.cn/article/id/8568)]

    -   **Hierarchical Closely-Spaced Object (CSO) Resolution for IR Sensor Surveillance** - *Macumber, Daniel and Gadaleta, Sabino and Floyd, Allison and Poore, Aubrey*, Signal and Data Processing of Small Targets, 2005 \
        [[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/5913/591304/)]

    -   **Model-based superresolution CSO processing** - *John T. Reagan, Theagenis J. Abatzoglou*, Signal and Data Processing of Small Targets 1993. SPIE, 2005 \
        [[Paper](https://opticalengineering.spiedigitallibrary.org/conference-proceedings-of-spie/1954/0000/Model-based-superresolution-CSO-processing/10.1117/12.157809.full)]
      
-   **Deep Learning-Based Methods**
    -   **[DISTA-Net: Dynamic Closely-Spaced Infrared Small Target Unmixing]()** - *Shengdong Han, Shangdong Yang, Xin Zhang, Yuxuan Li, Xiang Li, Jian Yang, Ming-Ming Cheng, Yimian Dai*, ICCV 2025 \
    [[Paper](https://arxiv.org/abs/2505.19148)]
    [[Code](https://github.com/GrokCV/GrokCSO) :star: ]
    -   **[SeqCSIST: Sequential Closely-Spaced Infrared Small Target Unmixing]()** - *Ximeng Zhai, Bohan Xu, Yaohong Chen, Hao Wang, Kehua Guo and Yimian Dai*, TGRS 2025 \
    [[Paper](https://arxiv.org/abs/2507.09556)]
    [[Code](https://github.com/GrokCV/SeqCSIST) :star: ]
    
    -   **A Resolution and Localization Algorithm for Closely-Spaced Objects Based on Improved YOLOv5 Joint Fuzzy C-Means Clustering** - *Li et al.*, IEEE Photonics Journal 2024 \
        [[Paper](https://ieeexplore.ieee.org/document/10418965)]
    
    -   **Closely-Spaced Object Classification Using MuyGPyS** - *Zhang et al.*, Conference 2023 \
        *("An end-to-end CNN architecture that directly outputs unmixed target parameters")* \
        [[Paper](https://arxiv.org/pdf/2311.10904)]

## Datasets and Benchmarks
*(This is crucial for a data-driven field. Provide details on how to access and use them.)*

-   **CSIST-100K** - A large-scale synthetic dataset (100k samples) for closely-spaced IR point target unmixing. Simulates 1-5 targets/image with a PSF of σ=0.5px, min separation ≥0.52 Rayleigh units, and random intensity. Targets overlap significantly in a 3×3 area, posing a strong challenge for counting and localization. (80k/10k/10k split).
    [Baidu Pan](https://pan.baidu.com/s/1nuedV5Okng8rgFWKy_sMoA?pwd=Grok)  [OneDrive](https://1drv.ms/f/c/698f69b8b2172561/EnQbsEb_rXpJlsNXinWyBbsBkhCsnSPM7UEgtczt7FDjmQ)

-   **SeqCSIST** - Sequential Closely-Spaced Infrared Small Target Unmixing \
    *A sequential benchmark dataset for sequential closely-spaced infrared small target unmixing. A synthetic dataset which is generated with an image size of 11 × 11 pixels. Each image contains two to four targets, with intensities randomly sampled from the range. The targets follow random trajectories. Targets are rendered based on the 84% energy concentration resolution standard and a diffusion variance of 0.5 pixels. The ground truth, including the precise coordinates and intensity for each target, is provided in corresponding XML files.* \
    [[Baidu Pan](https://pan.baidu.com/s/1_sxGh5oFQ8-3RpUUeMN2Mg?pwd=kxe9)  [OneDrive](https://1drv.ms/f/c/698f69b8b2172561/EuBC8549kZJIp_syz2Glft4BU2Fu5Ri-wYE888HJ9kmiiQ?e=zEISNc)]

## Evaluation Metrics
*(Explain the common metrics used to evaluate unmixing performance in your field.)*

-   **CSO-mAP**: The mean Average Precision over multiple sub-pixel distance thresholds (δ=0.05 to 0.25px). Designed to evaluate precise localization in scenarios where targets are closer than the Rayleigh criterion, where standard metrics fail.
    [[Paper](https://arxiv.org/abs/2505.19148)]
    [[Code](https://github.com/GrokCV/GrokCSO) :star: ]


## Related Research Groups

-   **[GrokCV](https://yimian.grokcv.ai/)** - [Nankai University](https://www.nankai.edu.cn/) - *Led by Prof. Yimian Dai. Long-term commitment to infrared small target detection and multi-modal visual perception in remote sensing.*


