# NLKI：轻量级自然语言知识整合框架——助力小型视觉语言模型在常识视觉问答任务中提升

发布时间：2025年08月28日

`RAG` `基础理论`

> NLKI: A lightweight Natural Language Knowledge Integration Framework for Improving Small VLMs in Commonsense VQA Tasks

# 摘要

> 常识视觉问答往往需要图像或问题本身未提供的知识支撑，因此ViLT、VisualBERT和FLAVA等小型视觉语言模型（sVLMs）在性能上落后于大型生成式视觉语言模型。为探索常识知识的精细化整合对小型视觉语言模型的作用，我们提出端到端框架NLKI，通过三步实现：（i）检索自然语言事实；（ii）引导大型语言模型生成自然语言解释；（iii）将这两种信号分别输入小型视觉语言模型，并在两个常识视觉问答数据集（CRIC、AOKVQA）和一个视觉蕴含数据集（e-SNLI-VE）上测试。研究发现，通过微调的ColBERTv2检索事实，结合对象信息增强的提示生成解释，不仅显著降低了幻觉现象，还将端到端答案准确率提升最高7%（跨3个数据集），使FLAVA等模型性能达到甚至超越Qwen-2 VL-2B、SmolVLM-2.5B等中型视觉语言模型。针对这些基准数据集含10-25%标签噪声的问题，额外采用抗噪声损失（如对称交叉熵、广义交叉熵）微调后，CRIC数据集准确率再提升2.5%，AOKVQA数据集提升5.5%。研究结果揭示了三大核心发现：基于大型语言模型的常识知识何时优于常识知识库检索、噪声感知训练如何在外部知识增强场景下稳定小型模型性能，以及为何2.5亿参数模型现已具备参数高效的常识推理能力。

> Commonsense visual-question answering often hinges on knowledge that is missing from the image or the question. Small vision-language models (sVLMs) such as ViLT, VisualBERT and FLAVA therefore lag behind their larger generative counterparts. To study the effect of careful commonsense knowledge integration on sVLMs, we present an end-to-end framework (NLKI) that (i) retrieves natural language facts, (ii) prompts an LLM to craft natural language explanations, and (iii) feeds both signals to sVLMs respectively across two commonsense VQA datasets (CRIC, AOKVQA) and a visual-entailment dataset (e-SNLI-VE). Facts retrieved using a fine-tuned ColBERTv2 and an object information-enriched prompt yield explanations that largely cut down hallucinations, while lifting the end-to-end answer accuracy by up to 7% (across 3 datasets), making FLAVA and other models in NLKI match or exceed medium-sized VLMs such as Qwen-2 VL-2B and SmolVLM-2.5B. As these benchmarks contain 10-25% label noise, additional finetuning using noise-robust losses (such as symmetric cross entropy and generalised cross entropy) adds another 2.5% in CRIC, and 5.5% in AOKVQA. Our findings expose when LLM-based commonsense knowledge beats retrieval from commonsense knowledge bases, how noise-aware training stabilises small models in the context of external knowledge augmentation, and why parameter-efficient commonsense reasoning is now within reach for 250M models.

[Arxiv](https://arxiv.org/abs/2508.19724)