# FaceBench: 一个多视角、多层级面部属性VQA数据集，用于评估面部感知多语言模型

发布时间：2025年03月27日

`LLM应用` `计算机视觉` `人工智能`

> FaceBench: A Multi-View Multi-Level Facial Attribute VQA Dataset for Benchmarking Face Perception MLLMs

# 摘要

> 多模态大型语言模型 (MLLMs) 在多种任务中表现优异，但在面部感知能力的评估方面仍存在研究空白。为此，我们提出了 FaceBench，一个专为评估 MLLMs 面部感知能力设计的数据集，包含层次化多视角和多层级属性。首先，我们构建了一个包含五个视角、总计超过 210 个属性和 700 个属性值的层次化面部属性结构。基于此结构，FaceBench 提供了 49,919 个用于评估的视觉问答 (VQA) 对和 23,841 个用于微调的对。此外，我们还开发了一个基于面部 VQA 数据训练的稳健面部感知 MLLM 基线模型 Face-LLaVA。通过广泛实验，我们测试了主流 MLLMs 和 Face-LLaVA 的面部感知能力，并将其与人类表现进行了对比。结果表明，现有 MLLMs 在理解精细面部属性方面仍有较大提升空间，而我们的 Face-LLaVA 仅使用少量训练数据就显著优于开源模型，并可与 GPT-4 和 Gemini 等商业模型相媲美。FaceBench 数据集将在 https://github.com/CVI-SZU/FaceBench 上公开发布。

> Multimodal large language models (MLLMs) have demonstrated remarkable capabilities in various tasks. However, effectively evaluating these MLLMs on face perception remains largely unexplored. To address this gap, we introduce FaceBench, a dataset featuring hierarchical multi-view and multi-level attributes specifically designed to assess the comprehensive face perception abilities of MLLMs. Initially, we construct a hierarchical facial attribute structure, which encompasses five views with up to three levels of attributes, totaling over 210 attributes and 700 attribute values. Based on the structure, the proposed FaceBench consists of 49,919 visual question-answering (VQA) pairs for evaluation and 23,841 pairs for fine-tuning. Moreover, we further develop a robust face perception MLLM baseline, Face-LLaVA, by training with our proposed face VQA data. Extensive experiments on various mainstream MLLMs and Face-LLaVA are conducted to test their face perception ability, with results also compared against human performance. The results reveal that, the existing MLLMs are far from satisfactory in understanding the fine-grained facial attributes, while our Face-LLaVA significantly outperforms existing open-source models with a small amount of training data and is comparable to commercial ones like GPT-4o and Gemini. The dataset will be released at https://github.com/CVI-SZU/FaceBench.

[Arxiv](https://arxiv.org/abs/2503.21457)