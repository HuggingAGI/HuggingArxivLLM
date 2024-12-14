# 利用大型语言模型进行隐式情感分析的多任务学习：数据层面和任务层面的自动权重学习

发布时间：2024年12月12日

`LLM应用` `情感分析` `多任务学习`

> Multi-Task Learning with LLMs for Implicit Sentiment Analysis: Data-level and Task-level Automatic Weight Learning

# 摘要

> 隐式情感分析（ISA）因缺少显著的提示词而挑战重重。过往的方法受限于数据匮乏和推理能力有限，难以推断出潜在的意见。将多任务学习（MTL）与大型语言模型（LLMs）相融合，有望让不同规模的模型能够可靠地感知和识别 ISA 中的真实意见。然而，现有的 MTL 方法被两种不确定性所制约：一是数据级不确定性，源自 LLM 生成的上下文信息中的幻觉问题；二是任务级不确定性，源于模型处理上下文信息的能力各异。为应对这些不确定性，我们推出了 MT-ISA，这是一个新颖的 MTL 框架，借助自动 MTL 利用 LLMs 的生成和推理能力来强化 ISA。具体而言，MT-ISA 利用生成式 LLMs 构建辅助任务来补充情感元素，并结合自动 MTL 充分利用辅助数据。我们引入了数据级和任务级自动权重学习（AWL），它能动态识别关系，优先考虑更可靠的数据和关键任务，使不同规模的模型能依据自身推理能力自适应地学习细粒度权重。我们探究了数据级 AWL 的三种策略，同时为任务级 AWL 引入了同方差不确定性。大量实验表明，不同规模的模型在 MT-ISA 中达成了主要预测和辅助任务之间的最优平衡。这凸显了我们方法的有效性和适应性。

> Implicit sentiment analysis (ISA) presents significant challenges due to the absence of salient cue words. Previous methods have struggled with insufficient data and limited reasoning capabilities to infer underlying opinions. Integrating multi-task learning (MTL) with large language models (LLMs) offers the potential to enable models of varying sizes to reliably perceive and recognize genuine opinions in ISA. However, existing MTL approaches are constrained by two sources of uncertainty: data-level uncertainty, arising from hallucination problems in LLM-generated contextual information, and task-level uncertainty, stemming from the varying capacities of models to process contextual information. To handle these uncertainties, we introduce MT-ISA, a novel MTL framework that enhances ISA by leveraging the generation and reasoning capabilities of LLMs through automatic MTL. Specifically, MT-ISA constructs auxiliary tasks using generative LLMs to supplement sentiment elements and incorporates automatic MTL to fully exploit auxiliary data. We introduce data-level and task-level automatic weight learning (AWL), which dynamically identifies relationships and prioritizes more reliable data and critical tasks, enabling models of varying sizes to adaptively learn fine-grained weights based on their reasoning capabilities. We investigate three strategies for data-level AWL, while also introducing homoscedastic uncertainty for task-level AWL. Extensive experiments reveal that models of varying sizes achieve an optimal balance between primary prediction and auxiliary tasks in MT-ISA. This underscores the effectiveness and adaptability of our approach.

[Arxiv](https://arxiv.org/abs/2412.09046)