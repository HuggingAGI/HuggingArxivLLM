# LLaVA-Octopus: 解锁指令驱动的自适应投影器融合，助力视频理解

发布时间：2025年01月09日

`LLM应用

理由：该论文介绍了一种创新的视频多模态大型语言模型（LLaVA-Octopus），并讨论了其在多模态任务中的性能提升。这属于大型语言模型在实际应用中的改进和优化，因此应归类为LLM应用。` `视频理解` `多模态任务`

> LLaVA-Octopus: Unlocking Instruction-Driven Adaptive Projector Fusion for Video Understanding

# 摘要

> 本文介绍了LLaVA-Octopus，一种创新的视频多模态大型语言模型。LLaVA-Octopus能够根据用户指令自适应地加权不同视觉投影器的特征，充分利用各投影器的互补优势。我们发现，不同投影器在处理特定任务时展现出独特特性：有的擅长捕捉静态细节，有的更擅长处理时间信息，还有的更适合需要时间一致性的任务。通过动态调整特征权重，LLaVA-Octopus能够灵活选择和组合最合适的特征，从而显著提升多模态任务的性能。实验结果显示，LLaVA-Octopus在多个基准测试中表现优异，尤其是在多模态理解、视觉问答和视频理解等任务中，展现了其广泛的应用前景。

> In this paper, we introduce LLaVA-Octopus, a novel video multimodal large language model. LLaVA-Octopus adaptively weights features from different visual projectors based on user instructions, enabling us to leverage the complementary strengths of each projector. We observe that different visual projectors exhibit distinct characteristics when handling specific tasks. For instance, some projectors excel at capturing static details, while others are more effective at processing temporal information, and some are better suited for tasks requiring temporal coherence. By dynamically adjusting feature weights according to user instructions, LLaVA-Octopus dynamically selects and combines the most suitable features, significantly enhancing the model's performance in multimodal tasks. Experimental results demonstrate that LLaVA-Octopus achieves excellent performance across multiple benchmarks, especially in tasks such as multimodal understanding, visual question answering, and video understanding, highlighting its broad application potential.

[Arxiv](https://arxiv.org/abs/2501.05067)