# 从文本用户报告中评估大型语言模型和提示策略在自动化硬件诊断中的应用

发布时间：2025年07月01日

`LLM应用` `制造业`

> Evaluating LLMs and Prompting Strategies for Automated Hardware Diagnosis from Textual User-Reports

# 摘要

> 计算机制造商为用户提供了通过文本报告描述设备故障的平台，例如“我的屏幕在闪烁”。从这些报告中识别出故障部件，对于实现自动化测试和提升用户体验至关重要。然而，这类报告通常模糊不清且细节不足，增加了识别难度。大型语言模型（LLMs）在解决此类问题方面展现出潜力。本研究对27个开源模型（参数规模从10亿到720亿）和2个专有LLMs进行了评估，采用了四种提示策略：零样本、少样本、链式思考（CoT）和CoT+少样本（CoT+FS）。我们进行了98,948次推理，处理了超过5100万输入标记并生成了1300万输出标记。研究结果显示，我们实现了高达0.76的F1分数。进一步分析表明，三个模型在规模和性能之间实现了最佳平衡：mistral-small-24b-instruct以及两个较小的模型，llama-3.2-1b-instruct和gemma-2-2b-it。这些模型不仅性能出色，而且对VRAM的需求较低，使得在现代笔记本电脑或带有NPUs的智能手机等终端设备上进行高效推理成为可能。

> Computer manufacturers offer platforms for users to describe device faults using textual reports such as "My screen is flickering". Identifying the faulty component from the report is essential for automating tests and improving user experience. However, such reports are often ambiguous and lack detail, making this task challenging. Large Language Models (LLMs) have shown promise in addressing such issues. This study evaluates 27 open-source models (1B-72B parameters) and 2 proprietary LLMs using four prompting strategies: Zero-Shot, Few-Shot, Chain-of-Thought (CoT), and CoT+Few-Shot (CoT+FS). We conducted 98,948 inferences, processing over 51 million input tokens and generating 13 million output tokens. We achieve f1-score up to 0.76. Results show that three models offer the best balance between size and performance: mistral-small-24b-instruct and two smaller models, llama-3.2-1b-instruct and gemma-2-2b-it, that offer competitive performance with lower VRAM usage, enabling efficient inference on end-user devices as modern laptops or smartphones with NPUs.

[Arxiv](https://arxiv.org/abs/2507.00742)