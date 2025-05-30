# # ToolHaystack：工具增强型语言模型的现实长期交互压力测试
ToolHaystack 是一个专注于评估工具增强型语言模型在真实长期互动场景下性能的框架。通过模拟复杂的现实任务，它可以全面测试模型在工具使用、决策制定和长期记忆等关键能力上的表现，从而帮助研究人员发现模型的局限性并提出优化方案。

发布时间：2025年05月29日

`LLM应用` `人机交互` `对话系统`

> ToolHaystack: Stress-Testing Tool-Augmented Language Models in Realistic Long-Term Interactions

# 摘要

> 大型语言模型（LLMs）在利用外部工具解决用户查询方面表现出强大的能力。然而，现有的评估大多集中在工具在短上下文中的使用，对模型在现实中的长期交互行为了解有限。为了填补这一空白，我们引入了ToolHaystack，这是一个用于测试长期交互中工具使用能力的基准。ToolHaystack中的每个测试实例包含多个任务执行上下文和连续对话中的现实噪声，能够评估模型在保持上下文和处理各种干扰方面的表现。将这一基准应用于14个最先进的LLMs后，我们发现，尽管当前模型在标准多轮设置中表现良好，但在ToolHaystack中却常常面临重大挑战，这凸显了它们在长期稳健性方面存在的关键差距，而这些差距并未在之前的工具基准中得到揭示。

> Large language models (LLMs) have demonstrated strong capabilities in using external tools to address user inquiries. However, most existing evaluations assume tool use in short contexts, offering limited insight into model behavior during realistic long-term interactions. To fill this gap, we introduce ToolHaystack, a benchmark for testing the tool use capabilities in long-term interactions. Each test instance in ToolHaystack includes multiple tasks execution contexts and realistic noise within a continuous conversation, enabling assessment of how well models maintain context and handle various disruptions. By applying this benchmark to 14 state-of-the-art LLMs, we find that while current models perform well in standard multi-turn settings, they often significantly struggle in ToolHaystack, highlighting critical gaps in their long-term robustness not revealed by previous tool benchmarks.

[Arxiv](https://arxiv.org/abs/2505.23662)