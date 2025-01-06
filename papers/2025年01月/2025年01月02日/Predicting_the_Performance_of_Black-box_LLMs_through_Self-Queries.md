# 通过自我查询预测黑箱LLMs的性能

发布时间：2025年01月02日

`LLM应用

**理由**：这篇论文主要讨论了如何通过黑盒方法预测大型语言模型（LLMs）的行为，特别是在仅通过API访问的情况下。论文提出了一种基于后续提示和响应概率的方法来训练模型行为的预测器，并展示了其在实例级别上的有效性。这种方法直接应用于LLMs的实际使用场景，属于LLM应用的范畴。` `人工智能` `模型评估`

> Predicting the Performance of Black-box LLMs through Self-Queries

# 摘要

> 随着大型语言模型（LLMs）在AI系统中的广泛应用，预测其错误行为变得至关重要。尽管许多研究通过内部表示来解释模型行为，但在仅通过API提供黑盒访问时，这些表示无法获取。本文提出了一种黑盒方法，通过后续提示和不同响应的概率作为特征，训练模型行为的可靠预测器。实验表明，基于这些低维表示训练的线性模型能够在实例级别（如某个生成是否准确回答问题）上提供可靠且可推广的性能预测。有趣的是，这些预测器甚至优于基于模型隐藏状态或词汇表分布的白盒线性预测器。此外，这些特征还可用于评估语言模型状态的细微差异，例如区分干净版本的GPT-4o-mini与受对抗性提示影响的版本（后者在问答任务中出错或生成代码时引入错误）。同时，这些特征还能可靠地区分不同模型架构和大小，从而检测API中提供的虚假模型（如识别是否用GPT-3.5冒充GPT-4o-mini）。

> As large language models (LLMs) are increasingly relied on in AI systems, predicting when they make mistakes is crucial. While a great deal of work in the field uses internal representations to interpret model behavior, these representations are inaccessible when given solely black-box access through an API. In this paper, we extract features of LLMs in a black-box manner by using follow-up prompts and taking the probabilities of different responses as representations to train reliable predictors of model behavior. We demonstrate that training a linear model on these low-dimensional representations produces reliable and generalizable predictors of model performance at the instance level (e.g., if a particular generation correctly answers a question). Remarkably, these can often outperform white-box linear predictors that operate over a model's hidden state or the full distribution over its vocabulary. In addition, we demonstrate that these extracted features can be used to evaluate more nuanced aspects of a language model's state. For instance, they can be used to distinguish between a clean version of GPT-4o-mini and a version that has been influenced via an adversarial system prompt that answers question-answering tasks incorrectly or introduces bugs into generated code. Furthermore, they can reliably distinguish between different model architectures and sizes, enabling the detection of misrepresented models provided through an API (e.g., identifying if GPT-3.5 is supplied instead of GPT-4o-mini).

[Arxiv](https://arxiv.org/abs/2501.01558)