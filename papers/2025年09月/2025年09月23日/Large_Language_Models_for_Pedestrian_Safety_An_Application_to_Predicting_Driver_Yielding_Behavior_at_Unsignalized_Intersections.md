# 大型语言模型助力行人安全：无信号交叉口驾驶员让行行为预测应用

发布时间：2025年09月23日

`LLM应用` `交通运输`

> Large Language Models for Pedestrian Safety: An Application to Predicting Driver Yielding Behavior at Unsignalized Intersections

# 摘要

> 行人安全是城市出行的核心议题，其保障效果很大程度上取决于人行横道处行人决策与驾驶员让行行为的交互作用。要对交叉口的驾驶员-行人交互进行建模，就必须精准捕捉这些行为的复杂性。传统机器学习模型依赖固定的特征表示，且可解释性有限，因此难以捕捉这些多因素交互中所需的细微且依赖上下文的推理过程。相比之下，大型语言模型（LLMs）擅长从异构交通数据中提取模式，从而实现对驾驶员-行人交互的精准建模。为此，本文提出一种新颖的提示设计，整合领域专业知识、结构化推理和少样本提示，以此利用多模态LLMs对驾驶员让行行为进行可解释且上下文感知的推理，作为建模行人-驾驶员交互的示例应用。我们将最先进的LLMs与传统分类器进行基准测试，结果显示GPT-4o的准确率和召回率始终最高，而Deepseek-V3则在精确率上表现突出。这些发现揭示了模型性能与计算效率之间的关键权衡，为LLMs在实际行人安全系统中的部署提供了实用指导。

> Pedestrian safety is a critical component of urban mobility and is strongly influenced by the interactions between pedestrian decision-making and driver yielding behavior at crosswalks. Modeling driver--pedestrian interactions at intersections requires accurately capturing the complexity of these behaviors. Traditional machine learning models often struggle to capture the nuanced and context-dependent reasoning required for these multifactorial interactions, due to their reliance on fixed feature representations and limited interpretability. In contrast, large language models (LLMs) are suited for extracting patterns from heterogeneous traffic data, enabling accurate modeling of driver-pedestrian interactions. Therefore, this paper leverages multimodal LLMs through a novel prompt design that incorporates domain-specific knowledge, structured reasoning, and few-shot prompting, enabling interpretable and context-aware inference of driver yielding behavior, as an example application of modeling pedestrian--driver interaction. We benchmarked state-of-the-art LLMs against traditional classifiers, finding that GPT-4o consistently achieves the highest accuracy and recall, while Deepseek-V3 excels in precision. These findings highlight the critical trade-offs between model performance and computational efficiency, offering practical guidance for deploying LLMs in real-world pedestrian safety systems.

[Arxiv](https://arxiv.org/abs/2509.19657)