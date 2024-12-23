# 检测具有可解释性的机器生成音乐——面临的挑战与早期基准

发布时间：2024年12月17日

`其他`

> Detecting Machine-Generated Music with Explainability -- A Challenge and Early Benchmarks

# 摘要

> 机器生成音乐（MGM）已成为一项开创性的创新成果，在音乐治疗、个性化编辑以及音乐创作灵感等方面有着广泛应用。然而，MGM 的无序扩张给娱乐、教育和艺术领域带来巨大挑战，可能会降低高质量人类创作的价值。所以，MGM 检测（MGMD）对维护这些领域的完整性至关重要。尽管 MGMD 意义重大，但该领域缺少推动其发展的全面基准结果。为填补这一空缺，我们利用一系列音频处理基础模型在现有大规模数据集上开展实验，确立了适用于 MGMD 任务的基准结果。我们所选模型包括传统机器学习模型、深度神经网络、基于 Transformer 的架构以及状态空间模型（SSM）。鉴于音乐融合旋律和歌词的固有多模态特性，我们在实验中还探索了基础多模态模型。除给出基本的二分类结果外，我们还运用多种可解释的人工智能（XAI）工具深入探究模型行为，洞察其决策过程。分析表明，根据域内和域外测试，ResNet18 表现最佳。通过对基准结果及其可解释性进行全面比较，我们提出了若干方向，以激励未来研究开发出更强大、更有效的 MGM 检测方法。

> Machine-generated music (MGM) has become a groundbreaking innovation with wide-ranging applications, such as music therapy, personalised editing, and creative inspiration within the music industry. However, the unregulated proliferation of MGM presents considerable challenges to the entertainment, education, and arts sectors by potentially undermining the value of high-quality human compositions. Consequently, MGM detection (MGMD) is crucial for preserving the integrity of these fields. Despite its significance, MGMD domain lacks comprehensive benchmark results necessary to drive meaningful progress. To address this gap, we conduct experiments on existing large-scale datasets using a range of foundational models for audio processing, establishing benchmark results tailored to the MGMD task. Our selection includes traditional machine learning models, deep neural networks, Transformer-based architectures, and State Space Models (SSM). Recognising the inherently multimodal nature of music, which integrates both melody and lyrics, we also explore fundamental multimodal models in our experiments. Beyond providing basic binary classification outcomes, we delve deeper into model behaviour using multiple explainable Aritificial Intelligence (XAI) tools, offering insights into their decision-making processes. Our analysis reveals that ResNet18 performs the best according to in-domain and out-of-domain tests. By providing a comprehensive comparison of benchmark results and their interpretability, we propose several directions to inspire future research to develop more robust and effective detection methods for MGM.

[Arxiv](https://arxiv.org/abs/2412.13421)