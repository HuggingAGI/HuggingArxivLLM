# FMNV: 用于假新闻检测的媒体新闻视频数据集

发布时间：2025年04月10日

`LLM应用` `新闻媒体` `视频内容检测`

> FMNV: A Dataset of Media-Published News Videos for Fake News Detection

# 摘要

> 新闻媒体，特别是基于视频的平台，已深深融入日常生活，同时加剧了虚假信息传播的风险。因此，多模态假新闻检测已成为研究热点。然而，现有数据集主要由用户生成的视频组成，这些视频通常编辑粗糙且公众参与度有限，而媒体机构发布的专业制作的假新闻视频（往往出于政治或 viral 意图）则会对社会造成更大的危害。为填补这一空白，我们构建了 FMNV 数据集，该数据集仅包含媒体机构发布的新闻视频。通过对现有数据集和我们整理的视频进行实证分析，我们将假新闻视频分为四种不同类型。在此分类基础上，我们利用大型语言模型（LLMs）通过篡改真实的媒体发布的新闻视频来自动生成欺骗性内容。此外，我们提出了 FMNVD 基线模型，该模型采用双流架构，结合 CLIP 和 Faster R-CNN 进行视频特征提取，并通过协同注意力机制进行特征优化和多模态聚合。对比实验表明，FMNV 数据集在多个基线模型上的泛化能力以及 FMNVD 模型的检测效果均优于现有方法。这项研究为媒体生态系统中检测高影响力假新闻奠定了关键基准，同时推动了跨模态不一致性分析方法的发展。

> News media, particularly video-based platforms, have become deeply embedded in daily life, concurrently amplifying risks of misinformation dissemination. Consequently, multimodal fake news detection has garnered significant research attention. However, existing datasets predominantly comprise user-generated videos characterized by crude editing and limited public engagement, whereas professionally crafted fake news videos disseminated by media outlets often politically or virally motivated pose substantially greater societal harm. To address this gap, we construct FMNV, a novel dataset exclusively composed of news videos published by media organizations. Through empirical analysis of existing datasets and our curated collection, we categorize fake news videos into four distinct types. Building upon this taxonomy, we employ Large Language Models (LLMs) to automatically generate deceptive content by manipulating authentic media-published news videos. Furthermore, we propose FMNVD, a baseline model featuring a dual-stream architecture integrating CLIP and Faster R-CNN for video feature extraction, enhanced by co-attention mechanisms for feature refinement and multimodal aggregation. Comparative experiments demonstrate both the generalization capability of FMNV across multiple baselines and the superior detection efficacy of FMNVD. This work establishes critical benchmarks for detecting high-impact fake news in media ecosystems while advancing methodologies for cross-modal inconsistency analysis.

[Arxiv](https://arxiv.org/abs/2504.07687)