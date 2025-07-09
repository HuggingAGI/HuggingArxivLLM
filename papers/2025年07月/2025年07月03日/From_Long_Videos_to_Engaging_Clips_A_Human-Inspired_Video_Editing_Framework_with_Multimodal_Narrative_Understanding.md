# 从长视频到引人入胜的短视频：以人类灵感为驱动，结合多模态叙事理解的视频编辑框架

发布时间：2025年07月03日

`LLM应用

理由：这篇论文探讨了如何利用多模态大语言模型在视频编辑中的应用，属于将LLM技术应用于具体任务的范畴，因此归类为LLM应用。` `视频行业` `内容生成`

> From Long Videos to Engaging Clips: A Human-Inspired Video Editing Framework with Multimodal Narrative Understanding

# 摘要

> 在线视频内容，尤其是短视频平台的蓬勃发展，催生了对高效视频编辑技术的迫切需求，这些技术能够将冗长的视频浓缩为简短而引人入胜的片段。然而，现有的自动编辑方法主要依赖于ASR字幕中的文本线索以及端到端的片段选择，往往忽视了丰富的视觉上下文，导致输出不连贯。本文中，我们提出了一种基于人类启发的自动视频编辑框架（HIVE），通过多模态叙事理解来克服这些局限。我们的方法结合了角色提取、对话分析和叙事总结，借助多模态大语言模型实现对视频内容的全面理解。为了进一步增强连贯性，我们应用了场景级分割，并将编辑过程分解为三个子任务：亮点检测、开头/结尾选择以及去除无关内容。为了促进该领域的研究，我们引入了DramaAD，这是一个包含800多集短剧和500个专业编辑广告片段的新基准数据集。实验结果表明，我们的框架在通用和广告导向的编辑任务中均显著优于现有基线，大幅缩小了自动编辑视频与人工编辑视频之间的质量差距。

> The rapid growth of online video content, especially on short video platforms, has created a growing demand for efficient video editing techniques that can condense long-form videos into concise and engaging clips. Existing automatic editing methods predominantly rely on textual cues from ASR transcripts and end-to-end segment selection, often neglecting the rich visual context and leading to incoherent outputs. In this paper, we propose a human-inspired automatic video editing framework (HIVE) that leverages multimodal narrative understanding to address these limitations. Our approach incorporates character extraction, dialogue analysis, and narrative summarization through multimodal large language models, enabling a holistic understanding of the video content. To further enhance coherence, we apply scene-level segmentation and decompose the editing process into three subtasks: highlight detection, opening/ending selection, and pruning of irrelevant content. To facilitate research in this area, we introduce DramaAD, a novel benchmark dataset comprising over 800 short drama episodes and 500 professionally edited advertisement clips. Experimental results demonstrate that our framework consistently outperforms existing baselines across both general and advertisement-oriented editing tasks, significantly narrowing the quality gap between automatic and human-edited videos.

[Arxiv](https://arxiv.org/abs/2507.02790)