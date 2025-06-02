# 洞察自我思维：推理助力展现 LLMs 的自信信号

发布时间：2025年05月28日

`LLM理论` `问答系统`

> Read Your Own Mind: Reasoning Helps Surface Self-Confidence Signals in LLMs

# 摘要

> 我们研究了 DeepSeek R1-32B 在问答任务中不确定性来源，通过分析其自报告置信度展开。在默认的回答-然后-置信度设置下，模型常过于自信，而通过采样多响应得到的语义熵依然可靠。我们推测这是因为语义熵在测试时需要更大计算量，从而让我们得以探索模型的预测分布。我们发现，通过强制在最终答案前进行长推理链，给予 DeepSeek 探索其分布的预算，能显著提升其置信度的有效性，即便是在通常无需推理的简单事实检索问题上也是如此。此外，仅查看推理链的独立阅读模型可以重建出非常相似的置信度，表明自报告置信度可能仅仅是推理过程中浮现的替代方案的统计量。我们的分析表明，可靠的不确定性估计需要显式地探索生成空间，而自报告置信度只有在进行这种探索后才值得信赖。

> We study the source of uncertainty in DeepSeek R1-32B by analyzing its self-reported verbal confidence on question answering (QA) tasks. In the default answer-then-confidence setting, the model is regularly over-confident, whereas semantic entropy - obtained by sampling many responses - remains reliable. We hypothesize that this is because of semantic entropy's larger test-time compute, which lets us explore the model's predictive distribution. We show that granting DeepSeek the budget to explore its distribution by forcing a long chain-of-thought before the final answer greatly improves its verbal score effectiveness, even on simple fact-retrieval questions that normally require no reasoning. Furthermore, a separate reader model that sees only the chain can reconstruct very similar confidences, indicating the verbal score might be merely a statistic of the alternatives surfaced during reasoning. Our analysis concludes that reliable uncertainty estimation requires explicit exploration of the generative space, and self-reported confidence is trustworthy only after such exploration.

[Arxiv](https://arxiv.org/abs/2505.23845)