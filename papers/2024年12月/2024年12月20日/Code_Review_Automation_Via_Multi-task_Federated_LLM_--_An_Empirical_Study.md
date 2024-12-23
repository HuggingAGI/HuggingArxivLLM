# 借助多任务联邦大型语言模型实现代码审查自动化——一项实证研究

发布时间：2024年12月20日

`LLM应用` `软件工程` `代码审查`

> Code Review Automation Via Multi-task Federated LLM -- An Empirical Study

# 摘要

> 代码审查是将代码部署到生产环境前的关键流程，它能验证代码、给出改进建议，还能找出像遗漏边缘情况这样的错误。在定期推出产品的项目中，同行代码审查所需的精力依旧很高。所以，软件工程（SE）研究人员对代码审查流程的自动化饶有兴趣。以往关于代码审查自动化的研究，通常把这个任务当作三个独立的子任务：审查必要性预测、审查评论生成和代码优化。我们的研究尝试（i）通过开发一个能综合处理所有任务的多任务模型来利用代码审查自动化子任务间的关系，（ii）通过使用联邦学习（FL），在基于协作大型语言模型（LLM）建模的同时，增强模型在未见过的数据上的稳健性，同时保留代码的专有特性。该研究探索了用于多任务训练的五种简单技术，包括两种顺序方法、一种并行方法和两种累积方法。结果显示，针对我们的代码审查多任务用例，顺序训练联邦LLM（FedLLM）在时间、计算和性能指标方面效率较低，相比之下，为每个任务训练单独的模型效果更好。因为顺序训练会出现灾难性遗忘，所以多任务训练中的累积微调比为单个任务训练模型的效果更佳。本研究凸显了针对SE任务的多任务FedLLM有效微调的研究需求。

> Code review is a crucial process before deploying code to production, as it validates the code, provides suggestions for improvements, and identifies errors such as missed edge cases. In projects with regular production releases, the effort required for peer code-reviews remains high. Consequently, there has been significant interest from software engineering (SE) researchers in automating the code review process. Previous research on code review automation has typically approached the task as three independent sub-tasks: review necessity prediction, review comment generation, and code refinement. Our study attempts to (i) leverage the relationships between the sub-tasks of code review automation, by developing a multi-task model that addresses all tasks in an integrated manner, and (ii) increase model robustness on unseen data via collaborative large language model (LLM) modeling, while retaining the proprietary nature of code, by using federated learning (FL). The study explores five simple techniques for multi-task training, including two sequential methods, one parallel method, and two cumulative methods. The results indicate that sequentially training a federated LLM (FedLLM) for our code review multi-task use case is less efficient in terms of time, computation, and performance metrics, compared to training separate models for each task. Because sequential training demonstrates catastrophic forgetting, alternatively cumulative fine-tuning for multi-task training performs better than training models for individual tasks. This study highlights the need for research focused on effective fine-tuning of multi-task FedLLMs for SE tasks.

[Arxiv](https://arxiv.org/abs/2412.15676)