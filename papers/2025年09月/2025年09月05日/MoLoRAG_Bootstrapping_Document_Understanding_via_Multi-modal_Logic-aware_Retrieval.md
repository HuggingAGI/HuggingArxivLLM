# MoLoRAG：借助多模态逻辑感知检索引导文档理解

发布时间：2025年09月05日

`RAG` `基础理论`

> MoLoRAG: Bootstrapping Document Understanding via Multi-modal Logic-aware Retrieval

# 摘要

> 文档理解是一项应用广泛的基础性AI能力，文档问答（DocQA）则是其核心评估任务。传统方法将文档转为文本交由大型语言模型（LLMs）处理，却会剥离图表等关键多模态信息。大型视觉语言模型（LVLMs）虽能解决这一问题，但其输入长度受限，难以应对多页文档理解。检索增强生成（RAG）方法通过筛选相关页面缓解了这一困境，然而它们仅依赖语义相关性，忽略了页面与查询间对推理至关重要的逻辑联系。
  为此，我们提出MoLoRAG——一个面向多模态、多页文档理解的逻辑感知检索框架。该框架通过构建捕获页面间上下文关系的页面图，借助轻量级视觉语言模型（VLM）执行图遍历，从而检索相关页面，包括那些常被忽略的存在逻辑关联的页面。这种方法融合语义与逻辑相关性，实现了更精准的检索。检索完成后，排名前K的页面被输入任意LVLM进行问答。为提升灵活性，MoLoRAG提供两种变体：一种无需训练的便捷部署方案，以及一个微调版本以增强逻辑相关性检查。在四个DocQA数据集上的实验显示，该方法准确率较LVLM直接推理平均提升9.68%，检索精度较基线方法平均提升7.44%。代码和数据集已发布于https://github.com/WxxShirley/MoLoRAG。

> Document Understanding is a foundational AI capability with broad applications, and Document Question Answering (DocQA) is a key evaluation task. Traditional methods convert the document into text for processing by Large Language Models (LLMs), but this process strips away critical multi-modal information like figures. While Large Vision-Language Models (LVLMs) address this limitation, their constrained input size makes multi-page document comprehension infeasible. Retrieval-augmented generation (RAG) methods mitigate this by selecting relevant pages, but they rely solely on semantic relevance, ignoring logical connections between pages and the query, which is essential for reasoning.
  To this end, we propose MoLoRAG, a logic-aware retrieval framework for multi-modal, multi-page document understanding. By constructing a page graph that captures contextual relationships between pages, a lightweight VLM performs graph traversal to retrieve relevant pages, including those with logical connections often overlooked. This approach combines semantic and logical relevance to deliver more accurate retrieval. After retrieval, the top-$K$ pages are fed into arbitrary LVLMs for question answering. To enhance flexibility, MoLoRAG offers two variants: a training-free solution for easy deployment and a fine-tuned version to improve logical relevance checking. Experiments on four DocQA datasets demonstrate average improvements of 9.68% in accuracy over LVLM direct inference and 7.44% in retrieval precision over baselines. Codes and datasets are released at https://github.com/WxxShirley/MoLoRAG.

[Arxiv](https://arxiv.org/abs/2509.07666)