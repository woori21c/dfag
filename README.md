# Boosting the Performance of Image Restoration Models through Training with Deep-Feature Auxiliary Guidance

[![Paper Status](https://img.shields.io/badge/Paper-Accepted-brightgreen)]([Link to Paper])
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the official PyTorch implementation of the paper: **"Boosting the Performance of Image Restoration Models through Training with Deep-Feature Auxiliary Guidance"**.  
Authors: Cheolhun Jang, Daehyun JI, and Nam Ik Cho  
Accepted at IEEE Access

> **🚧 Code Coming Soon 🚧**
>
> The code used in the paper is currently being cleaned up and will be uploaded soon. Thank you for your patience!

## Abstract

> Many neural network architectures have been proposed for image restoration to improve the accuracy of restored images while maintaining reasonable computational costs. However, most previous studies have primarily focused on designing new architectures, with relatively less attention on optimizing training strategies. In this paper, we introduce deep-feature auxiliary guidance (DFAG), a novel training method that enhances the accuracy of image restoration models without increasing inference time or modifying their structures. DFAG adds auxiliary losses to the feature maps at each multi-scale level during training, which stabilizes deep feature learning and improves feature quality. All modules used for DFAG are only active during training and are removed for inference, resulting in no additional computational cost. We validate DFAG on various multi-scale encoder-decoder-based image restoration models. Our experiments demonstrate consistent performance improvements across multiple tasks, including real image denoising, Gaussian denoising, motion deblurring, JPEG artifact reduction, and super-resolution. Our results highlight that DFAG is an effective strategy to boost restoration performance without any architectural modifications. The source code and pre-trained models will be released.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/woori21c/dfag.git](https://github.com/woori21c/dfag.git)
    cd dfag
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: The `requirements.txt` file will be uploaded along with the source code.)*

## Usage

(This section will be updated once the code is uploaded.)

#### **Training**

To train the model, run the following command:
```bash
python train.py --config [path_to_config_file]
