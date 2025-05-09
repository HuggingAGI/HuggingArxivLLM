# 对话式流程模型的重新设计

发布时间：2025年05月08日

`LLM应用

摘要中提到，大型语言模型（LLMs）被应用于业务流程管理系统的优化，特别是在流程模型设计与重设计中的应用。研究探索了LLMs在支持领域专家进行迭代式流程模型创建与重设计中的可行性，并提出了具体的对话式方法。这属于将LLMs应用于特定领域任务的研究，因此归类为LLM应用。` `业务流程管理`

> Conversational Process Model Redesign

# 摘要

> 大型语言模型（LLMs）的成功推动了AI增强的业务流程管理系统的发展。其关键特性在于支持对话式操作，使人类能够与LLM高效协作，完成流程模型设计与重设计等重要任务。然而，现有研究多聚焦于单次提示执行和结果评估，忽视了用户与LLM间的持续互动。本研究旨在探索利用LLMs赋能领域专家，以迭代且高效的方式进行流程模型创建与重设计的可行性。我们提出的对话式过程模型重设计（CPD）方法接收过程模型和用户的自然语言重设计请求作为输入。与直接让LLM进行修改不同，该方法通过LLM实现以下步骤：（a）从文献中识别过程变更模式，（b）将变更请求重新表述为与所识别模式含义相符的措辞，（c）将变更含义应用于过程模型。这种多步骤方法确保了变更的可解释性和可重复性。为了验证CPD方法的可行性，并评估文献中的模式在LLMs中的处理效果，我们进行了全面的评估。结果显示，部分模式难以被LLMs和用户理解。研究范围内，我们发现用户需要支持以清晰描述变更。总体而言，根据完整性和正确性标准，评估表明LLMs能够很好地处理大部分变更。

> With the recent success of large language models (LLMs), the idea of AI-augmented Business Process Management systems is becoming more feasible. One of their essential characteristics is the ability to be conversationally actionable, allowing humans to interact with the LLM effectively to perform crucial process life cycle tasks such as process model design and redesign. However, most current research focuses on single-prompt execution and evaluation of results, rather than on continuous interaction between the user and the LLM. In this work, we aim to explore the feasibility of using LLMs to empower domain experts in the creation and redesign of process models in an iterative and effective way. The proposed conversational process model redesign (CPD) approach receives as input a process model and a redesign request by the user in natural language. Instead of just letting the LLM make changes, the LLM is employed to (a) identify process change patterns from literature, (b) re-phrase the change request to be aligned with an expected wording for the identified pattern (i.e., the meaning), and then to (c) apply the meaning of the change to the process model. This multi-step approach allows for explainable and reproducible changes. In order to ensure the feasibility of the CPD approach, and to find out how well the patterns from literature can be handled by the LLM, we performed an extensive evaluation. The results show that some patterns are hard to understand by LLMs and by users. Within the scope of the study, we demonstrated that users need support to describe the changes clearly. Overall the evaluation shows that the LLMs can handle most changes well according to a set of completeness and correctness criteria.

[Arxiv](https://arxiv.org/abs/2505.05453)