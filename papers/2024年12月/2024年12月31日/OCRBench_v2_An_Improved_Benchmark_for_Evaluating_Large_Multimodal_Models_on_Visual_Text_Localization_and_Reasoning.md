# OCRBench v2: 一个升级版基准测试，专为评估大型多模态模型在视觉文本定位与推理能力而设计

发布时间：2024年12月31日

`LLM应用

理由：这篇论文主要关注的是大型多模态模型（LMMs）在光学字符识别（OCR）任务中的表现，并通过一个名为OCRBench v2的基准测试来评估这些模型的能力。虽然论文涉及多模态模型，但其核心是评估和改进这些模型在特定应用（OCR）中的性能，因此应归类为“LLM应用”。` `光学字符识别` `多模态模型`

> OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning

# 摘要

> # 评分大型多模态模型（LMMs）的光学字符识别（OCR）能力最近备受关注。现有基准测试已展示LMMs在文本识别上的卓越表现，但在文本定位、手写内容提取和逻辑推理等挑战性任务上的能力仍有待探索。为此，我们推出OCRBench v2，这是一个大规模双语文本中心基准测试，拥有最全面的任务集（比前代多4倍）、最广泛的场景覆盖（31种场景，如街景、收据、公式、图表等），以及全面的评估指标，包含10,000个人工验证的问答对，且高比例困难样本。在OCRBench v2上评估最先进的LMMs后，我们发现22个模型中有20个得分低于50（满分100），并存在五种局限性：罕见文本识别、细粒度感知、布局感知、复杂元素解析和逻辑推理。基准测试和评估脚本可在https://github.com/Yuliang-liu/MultimodalOCR获取。

> Scoring the Optical Character Recognition (OCR) capabilities of Large Multimodal Models (LMMs) has witnessed growing interest recently. Existing benchmarks have highlighted the impressive performance of LMMs in text recognition; however, their abilities on certain challenging tasks, such as text localization, handwritten content extraction, and logical reasoning, remain underexplored. To bridge this gap, we introduce OCRBench v2, a large-scale bilingual text-centric benchmark with currently the most comprehensive set of tasks (4x more tasks than the previous multi-scene benchmark OCRBench), the widest coverage of scenarios (31 diverse scenarios including street scene, receipt, formula, diagram, and so on), and thorough evaluation metrics, with a total of 10,000 human-verified question-answering pairs and a high proportion of difficult samples. After carefully benchmarking state-of-the-art LMMs on OCRBench v2, we find that 20 out of 22 LMMs score below 50 (100 in total) and suffer from five-type limitations, including less frequently encountered text recognition, fine-grained perception, layout perception, complex element parsing, and logical reasoning. The benchmark and evaluation scripts are available at https://github.com/Yuliang-liu/MultimodalOCR.

[Arxiv](https://arxiv.org/abs/2501.00321)