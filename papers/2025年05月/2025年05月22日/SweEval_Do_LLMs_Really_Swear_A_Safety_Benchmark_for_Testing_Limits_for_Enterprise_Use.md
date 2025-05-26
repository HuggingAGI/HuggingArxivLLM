# # SweEval：LLM真的会咒骂吗？企业级应用的安全边界测试基准

发布时间：2025年05月22日

`LLM应用

摘要讨论了大型语言模型在企业沟通任务中的实际应用，特别是处理不当语言和文化背景的问题，并开发了一个基准测试来评估模型的表现。这属于LLM的应用层面，因此归类为LLM应用。` `企业应用`

> SweEval: Do LLMs Really Swear? A Safety Benchmark for Testing Limits for Enterprise Use

# 摘要

> 越来越多的企业客户选择使用大型语言模型（LLMs）来处理关键沟通任务，如撰写邮件、设计销售文案和编写非正式信息。在不同地区部署这些模型时，它们需要理解多样化的文化与语言背景，并生成安全且得体的回应。对于企业应用，有效识别和处理不当或冒犯性语言至关重要，这不仅关乎声誉风险，更是维护信任和确保合规性的关键。为此，我们推出了SweEval，一个模拟现实场景的基准测试，涵盖语气（积极或消极）和上下文（正式或非正式）的变化。该测试明确要求模型在完成任务时包含特定脏话，以此评估LLMs是否能抵制不适当指令，并考察其在伦理框架、文化细微差别和语言理解方面的对齐程度。为了推动构建符合企业应用及更广泛领域伦理对齐的人工智能系统的研究，我们公开了相关数据集和代码：https://github.com/amitbcp/multilingual_profanity。

> Enterprise customers are increasingly adopting Large Language Models (LLMs) for critical communication tasks, such as drafting emails, crafting sales pitches, and composing casual messages. Deploying such models across different regions requires them to understand diverse cultural and linguistic contexts and generate safe and respectful responses. For enterprise applications, it is crucial to mitigate reputational risks, maintain trust, and ensure compliance by effectively identifying and handling unsafe or offensive language. To address this, we introduce SweEval, a benchmark simulating real-world scenarios with variations in tone (positive or negative) and context (formal or informal). The prompts explicitly instruct the model to include specific swear words while completing the task. This benchmark evaluates whether LLMs comply with or resist such inappropriate instructions and assesses their alignment with ethical frameworks, cultural nuances, and language comprehension capabilities. In order to advance research in building ethically aligned AI systems for enterprise use and beyond, we release the dataset and code: https://github.com/amitbcp/multilingual_profanity.

[Arxiv](https://arxiv.org/abs/2505.17332)