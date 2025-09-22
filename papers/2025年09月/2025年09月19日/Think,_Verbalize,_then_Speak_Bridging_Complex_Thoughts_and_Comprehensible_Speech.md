# 思考，组织语言，再表达：架起复杂思绪与易懂言语的桥梁

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Think, Verbalize, then Speak: Bridging Complex Thoughts and Comprehensible Speech

# 摘要

> 口语对话系统正越来越多地借助大型语言模型（LLMs）的强大推理能力。但在口语交流场景中，由于文本与口头表达的最佳方式存在差异，直接应用LLMs往往效果欠佳。现有方法虽能让LLMs生成更适配语音的输出，但其对推理性能的影响尚未得到充分研究。为此，我们提出Think-Verbalize-Speak框架，通过将推理与口语表达解耦，从而保留LLMs的完整推理能力。该方法的核心在于“言语化”（verbalizing）这一中间步骤——将思维转化为自然且适合语音输出的文本。我们还引入了ReVerT，这是一种基于增量异步总结的低延迟言语化器。多项基准实验表明，我们的方法在显著提升语音自然度与简洁性的同时，对推理能力的影响微乎其微。项目页面（含数据集与源代码）详见：https://yhytoto12.github.io/TVS-ReVerT

> Spoken dialogue systems increasingly employ large language models (LLMs) to leverage their advanced reasoning capabilities. However, direct application of LLMs in spoken communication often yield suboptimal results due to mismatches between optimal textual and verbal delivery. While existing approaches adapt LLMs to produce speech-friendly outputs, their impact on reasoning performance remains underexplored. In this work, we propose Think-Verbalize-Speak, a framework that decouples reasoning from spoken delivery to preserve the full reasoning capacity of LLMs. Central to our method is verbalizing, an intermediate step that translates thoughts into natural, speech-ready text. We also introduce ReVerT, a latency-efficient verbalizer based on incremental and asynchronous summarization. Experiments across multiple benchmarks show that our method enhances speech naturalness and conciseness with minimal impact on reasoning. The project page with the dataset and the source code is available at https://yhytoto12.github.io/TVS-ReVerT

[Arxiv](https://arxiv.org/abs/2509.16028)