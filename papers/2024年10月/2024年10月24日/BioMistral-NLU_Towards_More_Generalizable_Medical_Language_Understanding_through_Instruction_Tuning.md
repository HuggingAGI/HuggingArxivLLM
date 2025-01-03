# BioMistral-NLU：通过指令微调迈向更通用的医学语言理解

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何通过指令微调来提升大型语言模型（LLMs）在医学自然语言理解（NLU）任务中的表现。具体来说，作者提出了一个统一的提示格式，构建了一个指令微调数据集，并开发了一个新的模型BioMistral-NLU。这些工作都是围绕如何将LLMs应用于特定领域（医学NLU）的任务，因此属于LLM应用的范畴。` `自然语言理解`

> BioMistral-NLU: Towards More Generalizable Medical Language Understanding through Instruction Tuning

# 摘要

> 像ChatGPT这样的大型语言模型（LLMs）经过大量多样化指令语料库的微调，能够泛化到新任务。然而，这些经过指令微调的LLMs在需要领域知识、细粒度文本理解和结构化数据提取的专门医学自然语言理解（NLU）任务中表现不佳。为此，我们：（1）提出了一个统一的提示格式，涵盖7个重要NLU任务，通过跨度提取和多选问答（QA）实现，（2）利用多样化的开源医学NLU语料库，构建了指令微调数据集MNLU-Instruct，（3）通过在MNLU-Instruct上微调BioMistral，开发了可泛化的医学NLU模型BioMistral-NLU。我们在零-shot设置下评估了BioMistral-NLU，覆盖了来自BLUE和BLURB两个广泛采用的医学NLU基准测试的6个重要任务。实验表明，BioMistral-NLU优于原始BioMistral及专有LLMs——ChatGPT和GPT-4。我们的数据集无关提示策略和跨多样化NLU任务的指令微调步骤，显著提升了LLMs在医学NLU任务中的泛化能力。消融实验进一步证明，即使在训练实例总数不变的情况下，对更多样化的任务进行指令微调也能增强零-shot泛化能力。

> Large language models (LLMs) such as ChatGPT are fine-tuned on large and diverse instruction-following corpora, and can generalize to new tasks. However, those instruction-tuned LLMs often perform poorly in specialized medical natural language understanding (NLU) tasks that require domain knowledge, granular text comprehension, and structured data extraction. To bridge the gap, we: (1) propose a unified prompting format for 7 important NLU tasks, % through span extraction and multi-choice question-answering (QA), (2) curate an instruction-tuning dataset, MNLU-Instruct, utilizing diverse existing open-source medical NLU corpora, and (3) develop BioMistral-NLU, a generalizable medical NLU model, through fine-tuning BioMistral on MNLU-Instruct. We evaluate BioMistral-NLU in a zero-shot setting, across 6 important NLU tasks, from two widely adopted medical NLU benchmarks: Biomedical Language Understanding Evaluation (BLUE) and Biomedical Language Understanding and Reasoning Benchmark (BLURB). Our experiments show that our BioMistral-NLU outperforms the original BioMistral, as well as the proprietary LLMs - ChatGPT and GPT-4. Our dataset-agnostic prompting strategy and instruction tuning step over diverse NLU tasks enhance LLMs' generalizability across diverse medical NLU tasks. Our ablation experiments show that instruction-tuning on a wider variety of tasks, even when the total number of training instances remains constant, enhances downstream zero-shot generalization.

[Arxiv](https://arxiv.org/abs/2410.18955)