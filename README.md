# Awesome Closely-Spaced Infrared Small Target Unmixing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources (papers, codes, datasets, etc.) for Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing).

**Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing)** is a critical and challenging task in infrared search and track (IRST) systems. It focuses on separating and detecting multiple small, dim targets that are located very close to each other in the focal plane array, which often leads to them being perceived as a single blob. This repository aims to collect and organize the latest advances in this specific field.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

## Table of Contents

- [Awesome Closely-Spaced Infrared Small Target Unmixing ](#awesome-closely-spaced-infrared-small-target-unmixing-)
  - [Table of Contents](#table-of-contents)
  - [Papers](#papers)
    - [By Year](#by-year)
      - [2025](#2025)
      - [2024](#2024)
    - [By Method](#by-method)
  - [Datasets and Benchmarks](#datasets-and-benchmarks)
  - [Software and Libraries](#software-and-libraries)
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
    -   **采用分裂Ｂｒｅｇｍａｎ的空间邻近目标红外超分辨算法** - *左芝勇*, Telecommunication Engineering, 2020 \
        [[Paper](https://openurl.ebsco.com/EPDB%3Agcd%3A11%3A31617819/detailv2?sid=ebsco%3Aplink%3Ascholar&id=ebsco%3Agcd%3A144824734&crl=c&link_origin=scholar.google.com)]

    -   **Electromagnetic Imaging of Closely Spaced Objects using Matching Pursuit Based Approaches** - *Şenyuva, R. V., Özdemir, Ö., Kurt, G. K., & Anarım*, IEEE Antennas and Wireless Propagation Letters, 2015 \
        [[Paper](https://ieeexplore.ieee.org/abstract/document/7327171/)]
      

-   **Deep Learning-Based Methods**
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


## Related Research Groups

-   **[GrokCV](https://yimian.grokcv.ai/)** - Nankai University ([Lab Website]([Link](https://www.nankai.edu.cn/))) - *Led by Prof. Yimian Dai. Long-term commitment to infrared small target detection and multi-modal visual perception in remote sensing.*

## Other Awesome Lists

-   [Awesome Infrared Small Target Detection](https://github.com/xxx/awesome-infrared-small-target-detection) - A more general list on IR small target detection.
-   [Awesome Target Tracking](https://github.com/yyy/awesome-tracking) - A list for single and multiple target tracking.
-   [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) - The giant umbrella list for all things CV.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Your Name] has waived all copyright and related or neighboring rights to this work.
