# 从LLM标注到LLM编排器：协调小型模型进行数据标注

发布时间：2025年06月19日

`LLM应用` `标注工具`

> From LLM-anation to LLM-orchestrator: Coordinating Small Models for Data Labeling

# 摘要

> 尽管近年来基于大型语言模型（LLMs）的标注范式取得了重大突破，但实际应用中仍面临两大核心瓶颈：大规模标注调用商用API成本高昂，且在细粒度语义理解场景中，LLMs的标注准确率甚至低于专用小型语言模型（SLMs）。为解决这些问题，我们提出了一种全新的多模型协作标注范式，并设计了完全自动化的标注框架AutoAnnotator。该框架分为两层：上层元控制器层利用LLMs的生成与推理能力，自动选择SLMs、生成标注代码并验证困难样本；下层任务专家层则通过多模型投票机制完成标注。此外，我们采用持续学习策略，将元控制器层二次审核的困难样本作为强化学习集，对SLMs进行分阶段微调，显著提升了其泛化能力。实验结果表明，AutoAnnotator在零样本、单样本、CoT和多数投票设置下均优于现有开源/API LLMs。与直接使用GPT-3.5-turbo相比，AutoAnnotator将标注成本降低了74.15%，同时准确率提升了6.21%。项目地址：https://github.com/Zhaiyuan-Ji/AutoAnnotator。

> Although the annotation paradigm based on Large Language Models (LLMs) has made significant breakthroughs in recent years, its actual deployment still has two core bottlenecks: first, the cost of calling commercial APIs in large-scale annotation is very expensive; second, in scenarios that require fine-grained semantic understanding, such as sentiment classification and toxicity classification, the annotation accuracy of LLMs is even lower than that of Small Language Models (SLMs) dedicated to this field. To address these problems, we propose a new paradigm of multi-model cooperative annotation and design a fully automatic annotation framework AutoAnnotator based on this. Specifically, AutoAnnotator consists of two layers. The upper-level meta-controller layer uses the generation and reasoning capabilities of LLMs to select SLMs for annotation, automatically generate annotation code and verify difficult samples; the lower-level task-specialist layer consists of multiple SLMs that perform annotation through multi-model voting. In addition, we use the difficult samples obtained by the secondary review of the meta-controller layer as the reinforcement learning set and fine-tune the SLMs in stages through a continual learning strategy, thereby improving the generalization of SLMs. Extensive experiments show that AutoAnnotator outperforms existing open-source/API LLMs in zero-shot, one-shot, CoT, and majority voting settings. Notably, AutoAnnotator reduces the annotation cost by 74.15% compared to directly annotating with GPT-3.5-turbo, while still improving the accuracy by 6.21%. Project page: https://github.com/Zhaiyuan-Ji/AutoAnnotator.

[Arxiv](https://arxiv.org/abs/2506.16393)