# 提出了一种基于Frobenius范数的无数据自适应模型融合方法，命名为FroM.

发布时间：2025年06月03日

`LLM理论

摘要中讨论了模型融合技术在微调场景中的应用，提出了一种新的自适应融合方法FroM，用于解决任务干扰问题。这属于模型训练和优化的理论研究，因此归类为LLM理论。`

> FroM: Frobenius Norm-Based Data-Free Adaptive Model Merging

# 摘要

> 随着大语言模型的快速发展，微调作为一种通过注入领域特定知识来提升特定场景性能的有效方法应运而生。在此背景下，模型融合技术为融合多个微调模型的知识提供了解决方案，通过结合它们的参数。然而，传统方法在融合完整的微调模型时，常常会遇到任务干扰的问题，而在参数高效微调场景中，这个问题更加突出。本文中，我们对RegMean方法进行了改进，该方法通过间接利用训练数据来近似融合前后线性层的输出。我们提出了一种名为FroM的自适应融合方法，它直接使用Frobenius范数衡量模型参数，无需任何训练数据。通过引入额外的超参数进行控制，FroM在各种微调场景下均优于基线方法，有效缓解了任务干扰问题。

> With the development of large language models, fine-tuning has emerged as an effective method to enhance performance in specific scenarios by injecting domain-specific knowledge. In this context, model merging techniques provide a solution for fusing knowledge from multiple fine-tuning models by combining their parameters. However, traditional methods often encounter task interference when merging full fine-tuning models, and this problem becomes even more evident in parameter-efficient fine-tuning scenarios. In this paper, we introduce an improvement to the RegMean method, which indirectly leverages the training data to approximate the outputs of the linear layers before and after merging. We propose an adaptive merging method called FroM, which directly measures the model parameters using the Frobenius norm, without any training data. By introducing an additional hyperparameter for control, FroM outperforms baseline methods across various fine-tuning scenarios, alleviating the task interference problem.

[Arxiv](https://arxiv.org/abs/2506.02478)