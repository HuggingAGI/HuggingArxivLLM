# VideoLights：用于联合视频亮点检测与时刻检索的特征精修和跨任务对齐转换器

发布时间：2024年12月02日

`LLM应用` `视频分析` `多模态融合`

> VideoLights: Feature Refinement and Cross-Task Alignment Transformer for Joint Video Highlight Detection and Moment Retrieval

# 摘要

> 视频亮点检测和时刻检索（HD/MR）在视频分析中极其重要。近期的联合预测变压器模型往往忽视了其跨任务动态以及视频与文本的对齐和优化。而且，多数模型通常采用有限的单向注意力机制，致使表示集成度低，在捕捉视频和文本模式的相互依赖关系时表现不佳。尽管大型语言和视觉 - 语言模型（LLM/LVLMs）在众多领域已大放异彩，但在该领域的应用仍相对较少。在此，我们提出 VideoLights 这一新颖的 HD/MR 框架，通过（i）带有对齐损失的卷积投影和特征优化模块，实现更优的视频 - 文本特征对齐；（ii）双向跨模态融合网络，获取强耦合的查询感知剪辑表示；（iii）单向联合任务反馈机制，借助相关性增强两项任务。另外，（iv）引入硬正/负损失，用于自适应错误惩罚和改进学习；（v）利用如 BLIP - 2 之类的 LVLMs，进行强化的多模态特征集成，并使用由 LVLMs 生成的合成数据开展智能预训练。在 QVHighlights、TVSum 和 Charades - STA 基准上的综合实验呈现出了最先进的性能。代码和模型可在 https://github.com/dpaul06/VideoLights 获取。

> Video Highlight Detection and Moment Retrieval (HD/MR) are essential in video analysis. Recent joint prediction transformer models often overlook their cross-task dynamics and video-text alignment and refinement. Moreover, most models typically use limited, uni-directional attention mechanisms, resulting in weakly integrated representations and suboptimal performance in capturing the interdependence between video and text modalities. Although large-language and vision-language models (LLM/LVLMs) have gained prominence across various domains, their application in this field remains relatively underexplored. Here we propose VideoLights, a novel HD/MR framework addressing these limitations through (i) Convolutional Projection and Feature Refinement modules with an alignment loss for better video-text feature alignment, (ii) Bi-Directional Cross-Modal Fusion network for strongly coupled query-aware clip representations, and (iii) Uni-directional joint-task feedback mechanism enhancing both tasks through correlation. In addition, (iv) we introduce hard positive/negative losses for adaptive error penalization and improved learning, and (v) leverage LVLMs like BLIP-2 for enhanced multimodal feature integration and intelligent pretraining using synthetic data generated from LVLMs. Comprehensive experiments on QVHighlights, TVSum, and Charades-STA benchmarks demonstrate state-of-the-art performance. Codes and models are available at https://github.com/dpaul06/VideoLights .

[Arxiv](https://arxiv.org/abs/2412.01558)