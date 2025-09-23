# 通过引导式结构化模板提升大型语言模型的函数调用与可解释性

发布时间：2025年09月22日

`Agent` `基础理论`

> Improving Large Language Models Function Calling and Interpretability via Guided-Structured Templates

# 摘要

> 大型语言模型（LLMs）虽已展现出强大的推理与工具使用能力，但在现实工具交互中却常因参数设置错误、工具选择不当或用户意图误解而失败。这些问题的根源往往在于对用户目标理解不完整，以及对工具文档掌握不足。尽管思维链（CoT）提示在提升通用场景推理能力方面成效显著，但我们的分析发现，自由形式的CoT在结构化函数调用任务中不仅效果有限，有时甚至会适得其反。为此，我们提出一种受课程学习启发的框架，该框架借助结构化推理模板，引导LLMs通过更审慎的分步指令生成函数调用。实验结果显示，我们的方法有效减少了工具使用错误，在不同模型系列与方法上，相较于强基线实现了3-12%的相对性能提升。

> Large language models (LLMs) have demonstrated strong reasoning and tool-use capabilities, yet they often fail in real-world tool-interactions due to incorrect parameterization, poor tool selection, or misinterpretation of user intent. These issues often stem from an incomplete understanding of user goals and inadequate comprehension of tool documentation. While Chain-of-Thought (CoT) prompting has proven effective for enhancing reasoning in general contexts, our analysis reveals that free-form CoT is insufficient and sometimes counterproductive for structured function-calling tasks. To address this, we introduce a curriculum-inspired framework that leverages structured reasoning templates to guide LLMs through more deliberate step-by-step instructions for generating function callings. Experimental results show that our method reduces tool-use errors, achieving 3-12% relative improvements over strong baselines across diverse model series and approaches. Moreover, our framework enhances the robustness, interpretability, and transparency of tool-using agents, advancing the development of more reliable AI assistants for real-world applications.

[Arxiv](https://arxiv.org/abs/2509.18076)