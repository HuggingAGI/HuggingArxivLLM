# 多智能体辩论中的问题漂移：保持专注的重要性

发布时间：2025年02月26日

`Agent` `人工智能` `多智能体系统`

> Stay Focused: Problem Drift in Multi-Agent Debate

# 摘要

> 多智能体辩论——多个大型语言模型通过轮流交互讨论问题——在解决知识和推理任务方面展现出潜力。然而，这些方法存在局限性，尤其是在处理更长的推理链时。本研究揭示了多智能体辩论中的一个新问题：经过多轮交互后，讨论逐渐偏离初始问题。我们将这一现象定义为问题漂移，并在十项任务（即三项生成任务、三项知识任务、三项推理任务和一项指令遵循任务）中量化了该现象的存在。为了找出这一问题的原因，我们对八位专家进行了研究，他们分析了存在问题漂移的讨论，发现最常见的问题是缺乏进展（35%的情况）、低质量反馈（26%的情况）以及缺乏清晰度（25%的情况）。为了系统性地解决这一问题，我们提出了DRIFTJudge方法，该方法基于大型语言模型作为裁判，用于检测测试时的问题漂移。我们还提出了DRIFTPolicy方法，该方法可缓解31%的问题漂移情况。我们的研究可以被视为理解多智能体辩论关键局限性的第一步，并为未来提高其有效性提供了方向。

> Multi-agent debate - multiple instances of large language models discussing problems in turn-based interaction - has shown promise for solving knowledge and reasoning tasks. However, these methods show limitations, particularly when scaling them to longer reasoning chains. In this study, we unveil a new issue of multi-agent debate: discussions drift away from the initial problem over multiple turns. We define this phenomenon as problem drift and quantify its presence across ten tasks (i.e., three generative, three knowledge, three reasoning, and one instruction-following task). To identify the reasons for this issue, we perform a human study with eight experts on discussions suffering from problem drift, who find the most common issues are a lack of progress (35% of cases), low-quality feedback (26% of cases), and a lack of clarity (25% of cases). To systematically address the issue of problem drift, we propose DRIFTJudge, a method based on LLM-as-a-judge, to detect problem drift at test-time. We further propose DRIFTPolicy, a method to mitigate 31% of problem drift cases. Our study can be seen as a first step to understanding a key limitation of multi-agent debate, highlighting pathways for improving their effectiveness in the future.

[Arxiv](https://arxiv.org/abs/2502.19559)