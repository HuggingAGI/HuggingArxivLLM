# DisCoCLIP：分布组合张量网络编码器——用于视觉-语言理解

发布时间：2025年09月25日

`LLM应用` `基础理论`

> DisCoCLIP: A Distributional Compositional Tensor Network Encoder for Vision-Language Understanding

# 摘要

> 近年来，视觉语言模型在大规模图文对齐上表现卓越，却常常忽略语言的组合结构，致使在依赖词序和谓词-论元结构的任务中频频失利。为此，我们提出DisCoCLIP——一种多模态编码器，它将冻结的CLIP视觉Transformer与新型张量网络文本编码器相结合，而后者能显式编码句法结构。该模型利用组合范畴语法解析器解析句子，生成分布词张量，其张量收缩过程对应句子的语法推导。为确保模型高效，我们对高阶张量进行张量分解因式分解，将参数规模从数千万降至一百万以内。在自监督对比损失的端到端训练下，DisCoCLIP显著增强了对动词语义和词序的敏感性：它将CLIP在SVO-Probes上的动词准确率从77.6%提升至82.4%，ARO归因和关系分数分别提高超9%和4%，并在新推出的SVO-Swap基准测试中达到93.7%。这些结果证实，借助张量网络嵌入显式语言结构，能够得到可解释且参数高效的表示，从而大幅提升视觉语言任务的组合推理能力。

> Recent vision-language models excel at large-scale image-text alignment but often neglect the compositional structure of language, leading to failures on tasks that hinge on word order and predicate-argument structure. We introduce DisCoCLIP, a multimodal encoder that combines a frozen CLIP vision transformer with a novel tensor network text encoder that explicitly encodes syntactic structure. Sentences are parsed with a Combinatory Categorial Grammar parser to yield distributional word tensors whose contractions mirror the sentence's grammatical derivation. To keep the model efficient, high-order tensors are factorized with tensor decompositions, reducing parameter count from tens of millions to under one million. Trained end-to-end with a self-supervised contrastive loss, DisCoCLIP markedly improves sensitivity to verb semantics and word order: it raises CLIP's SVO-Probes verb accuracy from 77.6% to 82.4%, boosts ARO attribution and relation scores by over 9% and 4%, and achieves 93.7% on a newly introduced SVO-Swap benchmark. These results demonstrate that embedding explicit linguistic structure via tensor networks yields interpretable, parameter-efficient representations that substantially improve compositional reasoning in vision-language tasks.

[Arxiv](https://arxiv.org/abs/2509.21287)