# 重新审视代码智能中数据污染的影响

发布时间：2025年06月03日

`LLM应用` `软件工程`

> Rethinking the effects of data contamination in Code Intelligence

# 摘要

> 近年来，代码智能在自动化软件工程领域的重要性日益凸显。与此同时，预训练语言模型（PLMs）和大型语言模型（LLMs）的广泛应用引发了人们对数据污染及其对模型性能评估潜在影响的担忧。本文提出了一项系统性实证研究，深入探究代码智能任务中的细粒度数据污染问题。

研究涵盖多样化的代表性模型，包括RoBERTa、GPT-2等PLMs，以及LLaMA和StarCoder等LLMs，涉及代码翻译、生成和摘要三大核心任务。我们根据代码智能实践将污染场景划分为输入污染、输出污染、无配对污染和配对污染四种类型，并构建相应实验组和对照组展开深入探索。

实验结果揭示，在PLMs的预训练、微调和推理范式下，即使故意注入配对污染也不会显著高估性能。但直接推理或小规模微调则会揭示污染效应。相比之下，采用预训练和推理范式的LLMs对配对污染尤为敏感。除此之外，其他污染场景对PLMs和LLMs均无显著影响。我们的研究结果挑战了数据污染必然导致性能高估的传统认知，为代码智能模型的评估和部署提供了全新视角。


> In recent years, code intelligence has gained increasing importance in the field of automated software engineering. Meanwhile, the widespread adoption of Pretrained Language Models (PLMs) and Large Language Models (LLMs) has raised concerns regarding data contamination and its potential impact on model performance evaluation. This paper presents a systematic empirical study to investigate the fine-grained data contamination on code intelligence tasks. Our study involves diverse representative PLMs, namely RoBERTa and GPT-2, and LLMs, namely LLaMA and StarCoder, covering three major tasks: code translation, code generation, and code summarization. We categorize contamination scenarios into four types according to the code intelligence practice, namely input-only, output-only, unpaired, and paired contamination settings, and construct corresponding experimental and control groups for exploration.
  Experimental results show that, under the pre-training, fine-tuning, and inference paradigm adopted by PLMs, even deliberately injecting paired contamination does not lead to significant performance overestimation. But direct inference or small-scale fine-tuning uncovers the contamination effects. In contrast, LLMs with pre-training and inference paradigm are significantly affected by the paired contamination. Apart from the above, other contamination scenarios have no impact on both PLMs and LLMs. Our findings challenge the conventional belief that contamination inevitably leads to performance overestimation, providing new insights into the evaluation and deployment of code intelligence models.

[Arxiv](https://arxiv.org/abs/2506.02791)