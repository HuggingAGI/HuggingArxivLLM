# RAAD-LLM：基于LLMs与RAG的自适应异常检测

发布时间：2025年03月04日

`LLM应用` `预测性维护`

> RAAD-LLM: Adaptive Anomaly Detection Using LLMs and RAG Integration

# 摘要

> 复杂工业环境中的异常检测面临独特挑战，尤其是在数据稀疏和运行条件不断变化的场景下。针对这些挑战，我们提出了RAAD-LLM框架，将大型语言模型（LLMs）与检索增强生成（RAG）相结合，为预测性维护（PdM）提供了一种自适应解决方案。该框架无需特定数据集微调，即可有效提升时序数据中的异常检测能力。通过动态调整对正常运行条件的理解，RAAD-LLM显著提高了检测精度。实验结果表明，在真实数据集上，准确率从70.7提升至89.1。此外，RAAD-LLM通过丰富输入序列数据的语义信息，整合了多模态能力，促进模型与工厂操作员之间的协作决策。这一创新可能推动各行业异常检测实现范式转变，为工业智能化带来重要突破。

> Anomaly detection in complex industrial environments poses unique challenges, particularly in contexts characterized by data sparsity and evolving operational conditions. Predictive maintenance (PdM) in such settings demands methodologies that are adaptive, transferable, and capable of integrating domain-specific knowledge. In this paper, we present RAAD-LLM, a novel framework for adaptive anomaly detection, leveraging large language models (LLMs) integrated with Retrieval-Augmented Generation (RAG). This approach addresses the aforementioned PdM challenges. By effectively utilizing domain-specific knowledge, RAAD-LLM enhances the detection of anomalies in time series data without requiring fine-tuning on specific datasets. The framework's adaptability mechanism enables it to adjust its understanding of normal operating conditions dynamically, thus increasing detection accuracy. We validate this methodology through a real-world application for a plastics manufacturing plant and the Skoltech Anomaly Benchmark (SKAB). Results show significant improvements over our previous model with an accuracy increase from 70.7 to 89.1 on the real-world dataset. By allowing for the enriching of input series data with semantics, RAAD-LLM incorporates multimodal capabilities that facilitate more collaborative decision-making between the model and plant operators. Overall, our findings support RAAD-LLM's ability to revolutionize anomaly detection methodologies in PdM, potentially leading to a paradigm shift in how anomaly detection is implemented across various industries.

[Arxiv](https://arxiv.org/abs/2503.02800)