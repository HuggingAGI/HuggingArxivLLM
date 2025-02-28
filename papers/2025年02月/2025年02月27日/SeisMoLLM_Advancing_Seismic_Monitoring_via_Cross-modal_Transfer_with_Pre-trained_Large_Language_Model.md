# # 摘要  
SeisMoLLM：利用跨模态迁移学习，推动地震监测技术发展，基于预训练大型语言模型

发布时间：2025年02月27日

`LLM应用` `地震监测`

> SeisMoLLM: Advancing Seismic Monitoring via Cross-modal Transfer with Pre-trained Large Language Model

# 摘要

> 深度学习的最新突破为地震监测领域带来了翻天覆地的变化，但开发一个在多任务复杂场景下表现优异的基础模型仍具挑战，尤其在信号退化或数据稀缺的情况下。本研究推出SeisMoLLM——首个专为地震监测设计的跨模态迁移基础模型。它无需直接在地震数据集上进行预训练，即可充分释放大型语言模型的预训练潜力。

通过创新的波形分词策略和对预训练GPT-2模型的精心微调，SeisMoLLM在DiTing和STEAD数据集上实现了五项关键任务的最优性能：后向方位角估计、震中距估计、震级估计、相位检测以及首波极性分类。在43个任务指标中，SeisMoLLM取得了36项最佳成绩，并在16个少量样本泛化指标中获得12项顶尖得分，诸多相对提升幅度介于10%至50%之间。

除了卓越的性能，SeisMoLLM在训练和推理阶段的效率也与轻量化模型持平甚至更优。这些成果不仅确立了SeisMoLLM作为地震监测领域极具前景的基础模型地位，更凸显了跨模态迁移作为地震研究激动人心的新方向，充分展现了先进深度学习技术推动地震学研究向前发展的巨大潜力。

> Recent advances in deep learning have revolutionized seismic monitoring, yet developing a foundation model that performs well across multiple complex tasks remains challenging, particularly when dealing with degraded signals or data scarcity. This work presents SeisMoLLM, the first foundation model that utilizes cross-modal transfer for seismic monitoring, to unleash the power of large-scale pre-training from a large language model without requiring direct pre-training on seismic datasets. Through elaborate waveform tokenization and fine-tuning of pre-trained GPT-2 model, SeisMoLLM achieves state-of-the-art performance on the DiTing and STEAD datasets across five critical tasks: back-azimuth estimation, epicentral distance estimation, magnitude estimation, phase picking, and first-motion polarity classification. It attains 36 best results out of 43 task metrics and 12 top scores out of 16 few-shot generalization metrics, with many relative improvements ranging from 10% to 50%. In addition to its superior performance, SeisMoLLM maintains efficiency comparable to or even better than lightweight models in both training and inference. These findings establish SeisMoLLM as a promising foundation model for practical seismic monitoring and highlight cross-modal transfer as an exciting new direction for earthquake studies, showcasing the potential of advanced deep learning techniques to propel seismology research forward.

[Arxiv](https://arxiv.org/abs/2502.19960)