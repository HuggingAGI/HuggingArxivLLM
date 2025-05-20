# # FRAbench 和 GenEval：实现跨任务与跨模态的细粒度评估扩展

发布时间：2025年05月19日

`LLM应用` `多模态`

> FRAbench and GenEval: Scaling Fine-Grained Aspect Evaluation across Tasks, Modalities

# 摘要

> 评估大型语言模型（LLMs）的开放性输出已成为瓶颈，随着模型能力、任务多样性和模态覆盖的迅速扩展。现有的“LLM作为评估者”方法通常在几个特定任务、方面或模态上表现狭窄，且容易出现一致性低的问题。本文认为，明确、细致的方面规范是实现自动化评估的通用性和客观性的关键。

为此，我们引入了一个涵盖112个方面的层次化评估维度分类法，该分类法统一了四个代表性设置下的评估——自然语言生成、图像理解、图像生成以及交织文本与图像生成。基于此分类法，我们创建了FRAbench基准，包含60.4万个成对样本，这些样本带有32.5万个方面级别的标签，这些标签来自人工标注和LLM标注的结合。FRAbench提供了首个大规模、多模态的资源，用于训练和元评估细致的LMM评估者。

借助FRAbench，我们开发了GenEval，一个在任务和模态间具有通用性的细致评估器。实验表明，GenEval（i）与GPT-4o和专家标注者达成高度一致，（ii）能够稳健地迁移到未见过的任务和模态，（iii）揭示了当前LMM在评估方面的系统性弱点。

> Evaluating the open-ended outputs of large language models (LLMs) has become a bottleneck as model capabilities, task diversity, and modality coverage rapidly expand. Existing "LLM-as-a-Judge" evaluators are typically narrow in a few tasks, aspects, or modalities, and easily suffer from low consistency. In this paper, we argue that explicit, fine-grained aspect specification is the key to both generalizability and objectivity in automated evaluation. To do so, we introduce a hierarchical aspect taxonomy spanning 112 aspects that unifies evaluation across four representative settings - Natural Language Generation, Image Understanding, Image Generation, and Interleaved Text-and-Image Generation. Building on this taxonomy, we create FRAbench, a benchmark comprising 60.4k pairwise samples with 325k aspect-level labels obtained from a combination of human and LLM annotations. FRAbench provides the first large-scale, multi-modal resource for training and meta-evaluating fine-grained LMM judges. Leveraging FRAbench, we develop GenEval, a fine-grained evaluator generalizable across tasks and modalities. Experiments show that GenEval (i) attains high agreement with GPT-4o and expert annotators, (ii) transfers robustly to unseen tasks and modalities, and (iii) reveals systematic weaknesses of current LMMs on evaluation.

[Arxiv](https://arxiv.org/abs/2505.12795)