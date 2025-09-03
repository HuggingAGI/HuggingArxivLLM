# 面向低资源菲律宾语言零样本跨语言命名实体识别的元预训练

发布时间：2025年09月02日

`LLM应用` `基础理论`

> Meta-Pretraining for Zero-Shot Cross-Lingual Named Entity Recognition in Low-Resource Philippine Languages

# 摘要

> 低资源语言的命名实体识别（NER）通常依赖微调超大型多语言语言模型，但在内存或延迟受限的场景下，这种方案往往难以实现。我们探讨：能否预训练小型解码器语言模型，使其能够快速适应并对预训练时未接触过的语言实现零样本迁移？为此，我们将部分自回归目标函数替换为一阶模型无关元学习（MAML）。他加禄语和宿务语虽类型相近，但在施事/非施事语态系统上结构差异显著，因此构成了极具挑战性的测试场景。在四种模型规模（1100万-5.7亿参数）上，MAML在仅调整头部时能将零样本micro-F1提升2-6个百分点，全量微调后提升1-3个百分点，同时收敛时间缩短高达8%。尤其对于与他加禄语格标记si/ni共现的单标记人物实体，性能提升最为明显，这充分体现了表层锚点的关键作用。

> Named-entity recognition (NER) in low-resource languages is usually tackled by finetuning very large multilingual LMs, an option that is often infeasible in memory- or latency-constrained settings. We ask whether small decoder LMs can be pretrained so that they adapt quickly and transfer zero-shot to languages unseen during pretraining. To this end we replace part of the autoregressive objective with first-order model-agnostic meta-learning (MAML). Tagalog and Cebuano are typologically similar yet structurally different in their actor/non-actor voice systems, and hence serve as a challenging test-bed. Across four model sizes (11 M - 570 M) MAML lifts zero-shot micro-F1 by 2-6 pp under head-only tuning and 1-3 pp after full tuning, while cutting convergence time by up to 8%. Gains are largest for single-token person entities that co-occur with Tagalog case particles si/ni, highlighting the importance of surface anchors.

[Arxiv](https://arxiv.org/abs/2509.02160)