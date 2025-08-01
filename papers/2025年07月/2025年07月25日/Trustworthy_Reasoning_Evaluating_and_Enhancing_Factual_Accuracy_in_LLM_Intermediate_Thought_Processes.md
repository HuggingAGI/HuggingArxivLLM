# 可信推理：评估及优化大型语言模型的推理事实准确性

发布时间：2025年07月25日

`LLM理论`

> Trustworthy Reasoning: Evaluating and Enhancing Factual Accuracy in LLM Intermediate Thought Processes

# 摘要

> 我们提出了RELIANCE框架，旨在解决大型语言模型（LLMs）中的一个关键问题：尽管最终答案正确，但中间推理步骤中普遍存在的事实不准确现象。这一问题在医疗、法律和科研等高风险领域尤为突出，因为错误的推理可能误导用户做出危险决策。RELIANCE框架包含三个核心组件：(1) 一个专门的事实核查分类器，用于检测推理链中的事实不一致；(2) 一种基于组相对策略优化（GRPO）的强化学习方法，通过多维奖励平衡事实性、连贯性和结构正确性；(3) 一个机制可解释性模块，研究事实性改进在推理过程中如何体现在模型激活中。通过对十种先进模型的评估发现，即使是Claude-3.7和GPT-o1等领先模型，其推理事实准确性也只有81.93%和82.57%。RELIANCE显著提升了事实稳健性（提升高达49.90%），同时在Math-500、AIME-2024和GPQA等基准测试中保持或提升了性能。此外，我们的激活级别分析揭示了事实增强如何重塑模型架构中的推理轨迹，为未来通过激活引导优化显式针对事实稳健性的训练方法奠定了基础。

> We present RELIANCE (Reasoning Evaluation with Logical Integrity and Accuracy for Confidence Enhancement), a novel framework addressing a critical vulnerability in Large Language Models (LLMs): the prevalence of factual inaccuracies within intermediate reasoning steps despite correct final answers. This phenomenon poses substantial risks in high-stakes domains including healthcare, legal analysis, and scientific research, where erroneous yet confidently presented reasoning can mislead users into dangerous decisions. Our framework integrates three core components: (1) a specialized fact-checking classifier trained on counterfactually augmented data to detect subtle factual inconsistencies within reasoning chains; (2) a Group Relative Policy Optimization (GRPO) reinforcement learning approach that balances factuality, coherence, and structural correctness through multi-dimensional rewards; and (3) a mechanistic interpretability module examining how factuality improvements manifest in model activations during reasoning processes. Extensive evaluation across ten state-of-the-art models reveals concerning patterns: even leading models like Claude-3.7 and GPT-o1 demonstrate reasoning factual accuracy of only 81.93% and 82.57% respectively. RELIANCE significantly enhances factual robustness (up to 49.90% improvement) while maintaining or improving performance on challenging benchmarks including Math-500, AIME-2024, and GPQA. Furthermore, our activation-level analysis provides actionable insights into how factual enhancements reshape reasoning trajectories within model architectures, establishing foundations for future training methodologies that explicitly target factual robustness through activation-guided optimization.

[Arxiv](https://arxiv.org/abs/2507.22940)