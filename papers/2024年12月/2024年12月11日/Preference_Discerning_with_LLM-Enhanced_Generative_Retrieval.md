# 利用 LLM 增强的生成式检索进行偏好辨别

发布时间：2024年12月11日

`LLM应用` `推荐系统` `个性化服务`

> Preference Discerning with LLM-Enhanced Generative Retrieval

# 摘要

> 顺序推荐系统旨在依据用户的交互历史为用户提供个性化推荐。为达成此目的，它们通常会引入辅助信息，像物品的文本描述以及辅助任务，比如预测用户偏好和意图。尽管为强化这些模型付出诸多努力，但其个性化程度仍有限。为解决这一问题，我们提出了一种新范式，称作偏好辨别。在偏好辨别中，我们在其情境里明确依据用户偏好对生成式顺序推荐系统进行条件设定。为此，我们基于用户评论和特定项目数据，利用大型语言模型（LLMs）生成用户偏好。为评估顺序推荐系统的偏好辨别能力，我们引入了一个全新的基准，它在包括偏好引导和情感跟随等各种场景中提供了全面评估。我们用我们的基准评估当前最先进的方法，结果显示它们难以精准辨别用户偏好。于是，我们提出了一种名为 Mender（$	extbf{M}$ultimodal Prefer$	extbf{en}$ce $	extbf{d}$iscern$	extbf{er}$）的新方法，该方法改进了现有方法，并在我们的基准测试中达到了最先进的性能。我们的成果表明，即便在训练期间未观测到人类偏好，Mender 也能有效受其引导，为更具个性化的顺序推荐系统开辟了道路。我们会在发布时开源代码和基准。

> Sequential recommendation systems aim to provide personalized recommendations for users based on their interaction history. To achieve this, they often incorporate auxiliary information, such as textual descriptions of items and auxiliary tasks, like predicting user preferences and intent. Despite numerous efforts to enhance these models, they still suffer from limited personalization. To address this issue, we propose a new paradigm, which we term preference discerning. In preference dscerning, we explicitly condition a generative sequential recommendation system on user preferences within its context. To this end, we generate user preferences using Large Language Models (LLMs) based on user reviews and item-specific data. To evaluate preference discerning capabilities of sequential recommendation systems, we introduce a novel benchmark that provides a holistic evaluation across various scenarios, including preference steering and sentiment following. We assess current state-of-the-art methods using our benchmark and show that they struggle to accurately discern user preferences. Therefore, we propose a new method named Mender ($\textbf{M}$ultimodal Prefer$\textbf{en}$ce $\textbf{d}$iscern$\textbf{er}$), which improves upon existing methods and achieves state-of-the-art performance on our benchmark. Our results show that Mender can be effectively guided by human preferences even though they have not been observed during training, paving the way toward more personalized sequential recommendation systems. We will open-source the code and benchmarks upon publication.

[Arxiv](https://arxiv.org/abs/2412.08604)