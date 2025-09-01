# # 超越BEV：面向协同感知的点级令牌优化

发布时间：2025年08月27日

`Agent` `交通运输`

> Beyond BEV: Optimizing Point-Level Tokens for Collaborative Perception

# 摘要

> 协作感知技术让智能体通过共享中间特征来提升感知能力。现有方法常将这些中间特征转化为二维鸟瞰图（BEV）表示，却丢失了准确识别和定位目标所必需的细粒度3D结构细节。为此，我们首次提出将点级令牌作为协作感知的中间表示。但点云数据天生无序、规模庞大且位置敏感，要生成既能保留结构细节、又紧凑对齐的点级令牌序列并非易事。于是，我们推出了CoPLOT——一种基于点级优化令牌的全新协作感知框架。该框架打造了点原生处理流水线，涵盖令牌重排序、序列建模和多智能体空间对齐三大核心环节：语义感知令牌重排序模块借助场景级与令牌级语义信息，生成自适应一维序列；频率增强状态空间模型跨空间与频谱维度捕捉长程依赖，强化前景令牌与背景杂波的区分度；邻居到自车对齐模块则通过闭环处理，融合全局智能体级校正与局部令牌级优化，有效降低定位噪声。在模拟与真实数据集上的大量实验证实，CoPLOT不仅性能超越现有最优模型，还大幅降低了通信与计算开销。项目代码将开源于https://github.com/CheeryLeeyy/CoPLOT。

> Collaborative perception allows agents to enhance their perceptual capabilities by exchanging intermediate features. Existing methods typically organize these intermediate features as 2D bird's-eye-view (BEV) representations, which discard critical fine-grained 3D structural cues essential for accurate object recognition and localization. To this end, we first introduce point-level tokens as intermediate representations for collaborative perception. However, point-cloud data are inherently unordered, massive, and position-sensitive, making it challenging to produce compact and aligned point-level token sequences that preserve detailed structural information. Therefore, we present CoPLOT, a novel Collaborative perception framework that utilizes Point-Level Optimized Tokens. It incorporates a point-native processing pipeline, including token reordering, sequence modeling, and multi-agent spatial alignment. A semantic-aware token reordering module generates adaptive 1D reorderings by leveraging scene-level and token-level semantic information. A frequency-enhanced state space model captures long-range sequence dependencies across both spatial and spectral domains, improving the differentiation between foreground tokens and background clutter. Lastly, a neighbor-to-ego alignment module applies a closed-loop process, combining global agent-level correction with local token-level refinement to mitigate localization noise. Extensive experiments on both simulated and real-world datasets show that CoPLOT outperforms state-of-the-art models, with even lower communication and computation overhead. Code will be available at https://github.com/CheeryLeeyy/CoPLOT.

[Arxiv](https://arxiv.org/abs/2508.19638)