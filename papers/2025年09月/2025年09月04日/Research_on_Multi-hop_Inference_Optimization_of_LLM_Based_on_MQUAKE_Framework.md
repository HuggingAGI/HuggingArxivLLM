# 基于MQUAKE框架的LLM多跳推理优化研究

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Research on Multi-hop Inference Optimization of LLM Based on MQUAKE Framework

# 摘要

> 准确回答复杂问题始终是大型语言模型（LLMs）的一大难题。为此，本文在MQUAKE框架的研究基础上，提出了一种面向复杂问题的多跳问题分解方法。借助LLAMA3模型，我们系统探究了知识图谱中的多跳问题分解对模型理解与推理准确性的影响，涵盖模型训练前后两个阶段。实验中，我们将MQUAKE-T数据集系统分割并转换为两种格式：一种是用于直接回答复杂问题的单跳数据集，另一种是通过多跳问题分解方法构建的多跳数据集。随后，我们在这些数据集上微调LLAMA3模型并开展推理测试。结果显示，在未微调LLM时，基于多跳问题分解的预测性能显著优于直接回答复杂问题的方法；经LoRA（低秩适应）方法微调后，两种方法的性能均较未训练基线有所提升。关键在于，多跳分解方法始终保持优势。这些发现证实了多跳分解方法在训练前后均有效，能切实提升LLM回答复杂问题的能力。

> Accurately answering complex questions has consistently been a significant challenge for Large Language Models (LLMs). To address this, this paper proposes a multi-hop question decomposition method for complex questions, building upon research within the MQUAKE framework. Utilizing the LLAMA3 model, we systematically investigate the impact of multi-hop question decomposition within knowledge graphs on model comprehension and reasoning accuracy, both before and after model training. In our experiments, we systematically partitioned and converted the MQUAKE-T dataset into two distinct formats: a single-hop dataset designed for directly answering complex questions, and a multi-hop dataset constructed using the multi-hop question decomposition method. We then fine-tuned the LLAMA3 model on these datasets and conducted inference tests. Our results demonstrate that, without fine-tuning the LLM, the prediction performance based on the multi-hop question decomposition method significantly outperforms the method of directly answering complex questions. After fine-tuning using the LoRA (Low-Rank Adaptation) method, the performance of both approaches improved compared to the untrained baseline. Crucially, the method utilizing multi-hop decomposition consistently maintained its superiority. These findings validate the effectiveness of the multi-hop decomposition method both before and after training, demonstrating its capability to effectively enhance the LLM's ability to answer complex questions.

[Arxiv](https://arxiv.org/abs/2509.04770)