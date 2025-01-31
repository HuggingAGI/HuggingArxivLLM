# 智胜一筹：基于推理感知优化的自适应推理

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文主要讨论了如何通过推理预算约束策略优化（IBPO）来提升大型语言模型在解决数学问题时的效率。这属于对大型语言模型在实际应用中的优化和改进，因此应归类为LLM应用。` `人工智能`

> Think Smarter not Harder: Adaptive Reasoning with Inference Aware Optimization

# 摘要

> 解决数学问题是大型语言模型的一大亮点，许多研究通过扩展推理长度（如自我纠正和长链思维）来提升推理能力。然而，高级的长推理链模型在处理简单问题时，往往表现出不必要的冗长思维链。为此，我们提出了一种新方法——推理预算约束策略优化（IBPO），通过将推理预算约束下的效用最大化，让模型能够“感知”推理预算。简而言之，经过IBPO微调的模型能够根据问题的难度合理分配推理预算。在不同预算下，我们的最佳模型在MATH500数据集上，分别使用2.16倍和4.32倍的推理预算，相比LLaMA3.1 8B Instruct，实现了4.14%和5.74%的绝对提升（相对提升分别为8.08%和11.2%），这一提升大约是相同预算下自一致性改进的两倍。

> Solving mathematics problems has been an intriguing capability of large language models, and many efforts have been made to improve reasoning by extending reasoning length, such as through self-correction and extensive long chain-of-thoughts. While promising in problem-solving, advanced long reasoning chain models exhibit an undesired single-modal behavior, where trivial questions require unnecessarily tedious long chains of thought. In this work, we propose a way to allow models to be aware of inference budgets by formulating it as utility maximization with respect to an inference budget constraint, hence naming our algorithm Inference Budget-Constrained Policy Optimization (IBPO). In a nutshell, models fine-tuned through IBPO learn to ``understand'' the difficulty of queries and allocate inference budgets to harder ones. With different inference budgets, our best models are able to have a $4.14$\% and $5.74$\% absolute improvement ($8.08$\% and $11.2$\% relative improvement) on MATH500 using $2.16$x and $4.32$x inference budgets respectively, relative to LLaMA3.1 8B Instruct. These improvements are approximately $2$x those of self-consistency under the same budgets.

[Arxiv](https://arxiv.org/abs/2501.17974)