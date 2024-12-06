# Arabic Stable LM：把 Stable LM 2 1.6B 适配为阿拉伯语版本

发布时间：2024年12月05日

`LLM应用` `阿拉伯语`

> Arabic Stable LM: Adapting Stable LM 2 1.6B to Arabic

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）的多个领域成果斐然，不过主要聚焦于英语。近来，更多的LLMs融入了更多比例的多语言文本，以呈现低资源语言。在阿拉伯语自然语言处理领域，过去两年，数个以阿拉伯语为核心的LLMs在多项基准测试中表现出色。然而，与较小的LLMs相比，大多数阿拉伯语LLMs的参数超过70亿，这就提高了硬件要求和推理延迟。本文推出了基础版和聊天版的Arabic Stable LM 1.6B，作为小巧却强大的以阿拉伯语为中心的LLM。我们的Arabic Stable LM 1.6B聊天模型在多项基准测试中成绩出众，战胜了参数多达8倍的多个模型。另外，我们展示了通过用大型合成对话数据集扩充微调数据来混合合成指令调整数据的益处。

> Large Language Models (LLMs) have shown impressive results in multiple domains of natural language processing (NLP) but are mainly focused on the English language. Recently, more LLMs have incorporated a larger proportion of multilingual text to represent low-resource languages. In Arabic NLP, several Arabic-centric LLMs have shown remarkable results on multiple benchmarks in the past two years. However, most Arabic LLMs have more than 7 billion parameters, which increases their hardware requirements and inference latency, when compared to smaller LLMs. This paper introduces Arabic Stable LM 1.6B in a base and chat version as a small but powerful Arabic-centric LLM. Our Arabic Stable LM 1.6B chat model achieves impressive results on several benchmarks beating multiple models with up to 8x the parameters. In addition, we show the benefit of mixing in synthetic instruction tuning data by augmenting our fine-tuning data with a large synthetic dialogue dataset.

[Arxiv](https://arxiv.org/abs/2412.04277)