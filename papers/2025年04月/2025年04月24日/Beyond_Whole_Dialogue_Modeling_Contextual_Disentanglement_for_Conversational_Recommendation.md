# # 超越整体对话建模：对话推荐中的情境解耦

发布时间：2025年04月24日

`LLM应用

这篇论文探讨了对话推荐系统中如何利用大语言模型来提升推荐的准确性和响应生成。通过提出DisenCRS模型，研究者展示了大语言模型在实际应用中的潜力，属于LLM应用类别。` `推荐系统`

> Beyond Whole Dialogue Modeling: Contextual Disentanglement for Conversational Recommendation

# 摘要

> 对话推荐系统通过分析对话上下文提供个性化推荐，但现有方法往往忽视了对话中焦点信息与背景信息的复杂关联。本文提出DisenCRS模型，采用双解缠框架，包括自监督对比解缠和反事实推理解缠，在无监督条件下有效区分对话信息。同时设计自适应提示学习模块，充分发挥大模型潜力。实验表明，DisenCRS在推荐准确性和响应生成上均超越现有模型。

> Conversational recommender systems aim to provide personalized recommendations by analyzing and utilizing contextual information related to dialogue. However, existing methods typically model the dialogue context as a whole, neglecting the inherent complexity and entanglement within the dialogue. Specifically, a dialogue comprises both focus information and background information, which mutually influence each other. Current methods tend to model these two types of information mixedly, leading to misinterpretation of users' actual needs, thereby lowering the accuracy of recommendations. To address this issue, this paper proposes a novel model to introduce contextual disentanglement for improving conversational recommender systems, named DisenCRS. The proposed model DisenCRS employs a dual disentanglement framework, including self-supervised contrastive disentanglement and counterfactual inference disentanglement, to effectively distinguish focus information and background information from the dialogue context under unsupervised conditions. Moreover, we design an adaptive prompt learning module to automatically select the most suitable prompt based on the specific dialogue context, fully leveraging the power of large language models. Experimental results on two widely used public datasets demonstrate that DisenCRS significantly outperforms existing conversational recommendation models, achieving superior performance on both item recommendation and response generation tasks.

[Arxiv](https://arxiv.org/abs/2504.17427)