# ModuLM：模块化与多模态分子关系学习的实现，借助大型语言模型

发布时间：2025年06月01日

`LLM应用` `药物研发`

> ModuLM: Enabling Modular and Multimodal Molecular Relational Learning with Large Language Models

# 摘要

> 分子关系学习（MRL）旨在理解分子对之间的相互作用，在推动生化研究方面发挥着关键作用。随着大型语言模型（LLMs）的 recent development，越来越多的研究探索了将MRL与LLMs相结合，并取得了令人鼓舞的结果。然而，随着多样化的LLMs和分子结构编码器的日益增多，模型空间得到了显著扩展，这给基准测试带来了重大挑战。目前，还没有一个LLM框架能够同时支持灵活的分子输入格式和动态的架构切换。为了解决这些挑战，减少冗余编码，并确保公平的模型比较，我们提出了ModuLM，这是一个旨在支持灵活的基于LLM的模型构建和多样化分子表示的框架。ModuLM提供了一套丰富的模块化组件，包括8种2D分子图编码器、11种3D分子构象编码器、7种交互层以及7种主流的LLM主干。得益于其高度灵活的模型组装机制，ModuLM能够动态构建超过50,000种不同的模型配置。此外，我们提供了全面的结果，以证明ModuLM在支持基于LLM的MRL任务中的有效性。

> Molecular Relational Learning (MRL) aims to understand interactions between molecular pairs, playing a critical role in advancing biochemical research. With the recent development of large language models (LLMs), a growing number of studies have explored the integration of MRL with LLMs and achieved promising results. However, the increasing availability of diverse LLMs and molecular structure encoders has significantly expanded the model space, presenting major challenges for benchmarking. Currently, there is no LLM framework that supports both flexible molecular input formats and dynamic architectural switching. To address these challenges, reduce redundant coding, and ensure fair model comparison, we propose ModuLM, a framework designed to support flexible LLM-based model construction and diverse molecular representations. ModuLM provides a rich suite of modular components, including 8 types of 2D molecular graph encoders, 11 types of 3D molecular conformation encoders, 7 types of interaction layers, and 7 mainstream LLM backbones. Owing to its highly flexible model assembly mechanism, ModuLM enables the dynamic construction of over 50,000 distinct model configurations. In addition, we provide comprehensive results to demonstrate the effectiveness of ModuLM in supporting LLM-based MRL tasks.

[Arxiv](https://arxiv.org/abs/2506.00880)