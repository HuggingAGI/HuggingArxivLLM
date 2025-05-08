# M2Rec: 多尺度 Mamba 实现高效序列推荐

发布时间：2025年05月07日

`LLM应用` `电子商务`

> M2Rec: Multi-scale Mamba for Efficient Sequential Recommendation

# 摘要

> 序列推荐系统的目标是根据用户的交互历史预测其下一步偏好，但现有方法在效率和多尺度模式识别方面存在关键挑战。虽然基于Transformer的方法在计算复杂度上表现欠佳，但近期基于Mamba的模型虽然提升了效率，却未能捕捉到周期性用户行为，也无法充分利用丰富的语义信息或有效融合多模态特征。为了解决这些问题，我们提出了\mode，一个结合多尺度Mamba与傅里叶分析、大型语言模型（LLMs）和自适应门控机制的新型序列推荐框架。首先，我们通过快速傅里叶变换（FFT）增强Mamba，以显式建模频率域中的周期性模式，分离出有意义的趋势与噪声。其次，我们引入基于LLM的文本嵌入，利用商品描述中的语义上下文丰富稀疏的交互数据。最后，我们引入了一种可学习的门控机制，动态平衡时序（Mamba）、频率（FFT）和语义（LLM）特征，确保多模态特征的和谐融合。大量实验表明，\model在点击率@10指标上比现有基于Mamba的模型提升了3.2%，同时推理速度比Transformer基线快20%。我们的结果凸显了将频率分析、语义理解和自适应融合相结合在序列推荐中的有效性。代码和数据集可在以下链接获取：https://anonymous.4open.science/r/M2Rec.

> Sequential recommendation systems aim to predict users' next preferences based on their interaction histories, but existing approaches face critical limitations in efficiency and multi-scale pattern recognition. While Transformer-based methods struggle with quadratic computational complexity, recent Mamba-based models improve efficiency but fail to capture periodic user behaviors, leverage rich semantic information, or effectively fuse multimodal features. To address these challenges, we propose \model, a novel sequential recommendation framework that integrates multi-scale Mamba with Fourier analysis, Large Language Models (LLMs), and adaptive gating. First, we enhance Mamba with Fast Fourier Transform (FFT) to explicitly model periodic patterns in the frequency domain, separating meaningful trends from noise. Second, we incorporate LLM-based text embeddings to enrich sparse interaction data with semantic context from item descriptions. Finally, we introduce a learnable gate mechanism to dynamically balance temporal (Mamba), frequency (FFT), and semantic (LLM) features, ensuring harmonious multimodal fusion. Extensive experiments demonstrate that \model\ achieves state-of-the-art performance, improving Hit Rate@10 by 3.2\% over existing Mamba-based models while maintaining 20\% faster inference than Transformer baselines. Our results highlight the effectiveness of combining frequency analysis, semantic understanding, and adaptive fusion for sequential recommendation. Code and datasets are available at: https://anonymous.4open.science/r/M2Rec.

[Arxiv](https://arxiv.org/abs/2505.04445)