# 深度探索：一场定向视觉幻觉的奇幻之旅——揭示表征漏洞背后的视觉魔法
发布时间：2025年02月11日

`模型安全`
> DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities
>
> # 摘要
多模态大型语言模型（MLLMs）代表着AI技术的最前沿，其中DeepSeek模型作为开源领域的佼佼者，其性能已可与闭源系统相媲美。然而，这些模型在展现强大能力的同时，其视觉语言融合机制也带来了特定的脆弱性。我们针对DeepSeek Janus实施了一种适应性嵌入操控攻击，通过系统性优化图像嵌入，成功诱导目标视觉幻觉的产生。在COCO、DALL-E 3和SVIT数据集上的广泛实验表明，我们在开放性问题上实现了高达98.0%的幻觉率，同时保持了被操控图像的高视觉保真度（SSIM > 0.88）。分析表明，无论是1B还是7B版本的DeepSeek Janus均易受此类攻击影响，且闭合形式评估显示与开放性提问相比，幻觉率始终保持更高水平。我们引入了一种基于LLaMA-3.1 8B Instruct的新型多提示幻觉检测框架，用于稳健评估。鉴于DeepSeek的开源特性和广泛应用潜力，这些发现的潜在影响尤为令人担忧。本研究强调了在MLLM部署流水线中实施嵌入级安全措施的迫切需求，并为负责任的AI实现的更广泛讨论做出了贡献。
>
> https://arxiv.org/abs/2502.07905

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07905](https://arxiv.org/abs/2502.07905)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)