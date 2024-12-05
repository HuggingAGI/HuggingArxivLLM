# VideoICL：用于分布外视频理解的基于置信度的迭代式上下文学习

发布时间：2024年12月03日

`LLM应用` `人工智能`

> VideoICL: Confidence-based Iterative In-context Learning for Out-of-Distribution Video Understanding

# 摘要

> 近期，视频大型多模态模型（LMMs）的进步极大地提升了其视频理解与推理能力。然而，在训练数据中占比较少的分布外（OOD）任务上，其性能有所下降。由于计算成本高昂，在 OOD 数据集上进行微调这类传统方法并不可行。虽然在语言任务和图像-语言任务中，带有示例的上下文学习（ICL）无需微调就展现出良好的泛化性能，但将 ICL 应用于视频-语言任务时，由于视频 LMMs 的上下文长度有限（而视频需要更长的标记长度），面临诸多挑战。为应对这些问题，我们提出了 VideoICL，这是一种针对 OOD 任务的新型视频上下文学习框架，引入了基于相似性的相关示例选择策略和基于置信度的迭代推理方法。这能够选择出最相关的示例，并依据相似性进行排序，用于推理。若生成的响应置信度低，我们的框架会选取新示例并再次推理，通过迭代优化结果，直至获得高置信度的响应。此方法在不增加高额成本的情况下，通过延展有效上下文长度，提高了 OOD 视频的理解性能。在多个基准测试中的实验结果表明，性能有显著提升，尤其在特定领域场景中，为更广泛的视频理解应用奠定了基础。代码将在 https://github.com/KangsanKim07/VideoICL 发布。

> Recent advancements in video large multimodal models (LMMs) have significantly improved their video understanding and reasoning capabilities. However, their performance drops on out-of-distribution (OOD) tasks that are underrepresented in training data. Traditional methods like fine-tuning on OOD datasets are impractical due to high computational costs. While In-context learning (ICL) with demonstration examples has shown promising generalization performance in language tasks and image-language tasks without fine-tuning, applying ICL to video-language tasks faces challenges due to the limited context length in Video LMMs, as videos require longer token lengths. To address these issues, we propose VideoICL, a novel video in-context learning framework for OOD tasks that introduces a similarity-based relevant example selection strategy and a confidence-based iterative inference approach. This allows to select the most relevant examples and rank them based on similarity, to be used for inference. If the generated response has low confidence, our framework selects new examples and performs inference again, iteratively refining the results until a high-confidence response is obtained. This approach improves OOD video understanding performance by extending effective context length without incurring high costs. The experimental results on multiple benchmarks demonstrate significant performance gains, especially in domain-specific scenarios, laying the groundwork for broader video comprehension applications. Code will be released at https://github.com/KangsanKim07/VideoICL

[Arxiv](https://arxiv.org/abs/2412.02186)