# 基于定制化大型语言模型的可靠且可解释的交通事故模式预测与安全干预研究

发布时间：2025年05月18日

`LLM应用` `交通安全` `道路安全`

> Towards Reliable and Interpretable Traffic Crash Pattern Prediction and Safety Interventions Using Customized Large Language Models

# 摘要

> 预测交通事故对于理解事故分布及其影响因素至关重要，从而为制定主动交通安全政策干预措施提供依据。然而，现有方法难以解析各类交通事故数据源之间的复杂关联，包括数值特征、文本报告、事故图像、环境条件和驾驶行为记录等。因此，这些方法往往无法捕捉到这些多样化数据源中蕴含的丰富语义信息和复杂相互关系，限制了其识别关键事故风险因素的能力。

本研究提出了一种名为TrafficSafe的框架，通过将大型语言模型（LLMs）应用于基于文本的推理，重新定义了事故预测和特征归因。我们收集了一个包含58,903份真实报告及其相关基础设施、环境、驾驶人和车辆信息的多模态事故数据集，并将其转化为TrafficSafe事件数据集。通过对该数据集进行定制化和微调，TrafficSafe LLM在F1分数上比基线模型平均提高了42%。

为了诠释这些预测结果并揭示事故诱因，我们引入了TrafficSafe Attribution，这是一种基于句子级别的特征归因框架，支持条件风险分析。研究发现，酒驾是导致严重事故的主要因素，与其它驾驶行为相比，攻击性驾驶和酒驾相关行为对严重事故的贡献率接近两倍。此外，TrafficSafe Attribution还能够突出模型训练过程中的关键特征，为迭代提升模型性能提供战略性数据采集指导。

所提出的TrafficSafe框架为交通安全研究带来了革命性的进展，为将先进AI技术转化为负责任的、可操作的和挽救生命的实际成果提供了蓝图。

> Predicting crash events is crucial for understanding crash distributions and their contributing factors, thereby enabling the design of proactive traffic safety policy interventions. However, existing methods struggle to interpret the complex interplay among various sources of traffic crash data, including numeric characteristics, textual reports, crash imagery, environmental conditions, and driver behavior records. As a result, they often fail to capture the rich semantic information and intricate interrelationships embedded in these diverse data sources, limiting their ability to identify critical crash risk factors. In this research, we propose TrafficSafe, a framework that adapts LLMs to reframe crash prediction and feature attribution as text-based reasoning. A multi-modal crash dataset including 58,903 real-world reports together with belonged infrastructure, environmental, driver, and vehicle information is collected and textualized into TrafficSafe Event Dataset. By customizing and fine-tuning LLMs on this dataset, the TrafficSafe LLM achieves a 42% average improvement in F1-score over baselines. To interpret these predictions and uncover contributing factors, we introduce TrafficSafe Attribution, a sentence-level feature attribution framework enabling conditional risk analysis. Findings show that alcohol-impaired driving is the leading factor in severe crashes, with aggressive and impairment-related behaviors having nearly twice the contribution for severe crashes compared to other driver behaviors. Furthermore, TrafficSafe Attribution highlights pivotal features during model training, guiding strategic crash data collection for iterative performance improvements. The proposed TrafficSafe offers a transformative leap in traffic safety research, providing a blueprint for translating advanced AI technologies into responsible, actionable, and life-saving outcomes.

[Arxiv](https://arxiv.org/abs/2505.12545)