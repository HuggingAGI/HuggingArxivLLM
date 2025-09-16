# # 多模态检索的率失真极限：理论、最优码及有限样本保证

发布时间：2025年09月13日

`其他` `基础理论`

> Rate-Distortion Limits for Multimodal Retrieval: Theory, Optimal Codes, and Finite-Sample Guarantees

# 摘要

> 我们首次确立了多模态检索的信息论极限。通过将排序转化为有损信源编码问题，我们推导出互反排序失真的单字母率失真函数【数学公式】，并证明了一个逆界——该逆界由模态平衡项与捕捉熵不平衡及跨模态冗余的偏斜惩罚项【数学公式】共同构成。随后，我们构建了带自适应逐模态温度解码器的显式熵加权随机量化器；Blahut-Arimoto论证显示，利用n个训练三元组，该方案可将失真控制在【数学公式】的O(n⁻¹)范围内。VC型分析进一步得到首个有限样本超额风险界，其复杂度在模态数量与熵差距两方面均呈亚线性增长。在受控高斯混合模型与Flickr30k数据集上的实验表明，我们的自适应编码性能达到理论前沿的两个百分点以内，而固定温度及朴素CLIP基线则显著落后。综上，我们的研究结果为高质量多模态检索中“每个查询需多少比特”这一问题提供了理论依据，并为熵感知对比目标、持续学习检索器及检索增强生成器的设计提供了指导。

> We establish the first information-theoretic limits for multimodal retrieval. Casting ranking as lossy source coding, we derive a single-letter rate-distortion function $R(D)$ for reciprocal-rank distortion and prove a converse bound that splits into a modality-balanced term plus a skew penalty $κ\,ΔH$ capturing entropy imbalance and cross-modal redundancy. We then construct an explicit entropy-weighted stochastic quantizer with an adaptive, per-modality temperature decoder; a Blahut-Arimoto argument shows this scheme achieves distortion within $O(n^{-1})$ of $R(D)$ using $n$ training triples. A VC-type analysis yields the first finite-sample excess-risk bound whose complexity scales sub-linearly in both the number of modalities and the entropy gap. Experiments on controlled Gaussian mixtures and Flickr30k confirm that our adaptive codes sit within two percentage points of the theoretical frontier, while fixed-temperature and naive CLIP baselines lag significantly. Taken together, our results give a principled answer to "how many bits per query are necessary" for high-quality multimodal retrieval and provide design guidance for entropy-aware contrastive objectives, continual-learning retrievers, and retrieval-augmented generators.

[Arxiv](https://arxiv.org/abs/2509.11054)