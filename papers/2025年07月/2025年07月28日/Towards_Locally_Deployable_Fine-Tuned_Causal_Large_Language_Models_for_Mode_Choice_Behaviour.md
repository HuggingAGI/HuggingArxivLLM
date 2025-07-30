# 面向模式选择行为的本地部署微调因果大型语言模型研究

发布时间：2025年07月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在旅行模式选择预测中的应用，特别是通过微调和基准测试展示了其在特定任务中的有效性。研究集中在模型的应用和实际效果上，而非理论分析或代理行为，因此归类为LLM应用。`

> Towards Locally Deployable Fine-Tuned Causal Large Language Models for Mode Choice Behaviour

# 摘要

> 本研究旨在探讨开源、本地部署的因果大型语言模型（LLMs）在旅行模式选择预测中的应用，并推出了专为该任务开发的首个微调因果LLM——LiTransMC。我们系统性地对11种LLM（参数规模从1B到12B）进行了基准测试，涵盖3个声明和揭示偏好数据集，测试了396种配置，生成了超过79,000个合成通勤者预测。除了预测准确性，我们还通过BERTopic进行主题建模以及采用新型解释强度指数，评估了模型生成的推理，从而首次对LLMs如何与行为理论相符合地阐述决策因素进行了结构化分析。经过参数高效和损失屏蔽策略微调的LiTransMC，在加权F1分数达到0.6845，Jensen-Shannon散度为0.000245，超越了未经微调的本地模型和更大规模的专有系统，包括具备先进身份推理和基于嵌入加载功能的GPT-4o，同时也优于相同数据集上的经典模式选择方法，如离散选择模型和机器学习分类器。这种双重改进，即高单次预测准确性和近乎完美的分布校准，证明了创建集预测与可解释性于一体的专用本地部署LLMs的可行性。通过将结构化行为预测与自然语言推理相结合，这项工作解锁了对话式、多任务交通模型的潜力，能够支持基于智能体的仿真、政策测试和行为洞察生成。这些发现为将通用型LLMs转化为专用、可解释的交通研究和政策制定工具开辟了道路，同时通过本地部署实现了隐私保护、成本降低和应用范围的拓展。

> This study investigates the adoption of open-access, locally deployable causal large language models (LLMs) for travel mode choice prediction and introduces LiTransMC, the first fine-tuned causal LLM developed for this task. We systematically benchmark eleven LLMs (1-12B parameters) across three stated and revealed preference datasets, testing 396 configurations and generating over 79,000 synthetic commuter predictions. Beyond predictive accuracy, we evaluate models generated reasoning using BERTopic for topic modelling and a novel Explanation Strength Index, providing the first structured analysis of how LLMs articulate decision factors in alignment with behavioural theory. LiTransMC, fine-tuned using parameter efficient and loss masking strategy, achieved a weighted F1 score of 0.6845 and a Jensen-Shannon Divergence of 0.000245, surpassing both untuned local models and larger proprietary systems, including GPT-4o with advanced persona inference and embedding-based loading, while also outperforming classical mode choice methods such as discrete choice models and machine learning classifiers for the same dataset. This dual improvement, i.e., high instant-level accuracy and near-perfect distributional calibration, demonstrates the feasibility of creating specialist, locally deployable LLMs that integrate prediction and interpretability. Through combining structured behavioural prediction with natural language reasoning, this work unlocks the potential for conversational, multi-task transport models capable of supporting agent-based simulations, policy testing, and behavioural insight generation. These findings establish a pathway for transforming general purpose LLMs into specialized, explainable tools for transportation research and policy formulation, while maintaining privacy, reducing cost, and broadening access through local deployment.

[Arxiv](https://arxiv.org/abs/2507.21432)