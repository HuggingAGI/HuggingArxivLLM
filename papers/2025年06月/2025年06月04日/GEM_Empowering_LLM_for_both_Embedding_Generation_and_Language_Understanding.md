# GEM：为大型语言模型赋能，实现嵌入生成与语言理解

发布时间：2025年06月04日

`LLM应用` `大型语言模型`

> GEM: Empowering LLM for both Embedding Generation and Language Understanding

# 摘要

> 大型解码器-only语言模型（LLMs）在生成和推理任务中表现卓越，能够根据指令生成文本响应。然而，许多应用，如检索增强生成（RAG），仍依赖独立的嵌入模型生成文本嵌入，这不仅使系统复杂化，还可能导致嵌入模型与LLMs在理解查询时出现不一致。为解决这一问题，我们提出了一种名为生成式嵌入大型语言模型（GEM）的简单自监督方法，使任何大型解码器-only LLM在保持原有生成和推理能力的同时，能够生成高质量的文本嵌入。我们的方法通过在文本中插入新的特殊标记，并利用注意力掩码操作生成文本的总结嵌入。此方法可轻松集成到现有LLMs的后训练或微调阶段。我们将其应用于参数规模从1B到8B的两个流行LLM家族，并在文本嵌入基准测试（MTEB）和NLP基准测试（MMLU）上评估了转换后的模型。结果显示，我们的方法显著提升了LLMs在MTEB上的性能，同时对MMLU的影响微乎其微。这表明，我们的方法不仅赋予了LLMs先进的文本嵌入能力，还保持了其原有的NLP性能。
    

> Large decoder-only language models (LLMs) have achieved remarkable success in generation and reasoning tasks, where they generate text responses given instructions. However, many applications, e.g., retrieval augmented generation (RAG), still rely on separate embedding models to generate text embeddings, which can complicate the system and introduce discrepancies in understanding of the query between the embedding model and LLMs. To address this limitation, we propose a simple self-supervised approach, Generative Embedding large language Model (GEM), that enables any large decoder-only LLM to generate high-quality text embeddings while maintaining its original text generation and reasoning capabilities. Our method inserts new special token(s) into a text body, and generates summarization embedding of the text by manipulating the attention mask. This method could be easily integrated into post-training or fine tuning stages of any existing LLMs. We demonstrate the effectiveness of our approach by applying it to two popular LLM families, ranging from 1B to 8B parameters, and evaluating the transformed models on both text embedding benchmarks (MTEB) and NLP benchmarks (MMLU). The results show that our proposed method significantly improves the original LLMs on MTEB while having a minimal impact on MMLU. Our strong results indicate that our approach can empower LLMs with state-of-the-art text embedding capabilities while maintaining their original NLP performance

[Arxiv](https://arxiv.org/abs/2506.04344)