# 联合强化语言模型生成的多样性与质量

发布时间：2025年09月02日

`强化学习` `媒体与娱乐` `教育科技`

> Jointly Reinforcing Diversity and Quality in Language Model Generations

# 摘要

> 大型语言模型（LMs）的后训练往往优先追求准确性和有用性，却牺牲了多样性。这就形成了一个矛盾：后训练虽能提升响应质量，却会收窄输出分布、限制思路广度，进而限制了语言模型在创意探索类任务（如头脑风暴、故事创作、问题解决）中的实用价值。为解决这一难题，我们提出多样性感知强化学习（DARLING）——一种能同时优化响应质量与语义多样性的框架。DARLING 的核心创新在于引入学习型配分函数，可衡量超越表面词汇差异的深层多样性。在在线强化学习阶段，该多样性信号会与质量奖励融合，激励模型生成既优质又独特的结果。多模型家族、多规模实验显示，DARLING 能有效适配两类任务场景：不可验证任务（如指令遵循、创意写作）与可验证任务（如竞赛数学）。在第一类场景的五个基准测试中，DARLING 表现持续优于仅优化质量的强化学习基线，生成的结果质量更高、新颖性更强；在第二类场景中，它还实现了更高的 pass@1（解决方案质量）和 pass@k（解决方案多样性）。尤为值得关注的是，明确优化多样性还能促进在线强化学习中的探索过程，最终带来了更高质量的响应。

> Post-training of Large Language Models (LMs) often prioritizes accuracy and helpfulness at the expense of diversity. This creates a tension: while post-training improves response quality, it also sharpens output distributions and reduces the range of ideas, limiting the usefulness of LMs in creative and exploratory tasks such as brainstorming, storytelling, or problem solving. We address this challenge with Diversity-Aware Reinforcement Learning (DARLING), a framework that jointly optimizes for response quality and semantic diversity. At its core, DARLING introduces a learned partition function to measure diversity beyond surface-level lexical variations. This diversity signal is then combined with a quality reward during online reinforcement learning, encouraging models to generate outputs that are both high-quality and distinct. Experiments across multiple model families and sizes show that DARLING generalizes to two regimes: non-verifiable tasks (instruction following and creative writing) and verifiable tasks (competition math). On five benchmarks in the first setting, DARLING consistently outperforms quality-only RL baselines, producing outputs that are simultaneously of higher quality and novelty. In the second setting, DARLING achieves higher pass@1 (solution quality) and pass@k (solution variety). Most strikingly, explicitly optimizing for diversity catalyzes exploration in online RL, which manifests itself as higher-quality responses.

[Arxiv](https://arxiv.org/abs/2509.02534)