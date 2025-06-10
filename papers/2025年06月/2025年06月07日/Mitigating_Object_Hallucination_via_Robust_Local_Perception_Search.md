# 通过鲁棒局部感知搜索缓解物体幻觉

发布时间：2025年06月07日

`LLM应用` `计算机视觉` `图像处理`

> Mitigating Object Hallucination via Robust Local Perception Search

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展使其能够高效整合视觉与语言，应对多种下游任务。然而，尽管取得了显著成功，这些模型仍会出现幻觉现象，即输出看似合理却与图像内容不符。为解决这一问题，我们提出了一种简单且无需训练的推理解码方法——局部感知搜索（LPS），该方法能有效抑制幻觉。通过利用局部视觉先验信息作为价值函数，LPS能够修正解码过程。值得注意的是，局部视觉先验对模型性能的影响在高噪声图像场景中尤为显著。此外，LPS是一种即插即用的方法，能够与多种模型兼容。在广泛使用的幻觉基准测试和噪声数据上的大量实验表明，与基线相比，LPS显著减少了幻觉的发生，尤其在噪声环境下表现尤为出色。

> Recent advancements in Multimodal Large Language Models (MLLMs) have enabled them to effectively integrate vision and language, addressing a variety of downstream tasks. However, despite their significant success, these models still exhibit hallucination phenomena, where the outputs appear plausible but do not align with the content of the images. To mitigate this issue, we introduce Local Perception Search (LPS), a decoding method during inference that is both simple and training-free, yet effectively suppresses hallucinations. This method leverages local visual prior information as a value function to correct the decoding process. Additionally, we observe that the impact of the local visual prior on model performance is more pronounced in scenarios with high levels of image noise. Notably, LPS is a plug-and-play approach that is compatible with various models. Extensive experiments on widely used hallucination benchmarks and noisy data demonstrate that LPS significantly reduces the incidence of hallucinations compared to the baseline, showing exceptional performance, particularly in noisy settings.

[Arxiv](https://arxiv.org/abs/2506.06729)