# M3Ret：借助自监督赋能零样本多模态医学图像检索

发布时间：2025年09月01日

`其他` `医疗健康`

> M3Ret: Unleashing Zero-shot Multimodal Medical Image Retrieval via Self-Supervision

# 摘要

> 医学图像检索是临床决策与转化研究的关键支撑，其核心在于构建判别性视觉表征。但当前方法存在碎片化问题：针对2D、3D及视频医学数据，需采用独立的架构与训练策略。这种模态专属设计不仅制约了可扩展性，也阻碍了统一表征的构建。为实现统一学习，我们构建了一个大规模混合模态数据集，包含867,653个医学影像样本，涵盖2D X光片、超声图像、RGB内窥镜视频及3D CT扫描。基于该数据集，我们训练出M3Ret——一个无需任何模态定制的统一视觉编码器。它结合生成式（MAE）与对比式（SimDINO）自监督学习（SSL）范式，成功习得可迁移表征。该方法在所有单模态零样本图像检索任务中刷新了最先进水平，超越DINOv3和文本监督的BMC-CLIP等强基线。更值得关注的是，模型无需配对数据即可实现优异的跨模态对齐，且即便预训练未接触过MRI，仍能泛化至未见MRI任务，印证了纯视觉自监督对新模态的泛化潜力。综合分析进一步证实，我们的框架在模型规模与数据量上均具备良好的可扩展性。这些成果为医学影像领域注入新动力，使M3Ret成为构建多模态医学图像理解中视觉自监督基础模型的重要进展。

> Medical image retrieval is essential for clinical decision-making and translational research, relying on discriminative visual representations. Yet, current methods remain fragmented, relying on separate architectures and training strategies for 2D, 3D, and video-based medical data. This modality-specific design hampers scalability and inhibits the development of unified representations. To enable unified learning, we curate a large-scale hybrid-modality dataset comprising 867,653 medical imaging samples, including 2D X-rays and ultrasounds, RGB endoscopy videos, and 3D CT scans. Leveraging this dataset, we train M3Ret, a unified visual encoder without any modality-specific customization. It successfully learns transferable representations using both generative (MAE) and contrastive (SimDINO) self-supervised learning (SSL) paradigms. Our approach sets a new state-of-the-art in zero-shot image-to-image retrieval across all individual modalities, surpassing strong baselines such as DINOv3 and the text-supervised BMC-CLIP. More remarkably, strong cross-modal alignment emerges without paired data, and the model generalizes to unseen MRI tasks, despite never observing MRI during pretraining, demonstrating the generalizability of purely visual self-supervision to unseen modalities. Comprehensive analyses further validate the scalability of our framework across model and data sizes. These findings deliver a promising signal to the medical imaging community, positioning M3Ret as a step toward foundation models for visual SSL in multimodal medical image understanding.

[Arxiv](https://arxiv.org/abs/2509.01360)