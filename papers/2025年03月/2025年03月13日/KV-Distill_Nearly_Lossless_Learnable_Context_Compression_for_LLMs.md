# KV-Distill：大型语言模型的近乎无损可学习上下文压缩技术

发布时间：2025年03月13日

`LLM理论` `问答系统` `文本摘要`

> KV-Distill: Nearly Lossless Learnable Context Compression for LLMs

# 摘要

> 长上下文对序列到序列任务大有裨益，但标准Transformer中自注意力机制的二次复杂度使其实现颇具挑战性。生成过程中，存储在KV缓存中的临时表示占用了GPU内存的很大一部分，并且与上下文长度线性相关。我们提出KV-Distill，一个Transformer压缩框架，能够将长上下文KV缓存压缩为显著更短的表示，且与具体问题无关。KV-Distill可作为参数高效适配器，训练后能压缩任意长度的上下文，同时保留预训练模型功能。我们将压缩-未压缩缓存视为学生-教师配对，并应用KL散度来匹配生成输出。在最坏情况下的抽取任务中，KV-Distill的表现优于其他压缩技术，并在长上下文问答和摘要任务中接近未压缩性能。它还可以在特定领域上下文中进行微调，将长度缩短高达99%，同时保持下游性能。我们展示了KV-Distill在不同模型规模和架构中的通用性。

> Sequence-to-sequence tasks often benefit from long contexts, but the quadratic complexity of self-attention in standard Transformers renders this non-trivial. During generation, temporary representations -stored in the so-called KV cache-account for a large portion of GPU memory usage and scale linearly with context length. We introduce KV-Distill, a Transformer compression framework that distills long context KV caches into significantly shorter representations in a question-independent fashion. KV-Distill can be trained as a parameter-efficient adaptor for pretrained models, and enables the compression of arbitrary spans of a context while preserving pre-trained model capabilities. We treat a compressed-uncompressed cache as a student-teacher pairing and apply a KL-type divergence to match the generated outputs. KV-Distill outperforms other compression techniques in worst-case extractive tasks and approaches uncompressed performance in long context question answering and summarization, and it can be fine-tuned on domain-specific contexts to reduce lengths by up to 99% while preserving downstream performance. We demonstrate the generalizability of KV-Distill across various model sizes and architectures.

[Arxiv](https://arxiv.org/abs/2503.10337)