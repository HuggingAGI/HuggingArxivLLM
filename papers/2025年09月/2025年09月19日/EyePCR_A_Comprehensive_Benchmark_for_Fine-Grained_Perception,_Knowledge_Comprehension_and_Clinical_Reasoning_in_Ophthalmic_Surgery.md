# EyePCR：面向眼科手术领域细粒度感知、知识理解与临床推理的全面基准

发布时间：2025年09月19日

`LLM应用` `医疗健康`

> EyePCR: A Comprehensive Benchmark for Fine-Grained Perception, Knowledge Comprehension and Clinical Reasoning in Ophthalmic Surgery

# 摘要

> 多模态大型语言模型（MLLMs）虽展现出卓越能力，但其在高风险特定领域场景（如手术环境）中的表现尚未得到充分研究。为填补这一空白，我们构建了	extbf{EyePCR}——一个基于结构化临床知识的眼科手术分析大规模基准，用于评估	extit{感知}、	extit{理解}与	extit{推理}三大认知维度。EyePCR包含超过21万视觉问答（VQAs）的标注丰富语料库，涵盖1048个细粒度属性以支持多视图感知，超过2.5万三元组的医学知识图谱以助力理解，以及四项基于临床实践的推理任务。丰富的标注支持深入的认知分析，能模拟外科医生感知视觉线索并结合领域知识进行决策的过程，进而显著提升模型的认知能力。值得注意的是，	extbf{EyePCR-MLLM}作为Qwen2.5-VL-7B的领域适配变体，在	extit{感知}类多项选择题（MCQs）上准确率居所有对比模型之首，在	extit{理解}和	extit{推理}任务上超越开源模型，可媲美GPT-4.1等商业模型。EyePCR不仅揭示了现有MLLMs在手术认知中的局限性，更为手术视频理解模型的基准测试及临床可靠性提升奠定了基础。

> MLLMs (Multimodal Large Language Models) have showcased remarkable capabilities, but their performance in high-stakes, domain-specific scenarios like surgical settings, remains largely under-explored. To address this gap, we develop \textbf{EyePCR}, a large-scale benchmark for ophthalmic surgery analysis, grounded in structured clinical knowledge to evaluate cognition across \textit{Perception}, \textit{Comprehension} and \textit{Reasoning}. EyePCR offers a richly annotated corpus with more than 210k VQAs, which cover 1048 fine-grained attributes for multi-view perception, medical knowledge graph of more than 25k triplets for comprehension, and four clinically grounded reasoning tasks. The rich annotations facilitate in-depth cognitive analysis, simulating how surgeons perceive visual cues and combine them with domain knowledge to make decisions, thus greatly improving models' cognitive ability. In particular, \textbf{EyePCR-MLLM}, a domain-adapted variant of Qwen2.5-VL-7B, achieves the highest accuracy on MCQs for \textit{Perception} among compared models and outperforms open-source models in \textit{Comprehension} and \textit{Reasoning}, rivalling commercial models like GPT-4.1. EyePCR reveals the limitations of existing MLLMs in surgical cognition and lays the foundation for benchmarking and enhancing clinical reliability of surgical video understanding models.

[Arxiv](https://arxiv.org/abs/2509.15596)