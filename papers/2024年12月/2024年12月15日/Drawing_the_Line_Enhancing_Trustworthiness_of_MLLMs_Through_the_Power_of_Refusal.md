# 划定界限：利用拒绝机制提升多模态大语言模型的可信度

发布时间：2024年12月15日

`LLM应用` `人工智能`

> Drawing the Line: Enhancing Trustworthiness of MLLMs Through the Power of Refusal

# 摘要

> 多模态大型语言模型（MLLMs）在多模态感知和理解上表现卓越，但其生成的幻觉或不准确响应影响了其可信度。现有方法大多忽视了拒绝响应在提升MLLMs可靠性中的重要性。为此，我们提出了信息边界感知学习框架（InBoL），这一创新方法使MLLMs在信息不足时能够拒绝回答用户查询。InBoL是首个利用信息边界概念系统定义MLLMs拒绝条件的框架，并引入了全面的数据生成管道和定制训练策略，以增强模型的拒绝响应能力。为评估MLLMs的可信度，我们还提出了以用户为中心的对齐目标及相应指标。实验显示，拒绝准确性显著提升，且模型的有用性未受明显影响，标志着InBoL在构建更可信MLLMs方面迈出了关键一步。

> Multimodal large language models (MLLMs) excel at multimodal perception and understanding, yet their tendency to generate hallucinated or inaccurate responses undermines their trustworthiness. Existing methods have largely overlooked the importance of refusal responses as a means of enhancing MLLMs reliability. To bridge this gap, we present the Information Boundary-aware Learning Framework (InBoL), a novel approach that empowers MLLMs to refuse to answer user queries when encountering insufficient information. To the best of our knowledge, InBoL is the first framework that systematically defines the conditions under which refusal is appropriate for MLLMs using the concept of information boundaries proposed in our paper. This framework introduces a comprehensive data generation pipeline and tailored training strategies to improve the model's ability to deliver appropriate refusal responses. To evaluate the trustworthiness of MLLMs, we further propose a user-centric alignment goal along with corresponding metrics. Experimental results demonstrate a significant improvement in refusal accuracy without noticeably compromising the model's helpfulness, establishing InBoL as a pivotal advancement in building more trustworthy MLLMs.

[Arxiv](https://arxiv.org/abs/2412.11196)