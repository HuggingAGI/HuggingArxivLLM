# BizFinBench：一个以业务为导向的现实金融基准，专为评估大型语言模型而设计。

发布时间：2025年05月25日

`LLM应用

理由：这篇论文专注于评估大型语言模型在金融领域的实际应用，特别是通过创建BizFinBench基准测试来评估模型在各种金融任务中的表现。论文讨论了模型在不同任务中的性能，并揭示了它们的能力模式，但并未涉及模型的内部机制或理论改进，因此属于LLM应用类别。`

> BizFinBench: A Business-Driven Real-World Financial Benchmark for Evaluating LLMs

# 摘要

> 大型语言模型在通用任务中表现出色，但在金融、法律和医疗等逻辑密集型、精度要求高的领域中，其可靠性评估仍具挑战。为应对这一挑战，我们推出 BizFinBench，这是首个专门用于评估大型语言模型在实际金融应用场景中表现的基准测试。

BizFinBench 包含 6,781 个经过良好标注的中文查询，涵盖数值计算、推理、信息抽取、预测识别以及基于知识的问题回答五个维度，细分为九个类别。该基准测试包含客观和主观两种评估指标，并引入了 IteraJudge，这是一种全新的 LLM 评估方法，旨在减少 LLM 在客观指标中作为评估者时的偏见。

我们对 25 个模型进行了基准测试，包括专有系统和开源系统。大量实验表明，没有单一模型能够在所有任务中占据优势。我们的评估揭示了不同模型的能力模式：
1. 在数值计算方面，Claude-3.5-Sonnet（63.18）和 DeepSeek-R1（64.04）表现领先，而较小的模型如 Qwen2.5-VL-3B（15.92）则显著落后；
2. 在推理方面，专有模型占据主导地位（ChatGPT-o3: 83.58, Gemini-2.0-Flash: 81.15），开源模型则落后多达 19.49 分；
3. 在信息抽取方面，性能差异最大，DeepSeek-R1 得分为 71.46，而 Qwen3-1.7B 仅为 11.23；
4. 在预测识别方面，性能差异最小，顶尖模型得分在 39.16 到 50.00 之间。

我们发现，尽管当前的 LLMs 能够胜任日常的金融查询任务，但在需要跨概念推理的复杂场景下表现不佳。BizFinBench 为未来的研究提供了一个严格且与业务需求对齐的基准测试。代码和数据集可在 https://github.com/HiThink-Research/BizFinBench 获取。

> Large language models excel in general tasks, yet assessing their reliability in logic-heavy, precision-critical domains like finance, law, and healthcare remains challenging. To address this, we introduce BizFinBench, the first benchmark specifically designed to evaluate LLMs in real-world financial applications. BizFinBench consists of 6,781 well-annotated queries in Chinese, spanning five dimensions: numerical calculation, reasoning, information extraction, prediction recognition, and knowledge-based question answering, grouped into nine fine-grained categories. The benchmark includes both objective and subjective metrics. We also introduce IteraJudge, a novel LLM evaluation method that reduces bias when LLMs serve as evaluators in objective metrics. We benchmark 25 models, including both proprietary and open-source systems. Extensive experiments show that no model dominates across all tasks. Our evaluation reveals distinct capability patterns: (1) In Numerical Calculation, Claude-3.5-Sonnet (63.18) and DeepSeek-R1 (64.04) lead, while smaller models like Qwen2.5-VL-3B (15.92) lag significantly; (2) In Reasoning, proprietary models dominate (ChatGPT-o3: 83.58, Gemini-2.0-Flash: 81.15), with open-source models trailing by up to 19.49 points; (3) In Information Extraction, the performance spread is the largest, with DeepSeek-R1 scoring 71.46, while Qwen3-1.7B scores 11.23; (4) In Prediction Recognition, performance variance is minimal, with top models scoring between 39.16 and 50.00. We find that while current LLMs handle routine finance queries competently, they struggle with complex scenarios requiring cross-concept reasoning. BizFinBench offers a rigorous, business-aligned benchmark for future research. The code and dataset are available at https://github.com/HiThink-Research/BizFinBench.

[Arxiv](https://arxiv.org/abs/2505.19457)