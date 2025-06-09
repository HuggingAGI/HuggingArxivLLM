# SynthesizeMe！——基于角色引导的提示生成，助力大型语言模型的个性化奖励建模

发布时间：2025年06月05日

`LLM应用` `人机交互` `人工智能`

> SynthesizeMe! Inducing Persona-Guided Prompts for Personalized Reward Models in LLMs

# 摘要

> 近期关于大型语言模型（LLMs）的多元对齐研究呼吁让模型适应多样化的用户偏好。然而，此前大多数关于个性化奖励模型的工作都严重依赖额外的身份信息，例如人口统计细节或预先定义好的偏好类别。为此，我们提出了SynthesizeMe，这是一种通过用户交互生成合成用户角色以实现个性化奖励建模的方法。SynthesizeMe首先生成并验证解释用户偏好的推理过程，然后从该推理中诱导出合成用户角色，最后筛选出具有信息量的先前用户交互，以便为特定用户构建个性化提示。实验表明，使用SynthesizeMe生成的提示能够将个性化LLM作为评估者的准确性在Chatbot Arena上提高4.4%。将SynthesizeMe衍生的提示与奖励模型相结合，在PersonalRewardBench上实现了最佳性能：这是一个新的数据集，由来自854名Chatbot Arena和PRISM用户的分层用户与聊天机器人交互数据组成。

> Recent calls for pluralistic alignment of Large Language Models (LLMs) encourage adapting models to diverse user preferences. However, most prior work on personalized reward models heavily rely on additional identity information, such as demographic details or a predefined set of preference categories. To this end, we introduce SynthesizeMe, an approach to inducing synthetic user personas from user interactions for personalized reward modeling. SynthesizeMe first generates and verifies reasoning to explain user preferences, then induces synthetic user personas from that reasoning, and finally filters to informative prior user interactions in order to build personalized prompts for a particular user. We show that using SynthesizeMe induced prompts improves personalized LLM-as-a-judge accuracy by 4.4% on Chatbot Arena. Combining SynthesizeMe derived prompts with a reward model achieves top performance on PersonalRewardBench: a new curation of user-stratified interactions with chatbots collected from 854 users of Chatbot Arena and PRISM.

[Arxiv](https://arxiv.org/abs/2506.05598)