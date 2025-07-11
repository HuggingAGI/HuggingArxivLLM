# LangNavBench：针对语义导航的自然语言理解能力进行评测

发布时间：2025年07月09日

`Agent` `计算机视觉` `机器人`

> LangNavBench: Evaluation of Natural Language Understanding in Semantic Navigation

# 摘要

> 大型视觉语言模型的最新进展推动了语言基础语义导航的显著提升，其中智能体需根据自然语言描述到达目标对象。尽管如此，我们仍缺乏一个清晰的语言焦点基准来评估智能体如何将指令中的词语与实际对象对应。为此，我们推出了LangNav，一个专为测试智能体定位不同详细程度描述对象能力而设计的开放集数据集，涵盖从广泛类别名称到精细属性及对象间关系的描述。LangNav中的每条描述均经过人工审核，其错误率低于现有终身和语义导航数据集。基于LangNav，我们构建了LangNavBench，这是一个评估当前语义导航方法在向目标移动时理解和处理描述能力的基准。LangNavBench使我们能够系统地比较模型在处理属性、空间和关系线索以及类别层次结构方面的表现，提供了首个全面的语言中心具身导航系统评估。此外，我们提出了多层特征图（MLFM），一种构建可查询多层语义地图的方法，尤其在处理小型对象或涉及空间关系的指令时表现出色。MLFM在LangNav数据集上超越了现有基于映射的导航基线方法。

> Recent progress in large vision-language models has driven improvements in language-based semantic navigation, where an embodied agent must reach a target object described in natural language. Despite these advances, we still lack a clear, language-focused benchmark for testing how well such agents ground the words in their instructions. We address this gap with LangNav, an open-set dataset specifically created to test an agent's ability to locate objects described at different levels of detail, from broad category names to fine attributes and object-object relations. Every description in LangNav was manually checked, yielding a lower error rate than existing lifelong- and semantic-navigation datasets. On top of LangNav we build LangNavBench, a benchmark that measures how well current semantic-navigation methods understand and act on these descriptions while moving toward their targets. LangNavBench allows us to systematically compare models on their handling of attributes, spatial and relational cues, and category hierarchies, offering the first thorough, language-centric evaluation of embodied navigation systems. We also present Multi-Layered Feature Map (MLFM), a method that builds a queryable multi-layered semantic map, particularly effective when dealing with small objects or instructions involving spatial relations. MLFM outperforms state-of-the-art mapping-based navigation baselines on the LangNav dataset.

[Arxiv](https://arxiv.org/abs/2507.07299)