# 大型语言模型中的推理与性能关系研究 -- o3（mini）思考更深入，而非更持久
发布时间：2025年02月21日


> The Relationship Between Reasoning and Performance in Large Language Models -- o3 (mini) Thinks Harder, Not Longer
>
> 大型语言模型在数学推理领域取得了显著进展，通过链式思维和推理时计算资源扩展实现了突破。然而，推理过程中的token使用量与准确率提升之间的关系仍存在许多未解之谜。特别是，我们不清楚不同代际模型的性能提升是源于更长的推理链，还是更高效的推理过程。我们系统性地分析了o1-mini和o3-mini变体在Omni-MATH基准测试中的链式思维长度，发现o3-mini (m)在不依赖更长推理链的情况下，仍能实现更高准确率。此外，我们发现所有模型和计算设置下，推理链延长会导致准确率普遍下降，即使控制问题难度也是如此。然而，更熟练的模型中，这种准确率下降幅度显著较小，表明新世代推理模型能更高效地利用推理时计算资源。最后，尽管o3-mini (h)相较于o3-mini (m)在准确率上略有提升，但这种提升是通过在所有问题上分配更多推理token实现的，包括o3-mini (m)已能解决的问题。这些发现揭示了模型能力与推理长度之间的关系，为效率、扩展性和评估方法提供了重要启示。
>
> https://arxiv.org/abs/2502.15631

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.15631](https://arxiv.org/abs/2502.15631)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)