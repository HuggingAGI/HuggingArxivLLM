# AI与人类在内容审核中的判断对比：LLM担当裁判，基于伦理的回应拒绝

发布时间：2025年05月21日

`LLM应用` `内容审核` `AI评估`

> AI vs. Human Judgment of Content Moderation: LLM-as-a-Judge and Ethics-Based Response Refusals

# 摘要

> 随着大型语言模型 (LLMs) 在高风险场景中广泛应用，它们拒绝涉及仇恨言论或非法活动等伦理敏感性提示的能力已成为内容审核和负责任 AI 实践的核心。尽管拒绝回应可被视为伦理对齐和安全意识行为的证据，但近期研究表明，用户可能对这些回应持有负面看法。与此同时，模型输出的自动化评估在评估和训练中扮演着越来越重要的角色。特别是"LLM-as-a-Judge"框架——其中一种模型用于评估另一种模型的输出——现已被广泛采用以指导基准测试和微调。本文探讨了基于模型的评估器与人类用户对拒绝回应的评估是否存在差异。基于 Chatbot Arena 的数据以及来自两个 AI 评委 (GPT-4 和 Llama 3 70B) 的判断，我们比较了不同类型拒绝的评分。我们将拒绝分为两类：伦理拒绝，即明确提及安全或规范性问题（例如，"我不能帮助你完成这个请求，因为它可能有害"）；以及技术拒绝，即反映系统限制（例如，"我无法回答，因为我缺乏实时数据"）。我们发现，LLM-as-a-Judge 系统对伦理拒绝的评价显著优于人类用户的评价，而技术拒绝则未观察到这种差异。我们将这种差异称为 moderation bias，即基于模型的评估器奖励拒绝行为的程度超过人类用户的系统性倾向。这引发了关于自动化评估系统中透明度、价值对齐以及规范性假设的更广泛问题。

> As large language models (LLMs) are increasingly deployed in high-stakes settings, their ability to refuse ethically sensitive prompts-such as those involving hate speech or illegal activities-has become central to content moderation and responsible AI practices. While refusal responses can be viewed as evidence of ethical alignment and safety-conscious behavior, recent research suggests that users may perceive them negatively. At the same time, automated assessments of model outputs are playing a growing role in both evaluation and training. In particular, LLM-as-a-Judge frameworks-in which one model is used to evaluate the output of another-are now widely adopted to guide benchmarking and fine-tuning. This paper examines whether such model-based evaluators assess refusal responses differently than human users. Drawing on data from Chatbot Arena and judgments from two AI judges (GPT-4o and Llama 3 70B), we compare how different types of refusals are rated. We distinguish ethical refusals, which explicitly cite safety or normative concerns (e.g., "I can't help with that because it may be harmful"), and technical refusals, which reflect system limitations (e.g., "I can't answer because I lack real-time data"). We find that LLM-as-a-Judge systems evaluate ethical refusals significantly more favorably than human users, a divergence not observed for technical refusals. We refer to this divergence as a moderation bias-a systematic tendency for model-based evaluators to reward refusal behaviors more than human users do. This raises broader questions about transparency, value alignment, and the normative assumptions embedded in automated evaluation systems.

[Arxiv](https://arxiv.org/abs/2505.15365)