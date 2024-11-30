# RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。

发布时间：2024年04月18日

`分类：RAG` `政治话语分析` `信息安全`

> RAGAR, Your Falsehood RADAR: RAG-Augmented Reasoning for Political Fact-Checking using Multimodal Large Language Models

# 摘要

> 面对政治话语中日益严峻的虚假信息挑战，迫切需要更先进的事实核查方案。本文介绍了一种创新方法，通过融合大型语言模型（LLMs）和基于检索增强生成（RAG）的高级推理技术，以提升多模态事实核查的可信度和效率。我们提出了两种新颖的方法论：RAG 链（CoRAG）和 RAG 树（ToRAG），旨在通过分析先前证据来推理出需要回答的后续问题，以处理多模态的声明。这些方法不仅提高了真实性预测的精确度，还增强了解释生成的能力，相较于传统基于子问题生成和思维链真实性预测的事实核查方法，表现更为出色。本研究通过运用能够分析文本和图像的多模态 LLMs，进一步推动了自动化系统在识别和抵御虚假信息方面的能力。

> The escalating challenge of misinformation, particularly in the context of political discourse, necessitates advanced solutions for fact-checking. We introduce innovative approaches to enhance the reliability and efficiency of multimodal fact-checking through the integration of Large Language Models (LLMs) with Retrieval-augmented Generation (RAG)- based advanced reasoning techniques. This work proposes two novel methodologies, Chain of RAG (CoRAG) and Tree of RAG (ToRAG). The approaches are designed to handle multimodal claims by reasoning the next questions that need to be answered based on previous evidence. Our approaches improve the accuracy of veracity predictions and the generation of explanations over the traditional fact-checking approach of sub-question generation with chain of thought veracity prediction. By employing multimodal LLMs adept at analyzing both text and images, this research advances the capability of automated systems in identifying and countering misinformation.

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/FrontPagee.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/pipelinefc_new.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/figCoragTorag-2.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/ratings_graph.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/annot.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/Question_Generation.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/QA_Elimination.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/Veracity_Prediction.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/ZSCOTPROMPT.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/CoVeFigure.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/Verification_Prompt.png)

![RAGAR——您的虚假信息侦测雷达：通过增强的 RAG（Retrieval-Augmented Generation）推理，利用多模态大型语言模型进行政治事实核查。](../../../paper_images/2404.12065/Correction_Prompt.png)

[Arxiv](https://arxiv.org/abs/2404.12065)