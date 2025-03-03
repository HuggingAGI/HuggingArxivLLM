# 面向通用视觉-语言人脸伪造检测的探索(V2)

发布时间：2025年02月27日

`LLM应用

摘要讨论了如何将多模态大型语言模型（MLLM）应用于面部伪造检测任务，提出了一种新的标注方法，以提高检测的准确性和可解释性。这属于将LLM技术应用于实际问题的范畴。` `计算机视觉`

> Towards General Visual-Linguistic Face Forgery Detection(V2)

# 摘要

> 面部操控技术的快速发展给安全和社会信任带来了严峻挑战。近期研究表明，多模态模型能够有效提升面部伪造检测的泛化能力和可解释性。然而，现有标注方法无论是人工标注还是直接利用多模态大型语言模型（MLLM）生成，都常因幻觉问题导致文本描述不准确，尤其是面对高质量伪造内容时。为此，我们提出了一种名为Face Forgery Text Generator（FFTG）的新型标注流水线。该方法通过伪造掩码进行初始区域和类型识别，随后采用全面的提示策略引导MLLMs减少幻觉，从而生成更准确的文本描述。我们通过结合单模态和多模态目标的三分支训练框架微调CLIP，以及利用结构化标注微调MLLMs，验证了该方法的有效性。实验结果表明，我们的方法不仅实现了更精准的标注，区域识别精度显著提升，而且在各种伪造检测基准测试中显著增强了模型性能。我们的代码可在https://github.com/skJack/VLFFD.git获取。

> Face manipulation techniques have achieved significant advances, presenting serious challenges to security and social trust. Recent works demonstrate that leveraging multimodal models can enhance the generalization and interpretability of face forgery detection. However, existing annotation approaches, whether through human labeling or direct Multimodal Large Language Model (MLLM) generation, often suffer from hallucination issues, leading to inaccurate text descriptions, especially for high-quality forgeries. To address this, we propose Face Forgery Text Generator (FFTG), a novel annotation pipeline that generates accurate text descriptions by leveraging forgery masks for initial region and type identification, followed by a comprehensive prompting strategy to guide MLLMs in reducing hallucination. We validate our approach through fine-tuning both CLIP with a three-branch training framework combining unimodal and multimodal objectives, and MLLMs with our structured annotations. Experimental results demonstrate that our method not only achieves more accurate annotations with higher region identification accuracy, but also leads to improvements in model performance across various forgery detection benchmarks. Our Codes are available in https://github.com/skJack/VLFFD.git.

[Arxiv](https://arxiv.org/abs/2502.20698)