# City-VLM：探索多领域感知场景理解的多模态不完整学习

发布时间：2025年07月17日

`其他` `问答系统`

> City-VLM: Towards Multidomain Perception Scene Understanding via Multimodal Incomplete Learning

# 摘要

> <翻译失败>

> Scene understanding enables intelligent agents to interpret and comprehend their environment. While existing large vision-language models (LVLMs) for scene understanding have primarily focused on indoor household tasks, they face two significant limitations when applied to outdoor large-scale scene understanding. First, outdoor scenarios typically encompass larger-scale environments observed through various sensors from multiple viewpoints (e.g., bird view and terrestrial view), while existing indoor LVLMs mainly analyze single visual modalities within building-scale contexts from humanoid viewpoints. Second, existing LVLMs suffer from missing multidomain perception outdoor data and struggle to effectively integrate 2D and 3D visual information. To address the aforementioned limitations, we build the first multidomain perception outdoor scene understanding dataset, named \textbf{\underline{SVM-City}}, deriving from multi\textbf{\underline{S}}cale scenarios with multi\textbf{\underline{V}}iew and multi\textbf{\underline{M}}odal instruction tuning data. It contains $420$k images and $4, 811$M point clouds with $567$k question-answering pairs from vehicles, low-altitude drones, high-altitude aerial planes, and satellite. To effectively fuse the multimodal data in the absence of one modality, we introduce incomplete multimodal learning to model outdoor scene understanding and design the LVLM named \textbf{\underline{City-VLM}}. Multimodal fusion is realized by constructing a joint probabilistic distribution space rather than implementing directly explicit fusion operations (e.g., concatenation). Experimental results on three typical outdoor scene understanding tasks show City-VLM achieves $18.14 \%$ performance surpassing existing LVLMs in question-answering tasks averagely. Our method demonstrates pragmatic and generalization performance across multiple outdoor scenes.

[Arxiv](https://arxiv.org/abs/2507.12795)