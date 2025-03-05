# DivPrune：基于多样性的大规模多模态模型视觉标记剪枝

发布时间：2025年03月03日

`其他` `多模态` `模型优化`

> DivPrune: Diversity-based Visual Token Pruning for Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）作为强大的模型应运而生，能够理解文本、图像和视频等多种数据模态。LMMs将文本和视觉数据编码为token，然后通过集成的大型语言模型（LLM）对这些token进行融合和处理。然而，引入视觉token会大幅增加总token数量，通常增加数千个。LLM的输入长度增加显著提升了推理复杂度，导致LMMs出现高延迟。为了解决这一问题，我们提出了token剪枝方法，通过移除部分视觉token来优化性能。现有的token剪枝方法要么需要大量校准和微调，要么依赖次优的重要度指标，这会导致保留的token之间存在较多冗余。本文首先将token剪枝定义为最大最小多样性问题（MMDP），目标是从所有token中选择一个子集，使得所选token之间的多样性最大化。然后，我们通过求解MMDP来获得最优子集，并对剩余token进行剪枝。所提方法DivPrune通过最大化token多样性来减少冗余，即使在高剪枝比例下也能保持有效性能，且无需微调。在多种LMM上的大量实验表明，DivPrune在16个图像和视频语言数据集上实现了最先进的精度。此外，DivPrune还显著降低了测试模型的端到端延迟和GPU内存使用。代码可在此处获取：【数学公式】。
    

> Large Multimodal Models (LMMs) have emerged as powerful models capable of understanding various data modalities, including text, images, and videos. LMMs encode both text and visual data into tokens that are then combined and processed by an integrated Large Language Model (LLM). Including visual tokens substantially increases the total token count, often by thousands. The increased input length for LLM significantly raises the complexity of inference, resulting in high latency in LMMs. To address this issue, token pruning methods, which remove part of the visual tokens, are proposed. The existing token pruning methods either require extensive calibration and fine-tuning or rely on suboptimal importance metrics which results in increased redundancy among the retained tokens. In this paper, we first formulate token pruning as Max-Min Diversity Problem (MMDP) where the goal is to select a subset such that the diversity among the selected {tokens} is maximized. Then, we solve the MMDP to obtain the selected subset and prune the rest. The proposed method, DivPrune, reduces redundancy and achieves the highest diversity of the selected tokens. By ensuring high diversity, the selected tokens better represent the original tokens, enabling effective performance even at high pruning ratios without requiring fine-tuning. Extensive experiments with various LMMs show that DivPrune achieves state-of-the-art accuracy over 16 image- and video-language datasets. Additionally, DivPrune reduces both the end-to-end latency and GPU memory usage for the tested models. The code is available $\href{https://github.com/vbdi/divprune}{\text{here}}$.

[Arxiv](https://arxiv.org/abs/2503.02175)