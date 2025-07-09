# 基于LLM的重排器的效率-效果重排FLOPs

发布时间：2025年07月08日

`LLM应用` `信息检索`

> Efficiency-Effectiveness Reranking FLOPs for LLM-based Rerankers

# 摘要

> 大型语言模型（LLMs）在信息检索中的重排序任务中表现出色，但其高计算需求常阻碍实际应用部署。现有研究通过延迟、前向传播次数、输入标记数和输出标记数等代理指标来评估基于LLM的重排序器效率，但这些指标受硬件和运行时间选择影响（如是否并行、批处理大小等），且通常未考虑模型规模，难以解释，模糊了效率与效果权衡的评估。为此，我们提出E	extsuperscript{2}R-FLOPs，用于基于LLM的重排序器：每PetaFLOP的相关性排名指标（RPP）和每PetaFLOP的硬件无关吞吐量查询数（QPP）。配合新指标，我们构建了一个可解释的FLOPs估算器，即使不运行任何实验，也能估算基于LLM的重排序器的FLOPs。基于此，我们进行了全面实验，评估了多种基于LLM的重排序器，研究了效率与效果之间的权衡，并将这一问题提请研究社区关注。

> Large Language Models (LLMs) have recently been applied to reranking tasks in information retrieval, achieving strong performance. However, their high computational demands often hinder practical deployment. Existing studies evaluate the efficiency of LLM-based rerankers using proxy metrics such as latency, the number of forward passes, input tokens, and output tokens. However, these metrics depend on hardware and running-time choices (\eg parallel or not, batch size, etc), and often fail to account for model size, making it difficult to interpret and obscuring the evaluation of the efficiency-effectiveness tradeoff. To address this issue, we propose E\textsuperscript{2}R-FLOPs, for LLM-based rerankers: ranking metrics per PetaFLOP (RPP) for relevance per compute and queries per PetaFLOP (QPP) for hardware-agnostic throughput. Companied with the new metrics, an interpretable FLOPs estimator is built to estimate the FLOPs of an LLM-based reranker even without running any experiments. Based on the proposed metrics, we conduct comprehensive experiments to evaluate a wide range of LLM-based rerankers with different architecture, studying the efficiency-effectiveness trade-off and bringing this issue to the attention of the research community.

[Arxiv](https://arxiv.org/abs/2507.06223)