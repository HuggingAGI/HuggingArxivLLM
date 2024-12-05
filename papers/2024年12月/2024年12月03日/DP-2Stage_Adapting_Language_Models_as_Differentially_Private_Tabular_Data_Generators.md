# DP-2Stage：把语言模型改造成具有差异隐私的表格数据生成器

发布时间：2024年12月03日

`LLM应用` `机器学习` `数据隐私`

> DP-2Stage: Adapting Language Models as Differentially Private Tabular Data Generators

# 摘要

> 在差分隐私（DP）保护下生成表格数据，虽能确保理论上的隐私保障，却给机器学习模型的训练带来难题，主要原因在于需在嘈杂的监督信号下捕捉复杂结构。近来，预训练的大型语言模型（LLMs），哪怕是像 GPT-2 那种规模的，在合成表格数据方面展现出巨大潜力。然而，它们在 DP 约束下的应用大多尚未被探索。在本研究中，我们通过将 DP 技术用于合成表格数据的生成来填补这一空白。我们发现，用 DP 微调时，LLMs 在生成连贯文本上有困难，因为隐私预算低效地分配给了非隐私元素，比如表结构。为克服此问题，我们提出了\ours，这是一个用于差分隐私表格数据生成的两阶段微调框架。第一阶段是在伪数据集上进行非隐私微调，接着在私有数据集上进行 DP 微调。我们的实证结果表明，与在 DP 环境中直接微调的 LLMs 相比，此方法在各种设置和指标上均提升了性能。我们在 https://github.com/tejuafonja/DP-2Stage 发布了代码和相关设置。

> Generating tabular data under differential privacy (DP) protection ensures theoretical privacy guarantees but poses challenges for training machine learning models, primarily due to the need to capture complex structures under noisy supervision signals. Recently, pre-trained Large Language Models (LLMs) -- even those at the scale of GPT-2 -- have demonstrated great potential in synthesizing tabular data. However, their applications under DP constraints remain largely unexplored. In this work, we address this gap by applying DP techniques to the generation of synthetic tabular data. Our findings shows that LLMs face difficulties in generating coherent text when fine-tuned with DP, as privacy budgets are inefficiently allocated to non-private elements like table structures. To overcome this, we propose \ours, a two-stage fine-tuning framework for differentially private tabular data generation. The first stage involves non-private fine-tuning on a pseudo dataset, followed by DP fine-tuning on a private dataset. Our empirical results show that this approach improves performance across various settings and metrics compared to directly fine-tuned LLMs in DP contexts. We release our code and setup at https://github.com/tejuafonja/DP-2Stage.

[Arxiv](https://arxiv.org/abs/2412.02467)