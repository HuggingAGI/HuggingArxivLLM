# 为多模态语义分割定制带有 LoRA 专家混合的 Segment Anything 模型
发布时间：2024年12月05日


> Customize Segment Anything Model for Multi-Modal Semantic Segmentation with Mixture of LoRA Experts
>
> 近期的 Segment Anything 模型（SAM）在分割模型的规模扩展上实现了重大突破，在 RGB 模式的各类下游应用中表现强劲。然而，将 SAM 直接用于新兴视觉模式，如深度和事件数据时，在多模态分割任务中的表现欠佳。在本文中，我们首次尝试通过提出针对不同输入视觉模式定制的低秩适应专家混合（MoE-LoRA）来让 SAM 适配多模态语义分割。仅训练 MoE-LoRA 层，同时保持 SAM 的权重固定，能为下游任务留存 SAM 强大的泛化和分割能力。具体而言，为应对跨模态不一致的情况，我们提出了一种新颖的 MoE 路由策略，能自适应地跨模态生成加权特征，强化多模态特征的整合。另外，我们通过调整 SAM 的分割头并引入辅助分割头来融合多尺度特征，实现多尺度特征的提取和融合，有效提升分割性能。在 DELIVER、MUSES 和 MCubeS 这三个多模态基准上进行了大量实验。结果一致显示，所提方法在不同场景下显著优于前沿方法。特别值得注意的是，在模态缺失这一极具挑战性的条件下，我们的方法展现出显著的性能增益，与现有方法相比提升了 32.15%。
>
> https://arxiv.org/abs/2412.04220

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.04220](https://arxiv.org/abs/2412.04220)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)