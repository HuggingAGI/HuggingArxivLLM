# 通过注意力头的参数推断其功能

发布时间：2024年12月16日

`LLM理论

理由：这篇论文主要关注大型语言模型（LLMs）的核心组件——注意力头的功能和操作，提出了一个无需模型训练或推理即可从参数中推断注意力头功能的框架（MAPS）。研究内容涉及LLMs的内部机制和理论分析，旨在揭示LLMs的功能普遍性和架构偏见，属于对LLMs的理论性研究，因此分类为“LLM理论”。` `机器学习`

> Inferring Functionality of Attention Heads from their Parameters

# 摘要

> 注意力头是大型语言模型（LLMs）的核心组件之一。以往的研究多聚焦于它们在特定任务或电路推理中的表现。本研究旨在全面映射这些头在模型中的操作。我们提出了MAPS（Mapping Attention head ParameterS），一个无需模型训练或推理即可从参数中推断注意力头功能的高效框架。MAPS在两类问题上展现了其价值：（a）给定一个操作，映射模型中各头实现该操作的强度；（b）给定一个头，推断其主要功能。在6个主流LLMs上对20个操作的评估表明，MAPS的估计与推理过程中头的输出高度相关，且与模型预测存在因果关系。此外，MAPS的映射揭示了以往研究中被忽视的某些操作的注意力头，并提供了关于LLMs功能普遍性和架构偏见的新见解。我们还开发了一个自动化管道，利用MAPS来表征给定头的主要操作，生成的操作描述经人类评估合理，同时揭示了操作的多样性。

> Attention heads are one of the building blocks of large language models (LLMs). Prior work on investigating their operation mostly focused on analyzing their behavior during inference for specific circuits or tasks. In this work, we seek a comprehensive mapping of the operations they implement in a model. We propose MAPS (Mapping Attention head ParameterS), an efficient framework that infers the functionality of attention heads from their parameters, without any model training or inference. We showcase the utility of MAPS for answering two types of questions: (a) given a predefined operation, mapping how strongly heads across the model implement it, and (b) given an attention head, inferring its salient functionality. Evaluating MAPS on 20 operations across 6 popular LLMs shows its estimations correlate with the head's outputs during inference and are causally linked to the model's predictions. Moreover, its mappings reveal attention heads of certain operations that were overlooked in previous studies, and valuable insights on function universality and architecture biases in LLMs. Next, we present an automatic pipeline and analysis that leverage MAPS to characterize the salient operations of a given head. Our pipeline produces plausible operation descriptions for most heads, as assessed by human judgment, while revealing diverse operations.

[Arxiv](https://arxiv.org/abs/2412.11965)