# MMSearch-Plus：简单却极具挑战性的多模态浏览智能体基准

发布时间：2025年08月29日

`Agent` `基础理论`

> MMSearch-Plus: A Simple Yet Challenging Benchmark for Multimodal Browsing Agents

# 摘要

> 大型多模态语言模型（MLLMs）正日益成为网络代理的核心，但许多多模态浏览基准可通过浅层、固定的工作流程轻松解决——这些流程依赖高召回率图像搜索和附近文本，从而掩盖了细粒度视觉推理、来源验证与长程工具使用等真正的多模态挑战。为此，我们推出MMSearch-Plus基准，它包含311个任务，既对多模态理解能力提出极高要求，又保留了优秀纯文本浏览套件的难度水平。每个任务项都精心设计了多个微弱的局部视觉信号，必须先提取这些信号，通过迭代的文本-图像搜索进行传播，并在检索噪声环境下交叉验证，之后才能给出答案。我们的构建方法——时空外推法，生成的问题答案需要从空间线索（微文本、部件级外观、布局、标识）和时间痕迹（广播叠加层、季节背景）推断出图像外的事实，如事件、日期和地点。我们提供了一个配备浏览工具的与模型无关的智能体框架，并对一系列闭源和开源MLLMs进行了评估。结果显示，性能最强的智能体（o3）在我们的框架下，不使用搜索时准确率为15.1%，使用rollout搜索时达到36.0%；而性能较强的开源模型（Qwen-2.5-VL-72B-Instruct）不使用搜索时准确率为0.0%，经过20轮搜索后也仅为6.9%。除答案准确率外，我们还评估了边界框生成和裁剪图像搜索能力，并通过错误分析揭示了模型在来源验证、部件推理和长程规划方面的失败情况。

> Large multimodal language models (MLLMs) are increasingly deployed as web agents, yet many multimodal browsing benchmarks can be solved by shallow, fixed workflows that lean on high-recall image search and nearby text-masking the genuinely multimodal challenges of fine-grained visual reasoning, provenance verification, and long-horizon tool use. We introduce MMSearch-Plus, a benchmark of 311 tasks that highly demand multimodal understanding while preserving the difficulty profile of strong text-only browsing suites. Each item is constructed to contain multiple weak, localized visual signals that must be extracted, propagated through iterative text-image search, and cross-validated under retrieval noise before answering. Our curation procedure, Spatial-Temporal Extrapolation, seeds questions whose answers require extrapolating from spatial cues (micro-text, part-level appearance, layouts, signage) and temporal traces (broadcast overlays, seasonal context) to out-of-image facts such as events, dates, and venues. We provide a model-agnostic agent framework with browsing tools and evaluate a range of closed and open MLLMs. The strongest agent (o3) attains 15.1% without search and 36.0% accuracy with rollout under our framework, while a strong open-source model (Qwen-2.5-VL-72B-Instruct) achieves 0.0% without search and 6.9% after 20 rounds of search. Beyond answer accuracy, we assess bounding-box production and cropped-image search, and conduct an error analysis that surfaces failures in source verification, part-based reasoning, and long-horizon planning.

[Arxiv](https://arxiv.org/abs/2508.21475)