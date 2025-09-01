# 多模态LLMs如何解决图像任务：聚焦视觉接地、任务推理与答案解码

发布时间：2025年08月27日

`LLM理论` `基础理论`

> How Multimodal LLMs Solve Image Tasks: A Lens on Visual Grounding, Task Reasoning, and Answer Decoding

# 摘要

> 多模态大型语言模型（MLLMs）在各类视觉-语言任务中表现卓越，然而其内部处理机制的动态变化尚未得到充分研究。为此，我们提出了一种探测框架，用于系统分析MLLMs各层对视觉与文本输入的处理机制。我们通过标准化锚定问题，从各层提取的 token 嵌入中训练线性分类器，以预测细粒度视觉类别（如犬种）。为揭示不同层的功能，我们通过三种受控提示变体对这些探测器进行评估：（1）词汇变体，用于测试对表层变化的敏感性；（2）语义否定变体，通过修改提示中的视觉概念来翻转预期答案；（3）输出格式变体，保留推理过程但改变答案格式。将该框架应用于LLaVA-1.5、LLaVA-Next-LLaMA-3和Qwen2-VL后，我们发现了一致的阶段性结构：早期层负责视觉接地，中间层实现词汇整合与语义推理，末层则生成特定任务的输出。我们进一步发现，尽管视觉 token 化方式、指令微调数据及预训练语料库的变化不会影响整体阶段性结构的稳定性，但基础LLM架构的改变会导致各阶段的具体层分配发生显著变化。研究结果不仅为MLLMs的分层组织提供了统一视角，还为分析多模态表征动态提供了轻量级、模型无关的新方法。

> Multimodal Large Language Models (MLLMs) have demonstrated strong performance across a wide range of vision-language tasks, yet their internal processing dynamics remain underexplored. In this work, we introduce a probing framework to systematically analyze how MLLMs process visual and textual inputs across layers. We train linear classifiers to predict fine-grained visual categories (e.g., dog breeds) from token embeddings extracted at each layer, using a standardized anchor question. To uncover the functional roles of different layers, we evaluate these probes under three types of controlled prompt variations: (1) lexical variants that test sensitivity to surface-level changes, (2) semantic negation variants that flip the expected answer by modifying the visual concept in the prompt, and (3) output format variants that preserve reasoning but alter the answer format. Applying our framework to LLaVA-1.5, LLaVA-Next-LLaMA-3, and Qwen2-VL, we identify a consistent stage-wise structure in which early layers perform visual grounding, middle layers support lexical integration and semantic reasoning, and final layers prepare task-specific outputs. We further show that while the overall stage-wise structure remains stable across variations in visual tokenization, instruction tuning data, and pretraining corpus, the specific layer allocation to each stage shifts notably with changes in the base LLM architecture. Our findings provide a unified perspective on the layer-wise organization of MLLMs and offer a lightweight, model-agnostic approach for analyzing multimodal representation dynamics.

[Arxiv](https://arxiv.org/abs/2508.20279)