# ReFineG：协同融合小型监督模型与大型语言模型，赋能低资源场景接地多模态命名实体识别

发布时间：2025年09月13日

`LLM应用` `基础理论`

> ReFineG: Synergizing Small Supervised Models and LLMs for Low-Resource Grounded Multimodal NER

# 摘要

> 接地多模态命名实体识别（GMNER）通过联合检测文本提及并关联至视觉区域，拓展了传统NER的能力。现有监督方法虽性能优异，却依赖成本高昂的多模态标注，在低资源领域常表现欠佳。多模态大型语言模型（MLLMs）泛化能力突出，却受限于领域知识冲突，易为特定领域实体生成冗余或错误提及。为解决这些挑战，我们提出ReFineG——一个三阶段协作框架，将小型监督模型与冻结的MLLMs集成，以应对低资源GMNER任务。训练阶段采用领域感知的NER数据合成策略，通过监督训练将LLM知识迁移至小型模型，同时规避领域知识冲突；精修阶段借助基于不确定性的机制，保留监督模型的置信预测，将不确定部分交由MLLM处理；接地阶段则通过多模态上下文选择算法，利用类比推理强化视觉接地效果。在CCKS2025 GMNER共享任务中，ReFineG以0.6461的F1分数位列在线排行榜第二，印证了其在标注数据有限时的有效性。

> Grounded Multimodal Named Entity Recognition (GMNER) extends traditional NER by jointly detecting textual mentions and grounding them to visual regions. While existing supervised methods achieve strong performance, they rely on costly multimodal annotations and often underperform in low-resource domains. Multimodal Large Language Models (MLLMs) show strong generalization but suffer from Domain Knowledge Conflict, producing redundant or incorrect mentions for domain-specific entities. To address these challenges, we propose ReFineG, a three-stage collaborative framework that integrates small supervised models with frozen MLLMs for low-resource GMNER. In the Training Stage, a domain-aware NER data synthesis strategy transfers LLM knowledge to small models with supervised training while avoiding domain knowledge conflicts. In the Refinement Stage, an uncertainty-based mechanism retains confident predictions from supervised models and delegates uncertain ones to the MLLM. In the Grounding Stage, a multimodal context selection algorithm enhances visual grounding through analogical reasoning. In the CCKS2025 GMNER Shared Task, ReFineG ranked second with an F1 score of 0.6461 on the online leaderboard, demonstrating its effectiveness with limited annotations.

[Arxiv](https://arxiv.org/abs/2509.10975)