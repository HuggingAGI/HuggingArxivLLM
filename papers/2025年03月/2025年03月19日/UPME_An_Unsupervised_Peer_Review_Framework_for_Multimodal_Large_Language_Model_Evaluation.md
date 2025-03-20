# UPME：无监督多模态大语言模型评估框架

发布时间：2025年03月19日

`LLM应用` `计算机视觉`

> UPME: An Unsupervised Peer Review Framework for Multimodal Large Language Model Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）应运而生，旨在解决视觉问答（VQA）的挑战，这激发了对这些模型进行客观评估的新研究方向。现有评估方法的局限性主要源于设计图像问答对所需的巨大人工投入，这本质上限制了评估的规模和范围。尽管自动化的MLLM-as-judge方法试图通过自动评估来减少人工工作量，但它们常常引入偏见。为了解决这些问题，我们提出了一种无监督的同行评审MLLM评估框架。该框架仅利用图像数据，使模型能够自动生成问题，并对其他模型的回答进行同行评审评估，从而有效缓解了对人工工作量的依赖。此外，我们引入了视觉-语言评分系统来缓解偏见问题，该系统关注三个方面：(i) 响应正确性；(ii) 视觉理解和推理；(iii) 图像-文本相关性。实验结果表明，UPME在MMstar数据集上与人工评估的皮尔逊相关系数为0.944，在ScienceQA数据集上为0.814，表明我们的框架与人工设计的基准和固有人类偏好密切相关。

> Multimodal Large Language Models (MLLMs) have emerged to tackle the challenges of Visual Question Answering (VQA), sparking a new research focus on conducting objective evaluations of these models. Existing evaluation methods face limitations due to the significant human workload required to design Q&A pairs for visual images, which inherently restricts the scale and scope of evaluations. Although automated MLLM-as-judge approaches attempt to reduce the human workload through automatic evaluations, they often introduce biases. To address these problems, we propose an Unsupervised Peer review MLLM Evaluation framework. It utilizes only image data, allowing models to automatically generate questions and conduct peer review assessments of answers from other models, effectively alleviating the reliance on human workload. Additionally, we introduce the vision-language scoring system to mitigate the bias issues, which focuses on three aspects: (i) response correctness; (ii) visual understanding and reasoning; and (iii) image-text correlation. Experimental results demonstrate that UPME achieves a Pearson correlation of 0.944 with human evaluations on the MMstar dataset and 0.814 on the ScienceQA dataset, indicating that our framework closely aligns with human-designed benchmarks and inherent human preferences.

[Arxiv](https://arxiv.org/abs/2503.14941)