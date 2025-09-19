# 基于ModernBERT的专利语言模型预训练

发布时间：2025年09月18日

`LLM应用` `法律科技`

> Patent Language Model Pretraining with ModernBERT

# 摘要

> 基于Transformer的语言模型（如BERT）已成为自然语言处理（NLP）的基石，但在专利这类专业领域性能却不尽如人意——专利文本往往冗长、技术性强且具有严格的法律结构。以往专利NLP的研究方法主要依赖于微调整通用模型，或是采用基于有限数据预训练的领域适配变体。本研究中，我们基于ModernBERT架构，利用超过6000万条专利记录的精心整理语料库，为专利领域预训练了3个特定领域的掩码语言模型。我们的方法融入了架构优化，包括FlashAttention（快速注意力机制）、旋转位置编码和GLU前馈层。我们在四项下游专利分类任务上对模型进行了评估：其中，ModernBERT-base-PT模型在四个数据集中的三个上均持续优于通用ModernBERT基线，且与基线模型PatentBERT性能相当。通过ModernBERT-base-VX和Mosaic-BERT-large的额外实验还发现，扩大模型规模与定制分词器能进一步提升特定任务的性能。值得注意的是，所有ModernBERT变体的推理速度都显著更快（是PatentBERT的3倍以上），这使其非常适用于时间敏感型应用。这些结果充分证明，针对专利领域的特定预训练与架构改进，能为专利NLP任务带来显著优势。

> Transformer-based language models such as BERT have become foundational in NLP, yet their performance degrades in specialized domains like patents, which contain long, technical, and legally structured text. Prior approaches to patent NLP have primarily relied on fine-tuning general-purpose models or domain-adapted variants pretrained with limited data. In this work, we pretrain 3 domain-specific masked language models for patents, using the ModernBERT architecture and a curated corpus of over 60 million patent records. Our approach incorporates architectural optimizations, including FlashAttention, rotary embeddings, and GLU feed-forward layers. We evaluate our models on four downstream patent classification tasks. Our model, ModernBERT-base-PT, consistently outperforms the general-purpose ModernBERT baseline on three out of four datasets and achieves competitive performance with a baseline PatentBERT. Additional experiments with ModernBERT-base-VX and Mosaic-BERT-large demonstrate that scaling the model size and customizing the tokenizer further enhance performance on selected tasks. Notably, all ModernBERT variants retain substantially faster inference over - 3x that of PatentBERT - underscoring their suitability for time-sensitive applications. These results underscore the benefits of domain-specific pretraining and architectural improvements for patent-focused NLP tasks.

[Arxiv](https://arxiv.org/abs/2509.14926)