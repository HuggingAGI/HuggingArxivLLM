# # 摘要  
    近期大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现。

发布时间：2025年05月29日

`LLM理论` `机器学习`

> Diversity of Transformer Layers: One Aspect of Parameter Scaling Laws

# 摘要

> Transformer模型在众多任务中表现卓越，现已成为大型语言模型（LLMs）的核心架构。研究表明，增加参数规模能提升模型性能，这一点在参数缩放规律研究中得到证实。尽管通过解析残差流来研究Transformer内部机制的可解释性研究有所突破，但这些机制与参数缩放规律之间的关系仍不明确。为解决这一问题，我们聚焦于模型的层数及其规模，因为它们是决定Transformer参数总量的关键因素。为此，我们首先通过偏差-多样性分解，从理论上探究残差流中的各层。这种分解将（i）偏差，即每层输出与真实结果的误差，以及（ii）多样性，即各层输出彼此之间的差异程度区分开来。基于此理论分析Transformer模型，我们发现当各层的预测结果接近正确答案且彼此保持高度多样性时，模型性能得以提升。我们进一步证明，当各层输出远离真实结果时，多样性尤为重要。最后，我们引入信息论视角下的多样性概念，揭示了我们的核心发现：仅当新增的层表现出不同行为（即具有多样性）时，增加层数才能提升性能。我们还发现，增加层数带来的性能提升呈现次可加性：随着层数的增加，边际提升逐渐减弱，这一现象与参数缩放规律预测的对数收敛趋势相吻合。通过在多种语义理解任务上使用不同LLMs进行实验，我们实证验证了本研究中推导出的理论特性。

> Transformers deliver outstanding performance across a wide range of tasks and are now a dominant backbone architecture for large language models (LLMs). Their task-solving performance is improved by increasing parameter size, as shown in the recent studies on parameter scaling laws. Although recent mechanistic-interpretability studies have deepened our understanding of the internal behavior of Transformers by analyzing their residual stream, the relationship between these internal mechanisms and the parameter scaling laws remains unclear. To bridge this gap, we focus on layers and their size, which mainly decide the parameter size of Transformers. For this purpose, we first theoretically investigate the layers within the residual stream through a bias-diversity decomposition. The decomposition separates (i) bias, the error of each layer's output from the ground truth, and (ii) diversity, which indicates how much the outputs of each layer differ from each other. Analyzing Transformers under this theory reveals that performance improves when individual layers make predictions close to the correct answer and remain mutually diverse. We show that diversity becomes especially critical when individual layers' outputs are far from the ground truth. Finally, we introduce an information-theoretic diversity and show our main findings that adding layers enhances performance only when those layers behave differently, i.e., are diverse. We also reveal the performance gains from increasing the number of layers exhibit submodularity: marginal improvements diminish as additional layers increase, mirroring the logarithmic convergence predicted by the parameter scaling laws. Experiments on multiple semantic-understanding tasks with various LLMs empirically confirm the theoretical properties derived in this study.

[Arxiv](https://arxiv.org/abs/2505.24009)