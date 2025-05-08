# SLOT：大型语言模型输出的结构化设计

发布时间：2025年05月06日

`LLM应用` `信息提取` `智能体`

> SLOT: Structuring the Output of Large Language Models

# 摘要

> 结构化输出对大型语言模型（LLMs）在智能体和信息提取等关键应用中至关重要。然而，尽管LLMs功能强大，但它们生成的输出经常偏离预定义的模式，严重阻碍了可靠的应用开发。为此，我们提出了SLOT（结构化LLM输出转换器），这是一种模型不可知的方法，能够将非结构化的LLM输出转换为精确的结构化格式。与现有解决方案主要依赖于受约束的解码技术或与特定模型紧密耦合不同，SLOT采用经过微调的轻量级语言模型作为后处理层，实现了在各种LLMs和模式规范上的灵活性。我们引入了一个系统化的数据整理和合成流水线，以及一种正式的评估方法，该方法量化了模式准确性和内容保真度。实验结果显示，经过微调的Mistral-7B模型结合受约束的解码，实现了近乎完美的模式准确率（99.5%）和内容相似度（94.0%），显著超越了Claude-3.5-Sonnet（分别高出25和20个百分点）。特别值得注意的是，即使像Llama-3.2-1B这样的小型模型，在配备SLOT的情况下，也能匹敌或超越更大规模的专有模型在结构化输出方面的能力，从而在资源受限的环境中实现可靠的结构化生成。

> Structured outputs are essential for large language models (LLMs) in critical applications like agents and information extraction. Despite their capabilities, LLMs often generate outputs that deviate from predefined schemas, significantly hampering reliable application development. We present SLOT (Structured LLM Output Transformer), a model-agnostic approach that transforms unstructured LLM outputs into precise structured formats. While existing solutions predominantly rely on constrained decoding techniques or are tightly coupled with specific models, SLOT employs a fine-tuned lightweight language model as a post-processing layer, achieving flexibility across various LLMs and schema specifications. We introduce a systematic pipeline for data curation and synthesis alongside a formal evaluation methodology that quantifies both schema accuracy and content fidelity. Our results demonstrate that fine-tuned Mistral-7B model with constrained decoding achieves near perfect schema accuracy (99.5%) and content similarity (94.0%), outperforming Claude-3.5-Sonnet by substantial margins (+25 and +20 percentage points, respectively). Notably, even compact models like Llama-3.2-1B can match or exceed the structured output capabilities of much larger proprietary models when equipped with SLOT, enabling reliable structured generation in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2505.04016)