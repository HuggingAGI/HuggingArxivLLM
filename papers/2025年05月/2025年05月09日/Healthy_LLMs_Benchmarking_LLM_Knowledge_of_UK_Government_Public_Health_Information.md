# # 健康的 LLM？评估 LLM 对英国政府公共卫生信息的了解

发布时间：2025年05月09日

`LLM应用` `公共卫生` `问答系统`

> Healthy LLMs? Benchmarking LLM Knowledge of UK Government Public Health Information

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，对特定领域知识的深入了解变得至关重要，以确保其在现实世界中的成功应用。这一点在公共卫生领域尤为重要，因为未能检索到相关、准确且最新的信息可能会对英国居民产生重大影响。然而，目前我们对LLMs在英国政府公共卫生信息方面的知识了解甚少。

为了解决这一问题，本文引入了一个新的基准测试PubHealthBench，包含超过8000个问题，用于评估LLMs在多项选择题问答（MCQA）和自由形式公共卫生问题回答中的表现。这些问题通过自动化管道生成。我们还发布了从英国政府公共卫生指南文件中提取的新数据集，这些文件被用作PubHealthBench的来源文本。

在PubHealthBench上评估了24个LLMs后，我们发现最新的私人LLMs（GPT-4.5、GPT-4.1和o1）拥有高度的知识储备，在MCQA设置下达到了>90%的准确率，并且在使用基本搜索引擎的情况下表现优于人类。然而，在自由形式设置下，所有模型的表现较低，没有模型的得分超过75%。

因此，尽管最先进的（SOTA）LLMs在公共卫生信息方面显示出越来越准确的趋势，但在提供自由形式的公共卫生主题回答时，可能仍需要额外的安全措施或工具。

> As Large Language Models (LLMs) become widely accessible, a detailed understanding of their knowledge within specific domains becomes necessary for successful real world use. This is particularly critical in public health, where failure to retrieve relevant, accurate, and current information could significantly impact UK residents. However, currently little is known about LLM knowledge of UK Government public health information. To address this issue, this paper introduces a new benchmark, PubHealthBench, with over 8000 questions for evaluating LLMs' Multiple Choice Question Answering (MCQA) and free form responses to public health queries, created via an automated pipeline. We also release a new dataset of the extracted UK Government public health guidance documents used as source text for PubHealthBench. Assessing 24 LLMs on PubHealthBench we find the latest private LLMs (GPT-4.5, GPT-4.1 and o1) have a high degree of knowledge, achieving >90% in the MCQA setup, and outperform humans with cursory search engine use. However, in the free form setup we see lower performance with no model scoring >75%. Therefore, whilst there are promising signs that state of the art (SOTA) LLMs are an increasingly accurate source of public health information, additional safeguards or tools may still be needed when providing free form responses on public health topics.

[Arxiv](https://arxiv.org/abs/2505.06046)