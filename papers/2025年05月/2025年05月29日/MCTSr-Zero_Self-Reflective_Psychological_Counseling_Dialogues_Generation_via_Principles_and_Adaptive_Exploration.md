# # 标题
MCTSr-Zero: 基于原则与自适应探索的自我反思心理咨询对话生成

发布时间：2025年05月29日

`LLM应用` `心理辅导` `对话系统`

> MCTSr-Zero: Self-Reflective Psychological Counseling Dialogues Generation via Principles and Adaptive Exploration

# 摘要

> 蒙特卡洛树搜索（MCTS）与大型语言模型（LLMs）的结合在结构化、问题导向的任务中表现优异。然而，将其应用于心理辅导等开放性对话场景时，面临独特挑战。与具有明确正确性的任务不同，治疗性对话的成功依赖于同理心、伦理合规和与人类偏好的一致性，这些方面缺乏明确的“正确性”标准。现有注重结果的MCTS方法可能生成偏离预期的回答。为解决这一问题，我们提出了MCTSr-Zero，一个专为开放性、以人为中心的对话设计的MCTS框架。其核心创新是“领域对齐”，将MCTS的搜索目标从预定义的终点状态转向符合目标领域原则（如心理咨询中的同理心）的对话轨迹。此外，MCTSr-Zero还引入了“再生”和“元提示适应”机制，通过允许MCTS考虑根本不同的初始对话策略，大幅拓宽了探索范围。我们在心理辅导领域评估了MCTSr-Zero，通过生成多轮对话数据来微调LLM，即 PsyLLM。同时，我们推出了 PsyEval，一个用于评估多轮心理辅导对话的基准。实验表明， PsyLLM 在 PsyEval 和其他相关指标上达到了最先进的性能，验证了MCTSr-Zero在为人导向领域生成高质量、原则一致的对话数据方面的有效性，同时也解决了LLMs在持续遵循复杂心理标准方面的挑战。

> The integration of Monte Carlo Tree Search (MCTS) with Large Language Models (LLMs) has demonstrated significant success in structured, problem-oriented tasks. However, applying these methods to open-ended dialogues, such as those in psychological counseling, presents unique challenges. Unlike tasks with objective correctness, success in therapeutic conversations depends on subjective factors like empathetic engagement, ethical adherence, and alignment with human preferences, for which strict "correctness" criteria are ill-defined. Existing result-oriented MCTS approaches can therefore produce misaligned responses. To address this, we introduce MCTSr-Zero, an MCTS framework designed for open-ended, human-centric dialogues. Its core innovation is "domain alignment", which shifts the MCTS search objective from predefined end-states towards conversational trajectories that conform to target domain principles (e.g., empathy in counseling). Furthermore, MCTSr-Zero incorporates "Regeneration" and "Meta-Prompt Adaptation" mechanisms to substantially broaden exploration by allowing the MCTS to consider fundamentally different initial dialogue strategies. We evaluate MCTSr-Zero in psychological counseling by generating multi-turn dialogue data, which is used to fine-tune an LLM, PsyLLM. We also introduce PsyEval, a benchmark for assessing multi-turn psychological counseling dialogues. Experiments demonstrate that PsyLLM achieves state-of-the-art performance on PsyEval and other relevant metrics, validating MCTSr-Zero's effectiveness in generating high-quality, principle-aligned conversational data for human-centric domains and addressing the LLM challenge of consistently adhering to complex psychological standards.

[Arxiv](https://arxiv.org/abs/2505.23229)