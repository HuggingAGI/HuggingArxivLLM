# 语言与递归查询的结合方法
发布时间：2025年04月03日

`代码编写`
> Language-Integrated Recursive Queries
>
> 在对性能要求严格的工业应用中，包括大规模程序、网络和分布式系统分析，定点计算发挥着关键作用。SQL:1999引入的递归公共表表达式（CTEs）通过WITH RECURSIVE关键词，显著增强了关系型数据库处理定点计算的能力，将计算靠近数据，带来性能提升。然而，递归使得SQL具备图灵完备性，同时也引入了安全性和正确性风险。SQL语义模糊，不同数据库供应商处理方式各异，导致推理递归SQL程序的正确性需依赖孤立的数学属性，而非统一的形式化模型。为应对这些挑战，我们提出了一种演算，从嵌入式递归查询中自动推导数学属性，并根据数据库后端，拒绝可能导致三类错误的查询：数据库错误、不正确结果和非终止。我们开发了TyQL，一个用Scala实现的安全递归语言集成查询工具。通过命名元组和类型级模式匹配，TyQL确保查询的可移植性和安全性，性能与原始SQL相当，且比非递归查询快三个数量级。
>
> https://arxiv.org/abs/2504.02443

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.02443](https://arxiv.org/abs/2504.02443)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)