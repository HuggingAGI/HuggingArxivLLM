# 展示还是说明？一个评估语义分割中视觉与文本提示的基准研究

发布时间：2025年05月06日

`LLM应用` `计算机视觉` `语义分割`

> Show or Tell? A Benchmark To Evaluate Visual and Textual Prompts in Semantic Segmentation

# 摘要

> 提示工程在大型语言模型中取得了显著成功，但在计算机视觉领域的系统性探索仍十分有限。在语义分割领域，文本提示和视觉提示各具优势：文本提示通过开放词汇方法实现任意类别的分割，而视觉参考提示则提供直观的参考示例。然而，现有基准测试分别评估这些模态，缺乏在相同条件下直接比较。

我们提出Show or Tell (SoT)，这是一个专门设计用于评估语义分割中视觉和文本提示的新基准，涵盖7个不同领域（常见场景、城市、食物、废物、部件、工具和土地覆盖）的14个数据集。我们评估了5种开放词汇方法和4种视觉参考提示方法，并通过基于置信度的掩码融合策略，将后者适应多类分割。

我们的广泛实验表明，开放词汇方法在易于用文本描述的常见概念上表现出色，但在工具等复杂领域上表现挣扎，而视觉参考提示方法在平均结果上表现良好，但根据输入提示的不同，结果表现出高度变异性。通过全面的定量和定性分析，我们识别了两种提示模态的优缺点，为未来在分割任务中研究视觉基础模型提供了有价值的见解。

> Prompt engineering has shown remarkable success with large language models, yet its systematic exploration in computer vision remains limited. In semantic segmentation, both textual and visual prompts offer distinct advantages: textual prompts through open-vocabulary methods allow segmentation of arbitrary categories, while visual reference prompts provide intuitive reference examples. However, existing benchmarks evaluate these modalities in isolation, without direct comparison under identical conditions. We present Show or Tell (SoT), a novel benchmark specifically designed to evaluate both visual and textual prompts for semantic segmentation across 14 datasets spanning 7 diverse domains (common scenes, urban, food, waste, parts, tools, and land-cover). We evaluate 5 open-vocabulary methods and 4 visual reference prompt approaches, adapting the latter to handle multi-class segmentation through a confidence-based mask merging strategy. Our extensive experiments reveal that open-vocabulary methods excel with common concepts easily described by text but struggle with complex domains like tools, while visual reference prompt methods achieve good average results but exhibit high variability depending on the input prompt. Through comprehensive quantitative and qualitative analysis, we identify the strengths and weaknesses of both prompting modalities, providing valuable insights to guide future research in vision foundation models for segmentation tasks.

[Arxiv](https://arxiv.org/abs/2505.06280)