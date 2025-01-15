# 基于大语言模型的高速列车驾驶辅助系统

发布时间：2025年01月13日

`LLM应用

理由：这篇论文描述了一个基于大型语言模型（LLM）的智能司机咨询系统（IDAS）框架，名为IDAS-LLM。该系统通过领域微调和检索增强生成（RAG）架构来提高故障处理动作的准确性和可解释性。虽然提到了RAG架构，但主要焦点是LLM在特定应用场景（高铁司机故障处理）中的应用，因此归类为LLM应用更为合适。` `智能咨询系统`

> A Driver Advisory System Based on Large Language Model for High-speed Train

# 摘要

> 随着中国高铁的迅猛发展，司机在操作中面临的技术挑战日益显著，如故障处理。目前，司机在遇到牵引力丢失或传感器故障等技术问题时，依赖车载机械师。这种依赖不仅影响操作效率，还可能在等待故障解决时引发事故。为提高故障处理动作的准确性和可解释性，我们提出了一个基于大型语言模型（LLM）的智能司机咨询系统（IDAS）框架，名为IDAS-LLM。首先，我们利用构建的铁路知识问答数据集对LLM进行领域微调，以提升铁路相关问题的回答准确性。接着，系统设计中引入了检索增强生成（RAG）架构，进一步增强生成响应的可解释性。通过铁路驾驶知识评估数据集的对比实验，结果显示，领域微调的LLM在回答准确性上平均提升了10%，优于当前一些主流LLM。此外，RAG框架的加入使问答会话的平均召回率提高了约4%。最后，通过模拟真实操作场景，我们展示了IDAS-LLM的故障处理能力，证明了该框架的实际应用前景。

> With the rapid development of China high-speed railway, drivers face increasingly significant technical challenges during operations, such as fault handling. Currently, drivers depend on the onboard mechanic when facing technical issues, for instance, traction loss or sensor faults. This dependency can hinder effective operation, even lead to accidents, while waiting for faults to be addressed. To enhance the accuracy and explainability of actions during fault handling, an Intelligent Driver Advisory System (IDAS) framework based on a large language model (LLM) named IDAS-LLM, is introduced. Initially, domain-fine-tuning of the LLM is performed using a constructed railway knowledge question-and-answer dataset to improve answer accuracy in railway-related questions. Subsequently, integration of the Retrieval-augmented Generation (RAG) architecture is pursued for system design to enhance the explainability of generated responses. Comparative experiments are conducted using the constructed railway driving knowledge assessment dataset. Results indicate that domain-fine-tuned LLMs show an improvement in answer accuracy by an average of 10%, outperforming some current mainstream LLMs. Additionally, the inclusion of the RAG framework increases the average recall rate of question-and-answer sessions by about 4%. Finally, the fault handling capability of IDAS-LLM is demonstrated through simulations of real operational scenarios, proving that the proposed framework has practical application prospects.

[Arxiv](https://arxiv.org/abs/2501.07837)