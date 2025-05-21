# 按需思考：大规模混合推理模型的智慧决策。

发布时间：2025年05月20日

`LLM理论` `人工智能` `推理系统`

> Think Only When You Need with Large Hybrid-Reasoning Models

# 摘要

> 近期的大型推理模型（LRMs）相较于传统大型语言模型（LLMs），通过在生成最终回答前引入扩展的思考过程，展现出显著增强的推理能力。然而，过于冗长的思考过程带来了显著的令牌消耗和延迟开销，这对简单查询而言尤其没有必要。在本研究中，我们引入了大型混合推理模型（LHRMs），这是首款能够基于用户查询的上下文信息自适应决定是否进行思考的模型。为此，我们提出了一种两阶段训练流水线，首先采用混合微调（HFT）作为冷启动，随后通过结合提出的混合组策略优化（HGPO）进行在线强化学习，以隐式学习选择合适的思考模式。此外，我们引入了一项名为混合准确度的指标，用于定量评估模型的混合思考能力。大量实验结果表明，LHRMs能够自适应地对不同难度和类型的查询进行混合思考。在推理和通用能力方面，它超越了现有的LRMs和LLMs，同时显著提升了效率。总之，我们的工作呼吁重新审视扩展思考过程的适当应用，并为构建混合思考系统提供了坚实的基础。


> Recent Large Reasoning Models (LRMs) have shown substantially improved reasoning capabilities over traditional Large Language Models (LLMs) by incorporating extended thinking processes prior to producing final responses. However, excessively lengthy thinking introduces substantial overhead in terms of token consumption and latency, which is particularly unnecessary for simple queries. In this work, we introduce Large Hybrid-Reasoning Models (LHRMs), the first kind of model capable of adaptively determining whether to perform thinking based on the contextual information of user queries. To achieve this, we propose a two-stage training pipeline comprising Hybrid Fine-Tuning (HFT) as a cold start, followed by online reinforcement learning with the proposed Hybrid Group Policy Optimization (HGPO) to implicitly learn to select the appropriate thinking mode. Furthermore, we introduce a metric called Hybrid Accuracy to quantitatively assess the model's capability for hybrid thinking. Extensive experimental results show that LHRMs can adaptively perform hybrid thinking on queries of varying difficulty and type. It outperforms existing LRMs and LLMs in reasoning and general capabilities while significantly improving efficiency. Together, our work advocates for a reconsideration of the appropriate use of extended thinking processes and provides a solid starting point for building hybrid thinking systems.

[Arxiv](https://arxiv.org/abs/2505.14631)