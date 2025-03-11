# VLForgery 面部三重奏：多模态大语言模型助力检测、定位与归因

发布时间：2025年03月08日

`LLM应用

论文摘要：扩散模型 (DMs) 合成的高质量且可控属性的人脸为 Deepfake 检测带来了重大挑战。目前最先进的检测器仅能提供二元决策，无法实现伪造定位、伪造方法归属以及对伪造原因的分析。在这项研究中，我们将多模态大型语言模型 (MLLMs) 集成到基于 DM 的人脸取证中，并提出了一种名为 VLForgery 的精细分析三元组框架。该框架能够：1) 预测伪造的人脸图像；2) 定位部分合成的伪造人脸区域；3) 将合成过程归因于特定的生成器。

为了实现上述目标，我们引入了 VLF（视觉语言取证），这是一个新颖且多样化的合成人脸数据集，旨在促进 MLLMs 中视觉与语言模态之间的丰富交互。此外，我们提出了一种外部知识引导的描述方法，称为 EkCot，该方法利用图像生成管道的知识，使 MLLMs 能够快速捕捉图像内容。我们还引入了一种低级视觉比较管道，旨在识别 MLLMs 本质上可以理解的真实与伪造之间的差异特征。这些特征随后被整合到 EkCot 中，增强了其以检测、定位和归属的顺序进行结构化伪造分析的能力。

大量实验表明，VLForgery 在检测准确性方面优于其他最先进的取证方法，并且在伪造区域定位和归属分析方面也具有潜力。
LLM应用` `AI安全` `隐私保护` `深度伪造检测`

> VLForgery Face Triad: Detection, Localization and Attribution via Multimodal Large Language Models

# 摘要

> 扩散模型 (DMs) 合成的高质量且可控属性的人脸为 Deepfake 检测带来了重大挑战。目前最先进的检测器仅能提供二元决策，无法实现伪造定位、伪造方法归属以及对伪造原因的分析。在这项研究中，我们将多模态大型语言模型 (MLLMs) 集成到基于 DM 的人脸取证中，并提出了一种名为 VLForgery 的精细分析三元组框架。该框架能够：1) 预测伪造的人脸图像；2) 定位部分合成的伪造人脸区域；3) 将合成过程归因于特定的生成器。

为了实现上述目标，我们引入了 VLF（视觉语言取证），这是一个新颖且多样化的合成人脸数据集，旨在促进 MLLMs 中视觉与语言模态之间的丰富交互。此外，我们提出了一种外部知识引导的描述方法，称为 EkCot，该方法利用图像生成管道的知识，使 MLLMs 能够快速捕捉图像内容。我们还引入了一种低级视觉比较管道，旨在识别 MLLMs 本质上可以理解的真实与伪造之间的差异特征。这些特征随后被整合到 EkCot 中，增强了其以检测、定位和归属的顺序进行结构化伪造分析的能力。

大量实验表明，VLForgery 在检测准确性方面优于其他最先进的取证方法，并且在伪造区域定位和归属分析方面也具有潜力。

> Faces synthesized by diffusion models (DMs) with high-quality and controllable attributes pose a significant challenge for Deepfake detection. Most state-of-the-art detectors only yield a binary decision, incapable of forgery localization, attribution of forgery methods, and providing analysis on the cause of forgeries. In this work, we integrate Multimodal Large Language Models (MLLMs) within DM-based face forensics, and propose a fine-grained analysis triad framework called VLForgery, that can 1) predict falsified facial images; 2) locate the falsified face regions subjected to partial synthesis; and 3) attribute the synthesis with specific generators. To achieve the above goals, we introduce VLF (Visual Language Forensics), a novel and diverse synthesis face dataset designed to facilitate rich interactions between Visual and Language modalities in MLLMs. Additionally, we propose an extrinsic knowledge-guided description method, termed EkCot, which leverages knowledge from the image generation pipeline to enable MLLMs to quickly capture image content. Furthermore, we introduce a low-level vision comparison pipeline designed to identify differential features between real and fake that MLLMs can inherently understand. These features are then incorporated into EkCot, enhancing its ability to analyze forgeries in a structured manner, following the sequence of detection, localization, and attribution. Extensive experiments demonstrate that VLForgery outperforms other state-of-the-art forensic approaches in detection accuracy, with additional potential for falsified region localization and attribution analysis.

[Arxiv](https://arxiv.org/abs/2503.06142)