# 基于大型多模态模型的车辆网络中的任务导向语义通信

发布时间：2025年05月05日

`LLM应用` `通信技术` `智能驾驶`

> Task-Oriented Semantic Communication in Large Multimodal Models-based Vehicle Networks

# 摘要

> 任务导向的语义通信已成为提升各类通信场景性能的关键方法。尽管生成式人工智能（GenAI）的进展，如大型语言模型（LLMs），已被应用于语义通信设计，但大型多模态模型（LMMs）的潜力仍未得到充分探索。本文研究了基于LMM的车辆AI助手，采用大型语言和视觉助手（LLaVA），并提出了一种任务导向的语义通信框架，以促进用户与云端服务器之间的高效交互。为降低计算需求并缩短响应时间，我们优化了LLaVA的图像切片功能，使其能够精准聚焦用户最感兴趣区域。此外，我们通过结合客观和主观用户注意力评估图像块的重要性，并据此调整用于传输语义信息的能源使用。这一策略优化了资源利用，确保了关键信息的精准传输。我们构建了一个针对交通场景的视觉问答（VQA）数据集以评估框架的有效性。实验结果表明，在相同信道条件下，我们的语义通信框架显著提高了回答准确性，尤其在信号噪声比（SNR）较差的环境中表现突出。在12dB和10dB的SNR条件下，准确率分别提高了13.4%和33.1%。

> Task-oriented semantic communication has emerged as a fundamental approach for enhancing performance in various communication scenarios. While recent advances in Generative Artificial Intelligence (GenAI), such as Large Language Models (LLMs), have been applied to semantic communication designs, the potential of Large Multimodal Models (LMMs) remains largely unexplored. In this paper, we investigate an LMM-based vehicle AI assistant using a Large Language and Vision Assistant (LLaVA) and propose a task-oriented semantic communication framework to facilitate efficient interaction between users and cloud servers. To reduce computational demands and shorten response time, we optimize LLaVA's image slicing to selectively focus on areas of utmost interest to users. Additionally, we assess the importance of image patches by combining objective and subjective user attention, adjusting energy usage for transmitting semantic information. This strategy optimizes resource utilization, ensuring precise transmission of critical information. We construct a Visual Question Answering (VQA) dataset for traffic scenarios to evaluate effectiveness. Experimental results show that our semantic communication framework significantly increases accuracy in answering questions under the same channel conditions, performing particularly well in environments with poor Signal-to-Noise Ratios (SNR). Accuracy can be improved by 13.4% at an SNR of 12dB and 33.1% at 10dB, respectively.

[Arxiv](https://arxiv.org/abs/2505.02413)