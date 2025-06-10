# 图像感知与多模态推理的解耦：基于数字孪生表示的推理分割。

发布时间：2025年06月09日

`LLM应用` `计算机视觉`

> Decoupling the Image Perception and Multimodal Reasoning for Reasoning Segmentation with Digital Twin Representations

# 摘要

> # 摘要  
推理分割（RS）是一项多模态视觉-文本任务，要求基于隐式的文本查询对物体进行分割，需要同时具备精确的视觉感知能力和视觉-文本推理能力。目前的RS方法依赖于微调视觉-语言模型（VLMs）来实现感知和推理，但它们对图像的分词从根本上破坏了物体之间的连续空间关系。我们引入了DTwinSeger，这是一种新型的RS方法，它利用数字孪生（DT）表示作为中间层，将感知与推理解耦。创新性地，DTwinSeger将RS重新定义为一个两阶段的过程：首先将图像转换为结构化的DT表示，保留空间关系和语义属性，然后利用大规模语言模型（LLM）对这一表示进行显式推理，以识别目标物体。我们提出了一种专门针对具有DT表示的LLM的监督微调方法，并配合相应的微调数据集Seg-DT，以增强LLM基于DT表示的推理能力。实验表明，我们的方法在两个图像RS基准和三个图像引用分割基准上均达到了最先进的性能。结果表明，DT表示充当了视觉与文本之间的有效桥梁，使复杂的多模态推理任务仅凭一个LLM即可完成。

> Reasoning Segmentation (RS) is a multimodal vision-text task that requires segmenting objects based on implicit text queries, demanding both precise visual perception and vision-text reasoning capabilities. Current RS approaches rely on fine-tuning vision-language models (VLMs) for both perception and reasoning, but their tokenization of images fundamentally disrupts continuous spatial relationships between objects. We introduce DTwinSeger, a novel RS approach that leverages Digital Twin (DT) representation as an intermediate layer to decouple perception from reasoning. Innovatively, DTwinSeger reformulates RS as a two-stage process, where the first transforms the image into a structured DT representation that preserves spatial relationships and semantic properties and then employs a Large Language Model (LLM) to perform explicit reasoning over this representation to identify target objects. We propose a supervised fine-tuning method specifically for LLM with DT representation, together with a corresponding fine-tuning dataset Seg-DT, to enhance the LLM's reasoning capabilities with DT representations. Experiments show that our method can achieve state-of-the-art performance on two image RS benchmarks and three image referring segmentation benchmarks. It yields that DT representation functions as an effective bridge between vision and text, enabling complex multimodal reasoning tasks to be accomplished solely with an LLM.

[Arxiv](https://arxiv.org/abs/2506.07943)