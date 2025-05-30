# EL4NER：基于多个小参数的大型语言模型实现命名实体识别的集成学习方法

发布时间：2025年05月28日

`LLM应用`

> EL4NER: Ensemble Learning for Named Entity Recognition via Multiple Small-Parameter Large Language Models

# 摘要

> 基于大型语言模型（LLMs）的上下文学习（ICL）技术在命名实体识别（NER）任务中表现突出，因其计算资源消耗低、人工标注工作量少且泛化能力更强。然而，大多数基于ICL的NER方法依赖于大参数的LLMs，开源模型在部署和推理时计算资源需求高，而闭源模型则面临API成本高昂、数据隐私问题及社区协作受限的挑战。为应对这一问题，我们提出了EL4NER（用于命名实体识别的集成学习方法），通过聚合多个开源、小参数LLMs的ICL输出，在降低部署和推理成本的同时提升NER任务的整体性能。EL4NER包含三个关键组件：基于任务分解的流水线，以促进深度、多阶段的集成学习；一种新型基于跨度的句子相似度算法，建立更适合NER任务的ICL演示检索机制；以及一种自验证机制，以缓解集成过程中的噪声问题。我们在多个来自不同领域的广泛使用的NER数据集上评估了EL4NER。实验结果表明，EL4NER在较低的参数成本下超越了大多数基于闭源、大参数LLMs的方法，甚至在某些数据集上达到了基于ICL方法的最先进（SOTA）性能。这不仅展示了EL4NER的参数效率，也凸显了在ICL范式下利用开源、小参数LLMs进行NER任务的可行性。

> In-Context Learning (ICL) technique based on Large Language Models (LLMs) has gained prominence in Named Entity Recognition (NER) tasks for its lower computing resource consumption, less manual labeling overhead, and stronger generalizability. Nevertheless, most ICL-based NER methods depend on large-parameter LLMs: the open-source models demand substantial computational resources for deployment and inference, while the closed-source ones incur high API costs, raise data-privacy concerns, and hinder community collaboration. To address this question, we propose an Ensemble Learning Method for Named Entity Recognition (EL4NER), which aims at aggregating the ICL outputs of multiple open-source, small-parameter LLMs to enhance overall performance in NER tasks at less deployment and inference cost. Specifically, our method comprises three key components. First, we design a task decomposition-based pipeline that facilitates deep, multi-stage ensemble learning. Second, we introduce a novel span-level sentence similarity algorithm to establish an ICL demonstration retrieval mechanism better suited for NER tasks. Third, we incorporate a self-validation mechanism to mitigate the noise introduced during the ensemble process. We evaluated EL4NER on multiple widely adopted NER datasets from diverse domains. Our experimental results indicate that EL4NER surpasses most closed-source, large-parameter LLM-based methods at a lower parameter cost and even attains state-of-the-art (SOTA) performance among ICL-based methods on certain datasets. These results show the parameter efficiency of EL4NER and underscore the feasibility of employing open-source, small-parameter LLMs within the ICL paradigm for NER tasks.

[Arxiv](https://arxiv.org/abs/2505.23038)