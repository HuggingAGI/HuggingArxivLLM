# # 针对客服领域的越南语大型语言模型基准数据集与评估框架
本研究构建了专门用于评估越南语大型语言模型在客服场景下的基准数据集和评估框架。

发布时间：2025年07月30日

`LLM应用` `客户服务` `问答系统`

> A Benchmark Dataset and Evaluation Framework for Vietnamese Large Language Models in Customer Support

# 摘要

> 人工智能的迅猛发展使大型语言模型（LLMs）成为问答（QA）系统不可或缺的一部分，显著提升了客户服务效率并减轻了人工负担。越南语大型语言模型（ViLLMs）的诞生，以其高精度、高效能和隐私保护的优势，为轻量级开源模型的应用开辟了新天地。然而，针对特定领域的评估仍显不足，加之缺乏反映真实客户互动的基准数据集，企业在为支持应用选择合适模型时往往陷入困境。为解决这一难题，我们推出了客户支持对话数据集（CSConDa），一个精选的基准数据集，包含9,000多个问答对，这些问答对源自越南某大型软件公司与人工顾问的真实互动。从价格、产品 availability 到技术故障排除，CSConDa涵盖众多主题，为在实际场景中评估 ViLLMs 提供了坚实基础。我们还开发了一套全面的评估框架，在 CSConDa 上对 11 个轻量级开源 ViLLMs 进行基准测试，结合自动指标和句法分析，深入剖析了模型的优缺点及语言模式。本研究不仅揭示了模型行为，解释了性能差异，还明确了关键改进方向，为新一代 ViLLMs 的开发提供了有力支持。通过建立稳健的基准和系统化评估，我们的工作为客服问答中的模型选择提供了科学依据，同时推动了越南语 LLMs 的研究。数据集现已公开：https://huggingface.co/datasets/ura-hcmut/Vietnamese-Customer-Support-QA。

> With the rapid growth of Artificial Intelligence, Large Language Models (LLMs) have become essential for Question Answering (QA) systems, improving efficiency and reducing human workload in customer service. The emergence of Vietnamese LLMs (ViLLMs) highlights lightweight open-source models as a practical choice for their accuracy, efficiency, and privacy benefits. However, domain-specific evaluations remain limited, and the absence of benchmark datasets reflecting real customer interactions makes it difficult for enterprises to select suitable models for support applications. To address this gap, we introduce the Customer Support Conversations Dataset (CSConDa), a curated benchmark of over 9,000 QA pairs drawn from real interactions with human advisors at a large Vietnamese software company. Covering diverse topics such as pricing, product availability, and technical troubleshooting, CSConDa provides a representative basis for evaluating ViLLMs in practical scenarios. We further present a comprehensive evaluation framework, benchmarking 11 lightweight open-source ViLLMs on CSConDa with both automatic metrics and syntactic analysis to reveal model strengths, weaknesses, and linguistic patterns. This study offers insights into model behavior, explains performance differences, and identifies key areas for improvement, supporting the development of next-generation ViLLMs. By establishing a robust benchmark and systematic evaluation, our work enables informed model selection for customer service QA and advances research on Vietnamese LLMs. The dataset is publicly available at https://huggingface.co/datasets/ura-hcmut/Vietnamese-Customer-Support-QA.

[Arxiv](https://arxiv.org/abs/2507.22542)