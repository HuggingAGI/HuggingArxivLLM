# EventGPT：借助多模态大型语言模型来理解事件流
发布时间：2024年12月01日


> EventGPT: Event Stream Understanding with Multimodal Large Language Models
>
> 事件相机以异步像素变化流的形式记录视觉信息，在照明不佳或高动态条件下的场景感知中表现卓越。现有的多模态大型语言模型（MLLMs）侧重于自然RGB图像，在事件数据更适用的场景中表现欠佳。在本文中，据我们所知，我们推出了EventGPT，这是首个用于事件流理解的MLLM，开创了将大型语言模型（LLMs）与事件流理解相融合的先河。为缩小巨大的领域差距，我们开发了一个三阶段优化模式，逐步赋予预训练的LLM理解基于事件场景的能力。我们的EventGPT包含一个事件编码器，其后依次是时空聚合器、线性投影仪、事件语言适配器和LLM。首先，借助GPT生成的RGB图像文本对来预热线性投影仪，参考LLaVA，因为自然图像与语言模式之间的差距相对较小。其次，我们构建了一个合成但规模较大的数据集N-ImageNet-Chat，由事件帧及相应文本组成，用于启用时空聚合器并训练事件语言适配器，从而使事件特征与语言空间更紧密地匹配。最后，我们收集了一个指令数据集Event-Chat，其中包含大量真实世界数据，用于对整个模型进行微调，进一步增强其泛化能力。我们构建了一个综合基准，实验表明，EventGPT在生成质量、描述准确性和推理能力方面超越了以往最先进的MLLMs。
>
> https://arxiv.org/abs/2412.00832

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.00832](https://arxiv.org/abs/2412.00832)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)