# 仅凭训练前信息预测大型语言模型在闭卷问答任务中的表现

发布时间：2025年02月06日

`LLM理论

**理由**：这篇论文主要探讨了如何通过预训练数据和模型大小来预测大型语言模型在特定任务（如闭卷问答）上的表现。研究重点在于理解预训练过程、知识保留能力以及如何量化这些因素与任务表现之间的关系。这属于对大型语言模型的理论研究，特别是关于模型性能预测和知识保留的理论分析，因此分类为LLM理论。` `问答系统`

> Predicting Large Language Model Capabilities on Closed-Book QA Tasks Using Only Information Available Prior to Training

# 摘要

> OpenAI 的 GPT-4 技术报告表明，尽管具体方法尚未明确，但模型在特定任务上的表现可以在训练前预测。这一方法对优化资源分配和确保数据与目标任务的对齐至关重要。为此，我们专注于预测闭卷问答（CBQA）任务的表现，这些任务与预训练数据和知识保留密切相关。我们解决了三大挑战：1）掌握预训练全过程，尤其是数据构建；2）评估模型的知识保留能力；3）仅凭训练前信息预测任务特定的知识保留。为此，我们投入 56 万美元和 52 万 GPU 小时，预训练了三个大型语言模型（1.6B、7B 和 13B）。我们通过知识三元组分析预训练数据，并用现有方法评估知识保留。此外，我们引入了 SMI 指标，这是一种信息论度量，用于量化预训练数据、模型大小和任务特定知识保留之间的关系。实验表明，SMI 指标与不同大小模型（1.1B、1.6B、7B 和 13B）在 CBQA 任务上的准确性呈强线性相关（$	ext{R}^2 > 0.84$）。数据集、模型和代码可在 https://github.com/yuhui1038/SMI 获取。

> The GPT-4 technical report from OpenAI suggests that model performance on specific tasks can be predicted prior to training, though methodologies remain unspecified. This approach is crucial for optimizing resource allocation and ensuring data alignment with target tasks. To achieve this vision, we focus on predicting performance on Closed-book Question Answering (CBQA) tasks, which are closely tied to pre-training data and knowledge retention. We address three major challenges: 1) mastering the entire pre-training process, especially data construction; 2) evaluating a model's knowledge retention; and 3) predicting task-specific knowledge retention using only information available prior to training. To tackle these challenges, we pre-train three large language models (i.e., 1.6B, 7B, and 13B) using 560k dollars and 520k GPU hours. We analyze the pre-training data with knowledge triples and assess knowledge retention using established methods. Additionally, we introduce the SMI metric, an information-theoretic measure that quantifies the relationship between pre-training data, model size, and task-specific knowledge retention. Our experiments reveal a strong linear correlation ($\text{R}^2 > 0.84$) between the SMI metric and the model's accuracy on CBQA tasks across models of varying sizes (i.e., 1.1B, 1.6B, 7B, and 13B). The dataset, model, and code are available at https://github.com/yuhui1038/SMI.

[Arxiv](https://arxiv.org/abs/2502.04066)