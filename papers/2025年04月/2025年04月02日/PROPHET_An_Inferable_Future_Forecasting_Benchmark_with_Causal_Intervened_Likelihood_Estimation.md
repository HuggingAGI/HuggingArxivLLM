# PROPHET：一个基于因果干预似然估计的未来预测基准

发布时间：2025年04月02日

`RAG` `事件预测` `预测分析`

> PROPHET: An Inferable Future Forecasting Benchmark with Causal Intervened Likelihood Estimation

# 摘要

> 预测未来事件是人工智能追求的终极目标之一。近期，基于大型语言模型（LLM）的系统在预测未来事件方面展现出巨大潜力，引发了研究界的广泛关注。目前，已有多个基准被建立起来，通过将事件预测形式化为检索增强生成（RAG）和推理任务来评估预测能力。在这些基准中，每个预测问题都会通过检索相关新闻文章来回答。然而，由于没有考虑问题是否可以由有效的或充分的支持理由来支撑，这些基准中的某些问题可能本质上是不可推断的。为了解决这一问题，我们引入了一个新的基准PROPHET，其中包含可推断的预测问题，并配以相关新闻供检索。为了确保基准的可推断性，我们提出了一种统计度量方法——因果干预似然（CIL），它通过因果推理来评估可推断性。在构建这个基准时，我们首先收集了近期的趋势预测问题，然后利用CIL进行数据筛选，最终得到了一个可推断的事件预测基准。通过广泛的实验，我们首先验证了CIL的有效性，并借助CIL对事件预测进行了深入研究。随后，我们在PROPHET上评估了多个代表性的预测系统，为未来的研究方向提供了有价值的见解。

> Predicting future events stands as one of the ultimate aspirations of artificial intelligence. Recent advances in large language model (LLM)-based systems have shown remarkable potential in forecasting future events, thereby garnering significant interest in the research community. Currently, several benchmarks have been established to evaluate the forecasting capabilities by formalizing the event prediction as a retrieval-augmented generation (RAG) and reasoning task. In these benchmarks, each prediction question is answered with relevant retrieved news articles. However, because there is no consideration on whether the questions can be supported by valid or sufficient supporting rationales, some of the questions in these benchmarks may be inherently noninferable. To address this issue, we introduce a new benchmark, PROPHET, which comprises inferable forecasting questions paired with relevant news for retrieval. To ensure the inferability of the benchmark, we propose Causal Intervened Likelihood (CIL), a statistical measure that assesses inferability through causal inference. In constructing this benchmark, we first collected recent trend forecasting questions and then filtered the data using CIL, resulting in an inferable benchmark for event prediction. Through extensive experiments, we first demonstrate the validity of CIL and in-depth investigations into event prediction with the aid of CIL. Subsequently, we evaluate several representative prediction systems on PROPHET, drawing valuable insights for future directions.

[Arxiv](https://arxiv.org/abs/2504.01509)