# 当大型语言模型对自己的回答感到不确定时——以及这种不确定性是否合理

发布时间：2025年03月03日

`LLM应用` `模型评估`

> When an LLM is apprehensive about its answers -- and when its uncertainty is justified

# 摘要

> 评估大型语言模型（LLMs）的不确定性估计在高风险领域尤为重要，因为错误答案可能带来严重后果。目前，尽管有多种方法探讨了不确定性问题，但它们往往仅关注特定类型的不确定性，而忽视了其他方面。我们研究了针对不同主题的多项选择题问答任务中，逐token熵和模型作为裁判（MASJ）等估计方法的有效性。实验涵盖了从15亿到720亿参数的Phi-4、Mistral和Qwen模型，以及14个不同主题。尽管MASJ的表现与随机错误预测器相似，但响应熵在知识依赖领域能够有效预测模型错误，并且可以作为评估问题难度的指标：在生物学领域，ROC AUC达到0.73。然而，对于推理依赖领域，这种相关性消失：数学问题的ROC-AUC仅为0.55。更为根本的是，我们发现熵的度量需要一定的推理量。因此，与数据不确定性相关的熵应被整合到不确定性估计框架中，而MASJ需要进一步改进。此外，现有的MMLU-Pro样本存在偏差，应平衡不同子领域所需的推理量，以便更公平地评估LLMs的性能。

> Uncertainty estimation is crucial for evaluating Large Language Models (LLMs), particularly in high-stakes domains where incorrect answers result in significant consequences. Numerous approaches consider this problem, while focusing on a specific type of uncertainty, ignoring others. We investigate what estimates, specifically token-wise entropy and model-as-judge (MASJ), would work for multiple-choice question-answering tasks for different question topics. Our experiments consider three LLMs: Phi-4, Mistral, and Qwen of different sizes from 1.5B to 72B and $14$ topics. While MASJ performs similarly to a random error predictor, the response entropy predicts model error in knowledge-dependent domains and serves as an effective indicator of question difficulty: for biology ROC AUC is $0.73$. This correlation vanishes for the reasoning-dependent domain: for math questions ROC-AUC is $0.55$. More principally, we found out that the entropy measure required a reasoning amount. Thus, data-uncertainty related entropy should be integrated within uncertainty estimates frameworks, while MASJ requires refinement. Moreover, existing MMLU-Pro samples are biased, and should balance required amount of reasoning for different subdomains to provide a more fair assessment of LLMs performance.

[Arxiv](https://arxiv.org/abs/2503.01688)