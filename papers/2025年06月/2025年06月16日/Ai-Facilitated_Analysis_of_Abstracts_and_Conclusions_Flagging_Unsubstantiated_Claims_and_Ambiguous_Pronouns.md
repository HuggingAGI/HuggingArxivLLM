# AI辅助的摘要与结论分析：识别缺乏依据的主张与模糊指代的代词

发布时间：2025年06月16日

`LLM应用` `学术出版`

> Ai-Facilitated Analysis of Abstracts and Conclusions: Flagging Unsubstantiated Claims and Ambiguous Pronouns

# 摘要

> 我们提出并评估了一套概念验证（PoC）的结构化工作流程提示，旨在激发类似人类的分层推理，同时指导大型语言模型（LLMs）对学术手稿进行高级语义和语言分析。这些提示针对两个具有挑战性的分析任务：识别摘要中缺乏支持的主张（信息完整性）和标记模糊的代词引用（语言清晰度）。我们在 Gemini Pro 2.5 Pro 和 ChatGPT Plus o3 两种前沿模型上进行了系统性、多轮评估，测试了不同上下文条件下的表现。在信息完整性任务中，我们的结果显示了模型性能的显著差异：两种模型成功识别了名词短语中缺乏支持的头部（95% 成功），但 ChatGPT 未能识别缺乏支持的形容词修饰语（0% 成功），而 Gemini 准确标记了这一点（95% 成功），这引发了关于目标句法角色潜在影响的问题。对于语言分析任务，在完整手稿上下文中，两种模型表现良好（80-90% 成功）。然而，在仅摘要设置下，ChatGPT 实现了完美（100%）的成功率，而 Gemini 的性能则大幅下降。我们的研究结果表明，结构化提示是一种可行的复杂文本分析方法，但提示性能可能高度依赖于模型、任务类型和上下文之间的相互作用，强调了进行严格、针对特定模型测试的必要性。

> We present and evaluate a suite of proof-of-concept (PoC), structured workflow prompts designed to elicit human-like hierarchical reasoning while guiding Large Language Models (LLMs) in high-level semantic and linguistic analysis of scholarly manuscripts. The prompts target two non-trivial analytical tasks: identifying unsubstantiated claims in summaries (informational integrity) and flagging ambiguous pronoun references (linguistic clarity). We conducted a systematic, multi-run evaluation on two frontier models (Gemini Pro 2.5 Pro and ChatGPT Plus o3) under varied context conditions. Our results for the informational integrity task reveal a significant divergence in model performance: while both models successfully identified an unsubstantiated head of a noun phrase (95% success), ChatGPT consistently failed (0% success) to identify an unsubstantiated adjectival modifier that Gemini correctly flagged (95% success), raising a question regarding potential influence of the target's syntactic role. For the linguistic analysis task, both models performed well (80-90% success) with full manuscript context. In a summary-only setting, however, ChatGPT achieved a perfect (100%) success rate, while Gemini's performance was substantially degraded. Our findings suggest that structured prompting is a viable methodology for complex textual analysis but show that prompt performance may be highly dependent on the interplay between the model, task type, and context, highlighting the need for rigorous, model-specific testing.

[Arxiv](https://arxiv.org/abs/2506.13172)