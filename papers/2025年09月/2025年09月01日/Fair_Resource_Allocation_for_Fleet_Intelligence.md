# # 车队智能中的公平资源分配

发布时间：2025年09月01日

`Agent` `基础理论`

> Fair Resource Allocation for Fleet Intelligence

# 摘要

> 资源分配是云辅助多智能体系统性能优化的关键。传统方法常忽略智能体的多样化计算能力与复杂运行环境，造成资源分配低效且不公。为此，我们开源了算法框架Fair-Synergy，它借助智能体准确率与系统资源间的凹性关系，确保集群智能中的资源分配公平性。我们扩展传统分配方法，使其涵盖由模型参数、训练数据量和任务复杂度定义的多维机器学习效用空间。在MNIST、CIFAR-10、CIFAR-100、BDD及GLUE等数据集上，结合BERT、VGG16、MobileNet和ResNets等先进视觉与语言模型，我们对Fair-Synergy展开评估。结果显示，Fair-Synergy在多智能体推理任务中性能较标准基准提升高达25%，在多智能体学习场景中提升11%。同时，我们还探究了公平性水平对最弱势、最优势及平均智能体的影响，为实现公平的集群智能提供了洞见。

> Resource allocation is crucial for the performance optimization of cloud-assisted multi-agent intelligence. Traditional methods often overlook agents' diverse computational capabilities and complex operating environments, leading to inefficient and unfair resource distribution. To address this, we open-sourced Fair-Synergy, an algorithmic framework that utilizes the concave relationship between the agents' accuracy and the system resources to ensure fair resource allocation across fleet intelligence. We extend traditional allocation approaches to encompass a multidimensional machine learning utility landscape defined by model parameters, training data volume, and task complexity. We evaluate Fair-Synergy with advanced vision and language models such as BERT, VGG16, MobileNet, and ResNets on datasets including MNIST, CIFAR-10, CIFAR-100, BDD, and GLUE. We demonstrate that Fair-Synergy outperforms standard benchmarks by up to 25% in multi-agent inference and 11% in multi-agent learning settings. Also, we explore how the level of fairness affects the least advantaged, most advantaged, and average agents, providing insights for equitable fleet intelligence.

[Arxiv](https://arxiv.org/abs/2509.03353)