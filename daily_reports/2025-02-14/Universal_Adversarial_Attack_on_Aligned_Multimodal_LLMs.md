# 通用对抗攻击：对齐的多模态大型语言模型
发布时间：2025年02月13日

`模型安全`
> Universal Adversarial Attack on Aligned Multimodal LLMs
>
> 我们提出了一种针对多模态大型语言模型 (LLMs) 的通用对抗攻击方法，通过一张精心优化的图像，能够在多种查询甚至多个模型上绕过对齐防护机制。通过反向传播到视觉编码器和语言头，我们生成了一张合成图像，迫使模型以特定短语（例如“当然，这里就是”）或不安全内容（即使是恶意提示）进行响应。在 SafeBench 基准测试中，我们的方法相较于现有基线（包括仅文本的通用提示，例如对某些模型可达93%）取得了显著更高的攻击成功率。我们还通过同时训练多个多模态 LLM 并测试未见架构，展示了跨模型的迁移能力。此外，我们方法的多答案变体能够生成更自然（但仍然恶意）的响应。这些发现突显了当前多模态对齐中的关键漏洞，并呼吁更强大的对抗防御机制。我们将在 Apache-2.0 许可证下发布代码和数据集。警告：本文中多模态 LLM 生成的一些内容可能会冒犯某些读者。
>
> https://arxiv.org/abs/2502.07987

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07987](https://arxiv.org/abs/2502.07987)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)