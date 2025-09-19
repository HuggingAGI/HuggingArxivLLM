# CARGO：一种大型语言模型的置信度感知路由框架

发布时间：2025年09月18日

`LLM应用` `基础理论`

> CARGO: A Framework for Confidence-Aware Routing of Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在规模、专业化程度和延迟特性上的快速发展，如何将用户提示精准路由至最优模型以平衡性能与成本，已成为亟待解决的关键问题。为此，我们提出了CARGO（基于类别感知的差距优化路由）——一个轻量级且具备置信度感知能力的动态LLM选择框架。CARGO采用单个基于嵌入的回归器，通过在LLM评判的成对比较数据上训练来预测模型性能；当预测结果不确定时，会进一步调用可选的二元分类器。这种两阶段设计不仅能实现精准且具备成本感知的路由，还完全无需人工标注数据的监督。为适配不同领域的特性，CARGO还支持针对五大任务类别训练特定回归器，包括数学、编码、推理、摘要及创意写作。在GPT-4o、Claude 3.5 Sonnet、DeepSeek V3和Perplexity Sonar这四款主流LLM上的评估结果显示，CARGO的top-1路由准确率达76.4%，且相对各单一模型的胜率在72%至89%之间。上述结果表明，基于置信度引导的轻量级路由机制能以极低开销达到专家级性能，为实际场景中的多模型LLM部署提供了切实可行的解决方案。

> As large language models (LLMs) proliferate in scale, specialization, and latency profiles, the challenge of routing user prompts to the most appropriate model has become increasingly critical for balancing performance and cost. We introduce CARGO (Category-Aware Routing with Gap-based Optimization), a lightweight, confidence-aware framework for dynamic LLM selection. CARGO employs a single embedding-based regressor trained on LLM-judged pairwise comparisons to predict model performance, with an optional binary classifier invoked when predictions are uncertain. This two-stage design enables precise, cost-aware routing without the need for human-annotated supervision. To capture domain-specific behavior, CARGO also supports category-specific regressors trained across five task groups: mathematics, coding, reasoning, summarization, and creative writing. Evaluated on four competitive LLMs (GPT-4o, Claude 3.5 Sonnet, DeepSeek V3, and Perplexity Sonar), CARGO achieves a top-1 routing accuracy of 76.4% and win rates ranging from 72% to 89% against individual experts. These results demonstrate that confidence-guided, lightweight routing can achieve expert-level performance with minimal overhead, offering a practical solution for real-world, multi-model LLM deployments.

[Arxiv](https://arxiv.org/abs/2509.14899)