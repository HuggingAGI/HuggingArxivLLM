# 基于联合随机近似的检索增强生成模型端到端训练改进

发布时间：2025年08月25日

`RAG` `基础理论`

> Improving End-to-End Training of Retrieval-Augmented Generation Models via Joint Stochastic Approximation

# 摘要

> 检索增强生成（RAG）已成为广受认可的范式，实现了参数化记忆与非参数化记忆的融合。该模型由检索器与生成器两个串行组件构成。RAG端到端优化的一大挑战在于，需对知识库中的相关段落（建模为离散潜变量）进行边缘化处理。传统的top-K边缘化与变分RAG（VRAG）方法存在梯度估计偏差或高方差问题。为此，本文提出基于联合随机近似（JSA）的RAG端到端训练框架——JSA-RAG。JSA算法作为EM（期望最大化）算法的随机扩展，在离散潜变量模型估计方面表现突出。通过在五个数据集上针对开放域问答和知识接地对话两项任务开展广泛实验，结果显示JSA-RAG显著优于基础版RAG与VRAG。进一步分析从生成质量、检索性能及低方差梯度估计三个维度验证了JSA-RAG的优势。

> Retrieval-augmented generation (RAG) has become a widely recognized paradigm to combine parametric memory with non-parametric memories. An RAG model consists of two serial connecting components (retriever and generator). A major challenge in end-to-end optimization of the RAG model is that marginalization over relevant passages (modeled as discrete latent variables) from a knowledge base is required. Traditional top-K marginalization and variational RAG (VRAG) suffer from biased or high-variance gradient estimates. In this paper, we propose and develop joint stochastic approximation (JSA) based end-to-end training of RAG, which is referred to as JSA-RAG. The JSA algorithm is a stochastic extension of the EM (expectation-maximization) algorithm and is particularly powerful in estimating discrete latent variable models. Extensive experiments are conducted on five datasets for two tasks (open-domain question answering, knowledge-grounded dialogs) and show that JSA-RAG significantly outperforms both vanilla RAG and VRAG. Further analysis shows the efficacy of JSA-RAG from the perspectives of generation, retrieval, and low-variance gradient estimate.

[Arxiv](https://arxiv.org/abs/2508.18168)