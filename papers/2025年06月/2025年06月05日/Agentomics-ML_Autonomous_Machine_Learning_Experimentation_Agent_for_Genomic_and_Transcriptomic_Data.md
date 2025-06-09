# # Agentomics-ML: 基因组与转录组数据的自主机器学习实验代理

发布时间：2025年06月05日

`Agent` `分子医学` `计算生物学`

> Agentomics-ML: Autonomous Machine Learning Experimentation Agent for Genomic and Transcriptomic Data

# 摘要

> 机器学习和深度学习的引入为分子医学带来了革命性变化，在基因组学、转录组学、药物研发及生物系统建模领域取得了显著进展。面对日益增长的多模态、异质性生物数据集，开发能够生成可泛化预测模型的自动化方法变得尤为重要。基于大型语言模型的代理在结构化基准上实现端到端 ML 实验自动化展现出巨大潜力，但在处理异质性计算生物学数据时，其泛化能力和成功率仍有待提升。

为此，我们开发了 Agentomics-ML，一个完全自主的基于代理的系统。该系统能够自动生成分类模型，并提供用于可重复训练和推理的必要文件。Agentomics-ML 通过预定义的 ML 实验流程，借助 Bash 与文件系统交互，完成各项实验步骤。生成模型后，系统通过训练和验证指标反馈潜在问题（如过拟合），并为后续迭代提供改进建议，涵盖数据表示、模型架构及超参数调整等多个方面。

我们已在多个基因组和转录组基准数据集上验证了 Agentomics-ML 的有效性。结果表明，其在泛化能力和成功率方面均超越现有基于代理的方法。尽管目前由领域专家构建的最先进模型在计算生物学数据集上仍具优势，但 Agentomics-ML 显著缩小了自主系统与人工干预之间的差距，并在其中一个基准数据集上达到顶尖水准。代码已开源，详情请访问 https://github.com/BioGeMT/Agentomics-ML。


> The adoption of machine learning (ML) and deep learning methods has revolutionized molecular medicine by driving breakthroughs in genomics, transcriptomics, drug discovery, and biological systems modeling. The increasing quantity, multimodality, and heterogeneity of biological datasets demand automated methods that can produce generalizable predictive models. Recent developments in large language model-based agents have shown promise for automating end-to-end ML experimentation on structured benchmarks. However, when applied to heterogeneous computational biology datasets, these methods struggle with generalization and success rates. Here, we introduce Agentomics-ML, a fully autonomous agent-based system designed to produce a classification model and the necessary files for reproducible training and inference. Our method follows predefined steps of an ML experimentation process, repeatedly interacting with the file system through Bash to complete individual steps. Once an ML model is produced, training and validation metrics provide scalar feedback to a reflection step to identify issues such as overfitting. This step then creates verbal feedback for future iterations, suggesting adjustments to steps such as data representation, model architecture, and hyperparameter choices. We have evaluated Agentomics-ML on several established genomic and transcriptomic benchmark datasets and show that it outperforms existing state-of-the-art agent-based methods in both generalization and success rates. While state-of-the-art models built by domain experts still lead in absolute performance on the majority of the computational biology datasets used in this work, Agentomics-ML narrows the gap for fully autonomous systems and achieves state-of-the-art performance on one of the used benchmark datasets. The code is available at https://github.com/BioGeMT/Agentomics-ML.

[Arxiv](https://arxiv.org/abs/2506.05542)