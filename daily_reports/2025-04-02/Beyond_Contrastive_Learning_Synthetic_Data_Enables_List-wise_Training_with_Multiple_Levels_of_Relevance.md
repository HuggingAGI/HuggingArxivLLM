# # 超越对比学习：合成数据助力多层级相关性列表式训练
对比学习一直是机器学习领域的重要方法。如今，合成数据的引入使我们能够实现基于多层级相关性的列表式训练，这一突破标志着机器学习技术的又一次飞跃。
发布时间：2025年03月29日


> Beyond Contrastive Learning: Synthetic Data Enables List-wise Training with Multiple Levels of Relevance
>
> 大型语言模型（LLMs）的最新进展使合成数据在信息检索（IR）管道中得到了广泛应用。然而，当前主流的训练方法仍然是基于二元相关标签和InfoNCE损失的对比学习，即一个正样本与一个或多个负样本进行比较。这种设定将所有未标注为相关的文档一概视为负样本，忽视了它们实际相关性的细微差别，导致（a）丢失对排序有帮助的微妙信息，（b）易受标注噪声影响。为突破这一限制，我们完全摒弃真实训练文档和标注，改用开源LLMs直接生成合成文档，这些文档能够根据不同相关性级别准确回答真实用户查询。结合渐进相关性的合成排名上下文与适当的列表级损失（Wasserstein距离），我们的方法能够更精准地捕捉排序任务的本质。实验结果表明，与传统InfoNCE训练相比，我们的方法在各类IR数据集上表现显著更优。无需使用任何真实文档训练，我们的密集检索器性能远超自监督训练的同类模型。更重要的是，它与使用真实标注文档训练的模型表现相当，同时在分布偏移场景下更具鲁棒性，并在BEIR数据集的零样本评估中表现更佳。
>
> https://arxiv.org/abs/2503.23239

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23239](https://arxiv.org/abs/2503.23239)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)