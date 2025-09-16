# MOOM：超长角色扮演对话中的记忆维护、组织与优化

发布时间：2025年09月15日

`LLM应用` `媒体与娱乐`

> MOOM: Maintenance, Organization and Optimization of Memory in Ultra-Long Role-Playing Dialogues

# 摘要

> 记忆提取在人机角色扮演场景中维持连贯的超长对话方面至关重要。但现有方法常出现记忆不受控增长的问题。为此，我们提出MOOM——首个双分支记忆插件，它借鉴文学理论，将情节发展与人物塑造作为核心叙事要素进行建模。具体来说，一个分支负责总结不同时间尺度的情节冲突，另一个分支则提取用户的人物特征。MOOM还借鉴“竞争-抑制”记忆理论，融入遗忘机制，以此限制记忆容量，缓解记忆不受控增长的问题。此外，我们还构建了ZH-4O——一个专为角色扮演设计的中文超长对话数据集，该数据集的对话平均长达600轮，并包含人工标注的记忆信息。实验结果显示，MOOM在性能上超越了所有最先进的记忆提取方法，同时减少了大型语言模型的调用次数，并保持了可控的记忆容量。

> Memory extraction is crucial for maintaining coherent ultra-long dialogues in human-robot role-playing scenarios. However, existing methods often exhibit uncontrolled memory growth. To address this, we propose MOOM, the first dual-branch memory plugin that leverages literary theory by modeling plot development and character portrayal as core storytelling elements. Specifically, one branch summarizes plot conflicts across multiple time scales, while the other extracts the user's character profile. MOOM further integrates a forgetting mechanism, inspired by the ``competition-inhibition'' memory theory, to constrain memory capacity and mitigate uncontrolled growth. Furthermore, we present ZH-4O, a Chinese ultra-long dialogue dataset specifically designed for role-playing, featuring dialogues that average 600 turns and include manually annotated memory information. Experimental results demonstrate that MOOM outperforms all state-of-the-art memory extraction methods, requiring fewer large language model invocations while maintaining a controllable memory capacity.

[Arxiv](https://arxiv.org/abs/2509.11860)