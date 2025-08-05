# E-VRAG: 通过资源高效的检索增强生成提升长视频理解能力

发布时间：2025年08月02日

`RAG` `视频处理` `视频分析`

> E-VRAG: Enhancing Long Video Understanding with Resource-Efficient Retrieval Augmented Generation

# 摘要

> 视觉语言模型（VLMs）通过跨模态推理能力推动了视频理解的发展。然而，受限的上下文窗口和处理长视频的高计算成本限制了其效果。检索增强生成（RAG）通过选择最相关帧作为输入，降低了计算负担。然而，现有视频RAG方法在处理复杂视频内容时难以平衡效率与准确性。为此，我们提出了E-VRAG，一种新颖高效的视频RAG框架。首先，我们采用基于分层查询分解的帧预筛选方法，消除无关帧，降低数据层面的计算成本。然后，使用轻量级VLM进行帧评分，进一步降低模型层面的计算成本。此外，我们提出了一种帧检索策略，利用帧间分数的全局统计分布，缓解轻量级VLM可能导致的性能下降。最后，引入多视角问答方案，增强VLM从长视频上下文中提取信息的能力。在四个公开基准上的实验表明，E-VRAG的计算成本比基线方法降低约70%，且准确率更高，无需额外训练。这些结果证明了E-VRAG在提高视频RAG任务效率和准确性方面的有效性。

> Vision-Language Models (VLMs) have enabled substantial progress in video understanding by leveraging cross-modal reasoning capabilities. However, their effectiveness is limited by the restricted context window and the high computational cost required to process long videos with thousands of frames. Retrieval-augmented generation (RAG) addresses this challenge by selecting only the most relevant frames as input, thereby reducing the computational burden. Nevertheless, existing video RAG methods struggle to balance retrieval efficiency and accuracy, particularly when handling diverse and complex video content. To address these limitations, we propose E-VRAG, a novel and efficient video RAG framework for video understanding. We first apply a frame pre-filtering method based on hierarchical query decomposition to eliminate irrelevant frames, reducing computational costs at the data level. We then employ a lightweight VLM for frame scoring, further reducing computational costs at the model level. Additionally, we propose a frame retrieval strategy that leverages the global statistical distribution of inter-frame scores to mitigate the potential performance degradation from using a lightweight VLM. Finally, we introduce a multi-view question answering scheme for the retrieved frames, enhancing the VLM's capability to extract and comprehend information from long video contexts. Experiments on four public benchmarks show that E-VRAG achieves about 70% reduction in computational cost and higher accuracy compared to baseline methods, all without additional training. These results demonstrate the effectiveness of E-VRAG in improving both efficiency and accuracy for video RAG tasks.

[Arxiv](https://arxiv.org/abs/2508.01546)