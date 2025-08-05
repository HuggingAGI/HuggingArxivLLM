# 多模态医学推理的简单基线方案：MedVLThinker

发布时间：2025年08月04日

`LLM应用` `问答系统`

> MedVLThinker: Simple Baselines for Multimodal Medical Reasoning

# 摘要

> 大规模推理模型（LRMs）通过链式思维推理能力，使模型能够实现``先思考后响应''，从而开启了全新的AI范式。然而，构建以推理为核心的医疗领域LMM模型缺乏开放且可复现的构建方案，这阻碍了整个社区的研究、分析和对比工作。本文中，我们推出了MedVLThinker，一套简单而强大的基线工具。我们的完全开放方案包含：(1) 对纯文本和图文结合的医学数据进行系统化整理，根据推理难度的不同层次进行筛选；(2) 两种训练范式：基于蒸馏推理轨迹的有监督微调（SFT），以及基于最终答案正确性的可验证奖励强化学习（RLVR）。在Qwen2.5-VL模型系列（3B、7B）和六个医学问答基准数据集上的广泛实验表明，RLVR在性能上始终显著优于SFT。此外，在RLVR框架下，一个关键且反直觉的发现是：基于我们整理的纯文本推理数据进行训练，能够带来比基于多模态图文数据训练更显著的性能提升。我们使用RLVR方案在纯文本数据上训练的最佳开源7B模型，在现有的公开视觉问答基准测试中创下了新纪录，超越了所有之前的开源医疗领域LMM模型。进一步将模型扩展至32B规模，其性能可与专有版GPT-4相媲美。我们公开了所有整理的数据、模型和代码，为未来多模态医疗推理研究提供了强大且开放的研究基础。


> Large Reasoning Models (LRMs) have introduced a new paradigm in AI by enabling models to ``think before responding" via chain-of-thought reasoning. However, the absence of open and reproducible recipes for building reasoning-centric medical LMMs hinders community-wide research, analysis, and comparison. In this paper, we present MedVLThinker, a suite of simple yet strong baselines. Our fully open recipe consists of: (1) systematic data curation for both text-only and image-text medical data, filtered according to varying levels of reasoning difficulty, and (2) two training paradigms: Supervised Fine-Tuning (SFT) on distilled reasoning traces and Reinforcement Learning with Verifiable Rewards (RLVR) based on final answer correctness. Across extensive experiments on the Qwen2.5-VL model family (3B, 7B) and six medical QA benchmarks, we find that RLVR consistently and significantly outperforms SFT. Additionally, under the RLVR framework, a key, counter-intuitive finding is that training on our curated text-only reasoning data provides a more substantial performance boost than training on multimodal image-text data. Our best open 7B model, trained using the RLVR recipe on text-only data, establishes a new state-of-the-art on existing public VQA benchmarks, surpassing all previous open-source medical LMMs. Furthermore, scaling our model to 32B achieves performance on par with the proprietary GPT-4o. We release all curated data, models, and code to provide the community with a strong, open foundation for future research in multimodal medical reasoning.

[Arxiv](https://arxiv.org/abs/2508.02669)