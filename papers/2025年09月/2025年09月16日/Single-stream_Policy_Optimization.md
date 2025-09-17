# 单流策略优化

发布时间：2025年09月16日

`强化学习` `基础理论`

> Single-stream Policy Optimization

# 摘要

> 我们从单流视角重新审视大型语言模型（LLMs）的策略梯度优化。主流的组基方法（如GRPO）虽通过动态基线降低方差，却存在两大致命缺陷：退化组频繁出现会抹除学习信号，同步障碍则制约可扩展性。为此，我们提出单流策略优化（SPO），从设计根源上解决了这些问题。SPO用持续的KL自适应价值追踪器替代分组基线，并对批次内的优势函数进行全局归一化，为每个样本打造稳定且低方差的学习信号。得益于无组设计，SPO不仅吞吐量更高，在生成时间各异的长序列或工具集成场景中也能高效扩展。此外，持续价值追踪器通过优先采样自然实现了自适应课程学习。基于Qwen3-8B的实验显示，SPO收敛更平稳、准确率优于GRPO，同时避免了在退化组上的无效计算。消融研究证实，SPO的性能优势源于其基线估计与优势归一化的原则性设计，为LLM推理开辟了更稳健高效的新路径。在Qwen3 8B的五项数学难题基准测试中，SPO相较GRPO将平均maj@32指标提升3.4个百分点（pp），其中高难度数据集表现尤为突出：BRUMO 25提升7.3 pp、AIME 25提升4.4 pp、HMMT 25提升3.3 pp，且在所有评估的k值上，pass@k指标均实现了稳定的相对提升。SPO的成功挑战了当前强化学习算法堆砌附加复杂度的趋势，揭示出推动LLM推理下一波进步的关键在于基本原则创新，而非架构层面的权宜之计。

> We revisit policy-gradient optimization for Large Language Models (LLMs) from a single-stream perspective. Prevailing group-based methods like GRPO reduce variance with on-the-fly baselines but suffer from critical flaws: frequent degenerate groups erase learning signals, and synchronization barriers hinder scalability. We introduce Single-stream Policy Optimization (SPO), which eliminates these issues by design. SPO replaces per-group baselines with a persistent, KL-adaptive value tracker and normalizes advantages globally across the batch, providing a stable, low-variance learning signal for every sample. Being group-free, SPO enables higher throughput and scales effectively in long-horizon or tool-integrated settings where generation times vary. Furthermore, the persistent value tracker naturally enables an adaptive curriculum via prioritized sampling. Experiments using Qwen3-8B show that SPO converges more smoothly and attains higher accuracy than GRPO, while eliminating computation wasted on degenerate groups. Ablation studies confirm that SPO's gains stem from its principled approach to baseline estimation and advantage normalization, offering a more robust and efficient path for LLM reasoning. Across five hard math benchmarks with Qwen3 8B, SPO improves the average maj@32 by +3.4 percentage points (pp) over GRPO, driven by substantial absolute point gains on challenging datasets, including +7.3 pp on BRUMO 25, +4.4 pp on AIME 25, +3.3 pp on HMMT 25, and achieves consistent relative gain in pass@$k$ across the evaluated $k$ values. SPO's success challenges the prevailing trend of adding incidental complexity to RL algorithms, highlighting a path where fundamental principles, not architectural workarounds, drive the next wave of progress in LLM reasoning.

[Arxiv](https://arxiv.org/abs/2509.13232)