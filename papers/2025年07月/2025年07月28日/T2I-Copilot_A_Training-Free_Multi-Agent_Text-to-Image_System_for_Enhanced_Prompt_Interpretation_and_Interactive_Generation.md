# T2I-Copilot：零训练多智能体文本到图像系统，旨在提升提示理解与交互式生成能力

发布时间：2025年07月28日

`Agent` `人工智能` `创意设计`

> T2I-Copilot: A Training-Free Multi-Agent Text-to-Image System for Enhanced Prompt Interpretation and Interactive Generation

# 摘要

> 文本到图像（T2I）生成模型彻底改变了内容创作方式，但它们对提示词的表达方式仍然高度敏感，用户常常需要反复调整提示词却难以获得明确反馈。尽管自动提示工程、可控文本嵌入、去噪和多轮生成等技术在一定程度上缓解了这一问题，但它们在可控性和泛化能力上仍显不足。因此，我们提出了T2I-Copilot——一个无需训练的多智能体系统，通过多模态大型语言模型的协作，实现了提示词优化、模型选择和迭代改进的自动化。这种方法不仅显著简化了提示工程，还大幅提升了生成质量和文本-图像对齐度。T2I-Copilot由三个核心智能体组成：(1) 输入解释器，负责解析输入提示、消除歧义并生成标准化报告；(2) 生成引擎，从多种T2I模型中选择最优模型，并组织视觉与文本提示以启动生成流程；(3) 质量评估器，评估生成内容的美学质量及文本-图像对齐度，提供反馈以支持潜在的重新生成。T2I-Copilot既能完全自主运行，也支持人工介入的精细控制。在GenAI-Bench基准测试中，T2I-Copilot使用开源模型实现了与商用模型RecraftV3和Imagen 3相当的VQA得分，仅以FLUX1.1-pro 16.59%的成本就超越了其6.17%，并优于FLUX.1-dev和SD 3.5 Large的性能，分别高出9.11%和6.36%。项目代码已开源，欢迎访问：https://github.com/SHI-Labs/T2I-Copilot。

> Text-to-Image (T2I) generative models have revolutionized content creation but remain highly sensitive to prompt phrasing, often requiring users to repeatedly refine prompts multiple times without clear feedback. While techniques such as automatic prompt engineering, controlled text embeddings, denoising, and multi-turn generation mitigate these issues, they offer limited controllability, or often necessitate additional training, restricting the generalization abilities. Thus, we introduce T2I-Copilot, a training-free multi-agent system that leverages collaboration between (Multimodal) Large Language Models to automate prompt phrasing, model selection, and iterative refinement. This approach significantly simplifies prompt engineering while enhancing generation quality and text-image alignment compared to direct generation. Specifically, T2I-Copilot consists of three agents: (1) Input Interpreter, which parses the input prompt, resolves ambiguities, and generates a standardized report; (2) Generation Engine, which selects the appropriate model from different types of T2I models and organizes visual and textual prompts to initiate generation; and (3) Quality Evaluator, which assesses aesthetic quality and text-image alignment, providing scores and feedback for potential regeneration. T2I-Copilot can operate fully autonomously while also supporting human-in-the-loop intervention for fine-grained control. On GenAI-Bench, using open-source generation models, T2I-Copilot achieves a VQA score comparable to commercial models RecraftV3 and Imagen 3, surpasses FLUX1.1-pro by 6.17% at only 16.59% of its cost, and outperforms FLUX.1-dev and SD 3.5 Large by 9.11% and 6.36%. Code will be released at: https://github.com/SHI-Labs/T2I-Copilot.

[Arxiv](https://arxiv.org/abs/2507.20536)