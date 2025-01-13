# 大型语言模型在虚拟现实探索测试中的应用：案例研究

发布时间：2025年01月09日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在虚拟现实（VR）领域的应用，特别是用于自动化GUI测试和视野（FOV）分析。论文通过案例研究验证了LLMs在识别测试实体、描述实体特征以及进行场景识别和空间理解方面的能力。这些内容都属于LLM在实际应用中的具体使用场景，因此将其分类为LLM应用。` `虚拟现实` `自动化测试`

> Harnessing Large Language Model for Virtual Reality Exploration Testing: A Case Study

# 摘要

> 随着虚拟现实（VR）行业的蓬勃发展，自动化GUI测试的需求急剧上升。大型语言模型（LLMs）凭借其长期信息存储和视觉文本分析能力，正成为破解VR用户界面复杂性的关键。本文通过案例研究，探讨了LLMs（特别是GPT-4o）在VR探索测试中用于视野（FOV）分析的潜力。我们验证了LLMs能够识别FOV中的测试实体，并通过提示工程将识别准确率从41.67%提升至71.30%。研究还表明，LLMs能以至少90%的准确率描述实体特征，其中颜色、位置和形状是核心特征。这三个特征的组合尤其有助于提高多FOV中相同实体的识别准确率，最高F1得分为0.70。此外，LLMs通过精心设计的结构化提示，展现了在VR中进行场景识别和空间理解的能力。最后，我们发现LLMs在标记测试实体方面存在不足，并探讨了未来研究的潜在解决方案。

> As the Virtual Reality (VR) industry expands, the need for automated GUI testing is growing rapidly. Large Language Models (LLMs), capable of retaining information long-term and analyzing both visual and textual data, are emerging as a potential key to deciphering the complexities of VR's evolving user interfaces. In this paper, we conduct a case study to investigate the capability of using LLMs, particularly GPT-4o, for field of view (FOV) analysis in VR exploration testing. Specifically, we validate that LLMs can identify test entities in FOVs and that prompt engineering can effectively enhance the accuracy of test entity identification from 41.67% to 71.30%. Our study also shows that LLMs can accurately describe identified entities' features with at least a 90% correction rate. We further find out that the core features that effectively represent an entity are color, placement, and shape. Furthermore, the combination of the three features can especially be used to improve the accuracy of determining identical entities in multiple FOVs with the highest F1-score of 0.70. Additionally, our study demonstrates that LLMs are capable of scene recognition and spatial understanding in VR with precisely designed structured prompts. Finally, we find that LLMs fail to label the identified test entities, and we discuss potential solutions as future research directions.

[Arxiv](https://arxiv.org/abs/2501.05625)