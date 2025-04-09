# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月07日

`Agent` `机器人` `人工智能`

> Model-Agnostic Policy Explanations with Large Language Models

# 摘要

> 智能体（如机器人）正越来越多地被部署在以人类为中心的真实环境中。为了培养人类对智能体的信任并符合法律和伦理标准，这些智能体必须能够解释自己的行为。然而，最先进的智能体通常由黑箱模型（如深度神经网络）驱动，限制了它们的可解释性。我们提出了一种基于观察到的状态和动作生成智能体行为的自然语言解释的方法——无需访问智能体的底层模型。我们的方法从观察中学习智能体行为的局部可解释替代模型，然后引导大型语言模型生成具有最小幻觉的合理解释。实验结果表明，我们的方法生成的解释比基准方法更具可理解性和准确性，无论是语言模型还是人类评估者都对此给予了肯定。此外，我们发现，在用户研究中，参与者在获得我们的解释后，能够更准确地预测智能体的未来行为，这表明他们对智能体行为的理解得到了提升。

> Intelligent agents, such as robots, are increasingly deployed in real-world, human-centric environments. To foster appropriate human trust and meet legal and ethical standards, these agents must be able to explain their behavior. However, state-of-the-art agents are typically driven by black-box models like deep neural networks, limiting their interpretability. We propose a method for generating natural language explanations of agent behavior based only on observed states and actions -- without access to the agent's underlying model. Our approach learns a locally interpretable surrogate model of the agent's behavior from observations, which then guides a large language model to generate plausible explanations with minimal hallucination. Empirical results show that our method produces explanations that are more comprehensible and correct than those from baselines, as judged by both language models and human evaluators. Furthermore, we find that participants in a user study more accurately predicted the agent's future actions when given our explanations, suggesting improved understanding of agent behavior.

[Arxiv](https://arxiv.org/abs/2504.05625)