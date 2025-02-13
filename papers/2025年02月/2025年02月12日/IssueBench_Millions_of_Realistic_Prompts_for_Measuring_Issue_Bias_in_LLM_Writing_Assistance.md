# IssueBench：数百万现实提示，用于衡量LLM写作辅助中的议题偏见

发布时间：2025年02月12日

`LLM应用` `内容创作` `公共政策`

> IssueBench: Millions of Realistic Prompts for Measuring Issue Bias in LLM Writing Assistance

# 摘要

> 大型语言模型（LLMs）正在帮助数百万用户撰写涉及各种议题的文本，让用户接触到不同的观点和视角。然而，这引发了对议题偏见的担忧：LLMs往往在一个议题上只呈现一种观点，可能影响用户的思考方式。目前，我们无法衡量LLMs在实际使用中究竟表现出哪些议题偏见，这使得应对有偏见的LLMs带来的风险变得困难。因此，我们创建了IssueBench——一个包含249万个真实提示的数据集，用于测量LLMs在写作辅助中的议题偏见。我们根据3900个模板（如“写一篇博客”）和212个来自实际用户交互的政治议题（如“AI监管”）构建了IssueBench。通过IssueBench，我们发现议题偏见在最先进的LLMs中普遍存在且持续存在。不同模型之间的偏见惊人地相似，且所有模型在某些特定议题上更倾向于与美国民主党选民而非共和党选民的意见一致。IssueBench可以轻松扩展以包含其他议题、模板或任务。通过实现稳健且现实的测量，我们希望IssueBench能够为关于LLM偏见及其应对措施的讨论带来新的高质量证据。

> Large language models (LLMs) are helping millions of users write texts about diverse issues, and in doing so expose users to different ideas and perspectives. This creates concerns about issue bias, where an LLM tends to present just one perspective on a given issue, which in turn may influence how users think about this issue. So far, it has not been possible to measure which issue biases LLMs actually manifest in real user interactions, making it difficult to address the risks from biased LLMs. Therefore, we create IssueBench: a set of 2.49m realistic prompts for measuring issue bias in LLM writing assistance, which we construct based on 3.9k templates (e.g. "write a blog about") and 212 political issues (e.g. "AI regulation") from real user interactions. Using IssueBench, we show that issue biases are common and persistent in state-of-the-art LLMs. We also show that biases are remarkably similar across models, and that all models align more with US Democrat than Republican voter opinion on a subset of issues. IssueBench can easily be adapted to include other issues, templates, or tasks. By enabling robust and realistic measurement, we hope that IssueBench can bring a new quality of evidence to ongoing discussions about LLM biases and how to address them.

[Arxiv](https://arxiv.org/abs/2502.08395)