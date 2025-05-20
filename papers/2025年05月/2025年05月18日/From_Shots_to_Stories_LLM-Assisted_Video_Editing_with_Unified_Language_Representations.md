# # 从画面到故事：基于统一语言模型的LLM辅助视频编辑

发布时间：2025年05月18日

`LLM应用` `视频编辑` `智能视频`

> From Shots to Stories: LLM-Assisted Video Editing with Unified Language Representations

# 摘要

> 大型语言模型（LLMs）与视觉-语言模型（VLMs）在视频理解领域展现出卓越的推理与泛化能力，但在视频编辑领域的应用仍待深入探索。本文首次系统性研究了LLMs在视频编辑领域的潜力。为弥合视觉信息与语言推理之间的鸿沟，我们提出了一种名为L-Storyboard的中间表示方法，将离散的视频镜头转化为适合LLMs处理的结构化语言描述。我们还将视频编辑任务分为聚合型任务与发散型任务，并重点研究了镜头属性分类、下一镜头选择以及镜头序列排序这三大核心任务。针对发散型任务输出的不稳定性，我们创新性地提出了StoryFlow策略，将发散式多路径推理过程转化为收敛式选择机制，显著提升了任务的准确性和逻辑连贯性。实验结果表明，L-Storyboard能够实现视觉信息与语言描述之间更稳健的映射，大幅提升了视频编辑任务的可解释性与隐私保护能力。此外，StoryFlow策略在镜头序列排序任务中显著增强了逻辑一致性与输出稳定性，充分彰显了LLMs在智能视频编辑领域的巨大潜力。

> Large Language Models (LLMs) and Vision-Language Models (VLMs) have demonstrated remarkable reasoning and generalization capabilities in video understanding; however, their application in video editing remains largely underexplored. This paper presents the first systematic study of LLMs in the context of video editing. To bridge the gap between visual information and language-based reasoning, we introduce L-Storyboard, an intermediate representation that transforms discrete video shots into structured language descriptions suitable for LLM processing. We categorize video editing tasks into Convergent Tasks and Divergent Tasks, focusing on three core tasks: Shot Attributes Classification, Next Shot Selection, and Shot Sequence Ordering. To address the inherent instability of divergent task outputs, we propose the StoryFlow strategy, which converts the divergent multi-path reasoning process into a convergent selection mechanism, effectively enhancing task accuracy and logical coherence. Experimental results demonstrate that L-Storyboard facilitates a more robust mapping between visual information and language descriptions, significantly improving the interpretability and privacy protection of video editing tasks. Furthermore, StoryFlow enhances the logical consistency and output stability in Shot Sequence Ordering, underscoring the substantial potential of LLMs in intelligent video editing.

[Arxiv](https://arxiv.org/abs/2505.12237)