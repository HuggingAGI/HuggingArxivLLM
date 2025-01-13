# LLMQuoter: 通过高效提取大上下文中的引用来增强 RAG 能力

发布时间：2025年01月09日

`RAG

理由：这篇论文介绍了LLMQuoter，一个基于蒸馏的模型，旨在通过提取最相关的文本证据来增强检索增强生成（RAG）。RAG是一种结合检索和生成的技术，通常用于增强语言模型在下游任务中的表现。论文中提到的“先引用后回答”策略和引用推理都与RAG的核心思想密切相关，因此将其分类为RAG是合适的。` `信息检索`

> LLMQuoter: Enhancing RAG Capabilities Through Efficient Quote Extraction From Large Contexts

# 摘要

> 我们推出了LLMQuoter，一个轻量级、基于蒸馏的模型，旨在通过提取最相关的文本证据来增强检索增强生成（RAG），助力下游推理任务。LLMQuoter基于LLaMA-3B架构，并在HotpotQA的15,000个样本子集上使用LoRA进行微调，采用“先引用后回答”策略，高效识别关键引用，再将精选片段传递给推理模型。这一流程降低了认知负担，并在小型和大型语言模型上均优于全上下文方法（如RAFT），准确率提升超过20个百分点。通过高性能教师模型的知识蒸馏，LLMQuoter在资源高效的微调设置中表现出色，无需大量重新训练即可显著提升性能。我们的研究展示了基于蒸馏的引用推理在简化复杂工作流程中的潜力，为研究者和从业者提供了一个可扩展且实用的解决方案。

> We introduce LLMQuoter, a lightweight, distillation-based model designed to enhance Retrieval Augmented Generation (RAG) by extracting the most relevant textual evidence for downstream reasoning tasks. Built on the LLaMA-3B architecture and fine-tuned with Low-Rank Adaptation (LoRA) on a 15,000-sample subset of HotpotQA, LLMQuoter adopts a "quote-first-then-answer" strategy, efficiently identifying key quotes before passing curated snippets to reasoning models. This workflow reduces cognitive overhead and outperforms full-context approaches like Retrieval-Augmented Fine-Tuning (RAFT), achieving over 20-point accuracy gains across both small and large language models. By leveraging knowledge distillation from a high-performing teacher model, LLMQuoter achieves competitive results in a resource-efficient fine-tuning setup. It democratizes advanced RAG capabilities, delivering significant performance improvements without requiring extensive model retraining. Our results highlight the potential of distilled quote-based reasoning to streamline complex workflows, offering a scalable and practical solution for researchers and practitioners alike.

[Arxiv](https://arxiv.org/abs/2501.05554)