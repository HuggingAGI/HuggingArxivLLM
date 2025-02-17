# 小模型，大影响：高效语料与图结构适配小型多语言模型，助力低资源语言应用

发布时间：2025年02月14日

`LLM应用` `多语言`

> Small Models, Big Impact: Efficient Corpus and Graph-Based Adaptation of Small Multilingual Language Models for Low-Resource Languages

# 摘要

> 低资源语言（LRLs）在自然语言处理（NLP）中面临数据稀缺带来的重大挑战。尽管当前最先进的大型语言模型（LLMs）在处理LRLs时仍存在困难，但像mBERT和XLM-R这样的小型多语种模型（mLMs）由于其容量与低训练数据量的更好匹配，展现出更大的潜力。本研究系统性地探讨了基于参数高效的适配器方法，用于将mLMs适应LRLs，并评估了三种架构：序列瓶颈、可逆瓶颈和低秩适配。通过使用GlotCC的无结构文本和ConceptNet的结构化知识，我们发现，即使使用较小的适配数据集（例如，不超过1 GB的自由文本或几MB的知识图谱数据），也能在内在任务（如掩码语言建模）和外在任务（如主题分类、情感分析和命名实体识别）中获得性能提升。研究发现，序列瓶颈适配器在语言建模中表现出色，而可逆瓶颈适配器由于更好的嵌入对齐和更大的参数数量，在下游任务上略胜一筹。基于适配器的方法在使用远少于全微调的参数数量时，能够匹敌甚至超越全微调的性能。此外，小型mLMs在处理LRLs时比像LLaMA-3、GPT-4和DeepSeek-R1蒸馏模型等大型LLMs更为有效。尽管适配提升了性能，但预训练数据规模仍是主导因素，尤其对于那些预训练覆盖范围广泛的语言。

> Low-resource languages (LRLs) face significant challenges in natural language processing (NLP) due to limited data. While current state-of-the-art large language models (LLMs) still struggle with LRLs, smaller multilingual models (mLMs) such as mBERT and XLM-R offer greater promise due to a better fit of their capacity to low training data sizes. This study systematically investigates parameter-efficient adapter-based methods for adapting mLMs to LRLs, evaluating three architectures: Sequential Bottleneck, Invertible Bottleneck, and Low-Rank Adaptation. Using unstructured text from GlotCC and structured knowledge from ConceptNet, we show that small adaptation datasets (e.g., up to 1 GB of free-text or a few MB of knowledge graph data) yield gains in intrinsic (masked language modeling) and extrinsic tasks (topic classification, sentiment analysis, and named entity recognition). We find that Sequential Bottleneck adapters excel in language modeling, while Invertible Bottleneck adapters slightly outperform other methods on downstream tasks due to better embedding alignment and larger parameter counts. Adapter-based methods match or outperform full fine-tuning while using far fewer parameters, and smaller mLMs prove more effective for LRLs than massive LLMs like LLaMA-3, GPT-4, and DeepSeek-R1-based distilled models. While adaptation improves performance, pre-training data size remains the dominant factor, especially for languages with extensive pre-training coverage.

[Arxiv](https://arxiv.org/abs/2502.10140)