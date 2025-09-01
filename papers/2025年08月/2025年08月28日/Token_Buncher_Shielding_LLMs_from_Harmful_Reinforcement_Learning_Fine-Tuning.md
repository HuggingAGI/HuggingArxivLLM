# Token Buncher：为大型语言模型抵御有害强化学习微调

发布时间：2025年08月28日

`强化学习` `基础理论`

> Token Buncher: Shielding LLMs from Harmful Reinforcement Learning Fine-Tuning

# 摘要

> 随着大型语言模型（LLMs）能力的持续提升，通过微调实施有害滥用的风险也日益凸显。尽管以往多数研究认为攻击者会借助监督微调（SFT）实施此类滥用，但我们通过系统研究发现，在计算预算相当的情况下，强化学习（RL）能让攻击者更高效地破坏模型的安全对齐，进而提供更高级的有害任务辅助。为应对这一新兴威胁，我们提出了TokenBuncher——首个专门针对基于RL的有害微调的有效防御机制。TokenBuncher通过抑制RL的核心依赖——模型响应的不确定性——发挥作用：通过限制这种不确定性，基于RL的微调便无法再利用差异化的奖励信号诱导模型产生有害行为。我们通过“熵奖励强化学习”与“Token Noiser机制”实现了这一防御，后者专门用于阻止专家领域有害能力的升级。在多种模型和RL算法上的大量实验证实，TokenBuncher能稳健缓解有害的RL微调，同时保留良性任务的效用与可微调性。研究结果表明，基于RL的有害微调比SFT具有更大的系统性风险，而TokenBuncher则提供了一种有效且通用的防御方案。

> As large language models (LLMs) continue to grow in capability, so do the risks of harmful misuse through fine-tuning. While most prior studies assume that attackers rely on supervised fine-tuning (SFT) for such misuse, we systematically demonstrate that reinforcement learning (RL) enables adversaries to more effectively break safety alignment and facilitate advanced harmful task assistance, under matched computational budgets. To counter this emerging threat, we propose TokenBuncher, the first effective defense specifically targeting RL-based harmful fine-tuning. TokenBuncher suppresses the foundation on which RL relies: model response uncertainty. By constraining uncertainty, RL-based fine-tuning can no longer exploit distinct reward signals to drive the model toward harmful behaviors. We realize this defense through entropy-as-reward RL and a Token Noiser mechanism designed to prevent the escalation of expert-domain harmful capabilities. Extensive experiments across multiple models and RL algorithms show that TokenBuncher robustly mitigates harmful RL fine-tuning while preserving benign task utility and finetunability. Our results highlight that RL-based harmful fine-tuning poses a greater systemic risk than SFT, and that TokenBuncher provides an effective and general defense.

[Arxiv](https://arxiv.org/abs/2508.20697)