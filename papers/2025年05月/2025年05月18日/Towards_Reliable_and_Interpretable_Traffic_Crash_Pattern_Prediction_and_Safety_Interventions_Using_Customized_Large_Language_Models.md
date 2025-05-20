# # 摘要
基于定制化大型语言模型实现可靠且可解释的交通碰撞模式预测与安全干预

发布时间：2025年05月18日

`LLM应用` `交通安全` `自动驾驶`

> Towards Reliable and Interpretable Traffic Crash Pattern Prediction and Safety Interventions Using Customized Large Language Models

# 摘要

> 预测交通事故事件对理解事故分布及其成因至关重要，从而能够制定主动的交通安全政策干预措施。然而，现有方法难以解释交通数据中数值特性、文本报告、事故图像、环境条件和驾驶行为记录等多源信息之间的复杂相互作用，导致难以捕捉这些数据中的丰富语义信息和复杂关系，限制了识别关键风险因素的能力。

在此研究中，我们提出了TrafficSafe框架，通过将大型语言模型（LLMs）应用于基于文本的推理，重新定义了事故预测和特征归因。我们整理了一个包含58,903份真实报告及其基础设施、环境、驾驶人和车辆信息的多模态事故数据集，并将其转化为TrafficSafe事件数据集。通过对该数据集进行定制化微调，TrafficSafe LLM在F1分数上平均比基线提升了42%。

为了解释预测结果并揭示影响因素，我们引入了TrafficSafe Attribution，一个支持条件风险分析的句级特征归因框架。研究发现，酒驾是导致严重事故的主要原因，攻击性驾驶和与能力丧失相关的驾驶行为对严重事故的贡献几乎是其他驾驶行为的两倍。此外，TrafficSafe Attribution在模型训练过程中突出了关键特征，为迭代提升模型性能提供了有策略的数据收集指导。

TrafficSafe框架为交通安全研究带来了变革性的突破，为将先进AI技术转化为负责任的、可操作的和挽救生命的成果提供了完整方案。

> Predicting crash events is crucial for understanding crash distributions and their contributing factors, thereby enabling the design of proactive traffic safety policy interventions. However, existing methods struggle to interpret the complex interplay among various sources of traffic crash data, including numeric characteristics, textual reports, crash imagery, environmental conditions, and driver behavior records. As a result, they often fail to capture the rich semantic information and intricate interrelationships embedded in these diverse data sources, limiting their ability to identify critical crash risk factors. In this research, we propose TrafficSafe, a framework that adapts LLMs to reframe crash prediction and feature attribution as text-based reasoning. A multi-modal crash dataset including 58,903 real-world reports together with belonged infrastructure, environmental, driver, and vehicle information is collected and textualized into TrafficSafe Event Dataset. By customizing and fine-tuning LLMs on this dataset, the TrafficSafe LLM achieves a 42% average improvement in F1-score over baselines. To interpret these predictions and uncover contributing factors, we introduce TrafficSafe Attribution, a sentence-level feature attribution framework enabling conditional risk analysis. Findings show that alcohol-impaired driving is the leading factor in severe crashes, with aggressive and impairment-related behaviors having nearly twice the contribution for severe crashes compared to other driver behaviors. Furthermore, TrafficSafe Attribution highlights pivotal features during model training, guiding strategic crash data collection for iterative performance improvements. The proposed TrafficSafe offers a transformative leap in traffic safety research, providing a blueprint for translating advanced AI technologies into responsible, actionable, and life-saving outcomes.

[Arxiv](https://arxiv.org/abs/2505.12545)