# VLR-Bench：用于视觉语言检索增强生成的多语言基准数据集

发布时间：2024年12月13日

`RAG` `视觉语言模型` `视觉问答`

> VLR-Bench: Multilingual Benchmark Dataset for Vision-Language Retrieval Augmented Generation

# 摘要

> 我们推出了 VLR-Bench，这是用于评估基于检索增强生成（RAG）的视觉语言模型（VLMs）的视觉问答（VQA）基准。和现有的基于外部知识的 VQA 评估数据集不同，提出的 VLR-Bench 涵盖了五个输入段落。这能够检验确定哪个段落对回答给定问题有用的能力，而这在以往研究中是缺失的。在此情形下，我们构建了一个包含 32,000 个自动生成的遵循指令示例的数据集，称为 VLR-IF。此数据集专为增强 VLMs 的 RAG 能力而设，使其能够依据输入段落生成恰当答案。我们评估了所提基准和训练数据的有效性，并使用最先进的基于 Llama3 的 VLM——Llava-Llama-3 模型验证了其性能。所提出的 VLR-Bench 和 VLR-IF 数据集在网上可公开获取。

> We propose the VLR-Bench, a visual question answering (VQA) benchmark for evaluating vision language models (VLMs) based on retrieval augmented generation (RAG). Unlike existing evaluation datasets for external knowledge-based VQA, the proposed VLR-Bench includes five input passages. This allows testing of the ability to determine which passage is useful for answering a given query, a capability lacking in previous research. In this context, we constructed a dataset of 32,000 automatically generated instruction-following examples, which we denote as VLR-IF. This dataset is specifically designed to enhance the RAG capabilities of VLMs by enabling them to learn how to generate appropriate answers based on input passages. We evaluated the validity of the proposed benchmark and training data and verified its performance using the state-of-the-art Llama3-based VLM, the Llava-Llama-3 model. The proposed VLR-Bench and VLR-IF datasets are publicly available online.

[Arxiv](https://arxiv.org/abs/2412.10151)