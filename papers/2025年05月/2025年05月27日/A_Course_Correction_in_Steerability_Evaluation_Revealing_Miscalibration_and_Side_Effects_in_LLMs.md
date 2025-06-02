# # LLMs可控性评估的一次航向调整：揭示出误校准与副作用

发布时间：2025年05月27日

`LLM理论` `文本生成`

> A Course Correction in Steerability Evaluation: Revealing Miscalibration and Side Effects in LLMs

# 摘要

> 尽管大型语言模型（LLMs）在推理和指令遵循基准上取得了进展，但它们是否能可靠地生成与用户目标一致的输出仍不清楚。我们将其称为“可引导性”。当前，大量用于修改LLM行为的方法使得我们难以判断LLMs是否已具备可引导性，或者是否需要进一步干预。具体而言，LLMs可能面临三大挑战：(i) 覆盖不足，即罕见用户目标未能得到充分表达；(ii) 校准错误，即模型过度满足请求；以及(iii) 副作用，即对文本某一维度的修改会无意中影响其他维度。为系统性评估这些问题，我们提出了一种基于多维目标空间的框架，将用户目标和LLM输出建模为与文本属性（如阅读难度）相对应的向量。在文本重写任务中应用该框架，我们发现当前LLMs在可引导性方面存在明显不足，尤其是副作用问题持续存在。尽管提示工程、最佳-of-$N$采样和强化学习微调等干预措施在提升可引导性方面各有成效，但副作用问题依然突出。我们的研究结果表明，即使是强大的LLMs也难以完全实现可引导性，现有的对齐策略可能不足以应对这一挑战。我们已开源了我们的可引导性评估框架，地址为https://github.com/MLD3/steerability。

> Despite advances in large language models (LLMs) on reasoning and instruction-following benchmarks, it remains unclear whether they can reliably produce outputs aligned with a broad variety of user goals, a concept we refer to as steerability. The abundance of methods proposed to modify LLM behavior makes it unclear whether current LLMs are already steerable, or require further intervention. In particular, LLMs may exhibit (i) poor coverage, where rare user goals are underrepresented; (ii) miscalibration, where models overshoot requests; and (iii) side effects, where changes to one dimension of text inadvertently affect others. To systematically evaluate these failures, we introduce a framework based on a multi-dimensional goal space that models user goals and LLM outputs as vectors with dimensions corresponding to text attributes (e.g., reading difficulty). Applied to a text-rewriting task, we find that current LLMs struggle with steerability, as side effects are persistent. Interventions to improve steerability, such as prompt engineering, best-of-$N$ sampling, and reinforcement learning fine-tuning, have varying effectiveness, yet side effects remain problematic. Our findings suggest that even strong LLMs struggle with steerability, and existing alignment strategies may be insufficient. We open-source our steerability evaluation framework at https://github.com/MLD3/steerability.

[Arxiv](https://arxiv.org/abs/2505.23816)