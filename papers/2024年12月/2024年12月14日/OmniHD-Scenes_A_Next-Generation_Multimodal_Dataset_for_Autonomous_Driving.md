# OmniHD-Scenes: 面向自动驾驶的下一代多模态数据集

发布时间：2024年12月14日

`其他

理由：这篇论文主要讨论的是自动驾驶领域的数据集和传感器技术，虽然涉及到了深度学习和数据驱动的方法，但并没有直接涉及到Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `自动驾驶` `传感器技术`

> OmniHD-Scenes: A Next-Generation Multimodal Dataset for Autonomous Driving

# 摘要

> # 摘要
深度学习的迅猛发展使得自动驾驶算法对全面数据的需求愈发迫切。高质量的数据集是开发高效数据驱动自动驾驶解决方案的关键。下一代自动驾驶数据集需具备多模态特性，整合来自先进传感器的数据，这些传感器需具备广泛的数据覆盖、精细的注释和多样化的场景表现。为此，我们推出了OmniHD-Scenes，一个大规模多模态数据集，提供全方位的详尽高清数据。OmniHD-Scenes数据集融合了128束激光雷达、六个摄像头和六个4D成像雷达系统的数据，以实现全方位环境感知。该数据集包含1501个片段，每个片段约30秒，总计超过450K同步帧和585万同步传感器数据点。我们还开发了一种创新的4D注释流程。截至目前，我们已经注释了200个片段，包含超过514K精确的3D边界框。这些片段还包括静态场景元素的语义分割注释。此外，我们引入了一种自动化流程，用于生成密集占用地面的真实数据，有效利用非关键帧的信息。除了数据集，我们还建立了全面的评估指标、基线模型和基准，用于3D检测和语义占用预测。这些基准利用环绕摄像头和4D成像雷达，探索自动驾驶应用中的经济高效传感器解决方案。大量实验验证了我们低成本传感器配置的有效性及其在恶劣条件下的鲁棒性。数据将在https://www.2077ai.com/OmniHD-Scenes发布。

> The rapid advancement of deep learning has intensified the need for comprehensive data for use by autonomous driving algorithms. High-quality datasets are crucial for the development of effective data-driven autonomous driving solutions. Next-generation autonomous driving datasets must be multimodal, incorporating data from advanced sensors that feature extensive data coverage, detailed annotations, and diverse scene representation. To address this need, we present OmniHD-Scenes, a large-scale multimodal dataset that provides comprehensive omnidirectional high-definition data. The OmniHD-Scenes dataset combines data from 128-beam LiDAR, six cameras, and six 4D imaging radar systems to achieve full environmental perception. The dataset comprises 1501 clips, each approximately 30-s long, totaling more than 450K synchronized frames and more than 5.85 million synchronized sensor data points. We also propose a novel 4D annotation pipeline. To date, we have annotated 200 clips with more than 514K precise 3D bounding boxes. These clips also include semantic segmentation annotations for static scene elements. Additionally, we introduce a novel automated pipeline for generation of the dense occupancy ground truth, which effectively leverages information from non-key frames. Alongside the proposed dataset, we establish comprehensive evaluation metrics, baseline models, and benchmarks for 3D detection and semantic occupancy prediction. These benchmarks utilize surround-view cameras and 4D imaging radar to explore cost-effective sensor solutions for autonomous driving applications. Extensive experiments demonstrate the effectiveness of our low-cost sensor configuration and its robustness under adverse conditions. Data will be released at https://www.2077ai.com/OmniHD-Scenes.

[Arxiv](https://arxiv.org/abs/2412.10734)