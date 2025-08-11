# 思维图表：借助结构化数据提取，提升LLM的可视化素养

发布时间：2025年08月06日

`LLM应用` `可视化`

> Charts-of-Thought: Enhancing LLM Visualization Literacy Through Structured Data Extraction

# 摘要

> 本文评估了现代大型语言模型（LLMs）的可视化素养，并提出了一种名为 Charts-of-Thought 的全新提示技术。我们使用标准提示和我们的结构化方法，测试了三种最先进的 LLM（Claude-3.7-sonnet、GPT-4.5 预览版和 Gemini-2.0-pro）在可视化素养评估测试（VLAT）中的表现。Charts-of-Thought 方法引导 LLM 在回答可视化问题之前，系统地进行数据提取、验证和分析过程。结果显示，Claude-3.7-sonnet 采用此方法得到了 50.17 分，远超人类基准的 28.82 分。与标准提示相比，该方法提升了所有模型的表现，GPT-4.5 的得分提高了 21.8%，Gemini-2.0 提高了 9.4%，Claude-3.7 提高了 13.5%。这种性能提升在原始和修改后的 VLAT 图表中都是一致的，Claude 正确回答了多个以前对 LLM 构成挑战的图表类型的所有问题。研究发现，当给予适当的分析框架时，现代多模态 LLM 可以在可视化素养任务中超越人类表现。这些发现为 LLM 的可视化素养设定了新基准，并展示了结构化提示策略在复杂视觉解释任务中的重要性。除了提升 LLM 的可视化素养外，Charts-of-Thought 还可能增强可视化内容的可访问性，从而造福视力障碍者或可视化素养较低的个体。

> This paper evaluates the visualization literacy of modern Large Language Models (LLMs) and introduces a novel prompting technique called Charts-of-Thought. We tested three state-of-the-art LLMs (Claude-3.7-sonnet, GPT-4.5 preview, and Gemini-2.0-pro) on the Visualization Literacy Assessment Test (VLAT) using standard prompts and our structured approach. The Charts-of-Thought method guides LLMs through a systematic data extraction, verification, and analysis process before answering visualization questions. Our results show Claude-3.7-sonnet achieved a score of 50.17 using this method, far exceeding the human baseline of 28.82. This approach improved performance across all models, with score increases of 21.8% for GPT-4.5, 9.4% for Gemini-2.0, and 13.5% for Claude-3.7 compared to standard prompting. The performance gains were consistent across original and modified VLAT charts, with Claude correctly answering 100% of questions for several chart types that previously challenged LLMs. Our study reveals that modern multimodal LLMs can surpass human performance on visualization literacy tasks when given the proper analytical framework. These findings establish a new benchmark for LLM visualization literacy and demonstrate the importance of structured prompting strategies for complex visual interpretation tasks. Beyond improving LLM visualization literacy, Charts-of-Thought could also enhance the accessibility of visualizations, potentially benefiting individuals with visual impairments or lower visualization literacy.

[Arxiv](https://arxiv.org/abs/2508.04842)