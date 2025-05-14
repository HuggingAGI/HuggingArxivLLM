# InfoPO：互信息最大化在大型语言模型对齐中的应用研究

发布时间：2025年05月13日

`LLM理论` `人工智能` `人机交互`

> InfoPO: On Mutual Information Maximization for Large Language Model Alignment

# 摘要

> 我们研究了使用人类偏好数据对大型语言模型（LLMs）进行后训练。最近，直接偏好优化及其变体在对齐语言模型方面展现出了巨大潜力，无需依赖奖励模型和在线采样。尽管这些方法具有优势，但它们依赖于明确的Bradley-Terry (BT) 模型假设，这使得它们容易过拟合，并导致在推理密集型任务上的表现欠佳。为了解决这些问题，我们提出了一种基于原则的偏好微调算法，名为InfoPO，该算法能够有效地利用偏好数据对齐大型语言模型。InfoPO消除了对BT模型的依赖，并防止所选响应的可能性下降。大量实验表明，InfoPO在广泛使用的公开基准测试中始终优于 established baselines，尤其是在推理任务中表现突出。

> We study the post-training of large language models (LLMs) with human preference data. Recently, direct preference optimization and its variants have shown considerable promise in aligning language models, eliminating the need for reward models and online sampling. Despite these benefits, these methods rely on explicit assumptions about the Bradley-Terry (BT) model, which makes them prone to overfitting and results in suboptimal performance, particularly on reasoning-heavy tasks. To address these challenges, we propose a principled preference fine-tuning algorithm called InfoPO, which effectively and efficiently aligns large language models using preference data. InfoPO eliminates the reliance on the BT model and prevents the likelihood of the chosen response from decreasing. Extensive experiments confirm that InfoPO consistently outperforms established baselines on widely used open benchmarks, particularly in reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.08507)