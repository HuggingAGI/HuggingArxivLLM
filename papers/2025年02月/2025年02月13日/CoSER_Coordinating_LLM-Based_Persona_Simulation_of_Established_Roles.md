# CoSER: 协调基于LLM的既定角色模拟

发布时间：2025年02月13日

`LLM应用` `内容创作`

> CoSER: Coordinating LLM-Based Persona Simulation of Established Roles

# 摘要

> 角色扮演语言代理（RPLAs）作为大型语言模型（LLMs）的有前景的应用已经崭露头角。然而，模拟已建立角色对RPLAs来说是一项具有挑战性的任务，原因在于缺乏真实的角色数据集以及利用此类数据进行细致评估的方法。本文提出了一套名为CoSER的解决方案，包含高质量数据集、开放模型和评估协议，旨在提升RPLAs对已建立角色的模拟效果。CoSER数据集涵盖了771本著名书籍中的17,966个角色，不仅提供具有现实复杂性的真实对话，还包含对话设置、角色经历和内心想法等多种数据类型。我们借鉴表演方法，提出了一种基于给定情境的表演训练和评估方法，让LLMs能够依次在书中的场景中扮演多个角色。基于CoSER数据集，我们开发了CoSER 8B和CoSER 70B——两款基于LLaMA-3.1模型的先进开放角色扮演LLMs。大量实验表明，CoSER数据集在RPLA训练、评估和检索方面具有显著价值。此外，CoSER 70B在我们的评估和三个现有基准上的表现超越或达到了GPT-4o的水平，分别在InCharacter和LifeChoice基准上实现了75.80%和93.47%的准确率。

> Role-playing language agents (RPLAs) have emerged as promising applications of large language models (LLMs). However, simulating established characters presents a challenging task for RPLAs, due to the lack of authentic character datasets and nuanced evaluation methods using such data. In this paper, we present CoSER, a collection of a high-quality dataset, open models, and an evaluation protocol towards effective RPLAs of established characters. The CoSER dataset covers 17,966 characters from 771 renowned books. It provides authentic dialogues with real-world intricacies, as well as diverse data types such as conversation setups, character experiences and internal thoughts. Drawing from acting methodology, we introduce given-circumstance acting for training and evaluating role-playing LLMs, where LLMs sequentially portray multiple characters in book scenes. Using our dataset, we develop CoSER 8B and CoSER 70B, i.e., advanced open role-playing LLMs built on LLaMA-3.1 models. Extensive experiments demonstrate the value of the CoSER dataset for RPLA training, evaluation and retrieval. Moreover, CoSER 70B exhibits state-of-the-art performance surpassing or matching GPT-4o on our evaluation and three existing benchmarks, i.e., achieving 75.80% and 93.47% accuracy on the InCharacter and LifeChoice benchmarks respectively.

[Arxiv](https://arxiv.org/abs/2502.09082)