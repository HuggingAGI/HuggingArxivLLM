# 基于扩散的方法在异常检测中的应用

发布时间：2024年12月10日

`其他` `异常检测` `数据处理`

> Anomaly detection using Diffusion-based methods

# 摘要

> 这篇论文探究了基于扩散模型用于异常检测的作用，着重于其在识别紧凑和高分辨率数据集中偏差的效果。像去噪扩散概率模型（DDPMs）和扩散变压器（DiTs）这样的基于扩散的架构，依据重建目标来评估性能。借助这些模型的长处，本研究将其性能与传统异常检测方法（如孤立森林、一类支持向量机和 COPOD）作了对比。结果显示，基于扩散的方法在处理复杂的现实世界异常检测任务时，适应性、可扩展性和鲁棒性都更出色。重要发现凸显了重建误差对提高检测准确率的作用，并强调了这些模型在高维数据集上的可扩展性。未来的方向包括优化编解码器架构以及探索多模态数据集，以进一步推动基于扩散的异常检测。

> This paper explores the utility of diffusion-based models for anomaly detection, focusing on their efficacy in identifying deviations in both compact and high-resolution datasets. Diffusion-based architectures, including Denoising Diffusion Probabilistic Models (DDPMs) and Diffusion Transformers (DiTs), are evaluated for their performance using reconstruction objectives. By leveraging the strengths of these models, this study benchmarks their performance against traditional anomaly detection methods such as Isolation Forests, One-Class SVMs, and COPOD. The results demonstrate the superior adaptability, scalability, and robustness of diffusion-based methods in handling complex real-world anomaly detection tasks. Key findings highlight the role of reconstruction error in enhancing detection accuracy and underscore the scalability of these models to high-dimensional datasets. Future directions include optimizing encoder-decoder architectures and exploring multi-modal datasets to further advance diffusion-based anomaly detection.

[Arxiv](https://arxiv.org/abs/2412.07539)