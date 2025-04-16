# RealSafe-R1：安全对齐的DeepSeek-R1，同时保持推理能力不妥协
发布时间：2025年04月14日


> RealSafe-R1: Safety-Aligned DeepSeek-R1 without Compromising Reasoning Capability
>
> 大型推理模型（LRMs）如 OpenAI o1 和 DeepSeek-R1 正快速发展，并在数学和编程等复杂推理任务中取得了突破性表现。然而，开源的 R1 模型在广泛应用中引发了安全担忧，例如倾向于响应恶意查询，这严重影响了这些强大模型在实际应用中的效果。本文中，我们介绍了 RealSafe-R1，这是基于 DeepSeek-R1 蒸馏模型的安全对齐版本。为了训练这些模型，我们构建了一个包含 15,000 个安全意识推理轨迹的数据集，这些轨迹由 DeepSeek-R1 生成，并遵循了预期的拒绝行为指令。定量实验和定性案例研究表明，这些模型在安全性方面有了显著提升，具体表现在其对有害查询和越狱攻击的安全护栏上。值得注意的是，与以往经常损害推理性能的安全对齐方法不同，我们的方法通过保持训练数据在原始生成分布内，保留了模型的推理能力。RealSafe-R1 的模型权重在 https://huggingface.co/RealSafe 上开源。
>
> https://arxiv.org/abs/2504.10081

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.10081](https://arxiv.org/abs/2504.10081)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)