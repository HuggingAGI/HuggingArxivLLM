# Liger：将大型语言模型转换为门控循环结构

发布时间：2025年03月03日

`LLM理论` `人工智能`

> Liger: Linearizing Large Language Models to Gated Recurrent Structures

# 摘要

> 线性递归建模的Transformer模型实现了线性时间训练和常数级内存推理。尽管它们在效率和性能上表现出色，但从头预训练这些非标准架构仍然成本高昂且风险较大。LLMs的线性化将标准模型转化为线性递归结构，实现更高效部署。然而，现有方法通常引入额外特征映射模块，需大量微调，且忽视了现代线性递归模型的门控机制。为解决这些问题，本文提出Liger（Linearizing LLMs to gated recurrent structures），一种将预训练LLMs转换为门控线性递归模型的新方法，无需添加额外参数。Liger重新利用预训练关键矩阵权重构建多样化门控机制，形成多种门控递归结构，无需从头训练额外组件。结合轻量级微调和低秩适配（LoRA），Liger将线性化门控递归模型性能恢复至与原始LLMs相当。此外，我们引入Liger注意力机制，一种层内混合注意力机制，在线性化过程中以仅0.02%的预训练令牌恢复93%的基于Transformer的LLMs性能，并在多个基准测试中取得具有竞争力的结果，已在1B到8B参数规模的模型上验证。代码可在https://github.com/OpenSparseLLMs/Linearization获取。


> Transformers with linear recurrent modeling offer linear-time training and constant-memory inference. Despite their demonstrated efficiency and performance, pretraining such non-standard architectures from scratch remains costly and risky. The linearization of large language models (LLMs) transforms pretrained standard models into linear recurrent structures, enabling more efficient deployment. However, current linearization methods typically introduce additional feature map modules that require extensive fine-tuning and overlook the gating mechanisms used in state-of-the-art linear recurrent models. To address these issues, this paper presents Liger, short for Linearizing LLMs to gated recurrent structures. Liger is a novel approach for converting pretrained LLMs into gated linear recurrent models without adding extra parameters. It repurposes the pretrained key matrix weights to construct diverse gating mechanisms, facilitating the formation of various gated recurrent structures while avoiding the need to train additional components from scratch. Using lightweight fine-tuning with Low-Rank Adaptation (LoRA), Liger restores the performance of the linearized gated recurrent models to match that of the original LLMs. Additionally, we introduce Liger Attention, an intra-layer hybrid attention mechanism, which significantly recovers 93\% of the Transformer-based LLM at 0.02\% pre-training tokens during the linearization process, achieving competitive results across multiple benchmarks, as validated on models ranging from 1B to 8B parameters. Code is available at https://github.com/OpenSparseLLMs/Linearization.

[Arxiv](https://arxiv.org/abs/2503.01496)