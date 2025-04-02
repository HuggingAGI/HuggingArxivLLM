# CrossWordBench：通过可控谜题生成评估大语言模型与视觉语言模型的推理能力

发布时间：2025年03月30日

`LLM应用` `多模态模型`

> CrossWordBench: Evaluating the Reasoning Capabilities of LLMs and LVLMs with Controllable Puzzle Generation

# 摘要

> 现有的针对大型语言模型（LLMs）和大型视觉语言模型（LVLMs）的推理评估框架，主要侧重于评估基于文本的推理能力或视觉语言理解能力，且文本与视觉之间的动态交互作用有限。为了解决这一问题，我们提出了CrossWordBench——一个通过填字游戏任务来评估LLMs和LVLMs推理能力的基准测试。填字游戏需要同时满足基于文本线索的语义约束以及来自视觉网格结构的交叉约束。CrossWordBench采用了可控的谜题生成框架，能够生成多种格式的谜题（文本和图像），并提供从直接解谜到交互模式的多种评估策略。我们对20多个模型的广泛评估表明，具有推理能力的LLMs通过有效利用交叉字母约束，显著优于不具备推理能力的模型。进一步研究表明，LVLMs在该任务上表现困难，其解谜性能与网格解析准确性之间存在显著相关性。我们的研究结果不仅揭示了当前LLMs和LVLMs推理能力的局限性，还为未来评估提供了创建多模态约束任务的有效方法。

> Existing reasoning evaluation frameworks for Large Language Models (LLMs) and Large Vision-Language Models (LVLMs) predominantly either assess text-based reasoning or vision-language understanding capabilities, with limited dynamic interplay between textual and visual constraints. To address this limitation, we introduce CrossWordBench, a benchmark designed to evaluate the reasoning capabilities of both LLMs and LVLMs through the medium of crossword puzzles-a task requiring multimodal adherence to semantic constraints from text-based clues and intersectional constraints from visual grid structures. CrossWordBench leverages a controllable puzzle generation framework that produces puzzles in multiple formats (text and image) and offers different evaluation strategies ranging from direct puzzle solving to interactive modes. Our extensive evaluation of over 20 models reveals that reasoning LLMs outperform non-reasoning models substantially by effectively leveraging crossing-letter constraints. We further demonstrate that LVLMs struggle with the task, showing a strong correlation between their puzzle-solving performance and grid-parsing accuracy. Our findings offer insights into the limitations of the reasoning capabilities of current LLMs and LVLMs, and provide an effective approach for creating multimodal constrained tasks for future evaluations.

[Arxiv](https://arxiv.org/abs/2504.00043)