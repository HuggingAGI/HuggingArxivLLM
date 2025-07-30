# SafeDriveRAG：致力于实现安全自动驾驶的基于知识图谱增强检索生成方法

发布时间：2025年07月29日

`RAG` `自动驾驶` `交通安全`

> SafeDriveRAG: Towards Safe Autonomous Driving with Knowledge Graph-based Retrieval-Augmented Generation

# 摘要

> 本研究聚焦视觉语言模型（VLMs）在自动驾驶安全领域的应用，涵盖感知、情境理解和路径规划等核心环节。然而，现有研究对这些模型在交通安全场景中的评估存在明显不足。为解决这一问题，我们推出了 SafeDrive228K 数据集，并提出了一种基于知识图谱增强生成的视觉语言模型新基线（SafeDriveRAG），专为视觉问答任务设计。具体而言，SafeDrive228K 是首个大规模多模态问答基准，包含 22.8 万个样本，覆盖 18 个子任务。该基准涵盖从交通事故、边缘案例到常见安全知识的多样化交通安全查询，为全面评估模型的理解与推理能力提供了坚实基础。此外，我们提出了一种基于多模态知识图谱的即插即用检索增强生成方法，采用创新的多尺度子图检索算法实现高效信息检索。通过整合从互联网获取的交通安全指南，该框架进一步提升了模型在安全关键场景中的表现。最后，我们在五种主流 VLM 上进行了全面评估，以验证其在安全敏感驾驶任务中的可靠性。实验结果表明，引入 RAG 显著提升了性能，在交通事故任务中提升了 +4.73%，在边缘案例任务中提升了 +8.79%，在交通安全常识任务中提升了 +14.57%，充分展现了我们提出的基准和方法在推动交通安全研究中的潜力。我们的源代码和数据可在 https://github.com/Lumos0507/SafeDriveRAG 获取。

> In this work, we study how vision-language models (VLMs) can be utilized to enhance the safety for the autonomous driving system, including perception, situational understanding, and path planning. However, existing research has largely overlooked the evaluation of these models in traffic safety-critical driving scenarios. To bridge this gap, we create the benchmark (SafeDrive228K) and propose a new baseline based on VLM with knowledge graph-based retrieval-augmented generation (SafeDriveRAG) for visual question answering (VQA). Specifically, we introduce SafeDrive228K, the first large-scale multimodal question-answering benchmark comprising 228K examples across 18 sub-tasks. This benchmark encompasses a diverse range of traffic safety queries, from traffic accidents and corner cases to common safety knowledge, enabling a thorough assessment of the comprehension and reasoning abilities of the models. Furthermore, we propose a plug-and-play multimodal knowledge graph-based retrieval-augmented generation approach that employs a novel multi-scale subgraph retrieval algorithm for efficient information retrieval. By incorporating traffic safety guidelines collected from the Internet, this framework further enhances the model's capacity to handle safety-critical situations. Finally, we conduct comprehensive evaluations on five mainstream VLMs to assess their reliability in safety-sensitive driving tasks. Experimental results demonstrate that integrating RAG significantly improves performance, achieving a +4.73% gain in Traffic Accidents tasks, +8.79% in Corner Cases tasks and +14.57% in Traffic Safety Commonsense across five mainstream VLMs, underscoring the potential of our proposed benchmark and methodology for advancing research in traffic safety. Our source code and data are available at https://github.com/Lumos0507/SafeDriveRAG.

[Arxiv](https://arxiv.org/abs/2507.21585)