# 层次化多模态LLMs与语义空间对齐：提升时间序列分类效果

发布时间：2024年10月24日

`LLM应用` `时间序列分析`

> Hierarchical Multimodal LLMs with Semantic Space Alignment for Enhanced Time Series Classification

# 摘要

> 利用大型语言模型（LLMs）在时间序列分类中备受瞩目，并带来了新的视角。然而，现有方法往往忽略了时间序列数据中的关键动态时间信息，且在数据与文本语义对齐方面存在挑战。为此，我们提出了HiTime，一个分层多模态模型，将时间信息无缝融入LLMs，用于多变量时间序列分类（MTSC）。该模型通过分层特征编码器，结合数据特定和任务特定的嵌入，全面捕捉时间序列数据的多个维度。为了弥合时间序列与文本之间的语义鸿沟，我们引入了双视图对比对齐模块。此外，采用混合提示策略，以高效参数的方式微调预训练的LLM。通过有效整合动态时间特征并确保语义对齐，HiTime使LLMs能够处理连续时间序列数据，并通过文本生成实现顶尖的分类性能。在多个基准数据集上的实验表明，HiTime显著提升了时间序列分类的准确性，超越了大多数竞争性基线方法。我们的研究揭示了将时间特征整合到LLMs中的巨大潜力，为高级时间序列分析开辟了新路径。代码已公开，供进一步研究和验证。

> Leveraging large language models (LLMs) has garnered increasing attention and introduced novel perspectives in time series classification. However, existing approaches often overlook the crucial dynamic temporal information inherent in time series data and face challenges in aligning this data with textual semantics. To address these limitations, we propose HiTime, a hierarchical multi-modal model that seamlessly integrates temporal information into LLMs for multivariate time series classification (MTSC). Our model employs a hierarchical feature encoder to capture diverse aspects of time series data through both data-specific and task-specific embeddings. To facilitate semantic space alignment between time series and text, we introduce a dual-view contrastive alignment module that bridges the gap between modalities. Additionally, we adopt a hybrid prompting strategy to fine-tune the pre-trained LLM in a parameter-efficient manner. By effectively incorporating dynamic temporal features and ensuring semantic alignment, HiTime enables LLMs to process continuous time series data and achieves state-of-the-art classification performance through text generation. Extensive experiments on benchmark datasets demonstrate that HiTime significantly enhances time series classification accuracy compared to most competitive baseline methods. Our findings highlight the potential of integrating temporal features into LLMs, paving the way for advanced time series analysis. The code is publicly available for further research and validation. Our codes are publicly available1.

[Arxiv](https://arxiv.org/abs/2410.18686)