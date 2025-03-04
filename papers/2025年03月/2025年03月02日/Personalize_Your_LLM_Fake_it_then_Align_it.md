# 个性化你的LLM：先模拟，再对齐

发布时间：2025年03月02日

`LLM应用` `个性化`

> Personalize Your LLM: Fake it then Align it

# 摘要

> 个性化大型语言模型（LLMs）是提升用户体验的关键。然而，现有的个性化方法成本高昂，难以大规模应用。基于检索的方法虽然更高效，但依赖高质量数据集并非易事。为此，我们提出了CHAMELEON，一种快速且经济的个性化方法。实验表明，CHAMELEON在多种任务上表现出色，尤其在LaMP基准测试中，平均超越现有方法40%。

> Personalizing large language models (LLMs) is essential for delivering tailored interactions that improve user experience. Many existing personalization methods require fine-tuning LLMs for each user, rendering them prohibitively expensive for widespread adoption. Although retrieval-based approaches offer a more compute-efficient alternative, they still depend on large, high-quality datasets that are not consistently available for all users. To address this challenge, we propose CHAMELEON, a scalable and efficient personalization approach that uses (1) self-generated personal preference data and (2) representation editing to enable quick and cost-effective personalization. Our experiments on various tasks, including those from the LaMP personalization benchmark, show that CHAMELEON efficiently adapts models to personal preferences, improving instruction-tuned models and outperforms two personalization baselines by an average of 40% across two model architectures.

[Arxiv](https://arxiv.org/abs/2503.01048)