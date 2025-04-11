# GLUS：统一全局与局部推理于单一模型，实现视频分割新突破

发布时间：2025年04月10日

`LLM应用` `视频处理` `人工智能`

> GLUS: Global-Local Reasoning Unified into A Single Large Language Model for Video Segmentation

# 摘要

> 本文提出了一种基于多模态大语言模型（MLLMs）的参考视频对象分割（RefVOS）新框架。以往基于MLLM的方法常常在“Ref”与“VOS”之间面临两难抉择：它们要么专注于理解少数关键帧（全局推理），要么致力于连续帧上的目标追踪（局部推理），并且依赖外部的VOS或帧选择器来缓解另一端的挑战。然而，我们的框架GLUS表明，全局与局部一致性可以被整合到一个视频分割MLLM中：一组稀疏的“上下文帧”提供全局信息，而一串连续的“查询帧”则进行局部目标追踪。这一结论进一步通过联合训练MLLM与预训练的VOS记忆库得到支持，使其能够同时处理短时和长时的时间信息。为了提升MLLM有限上下文窗口内的信息效率，我们引入了目标对比学习以区分难以分辨的假阳性目标，并提出了一种自我优化框架来识别关键帧并执行传播。通过整合这些见解，我们的GLUS提供了一个简单而有效的基线，在MeViS和Ref-Youtube-VOS基准测试中为MLLMs实现了新的最先进水平。我们的项目页面位于https://glus-video.github.io/。


> This paper proposes a novel framework utilizing multi-modal large language models (MLLMs) for referring video object segmentation (RefVOS). Previous MLLM-based methods commonly struggle with the dilemma between "Ref" and "VOS": they either specialize in understanding a few key frames (global reasoning) or tracking objects on continuous frames (local reasoning), and rely on external VOS or frame selectors to mitigate the other end of the challenge. However, our framework GLUS shows that global and local consistency can be unified into a single video segmentation MLLM: a set of sparse "context frames" provides global information, while a stream of continuous "query frames" conducts local object tracking. This is further supported by jointly training the MLLM with a pre-trained VOS memory bank to simultaneously digest short-range and long-range temporal information. To improve the information efficiency within the limited context window of MLLMs, we introduce object contrastive learning to distinguish hard false-positive objects and a self-refined framework to identify crucial frames and perform propagation. By collectively integrating these insights, our GLUS delivers a simple yet effective baseline, achieving new state-of-the-art for MLLMs on the MeViS and Ref-Youtube-VOS benchmark. Our project page is at https://glus-video.github.io/.

[Arxiv](https://arxiv.org/abs/2504.07962)