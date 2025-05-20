# # Table-R1：区域强化学习用于表格理解

发布时间：2025年05月18日

`LLM应用` `数据分析` `人工智能`

> Table-R1: Region-based Reinforcement Learning for Table Understanding

# 摘要

> 表格由于其结构化的行-列交互关系，为语言模型带来了独特挑战，需要专门的方法才能实现有效理解。尽管大型语言模型（LLMs）通过提示和链式思维（CoT）及程序化思维（PoT）等技术在表格推理方面展现出了潜力，但针对表格问答任务的性能优化仍处于探索阶段。本文中，我们提出了基于区域的Table-R1，这是一种新型强化学习方法，通过将区域证据整合到推理步骤中，提升LLM对表格的理解能力。我们的方法采用区域增强监督微调（RE-SFT），指导模型在生成答案前识别相关表格区域，融合文本、符号和程序化推理。此外，基于表格感知的组相对策略优化（TARPO）引入了混合奖励系统，动态平衡区域准确性和答案正确性，通过递减区域奖励和一致性惩罚使推理步骤保持一致。实验表明，Table-R1在三个基准数据集上实现了多个基础模型平均性能提升14.36分，即使与参数量为其十倍的基线模型相比也表现更优，而TARPO相较于GRPO将响应标记消耗降低了67.5%，显著提升了LLM在高效表格推理方面的能力。

> Tables present unique challenges for language models due to their structured row-column interactions, necessitating specialized approaches for effective comprehension. While large language models (LLMs) have demonstrated potential in table reasoning through prompting and techniques like chain-of-thought (CoT) and program-of-thought (PoT), optimizing their performance for table question answering remains underexplored. In this paper, we introduce region-based Table-R1, a novel reinforcement learning approach that enhances LLM table understanding by integrating region evidence into reasoning steps. Our method employs Region-Enhanced Supervised Fine-Tuning (RE-SFT) to guide models in identifying relevant table regions before generating answers, incorporating textual, symbolic, and program-based reasoning. Additionally, Table-Aware Group Relative Policy Optimization (TARPO) introduces a mixed reward system to dynamically balance region accuracy and answer correctness, with decaying region rewards and consistency penalties to align reasoning steps. Experiments show that Table-R1 achieves an average performance improvement of 14.36 points across multiple base models on three benchmark datasets, even outperforming baseline models with ten times the parameters, while TARPO reduces response token consumption by 67.5% compared to GRPO, significantly advancing LLM capabilities in efficient tabular reasoning.

[Arxiv](https://arxiv.org/abs/2505.12415)