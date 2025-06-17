# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月14日

`LLM应用` `事实核查`

> Profiling News Media for Factuality and Bias Using LLMs and the Fact-Checking Methodology of Human Experts

# 摘要

> 在当今虚假和误导性信息泛滥的时代，帮助读者理解所阅读内容至关重要。当前的相关努力主要依赖于手动或自动的事实核查，但对于信息有限的新兴议题往往面临挑战。这种情境可以通过评估声明来源的可靠性和政治倾向来应对，即对整个新闻机构进行特征刻画，而非单独分析特定声明或文章。这是一个重要但研究不足的方向。

尽管先前的研究关注了语言和社会背景，但我们并未单独分析文章或社交媒体中的信息。相反，我们提出了一种新的方法，模拟专业事实核查人员评估整个新闻机构事实性和政治倾向的标准。具体而言，我们根据这些标准设计了多种提示，并从大型语言模型（LLMs）中获取响应，通过聚合这些响应来进行预测。

通过与多个LLMs的广泛实验，我们展示了相比强基线模型的显著提升。此外，我们深入分析了媒体流行度和地区对模型性能的影响，并通过消融实验突出了数据集中促进改进的关键组件。为了促进未来研究，我们在GitHub上公开了我们的数据集和代码：https://github.com/mbzuai-nlp/llm-media-profiling。


> In an age characterized by the proliferation of mis- and disinformation online, it is critical to empower readers to understand the content they are reading. Important efforts in this direction rely on manual or automatic fact-checking, which can be challenging for emerging claims with limited information. Such scenarios can be handled by assessing the reliability and the political bias of the source of the claim, i.e., characterizing entire news outlets rather than individual claims or articles. This is an important but understudied research direction. While prior work has looked into linguistic and social contexts, we do not analyze individual articles or information in social media. Instead, we propose a novel methodology that emulates the criteria that professional fact-checkers use to assess the factuality and political bias of an entire outlet. Specifically, we design a variety of prompts based on these criteria and elicit responses from large language models (LLMs), which we aggregate to make predictions. In addition to demonstrating sizable improvements over strong baselines via extensive experiments with multiple LLMs, we provide an in-depth error analysis of the effect of media popularity and region on model performance. Further, we conduct an ablation study to highlight the key components of our dataset that contribute to these improvements. To facilitate future research, we released our dataset and code at https://github.com/mbzuai-nlp/llm-media-profiling.

[Arxiv](https://arxiv.org/abs/2506.12552)