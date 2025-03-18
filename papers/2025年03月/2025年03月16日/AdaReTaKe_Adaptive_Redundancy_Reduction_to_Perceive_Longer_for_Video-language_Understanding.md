# # 标题
AdaReTaKe：自适应冗余减少，助力视频语言理解感知更远

发布时间：2025年03月16日

`LLM应用` `视频处理` `视频理解`

> AdaReTaKe: Adaptive Redundancy Reduction to Perceive Longer for Video-language Understanding

# 摘要

> 多模态大语言模型（MLLMs）彻底改变了视频理解的方式，但在处理长视频时仍受限于上下文长度。近期方法通过均匀利用视觉冗余压缩视频，取得了令人鼓舞的结果。然而，我们的定量分析表明，冗余在时间和模型层之间存在显著差异，因此需要更加灵活的压缩策略。我们提出了无训练的AdaReTaKe方法，通过在时间和层之间灵活分配压缩比率来减少视觉冗余，并提供理论保证。将其集成到最先进的MLLMs中，AdaReTaKe将处理能力从256帧提升至2048帧，同时保留关键信息。在VideoMME、MLVU、LongVideoBench和LVBench数据集上的实验表明，AdaReTaKe分别比现有方法高出2.3%和2.8%的性能，针对7B和72B模型，而在最长的LVBench上更是提升了5.9%和6.0%。我们的代码可在https://github.com/SCZwangxiao/video-FlexReduc.git获取。

> Multimodal Large Language Models (MLLMs) have revolutionized video understanding, yet are still limited by context length when processing long videos. Recent methods compress videos by leveraging visual redundancy uniformly, yielding promising results. Nevertheless, our quantitative analysis shows that redundancy varies significantly across time and model layers, necessitating a more flexible compression strategy. We propose AdaReTaKe, a training-free method that flexibly reduces visual redundancy by allocating compression ratios among time and layers with theoretical guarantees. Integrated into state-of-the-art MLLMs, AdaReTaKe improves processing capacity from 256 to 2048 frames while preserving critical information. Experiments on VideoMME, MLVU, LongVideoBench, and LVBench datasets demonstrate that AdaReTaKe outperforms existing methods by 2.3% and 2.8% for 7B and 72B models, respectively, with even greater improvements of 5.9% and 6.0% on the longest LVBench. Our code is available at https://github.com/SCZwangxiao/video-FlexReduc.git.

[Arxiv](https://arxiv.org/abs/2503.12559)