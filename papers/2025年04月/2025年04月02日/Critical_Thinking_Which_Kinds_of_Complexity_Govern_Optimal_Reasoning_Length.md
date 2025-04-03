# 批判性思维：复杂性类型如何影响最优推理长度？

发布时间：2025年04月02日

`LLM理论` `人工智能`

> Critical Thinking: Which Kinds of Complexity Govern Optimal Reasoning Length?

# 摘要

> 大型语言模型（LLMs）在推理过程中通常得益于语言化推理，但这些额外的推理代币究竟解决了任务难度中的哪些方面，目前尚不明确。为了解决这一问题，我们采用确定性有限自动机（DFAs）构建了一个形式化框架。通过DFAs，我们可以利用可测量的属性（如运行长度和状态空间大小）来表征任务复杂度。我们证明，无论任务类型、模型规模和训练范式如何，都存在一个最优的推理代币数量，使得生成正确解的概率最大化。进一步研究发现，任务实例的DFA运行时间越长（即需要更高潜在状态跟踪要求），推理长度也越长，但DFA大小（即状态空间复杂度）与推理长度无显著关联。这一发现的重要应用在于：能够预测新问题的最优推理代币数量，并筛选出非最优长度的答案，从而带来一致的准确性提升。

> Large language models (LLMs) often benefit from verbalized reasoning at inference time, but it remains unclear which aspects of task difficulty these extra reasoning tokens address. To investigate this question, we formalize a framework using deterministic finite automata (DFAs). DFAs offer a formalism through which we can characterize task complexity through measurable properties such as run length (number of reasoning steps required) and state-space size (decision complexity). We first show that across different tasks and models of different sizes and training paradigms, there exists an optimal amount of reasoning tokens such that the probability of producing a correct solution is maximized. We then investigate which properties of complexity govern this critical length: we find that task instances with longer corresponding underlying DFA runs (i.e. demand greater latent state-tracking requirements) correlate with longer reasoning lengths, but, surprisingly, that DFA size (i.e. state-space complexity) does not. We then demonstrate an implication of these findings: being able to predict the optimal number of reasoning tokens for new problems and filtering out non-optimal length answers results in consistent accuracy improvements.

[Arxiv](https://arxiv.org/abs/2504.01935)