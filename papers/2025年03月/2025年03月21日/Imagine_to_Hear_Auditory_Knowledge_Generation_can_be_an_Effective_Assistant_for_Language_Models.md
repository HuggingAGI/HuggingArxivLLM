# # 听见想象：听觉知识生成助力语言模型

发布时间：2025年03月21日

`LLM应用` `人工智能` `音频处理`

> Imagine to Hear: Auditory Knowledge Generation can be an Effective Assistant for Language Models

# 摘要

> 仅基于文本语料库预训练的语言模型在处理需要听觉常识的任务时常常表现不佳。此前的研究通过增强语言模型，从外部音频数据库中检索知识来解决这一问题，但这种方法存在诸多限制，比如数据库中可能缺乏相关音频，以及高昂的构建和查询成本。为了解决这些问题，我们提出了名为“Imagine to Hear”的全新方法，该方法利用生成模型动态生成听觉知识。我们的框架能够从给定提示中检测出多个与音频相关的文本片段，并生成相应的听觉知识。为了高效处理多个听觉知识，我们开发了多种机制，包括基于CLAP的拒绝采样器和语言-音频融合模块。实验结果表明，我们的方法在无需依赖外部数据库的情况下，在AuditoryBench基准测试中达到了最先进的性能水平，充分证明了生成方法的有效性。

> Language models pretrained on text-only corpora often struggle with tasks that require auditory commonsense knowledge. Previous work addresses this problem by augmenting the language model to retrieve knowledge from external audio databases. This approach has several limitations, such as the potential lack of relevant audio in databases and the high costs associated with constructing and querying the databases. To address these issues, we propose Imagine to Hear, a novel approach that dynamically generates auditory knowledge using generative models. Our framework detects multiple audio-related textual spans from the given prompt and generates corresponding auditory knowledge. We develop several mechanisms to efficiently process multiple auditory knowledge, including a CLAP-based rejection sampler and a language-audio fusion module. Our experiments show that our method achieves state-of-the-art performance on AuditoryBench without relying on external databases, highlighting the effectiveness of our generation-based approach.

[Arxiv](https://arxiv.org/abs/2503.16853)