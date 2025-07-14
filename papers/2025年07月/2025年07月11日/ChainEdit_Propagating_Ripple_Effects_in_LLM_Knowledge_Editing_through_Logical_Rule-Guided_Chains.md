# ChainEdit: 通过逻辑规则引导的链式结构，在 LLM 知识编辑中传播涟漪效应

发布时间：2025年07月11日

`LLM理论` `知识图谱` `知识编辑`

> ChainEdit: Propagating Ripple Effects in LLM Knowledge Editing through Logical Rule-Guided Chains

# 摘要

> 现有大型语言模型 (LLMs) 的知识编辑方法在传播连锁效应到相关事实时，往往难以保持逻辑一致性。为此，我们提出 ChainEdit，一个结合知识图谱逻辑规则与 LLM 逻辑推理能力的框架，实现系统化的链式更新。通过从结构化知识库中自动提取逻辑模式，并与 LLM 的内部逻辑相匹配，ChainEdit 动态生成并编辑逻辑相关联的知识集群。实验结果表明，与基线方法相比，逻辑泛化能力提升了超过 30%，同时保持了编辑的可靠性和特异性。我们还通过知识感知协议解决了现有基准中的评估偏差，这些协议可以消除外部依赖关系。这项工作在连锁效应方面取得了新的最先进性能，同时确保了知识编辑后的内部逻辑一致性。

> Current knowledge editing methods for large language models (LLMs) struggle to maintain logical consistency when propagating ripple effects to associated facts. We propose ChainEdit, a framework that synergizes knowledge graph-derived logical rules with LLM logical reasoning capabilities to enable systematic chain updates. By automatically extracting logical patterns from structured knowledge bases and aligning them with LLMs' internal logics, ChainEdit dynamically generates and edits logically connected knowledge clusters. Experiments demonstrate an improvement of more than 30% in logical generalization over baselines while preserving editing reliability and specificity. We further address evaluation biases in existing benchmarks through knowledge-aware protocols that disentangle external dependencies. This work establishes new state-of-the-art performance on ripple effect while ensuring internal logical consistency after knowledge editing.

[Arxiv](https://arxiv.org/abs/2507.08427)