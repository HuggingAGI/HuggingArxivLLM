# 分层自回归变换器：融合字节与词级处理，打造稳健且适应性强的语言模型

发布时间：2025年01月17日

`LLM理论

理由：这篇论文主要讨论了一种新的分层自回归语言建模架构，旨在解决子词分词器面临的问题。该研究涉及语言模型的架构设计和优化，属于对大型语言模型（LLM）的理论研究和改进，因此应归类为LLM理论。` `跨语言`

> Hierarchical Autoregressive Transformers: Combining Byte-~and Word-Level Processing for Robust, Adaptable Language Models

# 摘要

> # 摘要
分词是自然语言处理的基础步骤，将文本分解为计算模型可处理的单元。尽管子词分词器已成为主流，但其面临词汇量大、对新领域或语言适应性差、以及对拼写错误和变体敏感等问题。为此，我们提出了一种结合字符级和词级处理的分层自回归语言建模架构。该架构使用轻量级字符级编码器将字符序列转换为词嵌入，再由词级骨干模型处理，并通过紧凑的字符级解码器解码回字符。这种方法既保留了词级分词的序列压缩优势，又无需依赖固定的预定义词汇表。实验表明，在高达70亿参数的规模下，分层变换器不仅在下游任务中表现与子词分词器模型相当，还对输入扰动表现出更强的鲁棒性。此外，在对域外语言进行持续预训练时，我们的模型训练速度几乎翻倍，在目标语言上表现更优，且能更好地保留先前学到的知识。分层变换器为构建跨语言和领域的更鲁棒、灵活且可推广的NLP系统奠定了基础。

> Tokenization is a fundamental step in natural language processing, breaking text into units that computational models can process. While learned subword tokenizers have become the de-facto standard, they present challenges such as large vocabularies, limited adaptability to new domains or languages, and sensitivity to spelling errors and variations. To overcome these limitations, we investigate a hierarchical architecture for autoregressive language modelling that combines character-level and word-level processing. It employs a lightweight character-level encoder to convert character sequences into word embeddings, which are then processed by a word-level backbone model and decoded back into characters via a compact character-level decoder. This method retains the sequence compression benefits of word-level tokenization without relying on a rigid, predefined vocabulary. We demonstrate, at scales up to 7 billion parameters, that hierarchical transformers match the downstream task performance of subword-tokenizer-based models while exhibiting significantly greater robustness to input perturbations. Additionally, during continued pretraining on an out-of-domain language, our model trains almost twice as fast, achieves superior performance on the target language, and retains more of its previously learned knowledge. Hierarchical transformers pave the way for NLP systems that are more robust, flexible, and generalizable across languages and domains.

[Arxiv](https://arxiv.org/abs/2501.10322)