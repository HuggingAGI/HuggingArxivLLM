# ALCo-FM：适应性长上下文基础模型，应用于事故预测

发布时间：2025年07月10日

`LLM应用`

> ALCo-FM: Adaptive Long-Context Foundation Model for Accident Prediction

# 摘要

> 交通事故虽然罕见，却是影响深远的事件，准确预测风险需要长上下文多模态推理能力。本文中，我们介绍了ALCo-FM，一种统一的自适应长上下文基础模型。该模型首先计算波动性预评分，用于动态选择输入数据的上下文窗口，随后通过浅层交叉注意力机制对多模态数据进行编码和融合。经过本地GAT层和基于H3六边形网格的大鸟式稀疏全局变换器处理，并结合蒙特卡洛dropout进行置信度评估，该模型能够输出优异且校准良好的预测结果。在15个美国城市的数据上，通过类加权损失函数训练以缓解标签不平衡问题，并在预留城市上使用少量数据进行微调，ALCo-FM实现了0.94的准确率，0.92的F1值，以及0.04的校准误差（ECE），在大规模城市风险预测任务中超越了20多个最新基准模型。代码和数据集可在以下链接获取：https://github.com/PinakiPrasad12/ALCo-FM

> Traffic accidents are rare, yet high-impact events that require long-context multimodal reasoning for accurate risk forecasting. In this paper, we introduce ALCo-FM, a unified adaptive long-context foundation model that computes a volatility pre-score to dynamically select context windows for input data and encodes and fuses these multimodal data via shallow cross attention. Following a local GAT layer and a BigBird-style sparse global transformer over H3 hexagonal grids, coupled with Monte Carlo dropout for confidence, the model yields superior, well-calibrated predictions. Trained on data from 15 US cities with a class-weighted loss to counter label imbalance, and fine-tuned with minimal data on held-out cities, ALCo-FM achieves 0.94 accuracy, 0.92 F1, and an ECE of 0.04, outperforming more than 20 state-of-the-art baselines in large-scale urban risk prediction. Code and dataset are available at: https://github.com/PinakiPrasad12/ALCo-FM

[Arxiv](https://arxiv.org/abs/2507.08153)