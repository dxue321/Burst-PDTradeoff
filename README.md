# Burst-PDTradeoff

This is the code repository for the paper:
> **Burst Perception-Distortion Tradeoff: Analysis and Evaluation**
>
> [Danna Xue](https://github.com/dxue321), [Luis Herranz](http://www.lherranz.org), [Javier Vazquez Corral](https://www.jvazquez-corral.net/), and Yanning Zhang
> 
> **ICASSP 2023**

The code is Coming soon...

## Introduction
Burst image restoration attempts to effectively utilize the complementary cues appearing in sequential images to produce a high-quality image. Most current methods use all the available images to obtain the reconstructed image. However, using more images for burst restoration is not always the best option regarding reconstruction quality and efficiency, as the images acquired by handheld imaging devices suffer from degradation and misalignment caused by the camera noise and shake. In this paper, we extend the perception-distortion tradeoff theory by introducing multiple-frame information. We propose the area of the unattainable region as a new metric for perception-distortion tradeoff evaluation and comparison. Based on this metric, we analyse the performance of burst restoration from the perspective of the perception-distortion tradeoff under both aligned bursts and misaligned bursts situations. Our analysis reveals the importance of inter-frame alignment for burst restoration and shows that the optimal burst length for the restoration model depends both on the degree of degradation and misalignment.

## Acknowledgements
Our method is implemented based on code from the following projects:

 - Synthetic burst generation code from https://github.com/goutamgmb/deep-burst-sr
 - ESRGAN code from https://github.com/xinntao/ESRGAN
 - Evaluation method from https://github.com/XPixelGroup/BasicSR
We thank the authors for their open-source code.
