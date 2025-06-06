# CogMath：从人类认知视角评估大型语言模型的真实数学能力

发布时间：2025年06月04日

`LLM应用` `多智能体系统`

> CogMath: Assessing LLMs' Authentic Mathematical Ability from a Human Cognitive Perspective

# 摘要

> 虽然大型语言模型（LLMs）在解决复杂数学问题方面展现出潜力，但现有的评估方法仅依赖于对整体答案准确性的粗略衡量，无法准确评估其真实能力。本文提出了	extbf{CogMath}，通过人类认知的视角全面评估LLMs的数学能力。具体而言，受心理理论启发，CogMath将人类推理过程形式化为3个阶段：\emph{问题理解}、\emph{问题解决}和\emph{解决方案总结}。在这些阶段中，我们探讨了数值计算、知识和反事实等视角，并设计了总共9个细粒度的评估维度。在每个维度中，我们开发了一个``\emph{问询}-\emph{判断}-\emph{参考}''多智能体系统，以生成评估LLMs在该维度上掌握程度的问询。只有在所有9个维度的问询中都表现出色时，LLM才被认为真正掌握了该问题。通过在三个基准上应用CogMath，我们发现7种主流LLMs的数学能力被高估了30\%-40\%。此外，我们定位了它们在特定阶段/维度上的优势和劣势，为进一步提升其推理能力提供了深入见解。

> Although large language models (LLMs) show promise in solving complex mathematical tasks, existing evaluation paradigms rely solely on a coarse measure of overall answer accuracy, which are insufficient for assessing their authentic capabilities. In this paper, we propose \textbf{CogMath}, which comprehensively assesses LLMs' mathematical abilities through the lens of human cognition. Specifically, inspired by psychological theories, CogMath formalizes human reasoning process into 3 stages: \emph{problem comprehension}, \emph{problem solving}, and \emph{solution summarization}. Within these stages, we investigate perspectives such as numerical calculation, knowledge, and counterfactuals, and design a total of 9 fine-grained evaluation dimensions. In each dimension, we develop an ``\emph{Inquiry}-\emph{Judge}-\emph{Reference}'' multi-agent system to generate inquiries that assess LLMs' mastery from this dimension. An LLM is considered to truly master a problem only when excelling in all inquiries from the 9 dimensions. By applying CogMath on three benchmarks, we reveal that the mathematical capabilities of 7 mainstream LLMs are overestimated by 30\%-40\%. Moreover, we locate their strengths and weaknesses across specific stages/dimensions, offering in-depth insights to further enhance their reasoning abilities.

[Arxiv](https://arxiv.org/abs/2506.04481)