# 借助大型语言模型实现情绪状态的客观量化

发布时间：2025年02月13日

`LLM应用` `心理健康`

> Objective quantification of mood states using large language models

# 摘要

> 情绪状态影响人类行为与认知，导致不同的思维轨迹。类似地，大型语言模型（LLMs）在广泛的上下文中展现出卓越的响应一致性。我们利用这些相似性，构建了一个量化心理状态的框架。通过自我报告问卷，我们能够可靠地评估这些状态，因为问卷本身对共同出现的响应模式具有高度敏感性。

具体而言，我们招募了大量参与者（N=422），研究LLM（Mistral-7B-OpenOrca）如何量化通过参与者对抑郁症问卷的开放式回答所测量的异质性抑郁情绪状态。实验结果表明，LLM基于参与者的开放式回答，对预留多项选择题的回答与真实问卷分数高度相关（r: 0.52-0.84），这充分展示了LLM从情绪表示中进行泛化的强大能力。

我们进一步探讨了这些表示与因子分析之间的联系。通过岭回归分析，我们在LLM隐藏状态中发现与抑郁相关的子空间。研究结果表明，这些子空间能够有效预测参与者的“抑郁”和“躯体及情感困扰”因子分数，以及自杀严重程度。

总体而言，大型语言模型可以提供心理状态的定量测量。这些测量的可靠性取决于我们向参与者提出的问题是否足够具信息量。如果使用得当，这种方法可以在多种环境中补充传统心理状态评估，为心理健康研究与实践提供新的视角与工具。

> Emotional states influence human behaviour and cognition, leading to diverse thought trajectories. Similarly, Large Language Models (LLMs) showcase an excellent level of response consistency across wide-ranging contexts (prompts). We leverage these parallels to establish a framework for quantifying mental states. Our approach utilises self-report questionnaires that reliably assess these states due to their inherent sensitivity to patterns of co-occurring responses. Specifically, we recruited a large sample of participants (N=422) to investigate how well an LLM (Mistral-7B-OpenOrca) quantifies a heterogenous set of depressive mood states measured with participants' open-ended responses to a depression questionnaire. We show LLM responses to held-out multiple-choice questions, given participants' open-ended answers, correlate strongly (r: 0.52-0.84) with true questionnaire scores, demonstrating LLM's generalisation from mood representations. We explore a link between these representations and factor analysis. Using ridge regression, we find depression-related subspaces within LLM hidden states. We show these subspaces to be predictive of participants' "Depression" and "Somatic & Emotional Distress" factor scores, as well as suicidality severity. Overall, LLMs can provide quantitative measures of mental states. The reliability of these hinges upon how informative the questions we ask participants are. Used correctly, this approach could supplement mental state assessment in a variety of settings.

[Arxiv](https://arxiv.org/abs/2502.09487)