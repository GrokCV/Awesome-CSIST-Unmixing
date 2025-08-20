# Awesome Closely-Spaced Infrared Small Target Unmixing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources (papers, codes, datasets, etc.) for Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing).

**Closely-Spaced Infrared Small Target Unmixing (CSIST Unmixing)** is a critical and challenging task in infrared search and track (IRST) systems. It focuses on separating and detecting multiple small, dim targets that are located very close to each other in the focal plane array, which often leads to them being perceived as a single blob. This repository aims to collect and organize the latest advances in this specific field.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

## Table of Contents

-   [Papers](#papers)
    -   [By Year](#by-year)
    -   [By Method](#by-method)
-   [Datasets and Benchmarks](#datasets-and-benchmarks)
-   [Software and Libraries](#software-and-libraries)
-   [Evaluation Metrics](#evaluation-metrics)
-   [Tutorials and Talks](#tutorials-and-talks)
-   [Related Research Groups](#related-research-groups)
-   [Other Awesome Lists](#other-awesome-lists)

## Papers

### By Year
*(This structure is great for tracking the latest progress. List papers in reverse chronological order.)*

#### 2025
-   **Paper Title** - *First Author et al.*, Journal/Conference 2024 \
    *A brief description of the contribution and the core method (e.g., "Proposed a novel deep unmixing network based on...")* \
    [[Paper](Link to arXiv/DOI)] [[Code](Link to GitHub) :star: ] [[Project Page](Link)]

#### 2024
-   **...

### By Method
*(This structure helps researchers quickly find methods of a specific type.)*

-   **Model-Based / Optimization Methods**
    -   **Paper Title** - *Author et al.*, Journal 2022 \
        *("Leveraged sparse representation and non-convex optimization...")* \
        [[Paper](Link)]

-   **Deep Learning-Based Methods**
    -   **UnmixNet: A Deep Network for...** - *Zhang et al.*, Conference 2023 \
        *("An end-to-end CNN architecture that directly outputs unmixed target parameters")* \
        [[Paper](Link)] [[Code](Link) :star2: ]

## Datasets and Benchmarks
*(This is crucial for a data-driven field. Provide details on how to access and use them.)*

-   **CSIST-100K** - A large-scale synthetic dataset (100k samples) for closely-spaced IR point target unmixing. Simulates 1-5 targets/image with a PSF of σ=0.5px, min separation ≥0.52 Rayleigh units, and random intensity. Targets overlap significantly in a 3×3 area, posing a strong challenge for counting and localization. (80k/10k/10k split).
    [Baidu Pan](https://pan.baidu.com/s/1nuedV5Okng8rgFWKy_sMoA?pwd=Grok)  [OneDrive](https://1drv.ms/f/c/698f69b8b2172561/EnQbsEb_rXpJlsNXinWyBbsBkhCsnSPM7UEgtczt7FDjmQ)

-   **MUIST** - Multi-target Infrared Small Target dataset \
    *Description: ...* \
    [[Download Link](https://pan.baidu.com/s/1_sxGh5oFQ8-3RpUUeMN2Mg?pwd=kxe9)]

## Software and Libraries

-   **IRSTU-Toolbox** - \
    *A MATLAB toolbox featuring implementations of classic algorithms (e.g., LCM, MPCM) and evaluation metrics for IR small target detection and unmixing.* \
    [[GitHub](Link)] :star: 123

-   **UnmixLib** - \
    *A Python package for model-based infrared target unmixing, including utilities for generating synthetic data.* \
    [[GitHub](Link)] :star: 45

## Evaluation Metrics
*(Explain the common metrics used to evaluate unmixing performance in your field.)*

-   **CSO-mAP**: The mean Average Precision over multiple sub-pixel distance thresholds (δ=0.05 to 0.25px). Designed to evaluate precise localization in scenarios where targets are closer than the Rayleigh criterion, where standard metrics fail.


## Related Research Groups

-   **Advanced IR Lab** - University of Example ([Lab Website](Link)) - *Led by Prof. John Smith. Focuses on signal processing for infrared systems.*
-   **Aerospace Vision Group** - Example Institute of Technology ([Group Page](Link)) - *Known for work on target detection and tracking.*

## Other Awesome Lists

-   [Awesome Infrared Small Target Detection](https://github.com/xxx/awesome-infrared-small-target-detection) - A more general list on IR small target detection.
-   [Awesome Target Tracking](https://github.com/yyy/awesome-tracking) - A list for single and multiple target tracking.
-   [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) - The giant umbrella list for all things CV.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Your Name] has waived all copyright and related or neighboring rights to this work.
