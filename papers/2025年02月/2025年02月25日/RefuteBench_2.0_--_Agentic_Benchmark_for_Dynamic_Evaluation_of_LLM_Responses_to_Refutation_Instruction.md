# RefuteBench 2.0——评估 LLM 应对反驳指令能力的智能体基准

发布时间：2025年02月25日

`LLM应用` `对话系统`

> RefuteBench 2.0 -- Agentic Benchmark for Dynamic Evaluation of LLM Responses to Refutation Instruction

# 摘要

> 在多轮交互模式中，大型语言模型（LLMs）能够通过用户反馈提升回复质量，但评估其整合反驳反馈的能力仍具挑战。本研究推出RefuteBench 2.0，通过引入LLM代理作为反驳者和评估者，实现了更灵活全面的评估。我们设计了具有不同有效期的临时和持续性反驳指令。元评估表明，基于LLM的反驳者能生成更符合人类逻辑的反驳，评估结果也与人类高度相关。实验显示，现有模型虽能有效满足反驳需求，却无法记住反驳信息。值得注意的是，随着反驳次数增加，初始任务性能会下降。进一步分析注意力分数发现，当前LLMs在长上下文对话中难以保留并正确利用先前信息。https://github.com/ElliottYan/RefuteBench-2.0

> In the multi-turn interaction schema, large language models (LLMs) can leverage user feedback to enhance the quality and relevance of their responses. However, evaluating an LLM's ability to incorporate user refutation feedback is crucial yet challenging. In this study, we introduce RefuteBench 2.0, which significantly extends the original RefuteBench by incorporating LLM agents as refuters and evaluators, which allows for flexible and comprehensive assessment.
  We design both transient and persistent refutation instructions with different validity periods. Meta-evaluation shows that the LLM-based refuter could generate more human-like refutations and the evaluators could assign scores with high correlation with humans. Experimental results of various LLMs show that current models could effectively satisfy the refutation but fail to memorize the refutation information. Interestingly, we also observe that the performance of the initial task decreases as the refutations increase. Analysis of the attention scores further shows a potential weakness of current LLMs: they struggle to retain and correctly use previous information during long context dialogues. https://github.com/ElliottYan/RefuteBench-2.0

[Arxiv](https://arxiv.org/abs/2502.18308)