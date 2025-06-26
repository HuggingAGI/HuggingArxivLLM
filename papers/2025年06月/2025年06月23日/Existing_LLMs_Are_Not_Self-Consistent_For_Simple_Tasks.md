# 现有大型语言模型在简单任务上缺乏自洽性。

发布时间：2025年06月23日

`LLM理论` `人工智能` `逻辑推理`

> Existing LLMs Are Not Self-Consistent For Simple Tasks

# 摘要

> 大型语言模型（LLMs）的性能日益强大，但确保其决策透明可靠的关键在于自洽性——即内部推理无矛盾。研究发现，即使是处理直线或平面上的点比较，或家族树推理等简单任务，所有较小规模的模型均表现出高度不一致，甚至DeepSeek-R1和GPT-4-mini等先进模型也未能完全自洽。为量化并缓解这一问题，我们引入了不一致性指标，并提出了两种自动化方法——基于图和基于能量的方法。尽管这些修复措施带来了一定改进，但它们也凸显了自洽性在构建更可靠和可解释的人工智能系统中的复杂性和重要性。代码和数据可在https://github.com/scorpio-nova/llm-self-consistency获取。

> Large Language Models (LLMs) have grown increasingly powerful, yet ensuring their decisions remain transparent and trustworthy requires self-consistency -- no contradictions in their internal reasoning. Our study reveals that even on simple tasks, such as comparing points on a line or a plane, or reasoning in a family tree, all smaller models are highly inconsistent, and even state-of-the-art models like DeepSeek-R1 and GPT-o4-mini are not fully self-consistent. To quantify and mitigate these inconsistencies, we introduce inconsistency metrics and propose two automated methods -- a graph-based and an energy-based approach. While these fixes provide partial improvements, they also highlight the complexity and importance of self-consistency in building more reliable and interpretable AI. The code and data are available at https://github.com/scorpio-nova/llm-self-consistency.

[Arxiv](https://arxiv.org/abs/2506.18781)