# 基于大型语言模型的组合优化问题高效启发式生成方法

发布时间：2025年05月18日

`LLM应用` `组合优化` `优化算法`

> Efficient Heuristics Generation for Solving Combinatorial Optimization Problems Using Large Language Models

# 摘要

> 最近的研究通过提示大型语言模型（LLMs）自主生成解决组合优化问题（COPs）的启发式方法，首先提供搜索方向，然后据此推导启发式方法。然而，提示中缺乏特定任务的知识常常导致LLMs提供不具体的搜索方向，阻碍了高性能启发式方法的推导。此外，评估推导出的启发式方法仍然需要大量资源，尤其是对那些语义等价的启发式方法，经常需要不必要的资源消耗。为了使LLMs能够提供具体的搜索方向，我们提出了Hercules算法。该算法利用我们设计的核心抽象提示法（CAP）从精英启发式方法中提取核心组件，并将其作为先验知识纳入提示中。我们在理论上证明了CAP在减少不具体性方面的有效性，并在本研究中提供了实证结果。为了减少评估推导出的启发式方法所需的计算资源，我们提出了基于少量样本的性能预测提示法（PPP），这是首个针对启发式生成（HG）任务的方法。PPP通过分析新推导出的启发式方法与之前评估过的启发式方法的语义相似性，利用LLMs预测其适应度值。我们进一步为PPP开发了两个专门的机制，分别用于提高预测准确性和识别不可靠的预测。PPP的使用使Hercules更具资源效率，我们将这一变体命名为Hercules-P。在四个HG任务、五个COPs和八个LLMs上的广泛实验表明，Hercules在性能上优于现有的基于LLMs的HG算法，而Hercules-P则在最小化所需计算资源方面表现出色。此外，我们通过相关消融研究展示了CAP、PPP和其他提出机制的有效性。

> Recent studies exploited Large Language Models (LLMs) to autonomously generate heuristics for solving Combinatorial Optimization Problems (COPs), by prompting LLMs to first provide search directions and then derive heuristics accordingly. However, the absence of task-specific knowledge in prompts often leads LLMs to provide unspecific search directions, obstructing the derivation of well-performing heuristics. Moreover, evaluating the derived heuristics remains resource-intensive, especially for those semantically equivalent ones, often requiring omissible resource expenditure. To enable LLMs to provide specific search directions, we propose the Hercules algorithm, which leverages our designed Core Abstraction Prompting (CAP) method to abstract the core components from elite heuristics and incorporate them as prior knowledge in prompts. We theoretically prove the effectiveness of CAP in reducing unspecificity and provide empirical results in this work. To reduce computing resources required for evaluating the derived heuristics, we propose few-shot Performance Prediction Prompting (PPP), a first-of-its-kind method for the Heuristic Generation (HG) task. PPP leverages LLMs to predict the fitness values of newly derived heuristics by analyzing their semantic similarity to previously evaluated ones. We further develop two tailored mechanisms for PPP to enhance predictive accuracy and determine unreliable predictions, respectively. The use of PPP makes Hercules more resource-efficient and we name this variant Hercules-P. Extensive experiments across four HG tasks, five COPs, and eight LLMs demonstrate that Hercules outperforms the state-of-the-art LLM-based HG algorithms, while Hercules-P excels at minimizing required computing resources. In addition, we illustrate the effectiveness of CAP, PPP, and the other proposed mechanisms by conducting relevant ablation studies.

[Arxiv](https://arxiv.org/abs/2505.12627)