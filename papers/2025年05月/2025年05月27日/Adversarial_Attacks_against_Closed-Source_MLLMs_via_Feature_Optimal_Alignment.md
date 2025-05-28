# 通过特征最优对齐对闭源MLLMs实施对抗攻击

发布时间：2025年05月27日

`LLM应用` `对抗攻击` `多模态模型`

> Adversarial Attacks against Closed-Source MLLMs via Feature Optimal Alignment

# 摘要

> 多模态大型语言模型（MLLMs）易受可迁移对抗样本影响。现有方法虽能通过全局特征（如CLIP的[CLS]标记）对齐实现定向攻击，却常忽视补丁标记中的丰富局部信息，导致特征对齐不足，迁移能力受限，尤其针对闭源模型。为解决这一问题，我们提出一种基于特征最优对齐的定向可迁移对抗攻击方法——FOA-Attack，旨在提升对抗迁移能力。具体而言，我们从全局和局部双管齐下：全局层面，引入基于余弦相似度的全局特征损失，对齐粗粒度特征；局部层面，利用Transformer的丰富局部表示，通过聚类技术提取紧凑模式，缓解冗余特征问题，并将局部特征对齐建模为最优运输问题，提出局部聚类最优运输损失优化细粒度对齐。此外，我们还设计了动态集成模型加权策略，自适应平衡多模型影响，进一步提升迁移能力。实验表明，该方法显著优于现有先进方法，尤其在向闭源MLLMs迁移时表现突出。代码已开源：https://github.com/jiaxiaojunQAQ/FOA-Attack。

> Multimodal large language models (MLLMs) remain vulnerable to transferable adversarial examples. While existing methods typically achieve targeted attacks by aligning global features-such as CLIP's [CLS] token-between adversarial and target samples, they often overlook the rich local information encoded in patch tokens. This leads to suboptimal alignment and limited transferability, particularly for closed-source models. To address this limitation, we propose a targeted transferable adversarial attack method based on feature optimal alignment, called FOA-Attack, to improve adversarial transfer capability. Specifically, at the global level, we introduce a global feature loss based on cosine similarity to align the coarse-grained features of adversarial samples with those of target samples. At the local level, given the rich local representations within Transformers, we leverage clustering techniques to extract compact local patterns to alleviate redundant local features. We then formulate local feature alignment between adversarial and target samples as an optimal transport (OT) problem and propose a local clustering optimal transport loss to refine fine-grained feature alignment. Additionally, we propose a dynamic ensemble model weighting strategy to adaptively balance the influence of multiple models during adversarial example generation, thereby further improving transferability. Extensive experiments across various models demonstrate the superiority of the proposed method, outperforming state-of-the-art methods, especially in transferring to closed-source MLLMs. The code is released at https://github.com/jiaxiaojunQAQ/FOA-Attack.

[Arxiv](https://arxiv.org/abs/2505.21494)