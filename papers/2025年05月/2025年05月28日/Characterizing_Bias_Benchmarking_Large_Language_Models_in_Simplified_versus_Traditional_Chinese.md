# 表征偏差：大型语言模型在简体与繁体中文环境中的基准测试

发布时间：2025年05月28日

`LLM应用`

> Characterizing Bias: Benchmarking Large Language Models in Simplified versus Traditional Chinese

# 摘要

> 尽管大型语言模型（LLMs）在简体中文和繁体中文中的能力已被研究，但当使用这两种中文变体进行提示时，LLMs是否会表现出差异性表现仍不明确。这种理解至关重要，因为LLM回答质量的差异可能通过忽视简体与繁体中文背后不同的文化背景，从而延续表达性伤害，并可能加剧LLM辅助决策在教育或招聘等领域的下游伤害。

为了调查潜在的LLM性能差异，我们设计了两个反映现实场景的基准任务：地区术语选择（提示LLM命名一个在大陆和台湾使用不同名称的物品）和地区姓名选择（提示LLM从简体和繁体中文姓名列表中选择聘用对象）。对于这两个任务，我们评估了11款领先的商业LLM服务和开源模型的性能，涵盖主要基于英语、简体中文或繁体中文训练的模型。

我们的分析表明，LLM回答中的偏见取决于任务和提示语言：虽然大多数LLMs在地区术语选择任务中倾向于简体中文回答，但令人意外的是，它们在地区姓名选择任务中更倾向于繁体中文姓名。我们发现，这些差异可能源于训练数据表示、书面字符偏好以及简体和繁体中文的分词差异。

这些发现强调了进一步分析LLM偏见的必要性；为此，我们提供了一个开源基准数据集，以促进未来LLM在中文变体中的可重复行为评估（https://github.com/brucelyu17/SC-TC-Bench）。

> While the capabilities of Large Language Models (LLMs) have been studied in both Simplified and Traditional Chinese, it is yet unclear whether LLMs exhibit differential performance when prompted in these two variants of written Chinese. This understanding is critical, as disparities in the quality of LLM responses can perpetuate representational harms by ignoring the different cultural contexts underlying Simplified versus Traditional Chinese, and can exacerbate downstream harms in LLM-facilitated decision-making in domains such as education or hiring. To investigate potential LLM performance disparities, we design two benchmark tasks that reflect real-world scenarios: regional term choice (prompting the LLM to name a described item which is referred to differently in Mainland China and Taiwan), and regional name choice (prompting the LLM to choose who to hire from a list of names in both Simplified and Traditional Chinese). For both tasks, we audit the performance of 11 leading commercial LLM services and open-sourced models -- spanning those primarily trained on English, Simplified Chinese, or Traditional Chinese. Our analyses indicate that biases in LLM responses are dependent on both the task and prompting language: while most LLMs disproportionately favored Simplified Chinese responses in the regional term choice task, they surprisingly favored Traditional Chinese names in the regional name choice task. We find that these disparities may arise from differences in training data representation, written character preferences, and tokenization of Simplified and Traditional Chinese. These findings highlight the need for further analysis of LLM biases; as such, we provide an open-sourced benchmark dataset to foster reproducible evaluations of future LLM behavior across Chinese language variants (https://github.com/brucelyu17/SC-TC-Bench).

[Arxiv](https://arxiv.org/abs/2505.22645)