# 强化学习在 LLM 中的分布外推理应用：诊断相关组编码实证研究

发布时间：2025年05月27日

`LLM应用` `医疗管理`

> Reinforcement Learning for Out-of-Distribution Reasoning in LLMs: An Empirical Study on Diagnosis-Related Group Coding

# 摘要

> 诊断相关组（DRG）编码对医院的报销和运营至关重要，但传统的人工分配方式耗时费力。大型语言模型（LLMs）在DRG编码方面面临挑战，因为该任务具有领域外（OOD）性质：预训练语料库中很少包含私密的临床或计费数据。我们开发了DRG-Sapphire，它通过大规模强化学习（RL）从临床记录中实现自动DRG编码。DRG-Sapphire基于Qwen2.5-7B构建，并使用基于规则的奖励通过组相对策略优化（GRPO）进行训练。针对以往数学任务中未见的领域特定挑战，DRG-Sapphire引入了一系列RL增强。我们的模型在MIMIC-IV基准上达到了最先进的准确率，并生成了经医生验证的DRG分配推理，显著提升了可解释性。我们的研究进一步揭示了将RL应用于知识密集型、领域外任务的更广泛挑战。我们发现，RL性能与监督微调（SFT）示例数量的对数大致呈线性增长关系，这表明RL的有效性从根本上受到基础模型中编码的领域知识的限制。对于像DRG编码这样的OOD任务，强大的RL性能需要在RL之前充分注入知识。因此，对于此类任务，扩展SFT可能比单纯扩展RL更有效且计算效率更高。

> Diagnosis-Related Group (DRG) codes are essential for hospital reimbursement and operations but require labor-intensive assignment. Large Language Models (LLMs) struggle with DRG coding due to the out-of-distribution (OOD) nature of the task: pretraining corpora rarely contain private clinical or billing data. We introduce DRG-Sapphire, which uses large-scale reinforcement learning (RL) for automated DRG coding from clinical notes. Built on Qwen2.5-7B and trained with Group Relative Policy Optimization (GRPO) using rule-based rewards, DRG-Sapphire introduces a series of RL enhancements to address domain-specific challenges not seen in previous mathematical tasks. Our model achieves state-of-the-art accuracy on the MIMIC-IV benchmark and generates physician-validated reasoning for DRG assignments, significantly enhancing explainability. Our study further sheds light on broader challenges of applying RL to knowledge-intensive, OOD tasks. We observe that RL performance scales approximately linearly with the logarithm of the number of supervised fine-tuning (SFT) examples, suggesting that RL effectiveness is fundamentally constrained by the domain knowledge encoded in the base model. For OOD tasks like DRG coding, strong RL performance requires sufficient knowledge infusion prior to RL. Consequently, scaling SFT may be more effective and computationally efficient than scaling RL alone for such tasks.

[Arxiv](https://arxiv.org/abs/2505.21908)