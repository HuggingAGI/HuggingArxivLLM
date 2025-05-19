# # 结合多模态大语言模型，统一显微镜中的任意分割

发布时间：2025年05月15日

`LLM应用` `生物医学` `图像处理`

> Unifying Segment Anything in Microscopy with Multimodal Large Language Model

# 摘要

> 生物医学图像中感兴趣区域的精准分割在图像分析领域具有重要价值。尽管当前已有多种生物医学分割基础模型在特定数据集上表现优异，但它们在未见域数据上的效果往往不尽如人意。究其原因，主要是由于分割前缺乏视觉-语言知识。多模态大型语言模型（MLLMs）在多模态任务中展现了卓越的理解和推理能力，这启发我们利用MLLMs注入视觉-语言知识（VLK），从而提升视觉模型在跨域数据上的泛化能力。本文提出了一种基于MLLMs引导SAM学习显微镜跨域数据的方法，并将其命名为uLLSAM，实现了显微镜下的统一任意分割。具体而言，我们设计了视觉-语言语义对齐（VLSA）模块，将VLK注入分割一切模型（SAM）。研究发现，SAM在接收全局VLK提示后性能显著提升，但在边界轮廓感知方面仍存在不足。为此，我们进一步提出了语义边界正则化（SBR）方法来优化SAM。实验结果表明，我们的方法在9个域内显微镜数据集上实现了Dice指标提升7.71%和SA指标提升12.10%的优异表现，达到了当前最优水平。在10个域外数据集上，我们的方法也实现了Dice指标提升6.79%和SA指标提升10.08%的改进，展现了强大的泛化能力。代码可在https://github.com/ieellee/uLLSAM获取。

> Accurate segmentation of regions of interest in biomedical images holds substantial value in image analysis. Although several foundation models for biomedical segmentation have currently achieved excellent performance on certain datasets, they typically demonstrate sub-optimal performance on unseen domain data. We owe the deficiency to lack of vision-language knowledge before segmentation. Multimodal Large Language Models (MLLMs) bring outstanding understanding and reasoning capabilities to multimodal tasks, which inspires us to leverage MLLMs to inject Vision-Language Knowledge (VLK), thereby enabling vision models to demonstrate superior generalization capabilities on cross-domain datasets. In this paper, we propose using MLLMs to guide SAM in learning microscopy crose-domain data, unifying Segment Anything in Microscopy, named uLLSAM. Specifically, we propose the Vision-Language Semantic Alignment (VLSA) module, which injects VLK into Segment Anything Model (SAM). We find that after SAM receives global VLK prompts, its performance improves significantly, but there are deficiencies in boundary contour perception. Therefore, we further propose Semantic Boundary Regularization (SBR) to prompt SAM. Our method achieves performance improvements of 7.71% in Dice and 12.10% in SA across 9 in-domain microscopy datasets, achieving state-of-the-art performance. Our method also demonstrates improvements of 6.79% in Dice and 10.08% in SA across 10 out-ofdomain datasets, exhibiting strong generalization capabilities. Code is available at https://github.com/ieellee/uLLSAM.

[Arxiv](https://arxiv.org/abs/2505.10769)