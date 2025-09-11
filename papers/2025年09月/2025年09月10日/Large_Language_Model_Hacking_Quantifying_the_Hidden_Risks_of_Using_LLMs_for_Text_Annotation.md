# 大型语言模型攻击：量化将LLMs用于文本标注的潜在风险

发布时间：2025年09月10日

`LLM应用` `基础理论`

> Large Language Model Hacking: Quantifying the Hidden Risks of Using LLMs for Text Annotation

# 摘要

> 大型语言模型（LLMs）正通过自动化数据标注、文本分析等劳动密集型任务，迅速变革社会科学研究。然而，LLM的输出会因研究者的具体选择（如模型挑选、提示策略或温度设置）而存在显著差异。这种差异可能引入系统性偏差和随机误差，进而传播到下游分析，引发I类、II类、S类或M类错误——我们称之为“LLM操纵”。
  为量化LLM操纵风险，我们使用18种不同模型，复现了21项已发表社会科学研究中的37项数据标注任务。通过分析1300万个LLM标签，我们测试了2361个真实假设，以此衡量研究者的合理选择对统计结论的影响。结果显示，对于最先进的模型，基于LLM标注数据得出的错误结论约占假设的三分之一；而对于小型语言模型，这一比例高达一半。研究还发现，更高的任务性能和更强的模型通用能力虽能降低LLM操纵风险，但即便是高精度模型也无法完全消除这一风险。LLM操纵风险随效应量增大而降低，这意味着对接近显著性阈值的研究结果需进行更严格的验证。我们对LLM操纵缓解技术的深入分析表明，人工标注对减少假阳性结果和优化模型选择至关重要。出人意料的是，常见的回归估计量校正技术对降低LLM操纵风险基本无效，因其会严重权衡I类与II类错误。
  除意外误差外，我们还发现，有意的LLM操纵简单得令人无法接受——仅需几个模型和少量提示改写，就能将任何结果包装成具有统计显著性。

> Large language models (LLMs) are rapidly transforming social science research by enabling the automation of labor-intensive tasks like data annotation and text analysis. However, LLM outputs vary significantly depending on the implementation choices made by researchers (e.g., model selection, prompting strategy, or temperature settings). Such variation can introduce systematic biases and random errors, which propagate to downstream analyses and cause Type I, Type II, Type S, or Type M errors. We call this LLM hacking.
  We quantify the risk of LLM hacking by replicating 37 data annotation tasks from 21 published social science research studies with 18 different models. Analyzing 13 million LLM labels, we test 2,361 realistic hypotheses to measure how plausible researcher choices affect statistical conclusions. We find incorrect conclusions based on LLM-annotated data in approximately one in three hypotheses for state-of-the-art models, and in half the hypotheses for small language models. While our findings show that higher task performance and better general model capabilities reduce LLM hacking risk, even highly accurate models do not completely eliminate it. The risk of LLM hacking decreases as effect sizes increase, indicating the need for more rigorous verification of findings near significance thresholds. Our extensive analysis of LLM hacking mitigation techniques emphasizes the importance of human annotations in reducing false positive findings and improving model selection. Surprisingly, common regression estimator correction techniques are largely ineffective in reducing LLM hacking risk, as they heavily trade off Type I vs. Type II errors.
  Beyond accidental errors, we find that intentional LLM hacking is unacceptably simple. With few LLMs and just a handful of prompt paraphrases, anything can be presented as statistically significant.

[Arxiv](https://arxiv.org/abs/2509.08825)