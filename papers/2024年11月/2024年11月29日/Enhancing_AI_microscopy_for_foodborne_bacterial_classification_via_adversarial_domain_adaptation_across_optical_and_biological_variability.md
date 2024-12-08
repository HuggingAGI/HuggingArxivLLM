# 借助在光学和生物变异性方面的对抗性领域适应，增强用于食源性细菌分类的人工智能显微镜技术

发布时间：2024年11月29日

`其他` `食品安全` `细菌检测`

> Enhancing AI microscopy for foodborne bacterial classification via adversarial domain adaptation across optical and biological variability

# 摘要

> 快速检测食源性细菌对于食品安全和质量意义重大，然而传统的基于培养的方法不仅培养时间长，还需要专门的样品制备。本研究从两方面来应对这些难题：其一，运用对抗域适应增强基于人工智能的显微镜在细菌分类上的通用性；其二，对比单目标和多域适应的表现。对三种革兰氏阳性（凝结芽孢杆菌、枯草芽孢杆菌、无害李斯特菌）和三种革兰氏阴性（大肠杆菌、肠炎沙门氏菌、鼠伤寒沙门氏菌）菌株予以分类。EfficientNetV2 充当骨干架构，借助细粒度特征提取来应对小目标。少样本学习实现了可扩展性，域对抗神经网络（DANNs）处理单个域，多 DANNs（MDANNs）则能在所有目标域通用。该模型基于受控条件下（相差显微镜，60 倍放大，3 小时细菌培养）收集的源域数据进行训练，并在目标域上接受评估，目标域在显微镜模式（明场，BF）、放大倍数（20 倍）和延长培养以弥补较低分辨率（20 倍 - 5 小时）等方面存在差异。DANNs 使目标域分类准确率大幅提升，最高可达 54.45％（20 倍）、43.44％（20 倍 - 5 小时）和 31.67％（BF），而源域退化极小（<4.44％）。MDANNs 在 BF 域表现卓越，在 20 倍域也收获显著进步。Grad-CAM 和 t-SNE 可视化验证了该模型在不同条件下学习域不变特征的能力。本研究给出了一个可扩展且适应性强的细菌分类框架，降低了对大量样品制备的依赖，能够在分散和资源有限的环境中得以应用。

> Rapid detection of foodborne bacteria is critical for food safety and quality, yet traditional culture-based methods require extended incubation and specialized sample preparation. This study addresses these challenges by i) enhancing the generalizability of AI-enabled microscopy for bacterial classification using adversarial domain adaptation and ii) comparing the performance of single-target and multi-domain adaptation. Three Gram-positive (Bacillus coagulans, Bacillus subtilis, Listeria innocua) and three Gram-negative (E. coli, Salmonella Enteritidis, Salmonella Typhimurium) strains were classified. EfficientNetV2 served as the backbone architecture, leveraging fine-grained feature extraction for small targets. Few-shot learning enabled scalability, with domain-adversarial neural networks (DANNs) addressing single domains and multi-DANNs (MDANNs) generalizing across all target domains. The model was trained on source domain data collected under controlled conditions (phase contrast microscopy, 60x magnification, 3-h bacterial incubation) and evaluated on target domains with variations in microscopy modality (brightfield, BF), magnification (20x), and extended incubation to compensate for lower resolution (20x-5h). DANNs improved target domain classification accuracy by up to 54.45% (20x), 43.44% (20x-5h), and 31.67% (BF), with minimal source domain degradation (<4.44%). MDANNs achieved superior performance in the BF domain and substantial gains in the 20x domain. Grad-CAM and t-SNE visualizations validated the model's ability to learn domain-invariant features across diverse conditions. This study presents a scalable and adaptable framework for bacterial classification, reducing reliance on extensive sample preparation and enabling application in decentralized and resource-limited environments.

[Arxiv](https://arxiv.org/abs/2411.19514)