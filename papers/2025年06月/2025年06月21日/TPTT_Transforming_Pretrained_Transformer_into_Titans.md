# TPTT：将预训练的Transformer转变为巨擎

发布时间：2025年06月21日

`LLM理论` `模型优化`

> TPTT: Transforming Pretrained Transformer into Titans

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域取得了突破性进展，但长上下文推理中的计算和内存需求仍是重大挑战。我们推出TPTT（将预训练的Transformer模型转化为强大的Titans），一个通过高效线性化注意力机制和先进内存管理来优化预训练Transformer模型的创新框架。TPTT采用了Memory as Gate（MaG）和混合线性化注意力（LiZA）等技术，与Hugging Face Transformers库无缝兼容，支持通过参数高效微调（LoRA）快速适配任何因果LLM，无需重新训练。在MMLU基准测试中，TPTT展现了卓越性能，使用约10亿参数规模的模型，效率和准确性均显著提升。Titans-Llama-3.2-1B的Exact Match（EM）指标相比基础模型提升了20%。统计分析和与最先进方法的对比验证了TPTT的可扩展性和鲁棒性。代码和Python包分别在https://github.com/fabienfrfr/tptt和https://pypi.org/project/tptt/提供。

> Recent advances in large language models (LLMs) have led to remarkable progress in natural language processing, but their computational and memory demands remain a significant challenge, particularly for long-context inference. We introduce TPTT (Transforming Pretrained Transformer into Titans), a novel framework for enhancing pretrained Transformer models with efficient linearized attention mechanisms and advanced memory management. TPTT employs techniques such as Memory as Gate (MaG) and mixed linearized attention (LiZA). It is fully compatible with the Hugging Face Transformers library, enabling seamless adaptation of any causal LLM through parameter-efficient fine-tuning (LoRA) without full retraining. We show the effectiveness of TPTT on the MMLU benchmark with models of approximately 1 billion parameters, observing substantial improvements in both efficiency and accuracy. For instance, Titans-Llama-3.2-1B achieves a 20% increase in Exact Match (EM) over its baseline. Statistical analyses and comparisons with recent state-of-the-art methods confirm the practical scalability and robustness of TPTT. Code is available at https://github.com/fabienfrfr/tptt . Python package at https://pypi.org/project/tptt/ .

[Arxiv](https://arxiv.org/abs/2506.17671)