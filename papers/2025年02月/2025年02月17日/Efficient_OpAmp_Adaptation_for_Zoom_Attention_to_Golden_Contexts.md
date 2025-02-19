# 高效运算放大器适配：聚焦黄金上下文的注意力机制研究

发布时间：2025年02月17日

`LLM应用` `问答系统`

> Efficient OpAmp Adaptation for Zoom Attention to Golden Contexts

# 摘要

> 大型语言模型（LLMs）在问答（QA）任务中展现出巨大潜力，尤其是在检索增强生成（RAG）场景和长上下文应用中。然而，噪声参考文档常常干扰关键信息，导致模型性能受限。尽管进行了微调，基于Transformer的架构仍难以有效区分相关内容，这一点体现在模型往往过度关注无关或后置文档。近期研究提出的差异注意力机制试图解决这一问题，但受限于不合适的共模抑制比（CMRR）和高昂的计算成本。受运算放大器（OpAmp）启发，我们提出了OpAmp适配器，以高效解决这些问题。通过将适配器集成到预训练的Transformer模块中，我们的方法能够在不从头开始昂贵训练的情况下，增强对黄金上下文的关注。在噪声上下文基准上的实证评估表明，采用OpAmp适配器训练的Qwen2.5-OpAmp-72B模型，超越了包括DeepSeek-V3和GPT-4在内的最先进LLMs的性能表现。


> Large language models (LLMs) have shown significant promise in question-answering (QA) tasks, particularly in retrieval-augmented generation (RAG) scenarios and long-context applications. However, their performance is hindered by noisy reference documents, which often distract from essential information. Despite fine-tuning efforts, Transformer-based architectures struggle to prioritize relevant content. This is evidenced by their tendency to allocate disproportionate attention to irrelevant or later-positioned documents. Recent work proposes the differential attention mechanism to address this issue, but this mechanism is limited by an unsuitable common-mode rejection ratio (CMRR) and high computational costs. Inspired by the operational amplifier (OpAmp), we propose the OpAmp adaptation to address these challenges, which is implemented with adapters efficiently. By integrating the adapter into pre-trained Transformer blocks, our approach enhances focus on the golden context without costly training from scratch. Empirical evaluations on noisy-context benchmarks reveal that our Qwen2.5-OpAmp-72B model, trained with our OpAmp adaptation, surpasses the performance of state-of-the-art LLMs, including DeepSeek-V3 and GPT-4o.

[Arxiv](https://arxiv.org/abs/2502.12502)