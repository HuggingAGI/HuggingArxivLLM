# 苏格拉底图表：通过协作多个智能体实现稳健的SVG图表理解

发布时间：2025年04月13日

`LLM应用` `数据分析` `数据可视化`

> Socratic Chart: Cooperating Multiple Agents for Robust SVG Chart Understanding

# 摘要

> 多模态大型语言模型 (MLLMs) 虽然功能强大，但在图表推理任务中展现真正的视觉理解能力仍存在挑战。现有基准测试如 ChartQA 显示，模型依赖文本捷径和概率匹配而非真正视觉推理。我们通过移除文本标签并引入图表扰动，在 ChartQA 数据集中创建更具挑战性的测试场景。结果显示，GPT-4o 和 Gemini-2.0 Pro 等模型性能下降高达 30%，凸显其局限性。为此，我们提出 Socratic Chart 框架，将图表图像转换为 SVG 表示，使 MLLMs 能够融合文本与视觉信息，提升图表理解。该框架采用多智能体管道，生成器智能体提取图表属性，批评家智能体验证结果，确保高保真符号表示。我们的框架在捕捉图表元素和推理性能上超越现有最优模型，为提升 MLLM 视觉理解提供了坚实路径。

> Multimodal Large Language Models (MLLMs) have shown remarkable versatility but face challenges in demonstrating true visual understanding, particularly in chart reasoning tasks. Existing benchmarks like ChartQA reveal significant reliance on text-based shortcuts and probabilistic pattern-matching rather than genuine visual reasoning. To rigorously evaluate visual reasoning, we introduce a more challenging test scenario by removing textual labels and introducing chart perturbations in the ChartQA dataset. Under these conditions, models like GPT-4o and Gemini-2.0 Pro experience up to a 30% performance drop, underscoring their limitations. To address these challenges, we propose Socratic Chart, a new framework that transforms chart images into Scalable Vector Graphics (SVG) representations, enabling MLLMs to integrate textual and visual modalities for enhanced chart understanding. Socratic Chart employs a multi-agent pipeline with specialized agent-generators to extract primitive chart attributes (e.g., bar heights, line coordinates) and an agent-critic to validate results, ensuring high-fidelity symbolic representations. Our framework surpasses state-of-the-art models in accurately capturing chart primitives and improving reasoning performance, establishing a robust pathway for advancing MLLM visual understanding.

[Arxiv](https://arxiv.org/abs/2504.09764)