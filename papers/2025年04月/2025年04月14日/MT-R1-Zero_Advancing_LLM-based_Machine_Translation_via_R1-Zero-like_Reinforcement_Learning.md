# MT-R1-Zero：利用R1-Zero风格的强化学习提升基于LLM的机器翻译能力

发布时间：2025年04月14日

`LLM应用

理由：这篇论文探讨了将大规模强化学习（RL）方法应用于机器翻译（MT）任务，以提升大型语言模型（LLMs）的推理能力。研究中提出了MT-R1-Zero框架，并通过实验证明了其在翻译质量上的显著提升。这属于将LLM应用于具体任务（机器翻译）的范畴，因此归类为LLM应用。` `机器翻译`

> MT-R1-Zero: Advancing LLM-based Machine Translation via R1-Zero-like Reinforcement Learning

# 摘要

> 大规模强化学习（RL）方法在提升大型语言模型（LLMs）的推理能力方面表现出色，尤其在数学和编码等具有可验证解决方案的任务中。然而，将其应用于机器翻译（MT）领域仍具挑战，因为MT输出格式灵活且难以通过明确规则自动评估。在本研究中，我们推出了MT-R1-Zero，这是首个无需监督微调或冷启动的开源R1-Zero RL框架在MT领域的应用。我们提出了一种规则与指标混合奖励机制，引导LLMs通过涌现推理能力提升翻译质量。在WMT 24英汉基准测试中，我们的MT-R1-Zero-3B-Mix模型表现出色，平均分超越TowerInstruct-7B-v0.2达1.26分。同时，MT-R1-Zero-7B-Mix模型在所有评估指标中取得了62.25的高平均分，与GPT-4o和Claude-3.5-Sonnet等先进专有模型持平，而MT-R1-Zero-7B-Sem变体则在语义指标上达到了最新水平。此外，我们的方法在分布外MT任务中展现了强大的泛化能力，为多语言和低资源环境提供了有力支持。通过对不同初始化和奖励指标下模型行为的深入分析，我们为理解R1-Zero范式在MT中的奖励设计、LLM适应性、训练动态及涌现推理模式提供了开创性见解。我们的代码可在https://github.com/fzp0424/MT-R1-Zero获取。

> Large-scale reinforcement learning (RL) methods have proven highly effective in enhancing the reasoning abilities of large language models (LLMs), particularly for tasks with verifiable solutions such as mathematics and coding. However, applying this idea to machine translation (MT), where outputs are flexibly formatted and difficult to automatically evaluate with explicit rules, remains underexplored. In this work, we introduce MT-R1-Zero, the first open-source adaptation of the R1-Zero RL framework for MT without supervised fine-tuning or cold-start. We propose a rule-metric mixed reward mechanism to guide LLMs towards improved translation quality via emergent reasoning. On the WMT 24 English-Chinese benchmark, our MT-R1-Zero-3B-Mix achieves competitive performance, surpassing TowerInstruct-7B-v0.2 by an average of 1.26 points. Meanwhile, our MT-R1-Zero-7B-Mix attains a high average score of 62.25 across all metrics, placing it on par with advanced proprietary models such as GPT-4o and Claude-3.5-Sonnet, while the MT-R1-Zero-7B-Sem variant achieves state-of-the-art scores on semantic metrics. Moreover, our work exhibits strong generalization capabilities on out-of-distribution MT tasks, robustly supporting multilingual and low-resource settings. Extensive analysis of model behavior across different initializations and reward metrics offers pioneering insight into the critical role of reward design, LLM adaptability, training dynamics, and emergent reasoning patterns within the R1-Zero paradigm for MT. Our code is available at https://github.com/fzp0424/MT-R1-Zero.

[Arxiv](https://arxiv.org/abs/2504.10160)