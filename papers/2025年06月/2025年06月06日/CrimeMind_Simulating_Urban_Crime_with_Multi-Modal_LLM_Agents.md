# # CrimeMind：利用多模态大语言模型智能体模拟城市犯罪

发布时间：2025年06月06日

`Agent` `城市安全` `公共政策`

> CrimeMind: Simulating Urban Crime with Multi-Modal LLM Agents

# 摘要

> 城市犯罪建模是一项既重要又具挑战性的任务，需要深入理解城市环境中隐藏的视觉、社会和文化线索。此前的研究主要集中在基于规则的智能体建模（ABM）和深度学习方法上。ABM虽然能解释内部机制，但预测精度有限；而深度学习方法在预测上表现较好，却缺乏可解释性且需要大量数据支持。此外，这两种方法都难以适应环境的变化。我们利用大型语言模型（LLMs）的能力，提出了CrimeMind——一个基于LLM的新型ABM框架，旨在多模态城市背景下模拟城市犯罪。我们的设计亮点在于将日常活动理论（RAT）融入CrimeMind的智能体工作流程，使其能够处理丰富的多模态城市特征并推理犯罪行为。然而，RAT要求LLM智能体在评估监护责任时推断出评估环境安全的微妙线索，这对LLMs来说是一项挑战。为了解决这一问题，我们收集了一个小规模的人工标注数据集，并通过一种无训练的文本梯度方法将CrimeMind的感知与人类判断对齐。在四个美国主要城市的实验中，CrimeMind在犯罪热点预测和空间分布准确性方面表现优异，比最强的基线提高了高达24%。此外，我们进行了外部事件和政策干预的反事实模拟，成功捕捉到了预期的犯罪模式变化，展示了其反映反事实场景的能力。总体而言，CrimeMind不仅能够精细建模个体行为，还能有效评估现实世界中的干预措施。

> Modeling urban crime is an important yet challenging task that requires understanding the subtle visual, social, and cultural cues embedded in urban environments. Previous work has predominantly focused on rule-based agent-based modeling (ABM) and deep learning methods. ABMs offer interpretability of internal mechanisms but exhibit limited predictive accuracy.In contrast, deep learning methods are often effective in prediction but are less interpretable and require extensive training data. Moreover, both lines of work lack the cognitive flexibility to adapt to changing environments. Leveraging the capabilities of large language models (LLMs), we propose CrimeMind, a novel LLM-driven ABM framework for simulating urban crime within a multi-modal urban context.A key innovation of our design is the integration of the Routine Activity Theory (RAT) into the agentic workflow of CrimeMind, enabling it to process rich multi-modal urban features and reason about criminal behavior.However, RAT requires LLM agents to infer subtle cues in evaluating environmental safety as part of assessing guardianship, which can be challenging for LLMs. To address this, we collect a small-scale human-annotated dataset and align CrimeMind's perception with human judgment via a training-free textual gradient method.Experiments across four major U.S. cities demonstrate that CrimeMind outperforms both traditional ABMs and deep learning baselines in crime hotspot prediction and spatial distribution accuracy, achieving up to a 24% improvement over the strongest baseline.Furthermore, we conduct counterfactual simulations of external incidents and policy interventions and it successfully captures the expected changes in crime patterns, demonstrating its ability to reflect counterfactual scenarios.Overall, CrimeMind enables fine-grained modeling of individual behaviors and facilitates evaluation of real-world interventions.

[Arxiv](https://arxiv.org/abs/2506.05981)