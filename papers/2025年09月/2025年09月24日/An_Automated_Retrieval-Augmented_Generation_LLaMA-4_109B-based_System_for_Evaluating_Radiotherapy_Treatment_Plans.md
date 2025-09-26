# 基于LLaMA-4 109B的自动化检索增强生成系统：放射治疗计划评估

发布时间：2025年09月24日

`RAG` `医疗健康`

> An Automated Retrieval-Augmented Generation LLaMA-4 109B-based System for Evaluating Radiotherapy Treatment Plans

# 摘要

> Purpose: 开发由LLaMA-4 109B驱动的检索增强生成（RAG）系统，以实现放疗治疗计划的自动化、协议适配且可解释的评估。
  Methods and Materials: 我们构建了涵盖四个疾病部位的614个放疗计划多协议数据集，并建立了包含标准化剂量指标与协议定义约束的知识库。该RAG系统集成三个核心模块：基于五个SentenceTransformer骨干网络优化的检索引擎、基于队列相似性的百分位数预测组件，以及临床约束检查器。这些工具由大型语言模型（LLM）通过多步骤提示驱动的推理流程引导，生成简洁且有依据的评估结果。
  Results: 我们利用高斯过程在结合均方根误差（RMSE）、平均绝对误差（MAE）和临床相关准确度阈值的标量化损失函数上优化了检索超参数。基于all-MiniLM-L6-v2的最佳配置在5个百分位点范围内实现了完美的最近邻准确度，且MAE低于2分。端到端测试显示，RAG系统在百分位数估计和约束识别上与独立检索及约束检查模块的计算结果完全一致，验证了所有检索、预测和检查步骤的可靠执行。
  Conclusion: 本研究证实了将结构化人群评分与模块化工具增强推理相结合用于放疗计划评估的可行性，实现了透明且可扩展的评估过程。该系统不仅提供可追溯的输出，还能最大程度减少幻觉问题，并在多种协议中展现出稳健性。未来研究方向包括临床医生主导的验证，以及改进领域适配检索模型以加强实际应用整合。

> Purpose: To develop a retrieval-augmented generation (RAG) system powered by LLaMA-4 109B for automated, protocol-aware, and interpretable evaluation of radiotherapy treatment plans.
  Methods and Materials: We curated a multi-protocol dataset of 614 radiotherapy plans across four disease sites and constructed a knowledge base containing normalized dose metrics and protocol-defined constraints. The RAG system integrates three core modules: a retrieval engine optimized across five SentenceTransformer backbones, a percentile prediction component based on cohort similarity, and a clinical constraint checker. These tools are directed by a large language model (LLM) using a multi-step prompt-driven reasoning pipeline to produce concise, grounded evaluations.
  Results: Retrieval hyperparameters were optimized using Gaussian Process on a scalarized loss function combining root mean squared error (RMSE), mean absolute error (MAE), and clinically motivated accuracy thresholds. The best configuration, based on all-MiniLM-L6-v2, achieved perfect nearest-neighbor accuracy within a 5-percentile-point margin and a sub-2pt MAE. When tested end-to-end, the RAG system achieved 100% agreement with the computed values by standalone retrieval and constraint-checking modules on both percentile estimates and constraint identification, confirming reliable execution of all retrieval, prediction and checking steps.
  Conclusion: Our findings highlight the feasibility of combining structured population-based scoring with modular tool-augmented reasoning for transparent, scalable plan evaluation in radiation therapy. The system offers traceable outputs, minimizes hallucination, and demonstrates robustness across protocols. Future directions include clinician-led validation, and improved domain-adapted retrieval models to enhance real-world integration.

[Arxiv](https://arxiv.org/abs/2509.20707)