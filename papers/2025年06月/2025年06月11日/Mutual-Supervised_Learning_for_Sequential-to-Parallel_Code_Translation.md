# # **摘要**  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月11日

`其他` `高性能计算` `软件工程`

> Mutual-Supervised Learning for Sequential-to-Parallel Code Translation

# 摘要

> GPU驱动的高性能计算（HPC）推动了CUDA等并行编程模型的广泛应用。然而，面对并行编程的复杂性，自动化串行转并行方法的需求日益迫切。然而，数据稀缺性为机器学习驱动的代码翻译带来了严峻挑战。尽管近期的反向翻译方法有所突破，但翻译代码的功能等价性问题仍未解决。本文提出了一种创新的互监督学习（MSL）框架，专为解决串行转并行代码翻译中的功能等价性难题而设计。该框架由翻译器和测试器两大模块构成，通过协同验证与协同进化的迭代循环，双方互相生成数据并共同提升。测试器通过生成单元测试验证并筛选功能等价的翻译代码，从而推动翻译器的进化；同时，翻译器生成的代码作为增强输入，助力测试器的优化。实验结果表明，MuSL显著提升了基础模型的性能：应用于Qwen2.5-Coder时，Pass@1指标提升了28.91%，测试器性能提升了68.90%，并在BLEU和CodeBLEU得分上分别以1.56和6.92分超越了之前的最先进方法CodeRosetta，同时性能可与DeepSeek-R1和GPT-4.1相媲美。我们的代码已在GitHub上开源，地址为https://github.com/kcxain/musl。

> The rise of GPU-based high-performance computing (HPC) has driven the widespread adoption of parallel programming models such as CUDA. Yet, the inherent complexity of parallel programming creates a demand for the automated sequential-to-parallel approaches. However, data scarcity poses a significant challenge for machine learning-based sequential-to-parallel code translation. Although recent back-translation methods show promise, they still fail to ensure functional equivalence in the translated code. In this paper, we propose a novel Mutual-Supervised Learning (MSL) framework for sequential-to-parallel code translation to address the functional equivalence issue. MSL consists of two models, a Translator and a Tester. Through an iterative loop consisting of Co-verify and Co-evolve steps, the Translator and the Tester mutually generate data for each other and improve collectively. The Tester generates unit tests to verify and filter functionally equivalent translated code, thereby evolving the Translator, while the Translator generates translated code as augmented input to evolve the Tester. Experimental results demonstrate that MuSL significantly enhances the performance of the base model: when applied to Qwen2.5-Coder, it not only improves Pass@1 by up to 28.91% and boosts Tester performance by 68.90%, but also outperforms the previous state-of-the-art method CodeRosetta by 1.56 and 6.92 in BLEU and CodeBLEU scores, while achieving performance comparable to DeepSeek-R1 and GPT-4.1. Our code is available at https://github.com/kcxain/musl.

[Arxiv](https://arxiv.org/abs/2506.11153)