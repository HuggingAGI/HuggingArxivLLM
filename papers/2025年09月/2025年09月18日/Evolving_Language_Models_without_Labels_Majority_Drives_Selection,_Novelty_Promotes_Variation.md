# 无需标签的语言模型进化：多数主导选择，新颖性推动变异

发布时间：2025年09月18日

`强化学习` `基础理论`

> Evolving Language Models without Labels: Majority Drives Selection, Novelty Promotes Variation

# 摘要

> 大型语言模型（LLMs）如今越来越多地采用基于可验证奖励的强化学习（RLVR）进行训练，但实际部署却要求模型能在无标签、无外部评判的情况下实现自我改进。现有的无标签方法——如置信度最小化、自一致性或多数投票目标——虽能稳定学习，却会不断压缩探索空间，最终导致“熵崩溃”：生成内容越来越短、多样性锐减且脆弱不堪。不同于测试时强化学习（TTRL）等现有方法仅聚焦于让模型适配手头即时的无标签数据集，我们的目标更为高远：实现模型的通用改进，同时不牺牲其固有的探索能力与泛化能力，即“进化”。为此，我们将这一问题形式化，并提出面向进化的无标签强化学习（EVOL-RL）——一种在无标签场景下平衡稳定性与变异性的简洁方案。EVOL-RL以多数投票结果为稳定锚点（负责“选择”），同时引入新颖性感知奖励，鼓励生成推理过程与已有内容在语义空间中存在差异的响应（负责“变异”）。通过GRPO实现时，EVOL-RL还采用非对称裁剪保留强信号，并借助熵正则化维持探索活力。这种“多数投票选优+新颖性促变”的设计不仅能避免崩溃，还能生成更长、信息更丰富的思维链，显著提升pass@1和pass@n指标。在无标签AIME24数据集上的实验显示，EVOL-RL持续优于仅用多数投票的TTRL基线：例如，Qwen3-4B-Base模型在AIME25上的pass@1从TTRL的4.6%跃升至16.4%，pass@16从18.5%提升至37.9%。值得注意的是，EVOL-RL在RLVR场景下同样能提升性能，充分证明了其广泛适用性。

> Large language models (LLMs) are increasingly trained with reinforcement learning from verifiable rewards (RLVR), yet real-world deployment demands models that can self-improve without labels or external judges. Existing label-free methods, confidence minimization, self-consistency, or majority-vote objectives, stabilize learning but steadily shrink exploration, causing an entropy collapse: generations become shorter, less diverse, and brittle. Unlike prior approaches such as Test-Time Reinforcement Learning (TTRL), which primarily adapt models to the immediate unlabeled dataset at hand, our goal is broader: to enable general improvements without sacrificing the model's inherent exploration capacity and generalization ability, i.e., evolving. We formalize this issue and propose EVolution-Oriented and Label-free Reinforcement Learning (EVOL-RL), a simple rule that couples stability with variation under a label-free setting. EVOL-RL keeps the majority-voted answer as a stable anchor (selection) while adding a novelty-aware reward that favors responses whose reasoning differs from what has already been produced (variation), measured in semantic space. Implemented with GRPO, EVOL-RL also uses asymmetric clipping to preserve strong signals and an entropy regularizer to sustain search. This majority-for-selection + novelty-for-variation design prevents collapse, maintains longer and more informative chains of thought, and improves both pass@1 and pass@n. EVOL-RL consistently outperforms the majority-only TTRL baseline; e.g., training on label-free AIME24 lifts Qwen3-4B-Base AIME25 pass@1 from TTRL's 4.6% to 16.4%, and pass@16 from 18.5% to 37.9%. EVOL-RL not only prevents diversity collapse but also unlocks stronger generalization across domains (e.g., GPQA). Furthermore, we demonstrate that EVOL-RL also boosts performance in the RLVR setting, highlighting its broad applicability.

[Arxiv](https://arxiv.org/abs/2509.15194)