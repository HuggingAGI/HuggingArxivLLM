# MIA-DPO: 面向大型视觉语言模型的多图像增强直接偏好优化

发布时间：2024年10月23日

`LLM应用

理由：该论文主要讨论了如何通过多图像增强直接偏好优化（MIA-DPO）方法来训练大型视觉语言模型（LVLMs），以预测人类在视觉输入中的偏好。虽然涉及视觉语言模型，但其核心是应用大型语言模型（LLM）的技术来解决视觉偏好对齐的问题，因此应归类为LLM应用。` `视觉语言模型` `多图像处理`

> MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models

# 摘要

> # 摘要
视觉偏好对齐旨在训练大型视觉语言模型（LVLMs）预测人类在视觉输入中的偏好。通常，这通过使用标记的选择/拒绝对数据集并采用直接偏好优化（DPO）等算法实现。现有方法主要针对单图像场景，由于缺乏多样化训练数据和高昂的注释成本，难以应对多图像任务的复杂性。我们提出多图像增强直接偏好优化（MIA-DPO），一种有效处理多图像输入的视觉对齐方法。MIA-DPO通过扩展单图像数据为不相关图像的网格拼贴或画中画格式，显著降低多图像数据注释成本。我们发现，LVLMs的注意力值在不同图像间差异显著，并利用这些值识别和过滤模型可能错误关注的拒绝响应。我们的注意力感知选择无需依赖（i）人工注释，（ii）额外数据，或（iii）外部模型或API即可构建选择/拒绝对。MIA-DPO兼容多种架构，在五个多图像基准测试中表现优异，LLaVA-v1.5平均性能提升3.0%，InternLM-XC2.5提升4.3%。此外，MIA-DPO对模型理解单图像的能力影响极小。

> Visual preference alignment involves training Large Vision-Language Models (LVLMs) to predict human preferences between visual inputs. This is typically achieved by using labeled datasets of chosen/rejected pairs and employing optimization algorithms like direct preference optimization (DPO). Existing visual alignment methods, primarily designed for single-image scenarios, struggle to effectively handle the complexity of multi-image tasks due to the scarcity of diverse training data and the high cost of annotating chosen/rejected pairs. We present Multi-Image Augmented Direct Preference Optimization (MIA-DPO), a visual preference alignment approach that effectively handles multi-image inputs. MIA-DPO mitigates the scarcity of diverse multi-image training data by extending single-image data with unrelated images arranged in grid collages or pic-in-pic formats, significantly reducing the costs associated with multi-image data annotations. Our observation reveals that attention values of LVLMs vary considerably across different images. We use attention values to identify and filter out rejected responses the model may have mistakenly focused on. Our attention-aware selection for constructing the chosen/rejected pairs without relying on (i) human annotation, (ii) extra data, and (iii) external models or APIs. MIA-DPO is compatible with various architectures and outperforms existing methods on five multi-image benchmarks, achieving an average performance boost of 3.0% on LLaVA-v1.5 and 4.3% on the recent InternLM-XC2.5. Moreover, MIA-DPO has a minimal effect on the model's ability to understand single images.

[Arxiv](https://arxiv.org/abs/2410.17637)