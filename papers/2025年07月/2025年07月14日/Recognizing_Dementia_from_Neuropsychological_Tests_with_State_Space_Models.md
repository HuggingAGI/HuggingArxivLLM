# 基于状态空间模型从神经心理测试识别痴呆症

发布时间：2025年07月14日

`LLM应用` `医疗健康` `认知评估`

> Recognizing Dementia from Neuropsychological Tests with State Space Models

# 摘要

> 痴呆症的早期检测对及时干预和改善患者预后至关重要。神经心理测试在认知评估中广泛应用，但传统上依赖手动评分。我们提出了一种基于状态空间模型的新型自动痴呆症分类框架Demenba，其内存和计算需求与序列长度线性增长。在来自弗雷明汉心脏研究的超过1000小时的认知评估数据上进行训练，部分参与者通过审定审查被诊断为痴呆症。我们的方法在细粒度痴呆症分类上比现有方法提升了21%，且参数更少。进一步分析显示，当与大型语言模型融合时，模型性能进一步提升，为开发更透明和可扩展的痴呆症评估工具奠定了基础。代码：https://anonymous.4open.science/r/Demenba-0861

> Early detection of dementia is critical for timely medical intervention and improved patient outcomes. Neuropsychological tests are widely used for cognitive assessment but have traditionally relied on manual scoring. Automatic dementia classification (ADC) systems aim to infer cognitive decline directly from speech recordings of such tests. We propose Demenba, a novel ADC framework based on state space models, which scale linearly in memory and computation with sequence length. Trained on over 1,000 hours of cognitive assessments administered to Framingham Heart Study participants, some of whom were diagnosed with dementia through adjudicated review, our method outperforms prior approaches in fine-grained dementia classification by 21\%, while using fewer parameters. We further analyze its scaling behavior and demonstrate that our model gains additional improvement when fused with large language models, paving the way for more transparent and scalable dementia assessment tools. Code: https://anonymous.4open.science/r/Demenba-0861

[Arxiv](https://arxiv.org/abs/2507.10311)