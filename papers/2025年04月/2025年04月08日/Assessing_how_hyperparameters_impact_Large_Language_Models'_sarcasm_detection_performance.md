# 研究超参数对大型语言模型讽刺识别性能的影响

发布时间：2025年04月08日

`LLM应用

理由：该论文探讨了大型语言模型（如GPT和Llama-2）在讽刺检测任务中的应用，评估了不同模型规模、版本和微调策略对模型性能的影响。研究集中在模型的应用和性能评估上，属于LLM应用领域。` `人工智能`

> Assessing how hyperparameters impact Large Language Models' sarcasm detection performance

# 摘要

> 讽刺检测对人类和机器都是一项挑战。本研究聚焦于OpenAI的GPT和Meta的Llama-2模型，探讨其模型特性如何影响讽刺检测效果。基于这些模型强大的自然语言理解和广泛应用，我们评估了不同规模、版本和超参数的微调与零样本模型。实验采用Self-Annotated Reddit Corpus (SARC2.0) 数据集的pol-bal部分进行。研究发现，微调性能在模型家族内部随着模型规模的增加而提升，同时超参数调整也对性能产生影响。在微调场景下，Llama-2-13b全精度模型以0.83的准确率和F1分数达到最优水平，接近人类表现。在零样本设置中，GPT-4模型表现优异，准确率为0.70，F1分数为0.75。值得注意的是，模型性能可能随版本更新而波动，因此每次新版本发布后都需要重新评估其性能。

> Sarcasm detection is challenging for both humans and machines. This work explores how model characteristics impact sarcasm detection in OpenAI's GPT, and Meta's Llama-2 models, given their strong natural language understanding, and popularity. We evaluate fine-tuned and zero-shot models across various sizes, releases, and hyperparameters. Experiments were conducted on the political and balanced (pol-bal) portion of the popular Self-Annotated Reddit Corpus (SARC2.0) sarcasm dataset. Fine-tuned performance improves monotonically with model size within a model family, while hyperparameter tuning also impacts performance. In the fine-tuning scenario, full precision Llama-2-13b achieves state-of-the-art accuracy and $F_1$-score, both measured at 0.83, comparable to average human performance. In the zero-shot setting, one GPT-4 model achieves competitive performance to prior attempts, yielding an accuracy of 0.70 and an $F_1$-score of 0.75. Furthermore, a model's performance may increase or decline with each release, highlighting the need to reassess performance after each release.

[Arxiv](https://arxiv.org/abs/2504.06166)