# ELIS：配备响应长度预测器的高效 LLM 迭代调度系统

发布时间：2025年05月14日

`LLM应用` `云计算` `调度系统`

> ELIS: Efficient LLM Iterative Scheduling System with Response Length Predictor

# 摘要

> 我们提出了一种名为ELIS的大型语言模型（LLM）服务系统，采用迭代最短剩余时间优先（ISRTF）调度器，能够高效管理剩余标记最少的推理任务。现有的LLM服务系统通常采用先到先得的调度策略，这可能导致“队首阻塞”问题。为了解决这一局限，需要预测LLM推理时间并应用最短作业优先调度策略。然而，由于LLM的自回归特性，预测推理延迟颇具挑战性。ELIS通过使用基于编码器的先进模型BGE模型训练LLM响应长度预测器来应对这一挑战。此外，我们设计了ISRTF调度策略，这是一种针对现有LLM迭代批处理优化的最短剩余时间优先策略。为了在工业环境中评估我们的工作，我们根据对真实用户LLM服务跟踪记录的研究，模拟了请求流。此外，我们在Kubernetes上实现了ELIS作为云原生调度系统，以评估其在生产环境中的性能。我们的实验结果表明，ISRTF将平均作业完成时间减少了多达19.6%。

> We propose ELIS, a serving system for Large Language Models (LLMs) featuring an Iterative Shortest Remaining Time First (ISRTF) scheduler designed to efficiently manage inference tasks with the shortest remaining tokens. Current LLM serving systems often employ a first-come-first-served scheduling strategy, which can lead to the "head-of-line blocking" problem. To overcome this limitation, it is necessary to predict LLM inference times and apply a shortest job first scheduling strategy. However, due to the auto-regressive nature of LLMs, predicting the inference latency is challenging. ELIS addresses this challenge by training a response length predictor for LLMs using the BGE model, an encoder-based state-of-the-art model. Additionally, we have devised the ISRTF scheduling strategy, an optimization of shortest remaining time first tailored to existing LLM iteration batching. To evaluate our work in an industrial setting, we simulate streams of requests based on our study of real-world user LLM serving trace records. Furthermore, we implemented ELIS as a cloud-native scheduler system on Kubernetes to evaluate its performance in production environments. Our experimental results demonstrate that ISRTF reduces the average job completion time by up to 19.6%.

[Arxiv](https://arxiv.org/abs/2505.09142)