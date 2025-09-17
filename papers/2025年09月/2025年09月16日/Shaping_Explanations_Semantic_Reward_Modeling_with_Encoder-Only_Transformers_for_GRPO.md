# 塑造解释：面向GRPO的仅编码器Transformer语义奖励建模

发布时间：2025年09月16日

`强化学习` `教育科技`

> Shaping Explanations: Semantic Reward Modeling with Encoder-Only Transformers for GRPO

# 摘要

> 大型语言模型（LLMs）虽擅长生成类人文本，但要让其输出与教学合理性这类复杂的定性目标对齐，仍是一大难题。标准强化学习技术往往依赖缓慢昂贵的“LLM作为评判”评估，或是ROUGE等脆弱的基于关键词指标，而这些都无法捕捉高质量解释的语义核心。本研究提出一种新方法：在群体相对策略优化（GRPO）框架中，用小型高效的仅编码器Transformer模型作为语义奖励模型。该模型通过生成解释与真实参考间的余弦相似度，提供密集且语义丰富的奖励信号，引导策略生成不仅事实准确，而且在结构和概念上都与专家推理相符的解释。我们将此方法应用于意大利医学院入学考试模型训练——先经过标准的领域自适应持续预训练（CPT）和监督微调（SFT）。结果显示，带有语义奖励的GRPO在解释的忠实性与清晰度上显著优于性能强劲的SFT基线，充分证明了轻量级编码器模型在复杂生成任务中实现精细化奖励塑造的强大作用。

> While Large Language Models (LLMs) excel at generating human-like text, aligning their outputs with complex, qualitative goals like pedagogical soundness remains a significant challenge. Standard reinforcement learning techniques often rely on slow and expensive LLM-as-a-judge evaluations or on brittle, keyword-based metrics like ROUGE, which fail to capture the semantic essence of a high-quality explanation. In this work, we introduce a novel approach to reward shaping within the Group Relative Policy Optimisation (GRPO) framework. Our central contribution is the use of a small, efficient encoder-only transformer as a semantic reward model. This model provides a dense, semantically rich reward signal based on the cosine similarity between a generated explanation and a ground-truth reference, guiding the policy towards explanations that are not just factually correct but also structurally and conceptually aligned with expert reasoning. We apply this method to the task of training a model for the Italian medical-school entrance examinations, following standard domain-adaptive continued pre-training (CPT) and supervised fine-tuning (SFT). Our results demonstrate that GRPO with our proposed semantic reward significantly improves explanation faithfulness and clarity over a strong SFT baseline, showcasing the power of using lightweight encoder models for nuanced reward shaping in complex generation tasks

[Arxiv](https://arxiv.org/abs/2509.13081)