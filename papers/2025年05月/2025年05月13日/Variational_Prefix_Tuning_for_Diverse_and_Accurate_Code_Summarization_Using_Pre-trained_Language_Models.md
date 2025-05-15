# 变分前缀微调：基于预训练语言模型的多样且精准代码摘要方法

发布时间：2025年05月13日

`LLM应用` `软件工程`

> Variational Prefix Tuning for Diverse and Accurate Code Summarization Using Pre-trained Language Models

# 摘要

> 源代码摘要领域近期取得了显著进展，主要得益于基于变换器的预训练模型，特别是代码大型语言模型（LLMCs），这些模型在自动且高效生成代码摘要方面表现出色。然而，现有方法通常仅专注于为给定代码生成单一的高质量摘要，忽视了生成摘要可能不充分且需要替代选项的情况。本文提出了一种名为变分前缀调优（VPT）的新方法，该方法显著提升了预训练模型生成多样化且准确摘要集合的能力，使用户能够为特定代码选择最合适的摘要。我们的方法通过将条件变分自编码器（CVAE）框架作为模块化组件集成到预训练模型中，成功建模了目标摘要的分布，并通过采样连续嵌入作为前缀，引导解码过程中生成多样化输出。值得注意的是，我们采用了参数高效的构建方式，避免了昂贵的模型重新训练，尤其在使用LLMCs时效果显著。此外，我们引入了一种双准则重排序方法，从生成的摘要中精选出最优子集，确保提供给用户的选项在多样性和准确性之间取得平衡。我们通过广泛使用的数据集和当前最先进的预训练代码摘要模型进行了详尽的实验评估，充分证明了我们方法的有效性和其在不同模型上的出色适应性。

> Recent advancements in source code summarization have leveraged transformer-based pre-trained models, including Large Language Models of Code (LLMCs), to automate and improve the generation of code summaries. However, existing methods often focus on generating a single high-quality summary for a given source code, neglecting scenarios where the generated summary might be inadequate and alternative options are needed. In this paper, we introduce Variational Prefix Tuning (VPT), a novel approach that enhances pre-trained models' ability to generate diverse yet accurate sets of summaries, allowing the user to choose the most suitable one for the given source code. Our method integrates a Conditional Variational Autoencoder (CVAE) framework as a modular component into pre-trained models, enabling us to model the distribution of observed target summaries and sample continuous embeddings to be used as prefixes to steer the generation of diverse outputs during decoding. Importantly, we construct our method in a parameter-efficient manner, eliminating the need for expensive model retraining, especially when using LLMCs. Furthermore, we employ a bi-criteria reranking method to select a subset of generated summaries, optimizing both the diversity and the accuracy of the options presented to users. We present extensive experimental evaluations using widely used datasets and current state-of-the-art pre-trained code summarization models to demonstrate the effectiveness of our approach and its adaptability across models.

[Arxiv](https://arxiv.org/abs/2505.09062)