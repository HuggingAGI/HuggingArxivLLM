# PRE-MAP: 个性化强化眼动追踪多模态LLM，实现高分辨率多属性点预测

发布时间：2025年07月25日

`LLM应用` `视觉注意力模型`

> PRE-MAP: Personalized Reinforced Eye-tracking Multimodal LLM for High-Resolution Multi-Attribute Point Prediction

# 摘要

> 视觉选择性注意由个人偏好驱动，通过连接主观认知机制与客观视觉元素，调控人类对视觉刺激的优先级排序，从而引导动态视觉场景的语义解读与层次化处理。然而，现有模型与数据集主要忽略了主观认知多样性对注视行为的影响。传统显著性预测模型通常采用分割方法，依赖低分辨率图像生成显著性热图，随后放大至原生分辨率，这限制了它们捕捉个性化注意力模式的能力。此外，MLLMs受幻觉等因素限制，在涉及多个点预测的任务中严格遵循预期格式成本高昂，实现精准点定位颇具挑战。为克服这些限制，我们提出面向广告视频的主观个性化注意力模型SPA-ADV，这是一个大规模多模态数据集，记录了4500多名不同年龄和性别的参与者在486个视频上的注视行为。此外，我们提出PRE-MAP，一种新型眼动显著性模型，通过强化学习优化眼动追踪，基于MLLMs并结合多属性用户画像，用于预测点。为确保MLLMs生成的预测点在格式和空间位置上准确无误，我们引入了受眼动数据点变异性与多属性画像启发的一致性组相对策略优化（C-GRPO）。在SPA-ADV及其他基准数据集上的广泛实验验证了我们方法的有效性。代码与数据集可在此链接获取：\href{https://github.com/mininglamp-MLLM/PRE-MAP}{此链接}。

> Visual selective attention, driven by individual preferences, regulates human prioritization of visual stimuli by bridging subjective cognitive mechanisms with objective visual elements, thereby steering the semantic interpretation and hierarchical processing of dynamic visual scenes. However, existing models and datasets predominantly neglect the influence of subjective cognitive diversity on fixation behavior. Conventional saliency prediction models, typically employing segmentation approaches, rely on low-resolution imagery to generate saliency heatmaps, subsequently upscaled to native resolutions, which limiting their capacity to capture personalized attention patterns. Furthermore, MLLMs are constrained by factors such as hallucinations, making it very costly to strictly adhere to the expected format in tasks involving multiple point predictions, and achieving precise point positioning is challenging. To address these limitations, we present Subjective Personalized Attention for Advertisement Videos, namely SPA-ADV, a large-scale multimodal dataset capturing gaze behaviors from over 4,500 participants varying in age and gender with 486 videos. Furthermore, we propose PRE-MAP, a novel eye-tracking saliency model that characterizes Personalized visual disparities through Reinforcement learning-optimized Eye-tracking, built upon MLLMs and guided by Multi-Attribute user profiles to predict Points. To ensure MLLMs produce prediction points that are both format-correct and spatially accurate, we introduce Consistency Group Relative Policy Optimization (C-GRPO), inspired by the variability in eye movement points and Multi-Attribute profiles. Extensive experiments on SPA-ADV and other benchmarks demonstrate the effectiveness of our approach. The code and dataset are available at \href{https://github.com/mininglamp-MLLM/PRE-MAP}{this URL}.

[Arxiv](https://arxiv.org/abs/2507.19213)