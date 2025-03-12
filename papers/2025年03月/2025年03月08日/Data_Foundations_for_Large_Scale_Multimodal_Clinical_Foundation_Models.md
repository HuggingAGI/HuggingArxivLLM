# 构建大规模多模态临床基础模型的数据基石

发布时间：2025年03月08日

`其他` `多模态`

> Data Foundations for Large Scale Multimodal Clinical Foundation Models

# 摘要

> 临床AI领域的最新进展已在众多临床领域取得了显著突破。然而，现有的基准测试和模型主要局限于少量的模态和任务，这阻碍了能够全面评估患者健康和福祉的大型多模态方法的发展。为了解决这一问题，我们推出了临床大规模整合多模态基准（CLIMB），这是一个综合性的临床基准，整合了来自成像、语言、时间序列和图模态的多样化临床数据。

CLIMB包含451万份患者样本，总计19.01 TB的数据，分布在2D成像、3D视频、时间序列、图和多模态数据中。通过广泛的实证评估，我们证明了多任务预训练在欠研究领域中显著提升了性能，与单任务学习相比，在超声和心电图分析方面分别提升了29%和23%。在CLIMB上的预训练还有效提升了模型对新任务的泛化能力，当结合适当的融合策略时，强大的单模态编码器性能也能很好地转化为多模态性能。

我们的研究发现为新的架构设计和预训练策略奠定了基础，以推动临床AI研究的发展。代码已发布在https://github.com/DDVD233/climb。


> Recent advances in clinical AI have enabled remarkable progress across many clinical domains. However, existing benchmarks and models are primarily limited to a small set of modalities and tasks, which hinders the development of large-scale multimodal methods that can make holistic assessments of patient health and well-being. To bridge this gap, we introduce Clinical Large-Scale Integrative Multimodal Benchmark (CLIMB), a comprehensive clinical benchmark unifying diverse clinical data across imaging, language, temporal, and graph modalities. CLIMB comprises 4.51 million patient samples totaling 19.01 terabytes distributed across 2D imaging, 3D video, time series, graphs, and multimodal data. Through extensive empirical evaluation, we demonstrate that multitask pretraining significantly improves performance on understudied domains, achieving up to 29% improvement in ultrasound and 23% in ECG analysis over single-task learning. Pretraining on CLIMB also effectively improves models' generalization capability to new tasks, and strong unimodal encoder performance translates well to multimodal performance when paired with task-appropriate fusion strategies. Our findings provide a foundation for new architecture designs and pretraining strategies to advance clinical AI research. Code is released at https://github.com/DDVD233/climb.

[Arxiv](https://arxiv.org/abs/2503.07667)