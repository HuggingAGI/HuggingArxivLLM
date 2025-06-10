# ARGUS：视频-LLMs幻觉与遗漏评估研究

发布时间：2025年06月08日

`LLM应用` `视频处理`

> ARGUS: Hallucination and Omission Evaluation in Video-LLMs

# 摘要

> 视频大型语言模型尚未得到广泛应用，主要是因为它们容易产生幻觉。现有针对 Video-LLMs 的基准测试主要依赖多项选择题，但 Video-LLMs 在自由文本生成任务（如视频描述）中的幻觉问题远比在多项选择验证任务中严重。为了解决这一问题，我们提出了 ARGUS，一个评估 Video-LLMs 在自由视频描述任务上性能的基准。通过将模型输出与人类真实描述对比，ARGUS 量化了两个关键指标：一是错误描述视频内容或时间关系的幻觉率，二是遗漏重要描述细节的频率。这两个指标的结合，全面评估了视频描述的性能。

> Video large language models have not yet been widely deployed, largely due to their tendency to hallucinate. Typical benchmarks for Video-LLMs rely simply on multiple-choice questions. Unfortunately, VideoLLMs hallucinate far more aggressively on freeform text generation tasks like video captioning than they do on multiple choice verification tasks. To address this weakness, we propose ARGUS, a VideoLLM benchmark that measures freeform video captioning performance. By comparing VideoLLM outputs to human ground truth captions, ARGUS quantifies dual metrics. First, we measure the rate of hallucinations in the form of incorrect statements about video content or temporal relationships. Second, we measure the rate at which the model omits important descriptive details. Together, these dual metrics form a comprehensive view of video captioning performance.

[Arxiv](https://arxiv.org/abs/2506.07371)