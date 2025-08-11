# 资源受限场景下的联合多模态情感推理与分类通过链式思维增强与知识蒸馏实现

发布时间：2025年08月07日

`LLM应用` `社交媒体` `情感分析`

> Resource-Limited Joint Multimodal Sentiment Reasoning and Classification via Chain-of-Thought Enhancement and Distillation

# 摘要

> 社交媒体平台上多模态内容的激增推动了多模态情感分析（MSA）的蓬勃发展，而大型语言模型（LLMs）的出现更是为这一领域注入了新的活力。目前的研究主要依赖参数量庞大的（多模态）LLMs进行情感分类，却忽视了资源受限环境下自主多模态情感推理生成的重要性。为此，我们聚焦于资源受限的联合多模态情感推理与分类任务JMSRC，该任务仅借助轻量级模型即可同时实现多模态情感推理链生成和情感分类。针对这一挑战，我们提出了一种名为MulCoT-RD的多模态链式推理蒸馏模型，采用“教师-助理-学生”蒸馏范式，有效解决了资源受限环境下的部署难题。具体而言，我们首先利用高性能的多模态大型语言模型（MLLM）生成初始推理数据集，并通过多任务学习机制训练出一个中等规模的助理模型。在此基础上，我们进一步联合训练一个轻量级的学生模型，使其能够高效完成多模态情感推理生成和分类任务。通过在四个数据集上的大量实验，结果表明，仅包含30亿参数的MulCoT-RD在JMSRC任务上表现优异，不仅展现了强大的泛化能力，还显著提升了模型的可解释性。

> The surge in rich multimodal content on social media platforms has greatly advanced Multimodal Sentiment Analysis (MSA), with Large Language Models (LLMs) further accelerating progress in this field. Current approaches primarily leverage the knowledge and reasoning capabilities of parameter-heavy (Multimodal) LLMs for sentiment classification, overlooking autonomous multimodal sentiment reasoning generation in resource-constrained environments. Therefore, we focus on the Resource-Limited Joint Multimodal Sentiment Reasoning and Classification task, JMSRC, which simultaneously performs multimodal sentiment reasoning chain generation and sentiment classification only with a lightweight model. We propose a Multimodal Chain-of-Thought Reasoning Distillation model, MulCoT-RD, designed for JMSRC that employs a "Teacher-Assistant-Student" distillation paradigm to address deployment constraints in resource-limited environments. We first leverage a high-performance Multimodal Large Language Model (MLLM) to generate the initial reasoning dataset and train a medium-sized assistant model with a multi-task learning mechanism. A lightweight student model is jointly trained to perform efficient multimodal sentiment reasoning generation and classification. Extensive experiments on four datasets demonstrate that MulCoT-RD with only 3B parameters achieves strong performance on JMSRC, while exhibiting robust generalization and enhanced interpretability.

[Arxiv](https://arxiv.org/abs/2508.05234)