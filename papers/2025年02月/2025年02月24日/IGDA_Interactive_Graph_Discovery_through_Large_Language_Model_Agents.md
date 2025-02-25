# IGDA：借助大型语言模型智能体实现交互式图发现

发布时间：2025年02月24日

`LLM应用` `图发现` `数据科学`

> IGDA: Interactive Graph Discovery through Large Language Model Agents

# 摘要

> 大型语言模型（$	extbf{LLMs}$）作为一种强大的发现工具应运而生。与传统的数值数据不同，LLMs通过关联变量的$	extit{语义元数据}$来预测变量间的关系。同时，当给定一个目标函数$f$和一系列试验时，LLMs展现出作为黑箱优化器的卓越能力。我们聚焦于LLMs的这两个能力的交叉点，将其应用于$	extit{交互式图发现}$任务：给定一个捕获变量关系的真实图$G^*$，以及在$R$轮试验中进行$I$次边实验的预算，目标是在第$R$轮结束时，将预测图$\hat{G}_R$与真实图$G^*$之间的距离最小化。为了解决这一任务，我们提出了$	extbf{IGDA}$，一个基于LLMs的管道，包含两个关键组件：1）一种基于LLMs不确定性驱动的边实验选择方法；2）一种利用实验二进制反馈来改进未选邻接边预测的局部图更新策略。在八种不同真实图上的实验表明，我们的方法通常优于所有基线，包括交互式图发现中最先进的数值方法。此外，我们进行了一系列严格的消融实验，以解析管道每个组件的影响。最后，为了评估记忆化的影响，我们将交互式图发现策略应用于一个复杂的新（截至2024年7月）蛋白质转录因子因果图，在记忆化不可能的设置下取得了强劲的性能。总体而言，我们的结果表明，IGDA是一种强大的图发现方法，与现有的数值驱动方法相辅相成。

> Large language models ($\textbf{LLMs}$) have emerged as a powerful method for discovery. Instead of utilizing numerical data, LLMs utilize associated variable $\textit{semantic metadata}$ to predict variable relationships. Simultaneously, LLMs demonstrate impressive abilities to act as black-box optimizers when given an objective $f$ and sequence of trials. We study LLMs at the intersection of these two capabilities by applying LLMs to the task of $\textit{interactive graph discovery}$: given a ground truth graph $G^*$ capturing variable relationships and a budget of $I$ edge experiments over $R$ rounds, minimize the distance between the predicted graph $\hat{G}_R$ and $G^*$ at the end of the $R$-th round. To solve this task we propose $\textbf{IGDA}$, a LLM-based pipeline incorporating two key components: 1) an LLM uncertainty-driven method for edge experiment selection 2) a local graph update strategy utilizing binary feedback from experiments to improve predictions for unselected neighboring edges. Experiments on eight different real-world graphs show our approach often outperforms all baselines including a state-of-the-art numerical method for interactive graph discovery. Further, we conduct a rigorous series of ablations dissecting the impact of each pipeline component. Finally, to assess the impact of memorization, we apply our interactive graph discovery strategy to a complex, new (as of July 2024) causal graph on protein transcription factors, finding strong performance in a setting where memorization is impossible. Overall, our results show IGDA to be a powerful method for graph discovery complementary to existing numerically driven approaches.

[Arxiv](https://arxiv.org/abs/2502.17189)