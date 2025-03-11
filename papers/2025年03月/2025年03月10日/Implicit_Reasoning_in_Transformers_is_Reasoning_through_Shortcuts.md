# Transformers中的隐式推理：本质上是走捷径。

发布时间：2025年03月10日

`LLM理论`

> Implicit Reasoning in Transformers is Reasoning through Shortcuts

# 摘要

> 测试时间计算正成为提升语言模型复杂多步推理能力的新范式，OpenAI 的 o1 和 o3，以及 DeepSeek 的 R1 的成功印证了这一点。与显式的测试时间推理相比，隐式推理在推理效率上更胜一筹，生成标记更少。然而，为何高级推理能力未能在隐式推理中显现？本研究通过在精选的多步数学推理数据集上从零开始训练 GPT-2，并进行分析实验，探究语言模型在多步任务中的隐式推理机制。研究发现：1) 语言模型可通过隐式推理实现逐步推理，在同领域和跨领域测试中均表现优异。但这种能力仅在固定模式数据上训练时才会显现。2) 相反，非固定模式数据训练产生的隐式推理能力往往过度拟合特定模式，缺乏泛化能力。这一局限性甚至在最先进的大型语言模型中也有所体现。这表明，语言模型的隐式推理能力源于捷径学习，使其在相似模式任务中表现突出，但泛化能力不足。

> Test-time compute is emerging as a new paradigm for enhancing language models' complex multi-step reasoning capabilities, as demonstrated by the success of OpenAI's o1 and o3, as well as DeepSeek's R1. Compared to explicit reasoning in test-time compute, implicit reasoning is more inference-efficient, requiring fewer generated tokens. However, why does the advanced reasoning capability fail to emerge in the implicit reasoning style? In this work, we train GPT-2 from scratch on a curated multi-step mathematical reasoning dataset and conduct analytical experiments to investigate how language models perform implicit reasoning in multi-step tasks. Our findings reveal: 1) Language models can perform step-by-step reasoning and achieve high accuracy in both in-domain and out-of-domain tests via implicit reasoning. However, this capability only emerges when trained on fixed-pattern data. 2) Conversely, implicit reasoning abilities emerging from training on unfixed-pattern data tend to overfit a specific pattern and fail to generalize further. Notably, this limitation is also observed in state-of-the-art large language models. These findings suggest that language models acquire implicit reasoning through shortcut learning, enabling strong performance on tasks with similar patterns while lacking generalization.

[Arxiv](https://arxiv.org/abs/2503.07604)