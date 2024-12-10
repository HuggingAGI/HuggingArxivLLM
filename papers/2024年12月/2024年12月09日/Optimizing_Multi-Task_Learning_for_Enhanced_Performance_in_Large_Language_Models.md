# 优化大型语言模型中的多任务学习，提升性能

发布时间：2024年12月09日

`LLM应用` `多任务学习`

> Optimizing Multi-Task Learning for Enhanced Performance in Large Language Models

# 摘要

> 本研究致力于探索在多任务学习框架下基于 GPT-4 的大型语言模型的性能提升之法，并针对文本分类和自动摘要生成这两项任务开展实验。借由共享特征提取器与特定任务模块的联合设计，于同一模型中达成知识共享及多个任务的优化。实验运用 GLUE 数据集的多个子任务，对多任务模型与单任务 GPT-4、多任务版 GPT-3、BERT 基础模型以及经典的带注意力机制的 Bi-LSTM 模型的性能加以比较。结果显示，所提出的多任务学习模型在文本分类的准确率和摘要生成的 ROUGE 值方面均优于其他对比模型，彰显出多任务学习在提升模型泛化能力和任务间协同学习方面的优势。该模型在训练过程中保持稳定的损失收敛率，展现出良好的学习效率以及对测试集的适应能力。本研究证实了多任务学习框架在大型语言模型中的适用性，尤其在增强模型平衡不同任务的能力方面。未来，伴随大型语言模型与多模态数据的结合以及动态任务调整技术的应用，基于多任务学习的框架有望在跨领域的实际应用中发挥更重要的作用，并为通用人工智能的发展提供新思路。

> This study aims to explore the performance improvement method of large language models based on GPT-4 under the multi-task learning framework and conducts experiments on two tasks: text classification and automatic summary generation. Through the combined design of shared feature extractors and task-specific modules, we achieve knowledge-sharing and optimization of multiple tasks in the same model. The experiment uses multiple subtasks of the GLUE dataset to compare the performance of the multi-task model with the single-task GPT-4, the multi-task version of GPT-3, the BERT basic model, and the classic Bi-LSTM with Attention model. The results show that the proposed multi-task learning model outperforms other comparison models in terms of text classification accuracy and ROUGE value of summary generation, demonstrating the advantages of multi-task learning in improving model generalization ability and collaborative learning between tasks. The model maintains a stable loss convergence rate during training, showing good learning efficiency and adaptability to the test set. This study verifies the applicability of the multi-task learning framework in large language models, especially in improving the model's ability to balance different tasks. In the future, with the combination of large language models and multimodal data and the application of dynamic task adjustment technology, the framework based on multi-task learning is expected to play a greater role in practical applications across fields and provide new ideas for the development of general artificial intelligence.

[Arxiv](https://arxiv.org/abs/2412.06249)