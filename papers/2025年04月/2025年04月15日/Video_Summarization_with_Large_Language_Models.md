# # 基于大型语言模型的视频摘要

发布时间：2025年04月15日

`LLM应用` `视频处理` `多媒体`

> Video Summarization with Large Language Models

# 摘要

> 视频内容的指数级增长带来了高效导航、搜索和检索方面的重大挑战，亟需先进的视频摘要技术。现有方法主要依赖视觉特征和时间动态，往往难以捕捉视频内容的深层语义，导致摘要不完整或不连贯。我们提出了一种全新的视频摘要框架，充分挖掘近期大型语言模型（LLMs）的潜力。通过从海量数据中学习，LLMs能够以更符合多样语义和人类判断的方式评估视频帧，有效解决关键帧定义中的主观性问题。我们的方法——基于LLM的视频摘要（LLMVS），采用多模态大型语言模型（M-LLM）将视频帧转化为字幕序列，再基于局部上下文中的字幕内容，利用LLM评估每个帧的重要性。通过全局注意力机制优化这些局部重要性评分，确保摘要既反映细节又把握整体叙述。实验结果表明，我们的方法在标准基准上显著优于现有方案，充分展现了LLMs在多媒体内容处理中的强大潜力。

> The exponential increase in video content poses significant challenges in terms of efficient navigation, search, and retrieval, thus requiring advanced video summarization techniques. Existing video summarization methods, which heavily rely on visual features and temporal dynamics, often fail to capture the semantics of video content, resulting in incomplete or incoherent summaries. To tackle the challenge, we propose a new video summarization framework that leverages the capabilities of recent Large Language Models (LLMs), expecting that the knowledge learned from massive data enables LLMs to evaluate video frames in a manner that better aligns with diverse semantics and human judgments, effectively addressing the inherent subjectivity in defining keyframes. Our method, dubbed LLM-based Video Summarization (LLMVS), translates video frames into a sequence of captions using a Muti-modal Large Language Model (M-LLM) and then assesses the importance of each frame using an LLM, based on the captions in its local context. These local importance scores are refined through a global attention mechanism in the entire context of video captions, ensuring that our summaries effectively reflect both the details and the overarching narrative. Our experimental results demonstrate the superiority of the proposed method over existing ones in standard benchmarks, highlighting the potential of LLMs in the processing of multimedia content.

[Arxiv](https://arxiv.org/abs/2504.11199)