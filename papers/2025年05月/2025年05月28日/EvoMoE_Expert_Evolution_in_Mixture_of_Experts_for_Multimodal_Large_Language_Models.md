# EvoMoE：专家进化机制在混合专家模型中的应用，针对多模态大语言模型

发布时间：2025年05月28日

`LLM理论

摘要中讨论了专家混合模型（MoE）在大型语言模型中的应用，并提出了一种新的框架EvoMoE，以解决现有方法中的专家同质化和路由僵化问题。该研究主要关注模型架构和训练策略的优化，属于理论层面的探讨，因此归类为LLM理论。` `人工智能` `模型优化`

> EvoMoE: Expert Evolution in Mixture of Experts for Multimodal Large Language Models

# 摘要

> 近期研究表明，专家混合模型（MoE）方法能显著提升大型语言模型（LLMs）的能力，并在下游任务中表现更优。基于此，多模态大型语言模型（MLLMs）越来越多地采用MoE技术。然而，现有方法面临两大挑战：专家同质化和路由僵化。专家同质化源于简单复制LLMs的FFN参数初始化MoE专家，导致专家功能趋同，削弱了MoE架构的多样化优势。路由僵化则因静态线性路由选择器无法区分视觉与文本令牌，导致图像与文本的专家分布相似。为解决这些问题，我们提出EvoMoE，一个创新的MoE微调框架。EvoMoE采用精心设计的专家初始化策略，通过专家进化从单个可训练专家中逐步演化出多个稳健专家，有效缓解专家同质化问题。此外，我们引入动态令牌感知路由器（DTR），一种新型路由机制，根据输入令牌的模态和内在值将其分配到合适专家。动态路由通过超网络实现，为每个令牌动态生成定制路由权重。大量实验表明，EvoMoE在MME、MMBench、TextVQA和POPE等多种多模态基准测试中显著优于其他稀疏MLLMs。我们的结果凸显了EvoMoE通过解决专家同质化和路由僵化问题，有效提升MLLMs性能的优势。

> Recent advancements have shown that the Mixture of Experts (MoE) approach significantly enhances the capacity of large language models (LLMs) and improves performance on downstream tasks. Building on these promising results, multi-modal large language models (MLLMs) have increasingly adopted MoE techniques. However, existing multi-modal MoE tuning methods typically face two key challenges: expert uniformity and router rigidity. Expert uniformity occurs because MoE experts are often initialized by simply replicating the FFN parameters from LLMs, leading to homogenized expert functions and weakening the intended diversification of the MoE architecture. Meanwhile, router rigidity stems from the prevalent use of static linear routers for expert selection, which fail to distinguish between visual and textual tokens, resulting in similar expert distributions for image and text. To address these limitations, we propose EvoMoE, an innovative MoE tuning framework. EvoMoE introduces a meticulously designed expert initialization strategy that progressively evolves multiple robust experts from a single trainable expert, a process termed expert evolution that specifically targets severe expert homogenization. Furthermore, we introduce the Dynamic Token-aware Router (DTR), a novel routing mechanism that allocates input tokens to appropriate experts based on their modality and intrinsic token values. This dynamic routing is facilitated by hypernetworks, which dynamically generate routing weights tailored for each individual token. Extensive experiments demonstrate that EvoMoE significantly outperforms other sparse MLLMs across a variety of multi-modal benchmarks, including MME, MMBench, TextVQA, and POPE. Our results highlight the effectiveness of EvoMoE in enhancing the performance of MLLMs by addressing the critical issues of expert uniformity and router rigidity.

[Arxiv](https://arxiv.org/abs/2505.23830)