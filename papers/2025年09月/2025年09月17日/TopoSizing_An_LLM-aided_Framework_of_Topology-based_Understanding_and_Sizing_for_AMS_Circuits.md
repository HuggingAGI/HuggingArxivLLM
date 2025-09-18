# TopoSizing：一种LLM辅助的AMS电路拓扑理解与尺寸确定框架

发布时间：2025年09月17日

`Agent` `工业与制造`

> TopoSizing: An LLM-aided Framework of Topology-based Understanding and Sizing for AMS Circuits

# 摘要

> 模拟和混合信号电路设计依旧充满挑战：高质量数据匮乏，且领域知识难以嵌入自动化流程。传统黑盒优化虽能实现采样效率，却缺乏电路理解能力，往往导致评估资源浪费在设计空间的低价值区域。相比之下，基于学习的方法虽嵌入了结构知识，却存在案例特异性问题，且重新训练成本不菲。近期借助大型语言模型的尝试虽展现出潜力，却常依赖人工干预，从而限制了通用性与透明度。为此，我们提出TopoSizing——一个端到端框架，可直接从原始网表中实现稳健的电路理解，并将这些知识转化为优化收益。该方法首先运用图算法，将电路构建为分层的“器件-模块-级”表示结构。随后，LLM智能体通过内置一致性检查，执行迭代的“假设-验证-改进”循环，生成明确注释。这些经过验证的见解通过LLM引导的初始采样和停滞触发的信任区域更新，被整合至贝叶斯优化过程，在确保可行性的同时提升优化效率。

> Analog and mixed-signal circuit design remains challenging due to the shortage of high-quality data and the difficulty of embedding domain knowledge into automated flows. Traditional black-box optimization achieves sampling efficiency but lacks circuit understanding, which often causes evaluations to be wasted in low-value regions of the design space. In contrast, learning-based methods embed structural knowledge but are case-specific and costly to retrain. Recent attempts with large language models show potential, yet they often rely on manual intervention, limiting generality and transparency. We propose TopoSizing, an end-to-end framework that performs robust circuit understanding directly from raw netlists and translates this knowledge into optimization gains. Our approach first applies graph algorithms to organize circuits into a hierarchical device-module-stage representation. LLM agents then execute an iterative hypothesis-verification-refinement loop with built-in consistency checks, producing explicit annotations. Verified insights are integrated into Bayesian optimization through LLM-guided initial sampling and stagnation-triggered trust-region updates, improving efficiency while preserving feasibility.

[Arxiv](https://arxiv.org/abs/2509.14169)