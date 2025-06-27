# # 多模态提示对齐技术在面部表情识别中的应用

发布时间：2025年06月26日

`LLM应用` `面部表情识别` `计算机视觉`

> Multimodal Prompt Alignment for Facial Expression Recognition

# 摘要

> 提示学习已被广泛用于高效适应CLIP等视觉语言模型（VLM），以完成各种下游任务。然而，现有的基于VLM的面部表情识别方法在捕捉细微的文本-视觉关系方面仍存在困难，这些关系对于区分面部表情的细微差别至关重要。为了解决这一挑战，我们提出了一种用于FER的多模态提示对齐框架（MPA-FER），它为提示视觉特征的学习过程提供了细致的语义指导，从而生成更精确且可解释的表示。具体来说，我们引入了一种多粒度硬提示生成策略，利用像ChatGPT这样的大型语言模型（LLM）为每种面部表情生成详细描述。基于LLM的外部知识通过最小化软提示与硬提示之间的特征差异被注入到软提示中。为了保留预训练CLIP模型的泛化能力，我们的方法结合了基于原型的视觉特征对齐，确保来自冻结图像编码器的提示视觉特征与特定类别的原型紧密对齐。此外，我们提出了一种跨模态全局-局部对齐模块，专注于与表情相关的面部特征，进一步增强了文本与视觉特征之间的对齐。大量实验表明，我们的框架在三个FER基准数据集上优于现有最优方法，同时保留了预训练模型的优势并最小化了计算成本。

> Prompt learning has been widely adopted to efficiently adapt vision-language models (VLMs) like CLIP for various downstream tasks. Despite their success, current VLM-based facial expression recognition (FER) methods struggle to capture fine-grained textual-visual relationships, which are essential for distinguishing subtle differences between facial expressions. To address this challenge, we propose a multimodal prompt alignment framework for FER, called MPA-FER, that provides fine-grained semantic guidance to the learning process of prompted visual features, resulting in more precise and interpretable representations. Specifically, we introduce a multi-granularity hard prompt generation strategy that utilizes a large language model (LLM) like ChatGPT to generate detailed descriptions for each facial expression. The LLM-based external knowledge is injected into the soft prompts by minimizing the feature discrepancy between the soft prompts and the hard prompts. To preserve the generalization abilities of the pretrained CLIP model, our approach incorporates prototype-guided visual feature alignment, ensuring that the prompted visual features from the frozen image encoder align closely with class-specific prototypes. Additionally, we propose a cross-modal global-local alignment module that focuses on expression-relevant facial features, further improving the alignment between textual and visual features. Extensive experiments demonstrate our framework outperforms state-of-the-art methods on three FER benchmark datasets, while retaining the benefits of the pretrained model and minimizing computational costs.

[Arxiv](https://arxiv.org/abs/2506.21017)