# Delta激活：微调大型语言模型的表示

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Delta Activations: A Representation for Finetuned Large Language Models

# 摘要

> 强大的开源大型语言模型（LLMs）的成功，让社区得以构建海量针对特定任务和领域的后训练模型。然而，由于元数据杂乱无章、仓库结构松散，查找和理解这些模型仍颇具难度。为此，我们提出Delta Activations——一种通过测量微调模型内部激活相对于基础模型的变化，将其转化为向量嵌入的方法。这种表示能按领域和任务高效聚类，清晰呈现模型领域的内在结构。Delta Activations还具备诸多优势：在各种微调设置下均稳健可靠，混合微调数据集时还能呈现可加性。此外，我们发现Delta Activations能通过少样本微调嵌入任务，并进一步探索了其在模型选择与合并中的应用潜力。我们期待Delta Activations能为公开模型的复用实践提供助力。代码地址：https://github.com/OscarXZQ/delta_activations。

> The success of powerful open source Large Language Models (LLMs) has enabled the community to create a vast collection of post-trained models adapted to specific tasks and domains. However, navigating and understanding these models remains challenging due to inconsistent metadata and unstructured repositories. We introduce Delta Activations, a method to represent finetuned models as vector embeddings by measuring shifts in their internal activations relative to a base model. This representation allows for effective clustering by domain and task, revealing structure in the model landscape. Delta Activations also demonstrate desirable properties: it is robust across finetuning settings and exhibits an additive property when finetuning datasets are mixed. In addition, we show that Delta Activations can embed tasks via few-shot finetuning, and further explore its use for model selection and merging. We hope Delta Activations can facilitate the practice of reusing publicly available models. Code is available at https://github.com/OscarXZQ/delta_activations.

[Arxiv](https://arxiv.org/abs/2509.04442)