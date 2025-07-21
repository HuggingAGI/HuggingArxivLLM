# # KiC: 基于关键词启发的高效文本生成级联：利用大语言模型实现成本效益最大化

发布时间：2025年07月18日

`LLM应用` `生成模型`

> KiC: Keyword-inspired Cascade for Cost-Efficient Text Generation with LLMs

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理任务中表现卓越。然而，高性能模型通常仅通过API提供，导致高昂的推理成本。为此，我们提出了基于关键词的级联框架（KiC），一种高效生成自由形式文本的新方法。KiC首先在较弱模型的多个输出中识别最具代表性的答案，然后评估其他响应与它的语义一致性。根据一致性程度，KiC决定是采用较弱模型的输出还是升级到更强的模型。实验结果显示，KiC不仅达到了GPT-4准确率的97.53%，还平均降低了28.81%的API成本，甚至在特定基准上超越了GPT-4。

> Large language models (LLMs) have demonstrated state-of-the-art performance across a wide range of natural language processing tasks. However, high-performing models are typically accessible only via APIs, incurring substantial inference costs. Cascade methods address this by initially employing a cheaper model and escalating to a stronger one only when necessary. Nevertheless, existing cascade approaches struggle to select a reliable representative response and assess the overall reliability of free-form outputs, as they rely on exact text matching. To overcome these limitations, we propose Keyword-inspired Cascade (KiC), a novel framework for cost-efficient free-form text generation. KiC identifies the most representative answer among multiple outputs from a weaker model and evaluates the semantic alignment of other responses with it. Based on the degree of alignment, KiC determines whether to accept the weaker model's output or escalate to a stronger model. Experiments on three free-form text generation benchmarks show that KiC achieves 97.53 percent of GPT-4's accuracy while reducing API costs by 28.81 percent on average, and even outperforms GPT-4 in a specific benchmark.

[Arxiv](https://arxiv.org/abs/2507.13666)