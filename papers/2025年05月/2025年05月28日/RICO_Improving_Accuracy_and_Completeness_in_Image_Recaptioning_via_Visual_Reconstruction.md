# RICO: 利用视觉重构优化图像重新描述的准确性和完整性

发布时间：2025年05月28日

`LLM应用` `图像处理` `多模态`

> RICO: Improving Accuracy and Completeness in Image Recaptioning via Visual Reconstruction

# 摘要

> 图像重注释在生成多模态任务的高质量训练数据方面应用广泛。现有的方法通常依赖强大的多模态大型语言模型（MLLMs）来增强文本描述，但常因生成内容的不准确性和不完整性而受限，这主要由于缺少细粒度细节。针对这些限制，我们提出了RICO框架，通过视觉重建优化图像描述。具体来说，我们利用文本到图像的模型将描述重建为参考图像，并提示MLLM识别原始与重建图像的差异，从而优化描述。这一迭代过程逐步促进生成更忠实和全面的描述。为缓解迭代带来的计算成本，我们引入了RICO-Flash，通过DPO学习生成描述。实验表明，我们的方法显著提升了描述的准确性和完整性，在CapsBench和CompreCap上均优于大多数基线方法约10%。代码已发布在https://github.com/wangyuchi369/RICO。

> Image recaptioning is widely used to generate training datasets with enhanced quality for various multimodal tasks. Existing recaptioning methods typically rely on powerful multimodal large language models (MLLMs) to enhance textual descriptions, but often suffer from inaccuracies due to hallucinations and incompleteness caused by missing fine-grained details. To address these limitations, we propose RICO, a novel framework that refines captions through visual reconstruction. Specifically, we leverage a text-to-image model to reconstruct a caption into a reference image, and prompt an MLLM to identify discrepancies between the original and reconstructed images to refine the caption. This process is performed iteratively, further progressively promoting the generation of more faithful and comprehensive descriptions. To mitigate the additional computational cost induced by the iterative process, we introduce RICO-Flash, which learns to generate captions like RICO using DPO. Extensive experiments demonstrate that our approach significantly improves caption accuracy and completeness, outperforms most baselines by approximately 10% on both CapsBench and CompreCap. Code released at https://github.com/wangyuchi369/RICO.

[Arxiv](https://arxiv.org/abs/2505.22613)