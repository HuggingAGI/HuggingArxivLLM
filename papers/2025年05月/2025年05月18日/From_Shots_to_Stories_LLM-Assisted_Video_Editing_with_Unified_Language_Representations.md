# 从镜头到故事：借助统一语言表达的LLM辅助视频编辑

发布时间：2025年05月18日

`LLM应用` `视频编辑` `智能视频编辑`

> From Shots to Stories: LLM-Assisted Video Editing with Unified Language Representations

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）在视频理解中展现了卓越的推理与泛化能力，但在视频编辑领域的应用仍鲜有探索。本文首次系统性研究了LLMs在视频编辑中的应用，提出了L-Storyboard这一创新方法，将离散视频镜头转化为结构化的语言描述，实现了视觉信息与语言推理的高效对接。我们将视频编辑任务划分为收敛型与发散型两类，重点研究镜头属性分类、下一镜头选择和镜头序列排序三大核心任务。针对发散型任务输出的不稳定性，我们提出StoryFlow策略，将复杂的多路径推理转化为统一的选择机制，显著提升了任务的准确性和逻辑连贯性。实验结果表明，L-Storyboard有效增强了视觉信息与语言描述的映射关系，提升了视频编辑任务的可解释性和隐私保护能力。此外，StoryFlow策略在镜头序列排序任务中展现了强大的逻辑一致性和输出稳定性，充分彰显了LLMs在智能视频编辑领域的巨大潜力。

> Large Language Models (LLMs) and Vision-Language Models (VLMs) have demonstrated remarkable reasoning and generalization capabilities in video understanding; however, their application in video editing remains largely underexplored. This paper presents the first systematic study of LLMs in the context of video editing. To bridge the gap between visual information and language-based reasoning, we introduce L-Storyboard, an intermediate representation that transforms discrete video shots into structured language descriptions suitable for LLM processing. We categorize video editing tasks into Convergent Tasks and Divergent Tasks, focusing on three core tasks: Shot Attributes Classification, Next Shot Selection, and Shot Sequence Ordering. To address the inherent instability of divergent task outputs, we propose the StoryFlow strategy, which converts the divergent multi-path reasoning process into a convergent selection mechanism, effectively enhancing task accuracy and logical coherence. Experimental results demonstrate that L-Storyboard facilitates a more robust mapping between visual information and language descriptions, significantly improving the interpretability and privacy protection of video editing tasks. Furthermore, StoryFlow enhances the logical consistency and output stability in Shot Sequence Ordering, underscoring the substantial potential of LLMs in intelligent video editing.

[Arxiv](https://arxiv.org/abs/2505.12237)